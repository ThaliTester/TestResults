#### Test 63012666d6bb2e8_thali07_samsung-SM-A500FU Logs


```
--------- beginning of main
03-16 14:31:05.456  3236  3236 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 14:31:05.456  3236  3236 D ActivityThread: Added TimaKeyStore provider
03-16 14:31:05.466  3216  3216 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
03-16 14:31:05.466  3216  3216 D elm:15183: ELMEngine.ELMEngine( context ).
03-16 14:31:05.466  3216  3216 D elm:15183: MDMBridge.setEnterpriseBridge()
03-16 14:31:05.466  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:05.466  1020  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:05.466  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
--------- beginning of system
03-16 14:31:05.466  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
03-16 14:31:05.476  3216  3216 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
03-16 14:31:05.476  1908  1908 I InCall  : CallSContextMotion - stopPutDownListening
03-16 14:31:05.476  1908  1908 D InCall  : StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
03-16 14:31:05.476  3216  3216 D elm:15183: ElmAgentService : onCreate()
03-16 14:31:05.476  1193  1193 D PhoneStatusBarView: setCallBackground:0
03-16 14:31:05.476  1020  3134 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-16 14:31:05.476  1908  1908 D InCall  : InCallUtils - isCoverClosed false
03-16 14:31:05.476  3145  3228 I DBG_POLICYDM: [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
03-16 14:31:05.476  1020  1044 W libprocessgroup: failed to open /acct/uid_10113/pid_2201/cgroup.procs: No such file or directory
03-16 14:31:05.486  3216  3254 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
03-16 14:31:05.486  3216  3216 D elm:15183: ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
03-16 14:31:05.486  3216  3216 D elm:15183: BootCompletedState : startBootCompleted() call
03-16 14:31:05.486  3216  3216 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
03-16 14:31:05.486  3216  3216 I elm:15183: Get License : 0
03-16 14:31:05.486  3216  3216 D elm:15183: ElmAgentService : onDestroy().
03-16 14:31:05.486  1428  1428 V EmergencyMode: [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
03-16 14:31:05.496  1020  1234 I ActivityManager: Killing 1508:com.android.printspooler/u0a136 (adj 15): empty #31
03-16 14:31:05.506  3197  3197 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3166a47a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-16 14:31:05.506  3197  3197 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
03-16 14:31:05.506  3197  3197 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
03-16 14:31:05.536  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.536  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.536  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.536  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.536  3102  3102 I DBG_DM  : [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
03-16 14:31:05.546  1428  1428 V EmergencyMode: [EmergencyBase] setBootTime
03-16 14:31:05.546  1428  1428 V EmergencyMode: [EmergencyFactory] No Recovery State, kill my self.
03-16 14:31:05.546  3259  3259 E Zygote  : MountEmulatedStorage()
03-16 14:31:05.546  3259  3259 E Zygote  : v2
03-16 14:31:05.546  3259  3259 I libpersona: KNOX_SDCARD checking this for 10003
03-16 14:31:05.546  3259  3259 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:05.546  3259  3259 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-16 14:31:05.556  3259  3259 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-16 14:31:05.556  3259  3259 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 14:31:05.566  1020  1020 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3259 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
03-16 14:31:05.566  1020  1234 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
03-16 14:31:05.566  1020  1234 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:05.566  1020  1234 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:05.566  1020  1234 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-16 14:31:05.566  1020  1702 I ActivityManager: Killing 1731:com.google.android.partnersetup/u0a15 (adj 15): empty #31
03-16 14:31:05.576  3259  3259 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 14:31:05.576  3259  3259 D ActivityThread: Added TimaKeyStore provider
03-16 14:31:05.586  1020  3127 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.586  1020  3127 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.586  1020  3127 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.586  1020  3127 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.596  3274  3274 E Zygote  : MountEmulatedStorage()
03-16 14:31:05.596  3274  3274 E Zygote  : v2
03-16 14:31:05.596  3274  3274 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:05.596  3274  3274 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:05.596  3274  3274 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-16 14:31:05.606  3274  3274 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-16 14:31:05.606  3274  3274 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 14:31:05.606  1020  3127 I ActivityManager: Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3274 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-16 14:31:05.606  1020  3114 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
03-16 14:31:05.616  1020  3114 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:05.616  1020  3114 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:05.616  1020  3114 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-16 14:31:05.636  1908  1908 D VideoCallManager: Instantiating VideoCallManager
03-16 14:31:05.636  3274  3274 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 14:31:05.636  1908  1908 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
03-16 14:31:05.636  3274  3274 D ActivityThread: Added TimaKeyStore provider
03-16 14:31:05.636  1908  1908 I GFX construct_block_size_descriptor_2d second part: took 2.778385ms for 0*0 texture 0
03-16 14:31:05.646  1020  1044 W libprocessgroup: failed to open /acct/uid_10136/pid_1508/cgroup.procs: No such file or directory
03-16 14:31:05.646  1020  1044 W libprocessgroup: failed to open /acct/uid_10015/pid_1731/cgroup.procs: No such file or directory
03-16 14:31:05.646  1908  1908 I GFX generate_partition_tables: took 6.007031ms for 0*0 texture 0
03-16 14:31:05.656  1908  1908 I GFX raster: took 12.975884ms for 176*144 texture 0
03-16 14:31:05.656  1908  1908 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b701e8 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb8b73810 counterpartCT=4 counterpartW=176 counterparth=144
03-16 14:31:05.656  1908  1908 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
03-16 14:31:05.666  1908  1908 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-16 14:31:05.666  1908  1908 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-16 14:31:05.666  1908  1908 I Adreno-EGL: Build Date: 04/06/15 Mon
03-16 14:31:05.666  1908  1908 I Adreno-EGL: Local Branch: 
03-16 14:31:05.666  1908  1908 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-16 14:31:05.666  1908  1908 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-16 14:31:05.666  1908  1908 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
03-16 14:31:05.686  1908  1908 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
03-16 14:31:05.686  1908  1908 I glCompressedTexImage2D: took 0.416407ms for 320*61440 texture 37809
03-16 14:31:05.696  1908  1908 I draw setup: took 10.711719ms for 320*240 texture 37809
03-16 14:31:05.696  1908  1908 E GFX GPU raster: drawn
03-16 14:31:05.706  1908  1908 I GFX GPU raster ASTC: took 42.729063ms for 320*240 texture 12
03-16 14:31:05.706  1908  1908 I GFX raster: took 42.801927ms for 320*240 texture 0
03-16 14:31:05.706  1908  1908 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b73810 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb8b73a50 counterpartCT=4 counterpartW=320 counterparth=240
03-16 14:31:05.716  3259  3259 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
03-16 14:31:05.716  1908  1908 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
03-16 14:31:05.716  1908  1908 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
03-16 14:31:05.726  1908  1908 I glCompressedTexImage2D: took 0.333646ms for 480*122880 texture 37813
03-16 14:31:05.726  1908  1908 I draw setup: took 0.842136ms for 480*640 texture 37813
03-16 14:31:05.726  1908  1908 E GFX GPU raster: drawn
03-16 14:31:05.726  1908  1908 I GFX GPU raster ASTC: took 8.059270ms for 480*640 texture 12
03-16 14:31:05.726  1908  1908 I GFX raster: took 8.132188ms for 480*640 texture 0
03-16 14:31:05.726  1908  1908 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8da10c0 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb8b756c8 counterpartCT=4 counterpartW=480 counterparth=640
03-16 14:31:05.746  3274  3274 I CameraApp: CameraApp.onCreate()... mFeature : null
03-16 14:31:05.746  3274  3274 I testFeature: Feature.Feature(context)
03-16 14:31:05.746  3274  3274 I testFeature: Feature.readInternalDefaultXml()
03-16 14:31:05.746  3274  3274 I testFeature: ResetFeatureValue
03-16 14:31:05.746  3274  3274 I CameraFirmware_broadcast: CameraFirmwareBroadCastReceiver...
03-16 14:31:05.746  3274  3274 I CameraApp: CameraApp.getAppFeature()...
03-16 14:31:05.756  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.756  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.756  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.756  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.766  1908  1908 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
03-16 14:31:05.766  1908  1908 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
03-16 14:31:05.766  1908  1908 I glCompressedTexImage2D: took 0.446771ms for 440*116864 texture 37809
03-16 14:31:05.766  1908  1908 I draw setup: took 1.049219ms for 440*330 texture 37809
03-16 14:31:05.766  1908  1908 E GFX GPU raster: drawn
03-16 14:31:05.776  3297  3297 E Zygote  : MountEmulatedStorage()
03-16 14:31:05.776  3297  3297 E Zygote  : v2
03-16 14:31:05.776  3297  3297 I libpersona: KNOX_SDCARD checking this for 10100
03-16 14:31:05.776  3297  3297 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:05.776  1020  1033 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3297 uid=10100 gids={50100, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
03-16 14:31:05.776  1020  1033 I ActivityManager: Killing 2356:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
03-16 14:31:05.776  3297  3297 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-16 14:31:05.776  3297  3297 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-16 14:31:05.776  3297  3297 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 14:31:05.786  1908  1908 I GFX GPU raster ASTC: took 5.388595ms for 440*330 texture 12
03-16 14:31:05.786  1908  1908 I GFX raster: took 5.462396ms for 440*330 texture 0
03-16 14:31:05.786  1908  1908 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8dca290 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb8db57e8 counterpartCT=4 counterpartW=440 counterparth=330
03-16 14:31:05.816  3297  3297 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 14:31:05.816  3297  3297 D ActivityThread: Added TimaKeyStore provider
03-16 14:31:05.826  1908  1908 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
03-16 14:31:05.826  1908  1908 I GFX GPU raster: eglCreateImageKHR: EGL_SUCCESS
03-16 14:31:05.826  1908  1908 I glCompressedTexImage2D: took 0.415938ms for 480*163840 texture 37811
03-16 14:31:05.826  1908  1908 I draw setup: took 0.960521ms for 480*640 texture 37811
03-16 14:31:05.826  1908  1908 E GFX GPU raster: drawn
03-16 14:31:05.826  3282  3282 D AndroidRuntime: 
03-16 14:31:05.826  3282  3282 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-16 14:31:05.836  3282  3282 D AndroidRuntime: CheckJNI is OFF
03-16 14:31:05.836  3282  3282 D AndroidRuntime: readGMSProperty: start
03-16 14:31:05.836  3282  3282 D AndroidRuntime: readGMSProperty: already setted!!
03-16 14:31:05.836  3282  3282 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-16 14:31:05.836  3282  3282 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-16 14:31:05.836  3282  3282 D AndroidRuntime: readGMSProperty: end
03-16 14:31:05.836  3282  3282 D AndroidRuntime: addProductProperty: start
03-16 14:31:05.836  1908  1908 I GFX GPU raster ASTC: took 6.652657ms for 480*640 texture 12
03-16 14:31:05.836  1908  1908 I GFX raster: took 6.734583ms for 480*640 texture 0
03-16 14:31:05.836  1908  1908 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8de4fa0 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb8da5580 counterpartCT=4 counterpartW=480 counterparth=640
03-16 14:31:05.866  3297  3297 D PackageIntentReceiver: ACTION_BOOT_COMPLETED
03-16 14:31:05.866  3145  3159 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
03-16 14:31:05.866  3259  3259 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
03-16 14:31:05.866  3259  3259 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
03-16 14:31:05.866  3259  3259 D UserAnalysis: Create SecureDbHelper
03-16 14:31:05.866  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2356/cgroup.procs: No such file or directory
03-16 14:31:05.866  3145  3159 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
03-16 14:31:05.876  3145  3159 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
03-16 14:31:05.876  3297  3297 D PackageIntentReceiver: jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
03-16 14:31:05.876  1020  3137 I ActivityManager: Killing 2394:com.sec.android.omc/1000 (adj 15): empty #31
03-16 14:31:05.886  3259  3259 D IntelligenceServiceApplication: onCreate()
03-16 14:31:05.886  1020  3114 D ActivityManager: retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterIntentService; callingUser = 0; userId(target) = 0
03-16 14:31:05.886  3259  3259 D UserAnalysis.UserAnalysisBroadcastReceiver: Intent(action: android.intent.action.BOOT_COMPLETED) is received.
03-16 14:31:05.886  1020  3114 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:05.886  1020  3114 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:05.886  1020  3114 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
03-16 14:31:05.896  1908  1908 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
03-16 14:31:05.896  1908  1908 I GFX construct_block_size_descriptor_2d second part: took 3.907500ms for 0*0 texture 0
03-16 14:31:05.896  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.896  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.896  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.896  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.906  1696  3321 I GoogleHttpClient: GMS http client unavailable, use old client
03-16 14:31:05.906  1908  1908 I GFX generate_partition_tables: took 7.465261ms for 0*0 texture 0
03-16 14:31:05.906  1908  1908 I GFX raster: took 13.332240ms for 176*144 texture 0
03-16 14:31:05.906  1908  1908 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8d9ec28 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb8d9ed38 counterpartCT=4 counterpartW=176 counterparth=144
03-16 14:31:05.916  1908  1908 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
03-16 14:31:05.916  1908  1908 I GFX construct_block_size_descriptor_2d second part: took 2.293542ms for 0*0 texture 0
03-16 14:31:05.916  3323  3323 E Zygote  : MountEmulatedStorage()
03-16 14:31:05.916  3323  3323 E Zygote  : v2
03-16 14:31:05.916  3323  3323 I libpersona: KNOX_SDCARD checking this for 10060
03-16 14:31:05.916  3323  3323 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:05.926  3323  3323 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-16 14:31:05.926  3323  3323 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-16 14:31:05.926  3323  3323 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 14:31:05.926  1020  1492 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3323 uid=10060 gids={50060, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-16 14:31:05.926  1020  1492 I ActivityManager: Killing 2410:com.sec.modem.settings/1000 (adj 15): empty #31
03-16 14:31:05.926  1908  1908 I GFX generate_partition_tables: took 6.187291ms for 0*0 texture 0
03-16 14:31:05.936  1908  1908 I GFX raster: took 10.740260ms for 176*144 texture 0
03-16 14:31:05.936  1908  1908 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8da5658 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb8d9eb30 counterpartCT=4 counterpartW=176 counterparth=144
03-16 14:31:05.936  1908  1908 D ScoverManager: registerListener
03-16 14:31:05.936  1020  3137 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-16 14:31:05.936  1020  3134 D CoverManagerWhiteLists: isAllowedToUse : SIGNATURE_MATCH
03-16 14:31:05.936  1020  3134 D CoverManager.StateNotifier: registerListenerCallback : binder = android.os.BinderProxy@23bb5d1a, pid : 1908, uid : 1001, type : 1
03-16 14:31:05.946  3145  3160 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
03-16 14:31:05.946  3145  3160 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
03-16 14:31:05.946  3145  3160 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
03-16 14:31:05.956  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.956  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.956  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.956  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:05.966  3259  3259 D IntelligenceServiceApplication: no applications having user consent for prediction
03-16 14:31:05.966   291   291 E SMD     : DCD OFF
03-16 14:31:05.976  1020  1492 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=3335 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-16 14:31:05.976  3335  3335 E Zygote  : MountEmulatedStorage()
03-16 14:31:05.976  3335  3335 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:05.976  3335  3335 E Zygote  : v2
03-16 14:31:05.976  3335  3335 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:05.976  3335  3335 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-16 14:31:05.986  3335  3335 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-16 14:31:05.986  3335  3335 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 14:31:05.986  1908  1908 D InCall  : InCallPresenter -  - Finished InCallPresenter.setUp
03-16 14:31:05.996  3323  3323 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 14:31:05.996  3323  3323 D ActivityThread: Added TimaKeyStore provider
03-16 14:31:06.006  3102  3141 I DBG_DM  : [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
03-16 14:31:06.016   322   322 I ServiceManager: Waiting for service AtCmdFwd...
03-16 14:31:06.016  3282  3282 E AffinityControl: AffinityControl: registerfunction enter
03-16 14:31:06.016  1020  1490 I ActivityManager: Killing 2425:com.sec.tcpdumpservice/1000 (adj 15): empty #31
03-16 14:31:06.036  3335  3335 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 14:31:06.036  3335  3335 D ActivityThread: Added TimaKeyStore provider
03-16 14:31:06.046  3282  3282 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-16 14:31:06.046  3145  3228 I DBG_POLICYDM: [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
03-16 14:31:06.046  3145  3228 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
03-16 14:31:06.056  1020  1730 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
03-16 14:31:06.056  1020  1730 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:06.056  1020  1730 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:06.056  1020  1730 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-16 14:31:06.066  1020  1404 E PersonaManagerService: inState():  stateMachine is null !!
03-16 14:31:06.066  1020  1404 I PersonaManagerService: PersonaId don't exist
03-16 14:31:06.066  1020  1404 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-16 14:31:06.066  1020  1404 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-16 14:31:06.076  1020  1404 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-16 14:31:06.086  1020  1404 W ActivityManager: mDVFSHelper.acquire()
03-16 14:31:06.086  1020  1404 D FocusedStackFrame: Set to : 0
03-16 14:31:06.086  1020  1404 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-16 14:31:06.086  1020  1404 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-16 14:31:06.086  1493  1493 D Launcher.HomeView: onPause
03-16 14:31:06.096  1493  1493 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-16 14:31:06.096  1020  1404 D InputDispatcher: Focused application set to: xxxx
03-16 14:31:06.096  1020  1052 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-16 14:31:06.096  1020  1052 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-16 14:31:06.096  1020  1404 D InputDispatcher: Focus left window: 1493
03-16 14:31:06.096  3282  3282 D AndroidRuntime: Shutting down VM
03-16 14:31:06.096  1020  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-16 14:31:06.096  1020  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
03-16 14:31:06.106  3145  3228 I DBG_POLICYDM: [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
03-16 14:31:06.106  1020  1234 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.106  1020  1234 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.106  1020  1234 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.106  1020  1234 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.106  3145  3228 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
03-16 14:31:06.106  1020  1052 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-16 14:31:06.106  1020  1052 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-16 14:31:06.106   257   257 I SurfaceFlinger: id=10 createSurf (1x1),1 flag=404, uhalitest
03-16 14:31:06.116  3145  3228 I DBG_POLICYDM: [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
03-16 14:31:06.126  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2394/cgroup.procs: No such file or directory
03-16 14:31:06.126  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2425/cgroup.procs: No such file or directory
03-16 14:31:06.136  3361  3361 E Zygote  : MountEmulatedStorage()
03-16 14:31:06.136  3361  3361 E Zygote  : v2
03-16 14:31:06.136  3361  3361 I libpersona: KNOX_SDCARD checking this for 10174
03-16 14:31:06.136  3361  3361 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:06.136  3361  3361 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-16 14:31:06.146  3361  3361 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-16 14:31:06.146  1020  1234 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3361 uid=10174 gids={50174, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-16 14:31:06.146  3361  3361 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-16 14:31:06.146  3102  3141 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
03-16 14:31:06.156  2183  2183 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
03-16 14:31:06.156  2183  2183 I dhcpcd  : wlan0: no IPv6 Routers available
03-16 14:31:06.166  1020  1130 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
03-16 14:31:06.166  1020  1130 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:06.166  1020  1130 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:06.166  1020  1130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-16 14:31:06.166  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2410/cgroup.procs: No such file or directory
03-16 14:31:06.166  1493  1493 V ActivityThread: updateVisibility : ActivityRecord{2fe51670 token=android.os.BinderProxy@2cd6ed9b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
03-16 14:31:06.176  1020  1032 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.intelligenceservice/com.samsung.android.placedetection.main.service.ServiceManager; callingUser = 0; userId(target) = 0
03-16 14:31:06.176  3259  3259 V PlaceDetection v1.0.19 : [PlaceDetection::stopService] Service stopped.
03-16 14:31:06.176  3102  3141 I DBG_DM  : [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
03-16 14:31:06.176  3102  3141 I DBG_DM  : [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
03-16 14:31:06.186  3145  3228 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
03-16 14:31:06.186  1020  3114 E Tethering: No numeric data
03-16 14:31:06.186  3361  3361 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 14:31:06.186  3361  3361 D ActivityThread: Added TimaKeyStore provider
03-16 14:31:06.196  1020  1033 E Tethering: No numeric data
03-16 14:31:06.196  1020  3082 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-16 14:31:06.196  1020  3082 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-16 14:31:06.196  1020  3082 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-16 14:31:06.196  3145  3228 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
03-16 14:31:06.206  1493  1493 D Launcher.HomeView: onStop
03-16 14:31:06.206  1493  1493 V ActivityThread: updateVisibility : ActivityRecord{2fe51670 token=android.os.BinderProxy@2cd6ed9b {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-16 14:31:06.206  1020  1130 E Tethering: No numeric data
03-16 14:31:06.206  1020  1049 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-16 14:31:06.206  1020  3127 E Tethering: No numeric data
03-16 14:31:06.206  3145  3228 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
03-16 14:31:06.216  3145  3228 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
03-16 14:31:06.216  3145  3228 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
03-16 14:31:06.216  3145  3229 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
03-16 14:31:06.216  1020  3082 D PersonaManager: isKioskContainerExistOnDevice
03-16 14:31:06.216  1020  1702 E Tethering: No numeric data
03-16 14:31:06.226  3145  3228 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/03/18/13:15:33
03-16 14:31:06.226  1020  3127 E Tethering: No numeric data
03-16 14:31:06.226  3145  3228 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/03/16/14:31:06
03-16 14:31:06.226  3145  3228 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
03-16 14:31:06.226  3145  3228 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
03-16 14:31:06.236  3145  3229 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
03-16 14:31:06.236  1020  3137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
03-16 14:31:06.236  1020  3137 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:06.236  1020  3137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:06.236  1020  3137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-16 14:31:06.236  3145  3229 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
03-16 14:31:06.246  3145  3229 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
03-16 14:31:06.246  3145  3229 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
03-16 14:31:06.256  1020  1020 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
03-16 14:31:06.256  1020  1020 D SensorService: [SO] activate (ident=0xb8ff81f8, enabled=0)
03-16 14:31:06.256  1020  1020 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
03-16 14:31:06.256  3145  3229 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
03-16 14:31:06.256  3145  3229 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
03-16 14:31:06.256  3145  3229 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
03-16 14:31:06.256  3145  3229 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
03-16 14:31:06.256  3145  3229 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
03-16 14:31:06.266  1020  1020 D SensorManager: unregisterListener ::   
03-16 14:31:06.276  1020  1020 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
03-16 14:31:06.276  1020  1020 D SensorService: [SO] changed settle time [1]
03-16 14:31:06.276  1020  1020 D SensorService: [SO] setDelay [66000000]
03-16 14:31:06.276  1020  1020 D SensorService: [SO] activate (ident=0xb8ff81f8, enabled=1)
03-16 14:31:06.276  1020  1020 D SensorService: [SO] AR_init
03-16 14:31:06.276  1020  1020 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
03-16 14:31:06.276  3145  3229 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
03-16 14:31:06.286  1020  1020 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
03-16 14:31:06.296  1020  3114 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.296  1020  3114 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.296  1020  3114 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.296  1020  3114 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.296  3259  3259 V PlaceDetection v1.0.19 : [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
03-16 14:31:06.296  3259  3259 D UserAnalysis.MyPlaceDbPreference: Constructor Preference
03-16 14:31:06.306  3282  3282 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,03-16 14:31:06.316  1493  1493 D Launcher: onTrimMemory. Level: 20
,03-16 14:31:06.326  3382  3382 E Zygote  : MountEmulatedStorage()
03-16 14:31:06.326  3382  3382 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:06.326  3382  3382 E Zygote  : v2
03-16 14:31:06.326  3382  3382 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:06.326  3382  3382 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-16 14:31:06.326  3382  3382 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-16 14:31:06.326  3382  3382 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:06.336  1020  3114 I ActivityManager: Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3382 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-16 14:31:06.336  3145  3228 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,03-16 14:31:06.346  1020  3114 I ActivityManager: Killing 2533:com.sec.android.widgetapp.activeapplicationwidget/u0a142 (adj 15): empty #31
,03-16 14:31:06.346  1020  3114 I ActivityManager: Killing 2485:com.wsomacp/u0a25 (adj 15): empty #32
03-16 14:31:06.346  1020  3114 I ActivityManager: Killing 2436:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #33
,03-16 14:31:06.356  3382  3382 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:06.356  1020  1042 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-16 14:31:06.356  3382  3382 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:06.356  3145  3229 I DBG_POLICYDM: [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
,03-16 14:31:06.366  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:06.366  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:06.366  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.366  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:06.366  1389  3083 D [SBeam] : SBeamEnabler.isSBeamSupported : [-1]
,03-16 14:31:06.376  1389  3083 D [SBeam] : SBeamEnabler.isSBeamSupported : EXIST
,03-16 14:31:06.416  3398  3398 E Zygote  : MountEmulatedStorage(),
03-16 14:31:06.416  3398  3398 I libpersona: KNOX_SDCARD checking this for 1000,
03-16 14:31:06.416  3398  3398 E Zygote  : v2,
03-16 14:31:06.416  3398  3398 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:06.416  3398  3398 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-16 14:31:06.416  3398  3398 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-16 14:31:06.416  3398  3398 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:06.416  3361  3361 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,03-16 14:31:06.426  1020  1730 E Tethering: No numeric data,
03-16 14:31:06.426  1020  1033 I ActivityManager: Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=3398 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-16 14:31:06.426  1020  1042 D SensorService: [SO] 0.172 0.402 10.247,
03-16 14:31:06.426  1020  1042 D SensorService: [SO] [100 -> 255]
03-16 14:31:06.426  1020  1033 I ActivityManager: Killing 2550:com.sec.android.app.camera/u0a139 (adj 15): empty #31
,03-16 14:31:06.426  1020  1490 E Tethering: No numeric data
,03-16 14:31:06.436  1020  1730 E Tethering: No numeric data
,03-16 14:31:06.456  3323  3323 I sCloudBackupApp: sCloudBackupApp Version Info : 4.04.8.KK_APP
,03-16 14:31:06.456  1020  1033 E Tethering: No numeric data
03-16 14:31:06.456  3361  3361 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 7602-7607)
03-16 14:31:06.456  3361  3361 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-16 14:31:06.476  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:06.476  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:06.476  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.476  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:06.476  3398  3398 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:06.476  3398  3398 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:06.486  3418  3418 E Zygote  : MountEmulatedStorage()
03-16 14:31:06.486  3418  3418 E Zygote  : v2
03-16 14:31:06.486  3418  3418 I libpersona: KNOX_SDCARD checking this for 10062
03-16 14:31:06.486  3418  3418 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:06.486  3418  3418 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-16 14:31:06.496  3361  3361 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {28daeb86}
03-16 14:31:06.496  3361  3361 I LibraryLoader: Expected native library version number "",actual native library version number "",
03-16 14:31:06.496  3361  3361 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0,
03-16 14:31:06.496  1020  1130 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3418 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 14:31:06.496  1020  1130 I ActivityManager: Killing 2347:com.sec.android.app.mt/1000 (adj 15): empty #31
,03-16 14:31:06.496  3418  3418 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-16 14:31:06.506  3418  3418 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:06.516  1020  1404 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,03-16 14:31:06.516   309   309 I art     : Explicit concurrent mark sweep GC freed 8743(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 644us total 22.131ms
,03-16 14:31:06.526  1020  1404 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:06.526  1020  1404 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:06.526  1020  1404 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.books, destAppInfo.processName = com.google.android.gms
,03-16 14:31:06.526  3361  3361 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-16 14:31:06.526  3361  3361 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 14:31:06.526  3361  3361 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-16 14:31:06.536   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 637us total 19.349ms
,03-16 14:31:06.536  3418  3418 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:06.536  3418  3418 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:06.546  1020  1044 W libprocessgroup: failed to open /acct/uid_10025/pid_2485/cgroup.procs: No such file or directory
,03-16 14:31:06.546  1020  1044 W libprocessgroup: failed to open /acct/uid_10131/pid_2436/cgroup.procs: No such file or directory
,03-16 14:31:06.556   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 635us total 17.447ms
03-16 14:31:06.556  1020  1032 V VibratorService: hasVibrator - useVibetonz: true
03-16 14:31:06.556  1020  1044 W libprocessgroup: failed to open /acct/uid_10142/pid_2533/cgroup.procs: No such file or directory
03-16 14:31:06.556  1020  1044 W libprocessgroup: failed to open /acct/uid_10139/pid_2550/cgroup.procs: No such file or directory
03-16 14:31:06.556  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2347/cgroup.procs: No such file or directory
03-16 14:31:06.566  2732  2754 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
03-16 14:31:06.566  1950  1950 I GAv4-SVC: Google Analytics 7.8.99 is starting up.
03-16 14:31:06.566  3361  3361 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
03-16 14:31:06.566  1389  3083 W NotificationAccessSettings: Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
03-16 14:31:06.576  3361  3361 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-16 14:31:06.576  3361  3361 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-16 14:31:06.576  3361  3361 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-16 14:31:06.576  3361  3361 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-16 14:31:06.576  3361  3361 I Adreno-EGL: Build Date: 04/06/15 Mon
03-16 14:31:06.576  3361  3361 I Adreno-EGL: Local Branch: 
03-16 14:31:06.576  3361  3361 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-16 14:31:06.576  3361  3361 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-16 14:31:06.576  3361  3361 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
03-16 14:31:06.576  1020  3127 V VibratorService: hasVibrator - useVibetonz: true
,03-16 14:31:06.586  1020  1404 V VibratorService: hasVibrator - useVibetonz: true
,03-16 14:31:06.596  1389  3083 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-16 14:31:06.606  3177  3177 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-16 14:31:06.626  3382  3382 I DBG_FMMDM: [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
,03-16 14:31:06.636  3382  3382 I DBG_FMMDM: [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
,03-16 14:31:06.636  3382  3382 I DBG_FMMDM: [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
,03-16 14:31:06.636  3382  3382 I DBG_FMMDM: [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
,03-16 14:31:06.646  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:06.646  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.646  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.646  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:06.666  3455  3455 E Zygote  : MountEmulatedStorage(),
03-16 14:31:06.666  3455  3455 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:06.666  3455  3455 E Zygote  : v2
03-16 14:31:06.666  3455  3455 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:06.666  3455  3455 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-16 14:31:06.666  3398  3398 D KnoxSetupWizardDbHelper: dbMigrationFlag : false
,03-16 14:31:06.666  3455  3455 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-16 14:31:06.666  3418  3418 I ExternalOEMControlProvider: onCreate
,03-16 14:31:06.666  3455  3455 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:06.666  3145  3228 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
,03-16 14:31:06.666  1020  1032 I ActivityManager: Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3455 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-16 14:31:06.666   257   435 I SurfaceFlinger: id=8 Removed Mauncher (5/8)
03-16 14:31:06.676   257   441 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
,03-16 14:31:06.686  3145  3228 I DBG_POLICYDM: [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,03-16 14:31:06.686  1020  3127 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:06.686  1020  3127 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.686  1020  3127 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.686  1020  3127 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:06.706  3471  3471 E Zygote  : MountEmulatedStorage(),
03-16 14:31:06.706  3471  3471 E Zygote  : v2
03-16 14:31:06.706  3471  3471 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:06.706  3471  3471 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:06.706  3455  3455 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:06.706  3455  3455 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:06.706  1020  3127 I ActivityManager: Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3471 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-16 14:31:06.716  3471  3471 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-16 14:31:06.716  1020  3127 I ActivityManager: Killing 2600:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,03-16 14:31:06.716  3471  3471 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-16 14:31:06.716  3471  3471 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:06.716  1020  3134 D SettingsProvider: name = PREVIOUS_SYS_TIME
,03-16 14:31:06.716  1020  3134 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-16 14:31:06.716  1020  3134 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-16 14:31:06.716  3398  3398 D ShortcutReceiver:  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
03-16 14:31:06.716  1020  3134 D SettingsProvider: selectionArgs: false
,03-16 14:31:06.716  1020  3134 D SettingsProvider: selectionArgs: 10062
,03-16 14:31:06.726  1020  3134 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-16 14:31:06.726  1020  3134 D SettingsProvider: ret = -1
,03-16 14:31:06.736  1020  3134 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,03-16 14:31:06.736  1020  3137 D SettingsProvider: name = PREVIOUS_ELAPSED_TIME
03-16 14:31:06.736  1020  3137 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-16 14:31:06.736  1020  3137 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-16 14:31:06.736  1020  3137 D SettingsProvider: selectionArgs: false
03-16 14:31:06.736  1020  3137 D SettingsProvider: selectionArgs: 10062
03-16 14:31:06.736  1020  3137 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-16 14:31:06.736  1020  3137 D SettingsProvider: ret = -1
,03-16 14:31:06.746  3398  3398 D KnoxShortcutUtil: getIsShortcutMigrationFor_2_3_0_Done true
,03-16 14:31:06.746  3398  3398 D ShortcutReceiver:  KnoxContainerVersion 2.4.0
03-16 14:31:06.746  3398  3398 D ShortcutReceiver:  shortcut migration not required 
,03-16 14:31:06.746  1020  3137 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10062
,03-16 14:31:06.746  1193  1193 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 14:31:06.746  1389  3083 D ScoverManager: serviceVersion : 16908288
03-16 14:31:06.746  1020  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.746  1020  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.746  1020  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.746  1020  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:06.756  3490  3490 E Zygote  : MountEmulatedStorage()
03-16 14:31:06.756  3490  3490 E Zygote  : v2
03-16 14:31:06.756  3490  3490 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:06.756  3490  3490 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:06.756  3490  3490 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-16 14:31:06.766  3490  3490 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-16 14:31:06.766  3490  3490 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:06.766  3471  3471 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 14:31:06.766  1020  1730 I ActivityManager: Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=3490 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-16 14:31:06.766  3471  3471 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:06.766  1193  1193 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 14:31:06.766  1020  1730 I ActivityManager: Killing 2632:com.android.calendar/u0a135 (adj 15): empty #31
,03-16 14:31:06.786  3490  3490 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:06.786  3490  3490 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:06.796  3471  3471 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-16 14:31:06.816  3455  3455 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,03-16 14:31:06.816  3455  3455 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
,03-16 14:31:06.816  3455  3455 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,03-16 14:31:06.826  3455  3466 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-16 14:31:06.836  3490  3490 E KnoxSetupWizardClient: isShipMode : 1
,03-16 14:31:06.836  3490  3490 I KnoxSetupWizardClient: onReceive : android.intent.action.BOOT_COMPLETED
,03-16 14:31:06.846  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2600/cgroup.procs: No such file or directory
03-16 14:31:06.846  1020  1044 W libprocessgroup: failed to open /acct/uid_10135/pid_2632/cgroup.procs: No such file or directory
,03-16 14:31:06.846  1020  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-16 14:31:06.846  1020  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.846  1020  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.846  1020  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,03-16 14:31:06.856  3145  3229 I DBG_POLICYDM: [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,03-16 14:31:06.866  3511  3511 E Zygote  : MountEmulatedStorage()
03-16 14:31:06.866  3511  3511 E Zygote  : v2
03-16 14:31:06.866  3511  3511 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:06.866  3511  3511 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:06.866  3511  3511 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-16 14:31:06.866  1020  1702 I ActivityManager: Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=3511 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-16 14:31:06.866  1020  1702 I ActivityManager: Killing 2696:com.android.keychain/1000 (adj 15): empty #31
,03-16 14:31:06.866  3511  3511 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-16 14:31:06.876  1193  1193 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-16 14:31:06.876  1193  1193 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-16 14:31:06.876  1193  1193 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 14:31:06.876  1193  1193 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 14:31:06.876  1193  1193 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 14:31:06.876  1193  1193 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 14:31:06.876  3511  3511 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:06.886  3382  3382 I DBG_FMMDM: [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,03-16 14:31:06.886  3361  3361 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-16 14:31:06.896  3382  3382 I DBG_FMMDM: [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
03-16 14:31:06.896  3382  3382 I DBG_FMMDM: [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,03-16 14:31:06.906  3511  3511 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:06.906  3511  3511 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:06.906  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.906  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.906  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.906  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:06.926  3528  3528 E Zygote  : MountEmulatedStorage()
,03-16 14:31:06.926  3528  3528 E Zygote  : v2
03-16 14:31:06.926  3528  3528 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:06.926  3528  3528 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:06.926  3528  3528 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-16 14:31:06.926  3361  3361 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-16 14:31:06.926  3528  3528 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
03-16 14:31:06.926  3528  3528 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:06.926  1020  1492 I ActivityManager: Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3528 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-16 14:31:06.926  1020  1492 I ActivityManager: Killing 2503:com.sec.android.gallery3d/u0a44 (adj 15): empty #31
03-16 14:31:06.926  1020  1492 I ActivityManager: Killing 2801:com.android.email/u0a145 (adj 15): empty #32
,03-16 14:31:06.936  3361  3361 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-16 14:31:06.936  3361  3361 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-16 14:31:06.946  3361  3361 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-16 14:31:06.946  3471  3471 I ServiceMode: received = ACTION_BOOT_COMPLETED
,03-16 14:31:06.946  3471  3471 I ServiceMode: setReferenceIsDumpState : 0
,03-16 14:31:06.956  3361  3361 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-16 14:31:06.956  3361  3361 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-16 14:31:06.956  3528  3528 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:06.956  3528  3528 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:06.956  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:06.956  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:06.956  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:06.966  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:06.976  3550  3550 E Zygote  : MountEmulatedStorage(),
03-16 14:31:06.976  1020  1032 I ActivityManager: Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3550 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
03-16 14:31:06.976  1020  1032 I ActivityManager: Killing 2834:flipboard.boxer.app/u0a99 (adj 15): empty #31
03-16 14:31:06.986  3550  3550 E Zygote  : v2,
03-16 14:31:06.986  3550  3550 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:06.986  3145  3229 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
03-16 14:31:06.986  3550  3550 I libpersona: KNOX_SDCARD not a persona,
,03-16 14:31:06.986  3550  3550 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-16 14:31:06.996  3550  3550 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-16 14:31:06.996  3490  3507 W System.err: java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub,
03-16 14:31:06.996  3550  3550 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 14:31:06.996  3490  3507 W System.err: 	at android.os.Parcel.readException(Parcel.java:1544)
03-16 14:31:06.996  3490  3507 W System.err: 	at android.os.Parcel.readException(Parcel.java:1493)
,03-16 14:31:06.996  3490  3507 W System.err: 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
03-16 14:31:06.996  3490  3507 W System.err: 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
03-16 14:31:06.996  3490  3507 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88),
03-16 14:31:06.996  3490  3507 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
03-16 14:31:06.996  1020  3114 I art     : Explicit concurrent mark sweep GC freed 24740(1283KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 26MB/40MB, paused 2.792ms total 182.942ms
,03-16 14:31:07.006  3511  3511 D StatusChecker: onReceive : android.intent.action.BOOT_COMPLETED
,03-16 14:31:07.016   322   322 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,03-16 14:31:07.016  3145  3229 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,03-16 14:31:07.016  3550  3550 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:07.026  3550  3550 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:07.026  3511  3511 I StatusChecker: onReceive : net.mt.init : DONE
,03-16 14:31:07.036  1020  3127 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:07.036  1020  3127 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:07.036  1020  3127 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:07.036  1020  3127 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:07.046  1020  2818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 14:31:07.046  3571  3571 E Zygote  : MountEmulatedStorage()
03-16 14:31:07.046  3571  3571 E Zygote  : v2
03-16 14:31:07.046  3571  3571 I libpersona: KNOX_SDCARD checking this for 10116
03-16 14:31:07.046  3571  3571 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:07.046  3571  3571 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-16 14:31:07.056  3571  3571 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-16 14:31:07.056  3571  3571 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:07.056  1020  3127 I ActivityManager: Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=3571 uid=10116 gids={50116, 9997} abi=armeabi-v7a
,03-16 14:31:07.056  1020  3127 I ActivityManager: Killing 2277:flipboard.app/u0a98 (adj 15): empty #31
,03-16 14:31:07.066  3528  3528 I DBG_FMMDS: [50.18.150420][Line:56][onCreate] FMMDS Application Start
,03-16 14:31:07.086  3571  3571 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 14:31:07.086  3571  3571 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:07.096  3361  3586 D OpenGLRenderer: Render dirty regions requested: true
,03-16 14:31:07.096  3550  3550 D NPS_WSSNPS: [] android.intent.action.BOOT_COMPLETED
,03-16 14:31:07.106  3550  3550 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,03-16 14:31:07.106  1020  3137 D ActivityManager: retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,03-16 14:31:07.106  1020  3137 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:07.106  1020  3137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:07.106  1020  3137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,03-16 14:31:07.106  1020  1130 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-16 14:31:07.106  1020  1130 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-16 14:31:07.106  1020  1130 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-16 14:31:07.106  1020  1020 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-16 14:31:07.106  1020  1020 D PersonaManagerService: getPersonasForUser(): returning null!
03-16 14:31:07.106  3361  3448 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-16 14:31:07.116  3550  3550 D NPS_WSSNPS: [] Service onCreate!!
,03-16 14:31:07.116  1020  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:07.116  1020  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:07.116  1020  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:07.116  1020  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:07.116  3571  3571 I PageBuddyNotiSvc: Intent received : action=android.intent.action.BOOT_COMPLETED
,03-16 14:31:07.116  3571  3571 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,03-16 14:31:07.116  3528  3528 I DBG_FMMDS: [50.18.150420][Line:28][<init>] XDBHelper First Call!!!,
,03-16 14:31:07.126  3588  3588 E Zygote  : MountEmulatedStorage()
03-16 14:31:07.126  3588  3588 E Zygote  : v2
03-16 14:31:07.126  3588  3588 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:07.126  3588  3588 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:07.126  3588  3588 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-16 14:31:07.126  3588  3588 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-16 14:31:07.136  3588  3588 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-16 14:31:07.136  1020  1490 I ActivityManager: Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3588 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-16 14:31:07.136  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2696/cgroup.procs: No such file or directory
03-16 14:31:07.136  1020  1032 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-16 14:31:07.136  1020  1044 W libprocessgroup: failed to open /acct/uid_10044/pid_2503/cgroup.procs: No such file or directory
03-16 14:31:07.136  1020  1044 W libprocessgroup: failed to open /acct/uid_10099/pid_2834/cgroup.procs: No such file or directory
03-16 14:31:07.136  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:07.136  3550  3596 D NPS_WSSNPS: [] NpsServiceTask Start
03-16 14:31:07.136  1020  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:07.136  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,03-16 14:31:07.146  3571  3571 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,03-16 14:31:07.146  1020  1044 W libprocessgroup: failed to open /acct/uid_10098/pid_2277/cgroup.procs: No such file or directory
03-16 14:31:07.146  1020  1044 W libprocessgroup: failed to open /acct/uid_10145/pid_2801/cgroup.procs: No such file or directory
,03-16 14:31:07.146  3361  3361 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-16 14:31:07.146  3361  3361 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-16 14:31:07.156  3455  3466 D PCWCLIENTTRACE_DMContentProvider: [URIMatcher] - result : 2
,03-16 14:31:07.156  1020  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:07.156  1020  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:07.156  1020  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:07.156  1020  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:07.166  3588  3588 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 14:31:07.166  1020  2775 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.ec:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
,03-16 14:31:07.166  3588  3588 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:07.166   257   257 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, NainActivit
,03-16 14:31:07.176  3606  3606 E Zygote  : MountEmulatedStorage()
03-16 14:31:07.176  3606  3606 I libpersona: KNOX_SDCARD checking this for 10125
03-16 14:31:07.176  3606  3606 E Zygote  : v2
03-16 14:31:07.176  3606  3606 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:07.176  3177  3177 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: Dirty, need more hygiene.
03-16 14:31:07.176  1020  1730 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=3606 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
03-16 14:31:07.176  3606  3606 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-16 14:31:07.186  3606  3606 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-16 14:31:07.186  3606  3606 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:07.186  1020  1404 D InputDispatcher: Focus entered window: 3361
,03-16 14:31:07.196  3528  3528 E DBG_FMMDS: Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,03-16 14:31:07.196  1020  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-16 14:31:07.196  3361  3361 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-16 14:31:07.196  3361  3586 I OpenGLRenderer: Initialized EGL, version 1.4
03-16 14:31:07.196  1020  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-16 14:31:07.206  3361  3586 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-16 14:31:07.206  3361  3586 D OpenGLRenderer: Enabling debug mode 0
,03-16 14:31:07.206  3606  3606 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:07.206  3606  3606 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:07.216  3528  3528 I DBG_FMMDS: [50.18.150420][Line:43][xdbDBInit] 
,03-16 14:31:07.216  3550  3550 D NPS_WSSNPS: [50.150321] smlDBHelper
,03-16 14:31:07.226  3606  3606 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-16 14:31:07.236  3606  3606 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-16 14:31:07.236  3606  3606 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-16 14:31:07.236  1389  3083 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-16 14:31:07.246  1389  3083 D Settings_Utils: isSupportVNFestival SM-A500FU XEO
,03-16 14:31:07.296  3102  3141 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,03-16 14:31:07.306  1020  3134 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-16 14:31:07.316  1020  3624 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 14:31:07.316  1193  1193 D PanelView: There is/are notification(s) 
,03-16 14:31:07.326  1020  1052 I ActivityManager: Displayed Component not be shown by security: +1s222ms
,03-16 14:31:07.326  1020  1052 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@7
,03-16 14:31:07.326  1020  1052 W ActivityManager: mDVFSHelper.release()
03-16 14:31:07.326  1020  1052 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1a10a31f u0 com.test.thalitest/.MainActivity t236} time:38478
,03-16 14:31:07.326  1020  1045 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-16 14:31:07.336  1020  1234 D SettingsProvider: name = access_control_enabled
,03-16 14:31:07.336  3361  3361 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@146add10 time:38486
,03-16 14:31:07.336  1020  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:07.336  1020  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:07.336  1020  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:07.336  1020  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:07.336  1797  1797 I SamsungIME: getCurrentCandidateView
,03-16 14:31:07.356  3627  3627 E Zygote  : MountEmulatedStorage()
,03-16 14:31:07.356  3627  3627 I libpersona: KNOX_SDCARD checking this for 10069
03-16 14:31:07.356  3627  3627 E Zygote  : v2
03-16 14:31:07.356  3627  3627 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:07.356  3627  3627 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-16 14:31:07.356  1020  1730 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3627 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-16 14:31:07.356  3627  3627 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-16 14:31:07.356  3627  3627 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-16 14:31:07.386  3627  3627 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:07.386  3627  3627 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:07.396  3606  3606 D QuickConnect: PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,03-16 14:31:07.396  3606  3606 D QuickConnect: Util.setSCRunningSetting - [value]0
,03-16 14:31:07.406  3550  3550 I NPS_WSSNPS: [50.150321] AsyncBulkFlagCheck
,03-16 14:31:07.406  1020  1234 D SettingsProvider: name = scon_is_running
03-16 14:31:07.406  1020  1234 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-16 14:31:07.406  1020  1234 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-16 14:31:07.406  1020  1234 D SettingsProvider: selectionArgs: false
03-16 14:31:07.406  1020  1234 D SettingsProvider: selectionArgs: 10125
03-16 14:31:07.416  1020  1234 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-16 14:31:07.416  1020  1234 D SettingsProvider: ret = -1
,03-16 14:31:07.416  1020  1234 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10125
,03-16 14:31:07.426  3627  3627 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,03-16 14:31:07.426  1193  1193 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 14:31:07.426  3550  3642 I NPS_WSSNPS: [50.150321] IsRemain_AsyncBulkCheck
,03-16 14:31:07.426  3606  3606 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,03-16 14:31:07.436  3550  3642 I NPS_WSSNPS: [50.150321] IsRemain_Asyncing nothing
03-16 14:31:07.436  3550  3642 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,03-16 14:31:07.436  1020  3114 D ActivityManager: retrieveServiceLocked(): component = com.wssnps/com.wssnps.smlNpsService; callingUser = 0; userId(target) = 0
,03-16 14:31:07.436  1020  3114 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:07.436  1020  3114 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:07.436  1020  3114 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
03-16 14:31:07.436  3550  3550 D NPS_WSSNPS: [50.150321] Service onDestroy
,03-16 14:31:07.436  3550  3550 I NPS_WSSNPS: [50.150321] smlBRConfigurationDelete
,03-16 14:31:07.446  3550  3550 I NPS_WSSNPS: [50.150321] smlBRMessageDelete
,03-16 14:31:07.446  3550  3550 I NPS_WSSNPS: [50.150321] smlBREmailDelete
,03-16 14:31:07.446  3550  3550 I NPS_WSSNPS: [50.150321] smlBRNetworkDelete
03-16 14:31:07.446  3550  3550 I NPS_WSSNPS: [50.150321] smlBRCallLogDelete
,03-16 14:31:07.446  3550  3550 I NPS_WSSNPS: [50.150321] smlBRMiniDiaryDelete
03-16 14:31:07.446  3550  3550 I NPS_WSSNPS: [50.150321] smlBRPenMemoMDelete
,03-16 14:31:07.446  3550  3550 I NPS_WSSNPS: [50.150321] smlBRSMemoDelete
03-16 14:31:07.446  3550  3550 I NPS_WSSNPS: [50.150321] cpuBooster release : false
,03-16 14:31:07.446  3550  3550 D NPS_WSSNPS: [50.150321] dsServerSocket close
,03-16 14:31:07.456  1020  1702 I ActivityManager: Killing 2880:com.sec.usbsettings/1000 (adj 15): empty #31
,03-16 14:31:07.456  1020  1702 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-16 14:31:07.456  1020  1702 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:07.456  1020  1702 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:07.456  1020  1702 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,03-16 14:31:07.466  1797  1797 D SamsungIME: Dismiss ExpandCandiate
,03-16 14:31:07.476  3606  3606 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,03-16 14:31:07.476  1020  2957 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:07.476  1020  2957 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:07.476  1020  2957 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:07.476  1020  2957 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:07.486  3646  3646 E Zygote  : MountEmulatedStorage()
,03-16 14:31:07.486  3646  3646 I libpersona: KNOX_SDCARD checking this for 10131
03-16 14:31:07.486  3646  3646 E Zygote  : v2
03-16 14:31:07.486  3646  3646 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:07.486  1020  2957 I ActivityManager: Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=3646 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,03-16 14:31:07.496  3646  3646 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-16 14:31:07.496  3646  3646 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-16 14:31:07.496  3646  3646 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:07.516   309   309 I art     : Explicit concurrent mark sweep GC freed 8779(374KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 704us total 23.392ms
,03-16 14:31:07.536  3528  3528 I DBG_FMMDS: [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,03-16 14:31:07.536  3361  3361 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3361
,03-16 14:31:07.536   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 625us total 17.186ms
,03-16 14:31:07.536   257   441 I SurfaceFlinger: id=10 Removed uhalitest (7/8)
,03-16 14:31:07.536   257  1104 I SurfaceFlinger: id=10 Removed uhalitest (-2/8)
,03-16 14:31:07.546  3646  3646 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:07.546  3646  3646 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:07.556  3528  3528 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
,03-16 14:31:07.556  3528  3528 I DBG_FMMDS: [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-16 14:31:07.556  3528  3528 I DBG_FMMDS: [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
03-16 14:31:07.556   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 650us total 20.334ms
03-16 14:31:07.556  3528  3528 I DBG_FMMDS: [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,03-16 14:31:07.556  3528  3528 I DBG_FMMDS: [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
03-16 14:31:07.556  3528  3528 I DBG_FMMDS: [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,03-16 14:31:07.566  1797  1797 I SamsungIME: getDebugLevel  : 0x4f4c
,03-16 14:31:07.576  3177  3177 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-16 14:31:07.576  3177  3177 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-16 14:31:07.586  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2880/cgroup.procs: No such file or directory
,03-16 14:31:07.596  1020  1033 I ActivityManager: Killing 2377:com.android.mms/u0a46 (adj 15): empty #31
,03-16 14:31:07.596  3646  3646 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-16 14:31:07.596  3646  3646 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 14:31:07.596  3646  3646 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-16 14:31:07.596  3646  3646 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-16 14:31:07.606  3236  3236 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-16 14:31:07.636  1020  1020 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@11
,03-16 14:31:07.636  3236  3236 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-16 14:31:07.636  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:07.636  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:07.636  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:07.636  1020  1130 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:07.646  2654  3138 I FactoryTestApp: [IPCWriterToSecPhoneService$disConnectSecPhoneService](3138)  
,03-16 14:31:07.656  3670  3670 E Zygote  : MountEmulatedStorage(),
,03-16 14:31:07.656  3670  3670 I libpersona: KNOX_SDCARD checking this for 10014,
03-16 14:31:07.656  3670  3670 E Zygote  : v2,
03-16 14:31:07.656  3670  3670 I libpersona: KNOX_SDCARD not a persona,
03-16 14:31:07.656  3670  3670 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-16 14:31:07.656  3670  3670 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-16 14:31:07.656  3670  3670 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-16 14:31:07.666  1020  1130 I ActivityManager: Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3670 uid=10014 gids={50014, 9997} abi=armeabi-v7a
,03-16 14:31:07.676  1020  1490 V VibratorService: hasVibrator - useVibetonz: true
03-16 14:31:07.676  1020  1032 D CountryDetector: No listener is left
,03-16 14:31:07.686  1020  1130 I ActivityManager: Killing 2960:com.sec.android.app.safetyassurance/u0a48 (adj 15): empty #31,
,03-16 14:31:07.696  3646  3646 D SBrowserFeatureFlag: initialized in static block : loadCscFeatureValue() succeed! 
,03-16 14:31:07.706  3670  3670 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:07.706  3670  3670 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:07.706  1020  3137 I ActivityManager: Killing 2732:com.google.android.apps.books/u0a75 (adj 15): empty #31
,03-16 14:31:07.756  1797  1797 I SamsungIME: getDebugLevel  : 0x4f4c
,03-16 14:31:07.766  1020  1044 W libprocessgroup: failed to open /acct/uid_10046/pid_2377/cgroup.procs: No such file or directory
,03-16 14:31:07.766  3646  3646 D ManifestProvider: onCreate()
,03-16 14:31:07.786  1797  1797 I SamsungIME: KeybaordView init() : load resources
,03-16 14:31:07.786  3177  3545 D Volley  : [398] DiskBasedCache.clear: Cache cleared.
03-16 14:31:07.786  1020  1702 I ActivityManager: Killing 2866:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
,03-16 14:31:07.786  3361  3361 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-16 14:31:07.796  1020  1702 I ActivityManager: Killing 2990:com.sec.dsm.system/1000 (adj 15): empty #31
,03-16 14:31:07.796  3177  3440 D Volley  : [391] DiskBasedCache.clear: Cache cleared.
,03-16 14:31:07.806  1020  1020 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,03-16 14:31:07.806  1020  1020 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
,03-16 14:31:07.826  1020  2957 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,03-16 14:31:07.826  1020  2957 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:07.826  1020  2957 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:07.826  1020  2957 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-16 14:31:07.826  3670  3670 V OneTimeInitializerReceiver: OneTimeInitializerReceiver.onReceive
03-16 14:31:07.826  1020  1020 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-16 14:31:07.826  1020  1044 W libprocessgroup: failed to open /acct/uid_10048/pid_2960/cgroup.procs: No such file or directory
,03-16 14:31:07.826  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:07.826  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:07.826  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:07.826  1020  1020 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:07.846  3690  3690 E Zygote  : MountEmulatedStorage(),
03-16 14:31:07.846  3690  3690 E Zygote  : v2
03-16 14:31:07.846  3690  3690 I libpersona: KNOX_SDCARD checking this for 1000,
03-16 14:31:07.846  3690  3690 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-16 14:31:07.846  3690  3690 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:07.846  3690  3690 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-16 14:31:07.856  3690  3690 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:07.856  3646  3646 E NetworkSettingsReceiver: onReceive: android.intent.action.BOOT_COMPLETED
,03-16 14:31:07.856  1797  1797 I SamsungIME: getCurrentKeyboard
03-16 14:31:07.856  1797  1797 I SamsungIME: getTextKeyboard
,03-16 14:31:07.856  1020  1020 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3690 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-16 14:31:07.856  1020  3114 D ActivityManager: retrieveServiceLocked(): component = com.google.android.onetimeinitializer/com.google.android.onetimeinitializer.OneTimeService; callingUser = 0; userId(target) = 0
,03-16 14:31:07.856  1020  3114 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:07.856  1020  3114 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:07.856  1020  3114 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,03-16 14:31:07.866  1020  3134 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
,03-16 14:31:07.866  1020  3134 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:07.866  1020  3134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:07.866  1020  3134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-16 14:31:07.886  3690  3690 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:07.886  3690  3690 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:07.896  1020  3114 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-16 14:31:07.896  1020  3114 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:07.896  1020  3114 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-16 14:31:07.896  1020  3114 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-16 14:31:07.906  1696  1696 V GLSUser : [LoginAccountsChangedWakefulBroadcastReceiver] recieved broadcast intent with action: android.intent.action.BOOT_COMPLETED
,03-16 14:31:07.916  1020  1234 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
,03-16 14:31:07.916  1020  1234 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:07.916  1020  1234 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:07.916  1020  1234 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-16 14:31:07.926  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:07.926  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:07.926  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:07.926  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:07.936  3670  3700 V OneTimeService: OneTimeService.onHandleIntent
,03-16 14:31:07.936  1020  1044 W libprocessgroup: failed to open /acct/uid_10075/pid_2732/cgroup.procs: No such file or directory
03-16 14:31:07.936  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_2990/cgroup.procs: No such file or directory
03-16 14:31:07.936  1020  1044 W libprocessgroup: failed to open /acct/uid_10085/pid_2866/cgroup.procs: No such file or directory
,03-16 14:31:07.946  1797  1797 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-16 14:31:07.946  3177  3177 D Finsky  : [1] 2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
03-16 14:31:07.946  3712  3712 E Zygote  : MountEmulatedStorage()
03-16 14:31:07.946  3712  3712 E Zygote  : v2
03-16 14:31:07.946  3712  3712 I libpersona: KNOX_SDCARD checking this for 10015
03-16 14:31:07.946  3712  3712 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:07.946  3177  3177 D Finsky  : [1] 2.run: Finished loading 1 libraries.
03-16 14:31:07.946  3712  3712 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-16 14:31:07.946  1020  1491 I ActivityManager: Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GooglePartnerSetup: pid=3712 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
03-16 14:31:07.956  3712  3712 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-16 14:31:07.956  3712  3712 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-16 14:31:07.976  1950  1950 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,03-16 14:31:07.986  1020  3137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
03-16 14:31:07.986  3712  3712 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:07.986  3712  3712 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:07.986  1020  3137 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:07.986  1020  3137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:07.986  3646  3646 E SBrowserFeatureFlag: initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@f31159d
,03-16 14:31:07.986  1020  3137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:07.986  3646  3646 D SBrowserFeatureFlag: initialize : initSupportedPkg() succeed! 
03-16 14:31:07.986  3646  3646 I VerificationLog: SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,03-16 14:31:08.006  1020  2957 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-16 14:31:08.016  1020  2957 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:08.016  1020  2957 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:08.016  1020  2957 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:08.036  1020  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:08.036  1020  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:08.036  1020  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:08.036  1020  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:08.046  1797  1816 W art     : Suspending all threads took: 15.666ms,
,03-16 14:31:08.056  3731  3731 E Zygote  : MountEmulatedStorage(),
03-16 14:31:08.056  3731  3731 I libpersona: KNOX_SDCARD checking this for 10135
03-16 14:31:08.056  3731  3731 E Zygote  : v2
03-16 14:31:08.056  3731  3731 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:08.056  3731  3731 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-16 14:31:08.056  3731  3731 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
03-16 14:31:08.056  3731  3731 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:08.066  1020  1730 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=3731 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,03-16 14:31:08.066  1020  1730 I ActivityManager: Killing 3018:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31,
,03-16 14:31:08.066  1020  1730 I ActivityManager: Killing 1592:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,03-16 14:31:08.096  1696  1696 D PersistentNotificationBroadcastReceiver: Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,03-16 14:31:08.106  3690  3690 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,03-16 14:31:08.126  1020  1234 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,03-16 14:31:08.126  1020  1234 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:08.126  1020  1234 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:08.126  1020  1234 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,03-16 14:31:08.126  3731  3731 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:08.136  3731  3731 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:08.146  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:08.146  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:08.146  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:08.146  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:08.156  3731  3731 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-16 14:31:08.156  3731  3731 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 14:31:08.156  3731  3731 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-16 14:31:08.166  3361  3626 D jxcore_app_log: JniHelper::setJavaVM(0xb87cf450), pthread_self() = -1194106544
,03-16 14:31:08.176  3361  3626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-16 14:31:08.176  3361  3626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-16 14:31:08.176  3361  3626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-16 14:31:08.176  3361  3626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-16 14:31:08.176  3361  3626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-16 14:31:08.176  3361  3626 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a26871f added. We now have 1 listener(s)
03-16 14:31:08.176  3753  3753 E Zygote  : MountEmulatedStorage()
03-16 14:31:08.176  3753  3753 E Zygote  : v2
03-16 14:31:08.176  3753  3753 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:08.176  3753  3753 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:08.176  3753  3753 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-16 14:31:08.186  1020  1492 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.BootCompletedReceiver: pid=3753 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-16 14:31:08.186  3753  3753 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-16 14:31:08.186  3753  3753 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 14:31:08.196  3177  3177 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
03-16 14:31:08.196  3361  3626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:51:18:22
03-16 14:31:08.196  3361  3626 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"7C:F9:0E:51:18:22"}
03-16 14:31:08.196  3361  3626 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"7C:F9:0E:51:18:22"}
03-16 14:31:08.196  3361  3626 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-16 14:31:08.196  3361  3626 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
03-16 14:31:08.206  3361  3626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-16 14:31:08.206  3361  3626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-16 14:31:08.206  3361  3626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-16 14:31:08.206  3361  3626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:51:18:22
03-16 14:31:08.206  3361  3626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-16 14:31:08.206  3361  3626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-16 14:31:08.206  3361  3626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-16 14:31:08.206  3361  3626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-16 14:31:08.206  3361  3626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-16 14:31:08.206  3361  3626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-16 14:31:08.206  3361  3626 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@99f74ca added. We now have 1 listener(s)
03-16 14:31:08.206  3361  3626 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
03-16 14:31:08.216  1020  1130 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.ClientIdService; callingUser = 0; userId(target) = 0
,03-16 14:31:08.216  1020  1130 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:08.216  1020  1130 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:08.216  1020  1130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-16 14:31:08.216  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3018/cgroup.procs: No such file or directory
,03-16 14:31:08.226  1020  1044 W libprocessgroup: failed to open /acct/uid_10072/pid_1592/cgroup.procs: No such file or directory
,03-16 14:31:08.226  3361  3626 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-16 14:31:08.226  1020  1491 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
,03-16 14:31:08.226  1020  1491 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:08.226  1020  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-16 14:31:08.226  1020  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-16 14:31:08.236  1020  3137 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-16 14:31:08.236  1020  3137 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:08.236  1020  3137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:08.236  1020  3137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,03-16 14:31:08.236  3361  3626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,03-16 14:31:08.236  3361  3626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,03-16 14:31:08.236  3361  3626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
,03-16 14:31:08.246  3361  3626 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-16 14:31:08.246  1020  3127 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppHiderService; callingUser = 0; userId(target) = 0
,03-16 14:31:08.266  1020  3127 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:08.266  1020  3127 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:08.266  1020  3127 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-16 14:31:08.266  1020  1730 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccFallbackService; callingUser = 0; userId(target) = 0
,03-16 14:31:08.266  1020  1730 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:08.266  1020  1730 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:08.266  1020  1730 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-16 14:31:08.276  3177  3177 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-16 14:31:08.276  3753  3753 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:08.276  3753  3753 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:08.296  3361  3626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-16 14:31:08.296  3102  3141 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,03-16 14:31:08.296  1020  1491 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-16 14:31:08.306  1020  1491 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:08.306  1020  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:08.306  1020  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:08.306  1020  1490 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.MccOverrideService; callingUser = 0; userId(target) = 0
,03-16 14:31:08.316  1020  1490 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:08.316  1020  1490 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-16 14:31:08.316  1020  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-16 14:31:08.316  3361  3626 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:51:18:22
,03-16 14:31:08.326  1320  1328 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-16 14:31:08.326  1020  1234 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,03-16 14:31:08.326  1020  1234 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:08.326  1020  1234 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:08.326  1020  1234 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-16 14:31:08.346  3361  3626 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-16 14:31:08.346  3361  3626 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-16 14:31:08.346  3361  3626 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-16 14:31:08.346  3361  3626 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-16 14:31:08.346  3361  3626 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-16 14:31:08.346  3361  3626 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-16 14:31:08.346  3361  3626 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-16 14:31:08.346  3361  3626 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-16 14:31:08.346  3361  3626 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,03-16 14:31:08.346  3361  3626 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-16 14:31:08.346  3361  3361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-16 14:31:08.356  3361  3361 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-16 14:31:08.406  3753  3753 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,03-16 14:31:08.406  1020  3127 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,03-16 14:31:08.406  1020  3127 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:08.406  1020  3127 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:08.406  1020  3127 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-16 14:31:08.416  3361  3361 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-16 14:31:08.436  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:08.436  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:08.436  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:08.436  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:08.446  3785  3785 E Zygote  : MountEmulatedStorage()
03-16 14:31:08.446  3785  3785 E Zygote  : v2
03-16 14:31:08.446  3785  3785 I libpersona: KNOX_SDCARD checking this for 10139
03-16 14:31:08.446  3785  3785 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:08.446  3785  3785 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-16 14:31:08.456  3785  3785 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-16 14:31:08.456  3785  3785 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-16 14:31:08.466  1020  1492 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=3785 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a,
,03-16 14:31:08.466  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:08.466  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:08.466  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:08.466  1020  1491 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:08.496  1020  1491 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=3800 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,03-16 14:31:08.506  3800  3800 E Zygote  : MountEmulatedStorage(),
03-16 14:31:08.506  3800  3800 E Zygote  : v2
03-16 14:31:08.506  3800  3800 I libpersona: KNOX_SDCARD checking this for 10042
03-16 14:31:08.506  3800  3800 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:08.506  3800  3800 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-16 14:31:08.506  3800  3800 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-16 14:31:08.506  3800  3800 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-16 14:31:08.516  1020  1492 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,03-16 14:31:08.516  1020  1492 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:08.516  1020  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:08.516  1020  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
03-16 14:31:08.516  3785  3785 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:08.526  3785  3785 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:08.546  1020  1404 I ActivityManager: Killing 2092:com.google.android.gms.wearable/u0a12 (adj 15): empty #31
,03-16 14:31:08.556  1020  3082 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-16 14:31:08.556  3361  3374 I art     : Background sticky concurrent mark sweep GC freed 28016(1809KB) AllocSpace objects, 8(128KB) LOS objects, 8% free, 10MB/11MB, paused 18.152ms total 125.389ms
,03-16 14:31:08.556  1020  3082 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:08.556  1020  3082 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:08.556  1020  3082 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-16 14:31:08.556  2617  2617 I Hs20UtilService: Starting #2
,03-16 14:31:08.566  2617  2642 I Hs20UtilService: Message received 5003
,03-16 14:31:08.566  3800  3800 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:08.566  3800  3800 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:08.576  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:08.576  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:08.576  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:08.576  1020  1492 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:08.586  3785  3785 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.,
03-16 14:31:08.586  3785  3785 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-16 14:31:08.586  3785  3785 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-16 14:31:08.586  3785  3785 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,03-16 14:31:08.586  3785  3785 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-16 14:31:08.596  3816  3816 E Zygote  : MountEmulatedStorage()
03-16 14:31:08.596  3816  3816 I libpersona: KNOX_SDCARD checking this for 10019
03-16 14:31:08.596  3816  3816 E Zygote  : v2
03-16 14:31:08.596  3816  3816 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:08.596  3816  3816 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-16 14:31:08.606  3816  3816 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-16 14:31:08.606  1020  1492 I ActivityManager: Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3816 uid=10019 gids={50019, 9997, 3003} abi=armeabi-v7a
,03-16 14:31:08.606  3816  3816 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:08.636  3816  3816 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:08.646  3816  3816 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:08.686  3800  3800 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-16 14:31:08.696  1020  1730 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingService; callingUser = 0; userId(target) = 0
,03-16 14:31:08.696  1020  1730 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:08.696  1020  1730 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:08.696  1020  1730 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,03-16 14:31:08.716  1020  1033 I ActivityManager: Killing 3040:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,03-16 14:31:08.716  1389  3083 I LockPatternUtils: isSmartCardAuthenticationAvailable: false
,03-16 14:31:08.726  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:08.726  1020  1730 D TimaService: TIMA: in getTimaVersion
,03-16 14:31:08.726  1020  1032 D TimaService: TIMA3: KeyStore3_init
03-16 14:31:08.726  1020  1032 E TLC_TZ_KEYSTORE: : Inside TZ_KEYSTORE_initialize()
03-16 14:31:08.726  1020  1032 D TimaService: TIMA: in getTimaVersion
03-16 14:31:08.726  1020  1032 I TLC_TZ_KEYSTORE: : creating new keystore context...
03-16 14:31:08.726  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:08.726  1020  1032 I TLC_TZ_KEYSTORE: : initializing ccm context...
03-16 14:31:08.726  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:08.726  1020  1032 I TLC_TZ_KEYSTORE: : root = /firmware/image, root_strlen = 15
03-16 14:31:08.726  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:08.726  1020  1032 I TLC_TZ_KEYSTORE: : process = tima_key, process_strlen = 8
03-16 14:31:08.726  1020  1032 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
03-16 14:31:08.726  1020  1032 I TZ: qc_tlc_communication: process = tima_key, process_strlen = 8
03-16 14:31:08.726  1020  1032 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 1088 = 0x440
03-16 14:31:08.726  1020  1032 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 1088 = 0x440
03-16 14:31:08.726  1020  1032 I TZ: qc_tlc_communication: max_message_size = 2176 = 0x880
03-16 14:31:08.726  1020  1032 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x880
03-16 14:31:08.726  1020  1032 D QSEECOMAPI: : App is not loaded in QSEE
,03-16 14:31:08.736  3835  3835 E Zygote  : MountEmulatedStorage()
03-16 14:31:08.736  3835  3835 I libpersona: KNOX_SDCARD checking this for 10145
03-16 14:31:08.736  3835  3835 E Zygote  : v2
03-16 14:31:08.736  3835  3835 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:08.746  3835  3835 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-16 14:31:08.746  3835  3835 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-16 14:31:08.746  3835  3835 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:08.746  1020  1033 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=3835 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,03-16 14:31:08.766  3835  3835 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:08.766  3835  3835 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:08.786  1020  1032 D QSEECOMAPI: : Loaded image: APP id = 9
,03-16 14:31:08.786  1020  1032 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_key, tzapp is loaded
03-16 14:31:08.786  1020  1032 I TLC_TZ_KEYSTORE: : ctx = 0xb8fb14e0, comm = 0xb9032890, sendmsg = 0x9f24d000, recvmsg = 0x9f24d440
03-16 14:31:08.786  1020  1032 I TZ_init: : TZ_init: sending initialization request...
,03-16 14:31:08.796  1020  1032 E TZ_init: : TZ_init Process: Secure memory is not initialized!
03-16 14:31:08.796  1020  1032 E TZ_init: : trustlet initialization failed
03-16 14:31:08.796  1020  1032 I TZ_init: : TZ_init_START...
,03-16 14:31:08.796  1020  1044 E libprocessgroup: failed to kill 1 processes for processgroup 2092
,03-16 14:31:08.796  3816  3816 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Wed Mar 16 14:31:08 GMT+01:00 2016
,03-16 14:31:08.806  1020  1032 I TZ_init: : TZ_init_with_data: sending initialization request...
,03-16 14:31:08.806  1020  1032 I TZ_init: : TZ_init: successful initialization
03-16 14:31:08.806  1020  1032 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-16 14:31:08.806  1020  1032 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 9
,03-16 14:31:08.806  1020  3082 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
03-16 14:31:08.806  1020  1032 E TLC_TZ_KEYSTORE: : Count : 1, Ret : 0
,03-16 14:31:08.806  1020  3082 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:08.806  1020  3082 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:08.806  1020  3082 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-16 14:31:08.816  1950  1950 W InstanceID/Rpc: Found 10012
,03-16 14:31:08.836  3177  3177 V Finsky  : [1] GearheadStateMonitor.onReady: sIsProjecting:false
,03-16 14:31:08.846  1950  3772 D FileApkUtils: Spent 116ms computing apk sha1.
,03-16 14:31:08.846  1950  3772 D FileApkUtils: Module already staged or being staged:chimera-modules/MapsModule.apk
,03-16 14:31:08.846  1950  3772 I art     : DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
,03-16 14:31:08.846  3816  3816 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,03-16 14:31:08.856  3712  3712 I RlzPingService: Setting next ping for 1458739868848
,03-16 14:31:08.856  1950  3772 D DexOptUtils: Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk appears to be unoptimized.
03-16 14:31:08.856  1950  3772 D DexOptUtils: Lollipop platform, using <isa> directory.
,03-16 14:31:08.856  1950  3772 D DexOptUtils: Instantiating DexClassLoader to force creation of odex.
03-16 14:31:08.856  1950  3772 D DexOptUtils: Primary ABI of odexing process is armeabi-v7a
,03-16 14:31:08.856  3835  3835 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-16 14:31:08.856  3835  3835 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 14:31:08.856  3835  3835 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,03-16 14:31:08.866  3835  3835 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-16 14:31:08.866  3835  3835 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-16 14:31:08.866  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
03-16 14:31:08.866  3690  3749 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:08.866  3690  3749 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-16 14:31:08.866  3690  3749 I AMMetaDataParserService: getResourcePackageName:assistantlist
03-16 14:31:08.866  3690  3749 I AMMetaDataParserService: Resource data:2131165186
,03-16 14:31:08.876  1020  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:08.876  1020  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:08.876  1020  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:08.876  1020  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:08.886  3855  3855 E Zygote  : MountEmulatedStorage()
03-16 14:31:08.886  3855  3855 E Zygote  : v2,
03-16 14:31:08.886  3855  3855 I libpersona: KNOX_SDCARD checking this for 10022
03-16 14:31:08.886  3855  3855 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:08.886  1020  1730 I ActivityManager: Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3855 uid=10022 gids={50022, 9997, 1028, 3003} abi=armeabi-v7a,
03-16 14:31:08.886  3855  3855 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-16 14:31:08.896  3855  3855 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-16 14:31:08.896  3855  3855 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:08.906  3800  3800 I CalendarProvider2: CalendarProvider2.onCreate() called
,03-16 14:31:08.936  1193  1193 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-16 14:31:08.936  1193  1193 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-16 14:31:08.936  1193  1193 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 14:31:08.936  1193  1193 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 14:31:08.936  1193  1193 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 14:31:08.936  1193  1193 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 14:31:08.946  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3040/cgroup.procs: No such file or directory
,03-16 14:31:08.976   291   291 E SMD     : DCD OFF
,03-16 14:31:08.986  3816  3816 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,03-16 14:31:08.996  3690  3749 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-16 14:31:08.996  3690  3749 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 14:31:08.996  3690  3749 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-16 14:31:08.996  3690  3749 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-16 14:31:08.996  3690  3749 I AMMetaDataParserService: getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
03-16 14:31:08.996  3690  3749 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 14:31:09.006  3853  3853 I dex2oat : ----------------------------------------------------,
03-16 14:31:09.006  3853  3853 I dex2oat : <SS>: S T A R T I N G . . .
03-16 14:31:09.006  3853  3853 I dex2oat : <SS>: Zip is absent. Canceled.,
03-16 14:31:09.006  3853  3853 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/MapsModule.apk --oat-fd=94 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,03-16 14:31:09.036  3855  3855 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:09.036  3855  3855 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:09.046  1020  3137 I art     : Explicit concurrent mark sweep GC freed 21845(1160KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/40MB, paused 2.813ms total 182.855ms
,03-16 14:31:09.076  3690  3749 I AMMetaDataParserService: Icon data: ResourceEnter URL2131755287android.intent.action.doInputURL2130837509
,03-16 14:31:09.086  3816  3816 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-16 14:31:09.096  1020  3082 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
,03-16 14:31:09.106  1020  3082 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:09.106  1020  3082 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:09.106  1020  3082 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-16 14:31:09.126  1020  1234 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0
,03-16 14:31:09.126  1020  1234 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:09.126  1020  1234 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:09.126  1020  1234 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:09.126  3753  3753 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.bbc.bbcagent.bbccontroller.BBCDataConsistency.checkDBConsistencyFromPM:220 com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BootCompletedReceiver.onReceive:50 
,03-16 14:31:09.136  1020  3127 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.service.BBCAgentService; callingUser = 0; userId(target) = 0
,03-16 14:31:09.136  1020  3127 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:09.136  1020  3127 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:09.136  1020  3127 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.bbc.bbcagent, destAppInfo.processName = com.samsung.android.bbc.bbcagent
,03-16 14:31:09.146  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:09.146  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:09.146  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:09.146  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:09.166  3876  3876 E Zygote  : MountEmulatedStorage(),
03-16 14:31:09.166  3876  3876 E Zygote  : v2
03-16 14:31:09.166  3876  3876 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:09.166  3876  3876 I libpersona: KNOX_SDCARD not a persona,
03-16 14:31:09.166  3876  3876 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-16 14:31:09.166  3876  3876 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-16 14:31:09.166  3876  3876 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:09.166  1020  1033 I ActivityManager: Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=3876 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-16 14:31:09.166  3816  3816 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-16 14:31:09.186  1020  3114 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,03-16 14:31:09.186  1020  3114 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:09.186  1020  3114 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:09.186  1020  3114 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-16 14:31:09.196  3876  3876 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 14:31:09.196  3876  3876 D ActivityThread: Added TimaKeyStore provider
03-16 14:31:09.196   309   309 I art     : Explicit concurrent mark sweep GC freed 8736(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 629us total 34.276ms
,03-16 14:31:09.206  3690  3749 I AMMetaDataParserService: Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,03-16 14:31:09.206  1020  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,03-16 14:31:09.216  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:09.216  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-16 14:31:09.216  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:09.216  1020  3127 I ActivityManager: Killing 1883:com.android.defcontainer/u0a4 (adj 15): empty #31
,03-16 14:31:09.226   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 624us total 21.489ms
,03-16 14:31:09.236  3690  3749 I AMMetaDataParserService: Icon data: ResourceNew Tab2131755458android.intent.action.doNewWindow2130837510
,03-16 14:31:09.246   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 630us total 16.931ms
,03-16 14:31:09.246  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
,03-16 14:31:09.246  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity,
03-16 14:31:09.246  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
03-16 14:31:09.246  3690  3749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-16 14:31:09.246  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
03-16 14:31:09.246  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
03-16 14:31:09.246  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
03-16 14:31:09.246  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
03-16 14:31:09.246  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
03-16 14:31:09.246  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
03-16 14:31:09.246  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
03-16 14:31:09.246  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
03-16 14:31:09.246  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
03-16 14:31:09.246  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
03-16 14:31:09.246  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
03-16 14:31:09.246  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
03-16 14:31:09.246  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
03-16 14:31:09.246  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
03-16 14:31:09.246  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
03-16 14:31:09.246  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
03-16 14:31:09.246  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
03-16 14:31:09.246  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
03-16 14:31:09.246  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
03-16 14:31:09.246  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
03-16 14:31:09.246  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
03-16 14:31:09.246  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
03-16 14:31:09.246  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activ,itycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
03-16 14:31:09.246  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
03-16 14:31:09.246  3876  3876 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-16 14:31:09.246  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
03-16 14:31:09.246  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
03-16 14:31:09.246  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
03-16 14:31:09.246  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
03-16 14:31:09.246  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity,
03-16 14:31:09.246  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity,
03-16 14:31:09.246  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
03-16 14:31:09.246  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
,03-16 14:31:09.256  1020  2957 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.sharing.service.NearbySharingService; callingUser = 0; userId(target) = 0
,03-16 14:31:09.286  1020  2957 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
,03-16 14:31:09.286  1020  2957 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:09.286  1020  2957 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:09.286  1020  2957 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:09.296  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.config.ConfigFetchService; callingUser = 0; userId(target) = 0
,03-16 14:31:09.296  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:09.296  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:09.296  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:09.306  1950  3872 D GCM     : COMPAT: Multi user not supported
,03-16 14:31:09.306  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,03-16 14:31:09.306  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:09.306  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:09.306  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:09.306  1020  3134 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0
,03-16 14:31:09.306  1020  3134 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:09.306  1020  3134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:09.306  1020  3134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:09.316  1020  1702 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
,03-16 14:31:09.316  1020  1702 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:09.316  1020  1702 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:09.316  1020  1702 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:09.326  3876  3876 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,03-16 14:31:09.326  1020  1234 D ActivityManager: retrieveServiceLocked(): component = com.sec.bcservice/com.sec.bcservice.BroadcastService; callingUser = 0; userId(target) = 0
,03-16 14:31:09.336  1020  1234 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:09.336  1020  1234 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:09.336  1020  1234 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,03-16 14:31:09.346  1696  3897 D GCM     : GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,03-16 14:31:09.356  3102  3141 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,03-16 14:31:09.376  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
03-16 14:31:09.376  3690  3749 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:09.376  3690  3749 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 14:31:09.376  3690  3749 I AMMetaDataParserService: Resource data:2131034113
,03-16 14:31:09.376  1696  1705 I art     : Explicit concurrent mark sweep GC freed 7216(421KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 10MB/17MB, paused 1.135ms total 45.396ms
03-16 14:31:09.376  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:09.376  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:09.376  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:09.376  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:09.376  3690  3749 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-16 14:31:09.376  3690  3749 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 14:31:09.376  3690  3749 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-16 14:31:09.386  1950  3903 I CheckinService: Disabling old GoogleServicesFramework version
,03-16 14:31:09.386  3690  3749 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-16 14:31:09.386  3690  3749 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 14:31:09.396  3904  3904 E Zygote  : MountEmulatedStorage()
,03-16 14:31:09.396  3904  3904 E Zygote  : v2
03-16 14:31:09.396  3904  3904 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:09.396  3904  3904 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:09.396  3904  3904 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-16 14:31:09.396  1020  1032 I ActivityManager: Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=3904 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-16 14:31:09.396  1020  1404 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,03-16 14:31:09.396  3690  3749 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:09.396  3904  3904 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-16 14:31:09.406  3690  3749 I GFX construct_block_size_descriptor_2d second part: took 2.596668ms for 0*0 texture 0
,03-16 14:31:09.406  3904  3904 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:09.406  1020  1404 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:09.406  1020  1404 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:09.406  1020  1404 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:09.406  1020  3134 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
,03-16 14:31:09.416  1020  3134 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:09.416  1020  3134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:09.416  1020  3134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:09.416  1020  3137 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,03-16 14:31:09.416  3690  3749 I GFX generate_partition_tables: took 6.467394ms for 0*0 texture 0
,03-16 14:31:09.426  1020  3137 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:09.426  1020  3137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-16 14:31:09.426  1020  3137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:09.426  1950  3872 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,03-16 14:31:09.426  1020  3134 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
,03-16 14:31:09.426  1020  3134 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:09.426  1020  3134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:09.426  1020  3134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:09.446  1020  1492 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0
,03-16 14:31:09.456  1020  1492 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:09.456  1020  1492 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:09.456  1020  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:09.466  1950  1950 D SystemUpdateService: onCreate
03-16 14:31:09.466  3904  3904 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:09.466  3904  3904 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:09.486  3361  3779 W jxcore-log: Initializing JXcore engine
03-16 14:31:09.486  3361  3779 W jxcore-log: JXcore engine is ready
,03-16 14:31:09.486  2676  2758 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,03-16 14:31:09.496  1950  1950 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-16 14:31:09.516  1020  3127 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-16 14:31:09.526  1020  3127 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:09.526  1020  3127 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:09.526  1020  3127 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:09.526  1950  1950 I ConfigFetchService: onStartCommand Intent { cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
03-16 14:31:09.526  1020  1730 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-16 14:31:09.526  1696  1696 I ConfigService: onCreate
03-16 14:31:09.536  1020  1730 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:09.536  1020  1730 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:09.536  1020  1730 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:09.536  1950  3930 V AuthZen : Handling intent: android.intent.action.BOOT_COMPLETED
,03-16 14:31:09.546  1020  1404 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,03-16 14:31:09.546  1950  3930 D AuthZenEventHandler: Handling event: android.intent.action.BOOT_COMPLETED
,03-16 14:31:09.566  1020  1044 E libprocessgroup: failed to kill 1 processes for processgroup 1883
,03-16 14:31:09.566  1020  1404 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:09.566  1020  1404 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:09.566  1020  1404 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:09.586  1743  1743 I GCoreUlr: DispatchingService.onCreate()
,03-16 14:31:09.586  3904  3904 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-16 14:31:09.596  1867  1867 E audit   : type=1400 msg=audit(1458135069.596:205): avc:  denied  { ioctl } for  pid=3779 comm="Thread-454" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,03-16 14:31:09.596  1867  1867 E audit   :  SEPF_SM-A500FU_5.0.2_0027
,03-16 14:31:09.596  1867  1867 E audit   : type=1300 msg=audit(1458135069.596:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=9b1378f8 items=0 ppid=309 ppcomm=main pid=3779 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm="Thread-454" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-16 14:31:09.596  1867  1867 E audit   : type=1320 msg=audit(1458135069.596:205): 
,03-16 14:31:09.606  2654  2654 D FactoryTestApp: [DummyFtClient$onDestroy](2654) Destroy DummyFtClient service
,03-16 14:31:09.606  3361  3779 W jxcore-log: Starting JXcore engine
,03-16 14:31:09.616  2654  2654 D FactoryTestApp: [Support$Values.getString](2654) id=MODEL_COMMUNICATION_MODE, value=gsm
03-16 14:31:09.616  2654  2654 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2654) mConnectionMode = gsm
03-16 14:31:09.616  2654  2654 I FactoryTestApp: [ModuleCommon$isRunningFtClient](2654) RUNNING_FTCLIENT : false
03-16 14:31:09.616  2654  2654 D FactoryTestApp: [DummyFtClient$onDestroy](2654) kill process
03-16 14:31:09.616  2654  2654 I Process : Sending signal. PID: 2654 SIG: 9
,03-16 14:31:09.706  3690  3749 I GFX raster: took 10.744374ms for 96*96 texture 0
03-16 14:31:09.706  3690  3749 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8ba1320 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8ba16a0 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:09.736  3361  3779 W jxcore-log: Platform android
03-16 14:31:09.736  3361  3779 W jxcore-log: 
,03-16 14:31:09.736  3361  3779 W jxcore-log: Process ARCH arm
03-16 14:31:09.736  3361  3779 W jxcore-log: 
,03-16 14:31:09.736  3876  3876 I F_PHONE : [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,03-16 14:31:09.746  3876  3876 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,03-16 14:31:09.746  1020  3137 D ActivityManager: retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,03-16 14:31:09.746  1020  3137 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:09.746  1020  3137 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:09.746  1020  3137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,03-16 14:31:09.746  3816  3852 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,03-16 14:31:09.756  3690  3749 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-16 14:31:09.766  1020  1234 W SEAMService:  hashset_to_int_array returning null
,03-16 14:31:09.776  1020  1032 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-16 14:31:09.796  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:09.796  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-16 14:31:09.796  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:09.806  1020  1730 W SEAMService:  hashset_to_int_array returning null
,03-16 14:31:09.816  3816  3852 I KLMS-2.5.183: : KLMSIntentService(): BOOT_COMPLETED
,03-16 14:31:09.826  3753  3753 E SQLiteLog: (284) automatic index on seams_container_info(seams_container_id)
,03-16 14:31:09.826  3753  3753 E SQLiteLog: (284) automatic index on seams_container_info(sp_id)
,03-16 14:31:09.856  1020  2957 W SEAMService:  hashset_to_int_array returning null
,03-16 14:31:09.866  3690  3749 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:09.866  3690  3749 I GFX raster: took 1.061459ms for 96*96 texture 0
03-16 14:31:09.866  3690  3749 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8ba1320 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8ba96f0 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:09.916  3904  3904 D BluetoothBDAdrressReceiver: onReceive(), action: android.intent.action.BOOT_COMPLETED
,03-16 14:31:09.916  3904  3904 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,03-16 14:31:09.926  1020  1492 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.bluetoothtest/com.sec.android.app.bluetoothtest.BluetoothBDTestService; callingUser = 0; userId(target) = 0
,03-16 14:31:09.926  1020  1492 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:09.926  1020  1492 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:09.926  1020  1492 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,03-16 14:31:09.936  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:09.936  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:09.936  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:09.936  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:09.946  1466  1466 D BluetoothBDTestService: onCreate(),
03-16 14:31:09.946  1466  1466 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
03-16 14:31:09.946  1466  1466 E BluetoothBDTestService: onStart(), extra_type: BOOT_COMPLETED,
03-16 14:31:09.956  3941  3941 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:09.946  1466  1466 E BluetoothBDTestService: bd_address_path: /efs/bluetooth/bt_addr
03-16 14:31:09.956  3941  3941 I libpersona: KNOX_SDCARD not a persona,
03-16 14:31:09.946  1466  1466 E BluetoothBDTestService: already exist!( /efs/bluetooth/bt_addr ), file length: 17
03-16 14:31:09.956  3941  3941 E Zygote  : MountEmulatedStorage()
03-16 14:31:09.956  3941  3941 E Zygote  : v2
,03-16 14:31:09.956  3941  3941 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-16 14:31:09.956  3941  3941 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
03-16 14:31:09.956  3941  3941 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:09.956  1020  1033 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=3941 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-16 14:31:09.956  1020  3114 I ActivityManager: Process com.sec.factory (pid 2654)(adj 0) has died(42,1095)
,03-16 14:31:09.986  3145  3228 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-16 14:31:09.996  3690  3749 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-16 14:31:10.006  3876  3876 D F_PHONE : [[com.sec.bcservice]] onServiceConnected()
03-16 14:31:10.006  3876  3876 I F_PHONE : default registerAction()
03-16 14:31:10.006  3876  3876 I F_PHONE : [[com.sec.bcservice]] sendPendingMessage()
,03-16 14:31:10.036  3941  3941 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:10.036  3941  3941 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:10.096  3941  3941 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-16 14:31:10.106  3361  3779 I jxcore-log: JXcore Cordova bridge is ready!
03-16 14:31:10.106  3361  3779 I jxcore-log: 
,03-16 14:31:10.106  3361  3779 W jxcore-log: JXcore engine is started
,03-16 14:31:10.106  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:10.106  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:10.106  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:10.106  1020  1033 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:10.116  3361  3626 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION,
,03-16 14:31:10.126  3958  3958 E Zygote  : MountEmulatedStorage()
03-16 14:31:10.126  3958  3958 E Zygote  : v2
03-16 14:31:10.126  3958  3958 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:10.126  3958  3958 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:10.126  3958  3958 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-16 14:31:10.126  3361  3361 I chromium: [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,03-16 14:31:10.126  3958  3958 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
03-16 14:31:10.126  3958  3958 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 14:31:10.126  1020  1033 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3958 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-16 14:31:10.136  1020  1033 I ActivityManager: Killing 3065:com.sec.android.diagmonagent/1000 (adj 15): empty #31,
,03-16 14:31:10.136  3361  3779 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-16 14:31:10.136  3361  3779 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-16 14:31:10.146  3361  3361 I chromium: [INFO:CONSOLE(62)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (62)
,03-16 14:31:10.146  3361  3361 I chromium: [INFO:CONSOLE(33)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (33)
,03-16 14:31:10.146  1020  1234 D FocusedStackFrame: Set to : 0
03-16 14:31:10.146  1020  1234 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-16 14:31:10.146  1020  1234 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-16 14:31:10.146  1020  1234 D InputDispatcher: Focused application set to: xxxx
03-16 14:31:10.146  1020  1234 D InputDispatcher: Focus left window: 3361
03-16 14:31:10.156  1020  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-16 14:31:10.156  1020  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
03-16 14:31:10.156   257   441 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (410 us)
,03-16 14:31:10.196  3361  3626 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 48ms. Plugin should use CordovaInterface.getThreadPool().
,03-16 14:31:10.196  1020  1404 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@7
,03-16 14:31:10.196  1020  1404 W ActivityManager: mDVFSHelper.acquire()
,03-16 14:31:10.256  3958  3958 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:10.266  3958  3958 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:10.296  1950  2142 I art     : Explicit concurrent mark sweep GC freed 33126(2MB) AllocSpace objects, 38(608KB) LOS objects, 40% free, 11MB/19MB, paused 1.844ms total 128.716ms,
,03-16 14:31:10.336  3690  3749 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:10.346  3690  3749 I GFX construct_block_size_descriptor_2d second part: took 2.965626ms for 0*0 texture 0
,03-16 14:31:10.356  3690  3749 I GFX generate_partition_tables: took 7.725938ms for 0*0 texture 0
,03-16 14:31:10.356  3690  3749 I GFX raster: took 11.640419ms for 96*96 texture 0
03-16 14:31:10.356  3690  3749 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8ba5e58 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ba5f90 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:10.376  3690  3749 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-16 14:31:10.416  3102  3141 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,03-16 14:31:10.456  1020  1404 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-16 14:31:10.456  1020  1404 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-16 14:31:10.456  1020  1404 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,03-16 14:31:10.466  1493  1493 D Launcher: onRestart, Launcher: 254875037
,03-16 14:31:10.476  1020  3134 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,03-16 14:31:10.526  3974  3974 D AndroidRuntime: 
03-16 14:31:10.526  3974  3974 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,03-16 14:31:10.536  3974  3974 D AndroidRuntime: CheckJNI is OFF
,03-16 14:31:10.536  3974  3974 D AndroidRuntime: readGMSProperty: start
,03-16 14:31:10.536  3974  3974 D AndroidRuntime: readGMSProperty: already setted!!
03-16 14:31:10.536  3974  3974 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-16 14:31:10.536  3974  3974 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-16 14:31:10.536  3974  3974 D AndroidRuntime: readGMSProperty: end
,03-16 14:31:10.536  3974  3974 D AndroidRuntime: addProductProperty: start
,03-16 14:31:10.576  3690  3749 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:10.576  3690  3749 I GFX raster: took 0.627396ms for 96*96 texture 0
03-16 14:31:10.576  3690  3749 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8baa910 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8baaa48 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:10.586  3690  3749 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-16 14:31:10.596  1020  3134 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:10.596  1020  3134 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:10.596  1020  3134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:10.596  3816  3816 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,03-16 14:31:10.606  3690  3749 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:10.606  3690  3749 I GFX raster: took 1.677031ms for 96*96 texture 0
03-16 14:31:10.606  3690  3749 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8ba72f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ba7450 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:10.616  3690  3749 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-16 14:31:10.626  1020  3134 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 14:31:10.636  1743  3956 I art     : Explicit concurrent mark sweep GC freed 13573(836KB) AllocSpace objects, 5(80KB) LOS objects, 39% free, 10MB/17MB, paused 1.149ms total 556.968ms
,03-16 14:31:10.656  1493  1493 D Launcher: onStart, Launcher: 254875037
03-16 14:31:10.656  1493  1493 D Launcher.HomeView: onStart
03-16 14:31:10.656  1493  1493 D Launcher: onResume, Launcher: 254875037
03-16 14:31:10.656  1020  3127 D SettingsProvider: name = kids_home_mode
03-16 14:31:10.656  1020  3127 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-16 14:31:10.656  1020  3127 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-16 14:31:10.656  1020  3127 D SettingsProvider: selectionArgs: false
03-16 14:31:10.656  1020  3127 D SettingsProvider: selectionArgs: 10007
03-16 14:31:10.656  1020  3127 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-16 14:31:10.656  1020  3127 D SettingsProvider: ret = -1
,03-16 14:31:10.656  1493  1493 D Launcher.HomeView: onResume
,03-16 14:31:10.666  1950  1950 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,03-16 14:31:10.676  1020  1020 D SensorService: [SO] activate (ident=0xb8ff81f8, enabled=0)
03-16 14:31:10.676  1020  1020 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
03-16 14:31:10.676  1020  1020 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
03-16 14:31:10.676  1020  1490 I ActivityManager: Killing 3118:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
,03-16 14:31:10.676  1389  3083 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
03-16 14:31:10.676  1020  2957 D PersonaManagerService: getPersonasForUser(): returning null!
,03-16 14:31:10.686  3974  3974 E AffinityControl: AffinityControl: registerfunction enter
,03-16 14:31:10.686  1020  1020 D SensorManager: unregisterListener ::   
,03-16 14:31:10.686  1020  1020 I Sensors : AccelerometerSensor(0) setDelay : 200000000(ns)
,03-16 14:31:10.686  3941  3941 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
,03-16 14:31:10.686  1020  1020 D SensorService: [SO] changed settle time [0]
,03-16 14:31:10.686  1020  1020 D SensorService: [SO] setDelay [200000000]
,03-16 14:31:10.696  1020  1020 D SensorService: [SO] activate (ident=0xb8ff81f8, enabled=1),
03-16 14:31:10.696  1020  1020 D SensorService: [SO] AR_init
03-16 14:31:10.696  1020  1020 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-16 14:31:10.696  3145  3228 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-16 14:31:10.696  3145  3228 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-16 14:31:10.696  3853  3853 I dex2oat : dex2oat took 1.694s (threads: 4)
,03-16 14:31:10.696  3145  3228 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,03-16 14:31:10.696  1020  1020 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
03-16 14:31:10.696  3145  3228 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-16 14:31:10.706  1389  3083 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,03-16 14:31:10.706  3145  3228 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-16 14:31:10.706  3145  3228 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-16 14:31:10.706  3145  3228 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-16 14:31:10.716  1020  1045 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@7
,03-16 14:31:10.716  3974  3974 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
03-16 14:31:10.716  1020  1045 W ActivityManager: mDVFSHelper.release()
03-16 14:31:10.716  1389  3083 I SettingSearch/SearchIntentReceiver: InitSerachDBThread thread end!
03-16 14:31:10.716  1020  1045 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  pkgName : ACTIVITY_RESUME_BOOSTER@11
03-16 14:31:10.716  1950  3772 D DexOptUtils: Odex created at:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.dex
03-16 14:31:10.716  1950  3772 D DexOptUtils: Set odex to world readable.
,03-16 14:31:10.716  1950  3772 D DexOptUtils: Renamed odex to /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.odex
,03-16 14:31:10.716  1950  3772 D FileApkUtils: Keeping up-to-date module: module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc
,03-16 14:31:10.716  3941  3988 I KnoxUsageLogPro: savePreference: key = previous_sys_time value = 1458135070728
,03-16 14:31:10.736  1020  1490 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 14:31:10.736  3941  3941 I KnoxUsageLogPro: premStatus:2
,03-16 14:31:10.746  1020  2957 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
03-16 14:31:10.746  1020  2957 D PackageManager: START PACKAGE DELETE: observer{682601548}
03-16 14:31:10.746  1020  2957 D PackageManager: pkg{<packageName>}
03-16 14:31:10.746  1020  2957 D PackageManager: user{0}
03-16 14:31:10.746  1020  2957 D PackageManager: caller{2000}
03-16 14:31:10.746  1020  2957 D PackageManager: flags{2}
03-16 14:31:10.746  1020  2957 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
03-16 14:31:10.746  1020  2957 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
03-16 14:31:10.746  1020  2957 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
03-16 14:31:10.746  1020  2957 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,03-16 14:31:10.746  1020  1065 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
03-16 14:31:10.746  1020  1065 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
03-16 14:31:10.746  1020  1065 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
03-16 14:31:10.746  1020  1065 D ApplicationPolicy: getApplicationUninstallationEnabled
03-16 14:31:10.746  1020  1065 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,03-16 14:31:10.746  1020  1234 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 14:31:10.746  1020  1065 D PackageManager: !@killApplicatoin: 10174, uninstall pkg
,03-16 14:31:10.756  3690  3749 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-16 14:31:10.756  3690  3749 I GFX raster: took 0.633490ms for 96*96 texture 0
03-16 14:31:10.756  3690  3749 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8baacf0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8baadb8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:10.756  3941  3941 I KnoxUsageLogPro: isEulaShown : false
,03-16 14:31:10.756  1020  1045 I ActivityManager: Force stopping com.test.thalitest appid=10174 user=-1: uninstall pkg
03-16 14:31:10.756  1020  1045 I ActivityManager: Killing 3361:com.test.thalitest/u0a174 (adj 1): stop com.test.thalitest cause uninstall pkg
,03-16 14:31:10.756  1950  3930 W BaseAppContext: Using Auth Proxy for data requests.
03-16 14:31:10.766  3941  3941 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
03-16 14:31:10.766  1493  1493 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-16 14:31:10.766  3958  3958 E MTPRx   : In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,03-16 14:31:10.776  3941  3988 I KnoxUsageLogPro: savePreference: key = previous_elapsed_time value = 41868
,03-16 14:31:10.786  1020  1491 I ActivityManager: Killing 3145:com.policydm/1000 (adj 15): empty #31
,03-16 14:31:10.786  1020  3134 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,03-16 14:31:10.796  3690  3749 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-16 14:31:10.796  3690  3749 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-16 14:31:10.796  3690  3749 I GFX raster: took 0.781198ms for 96*96 texture 0
03-16 14:31:10.796  3690  3749 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8ba76d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ba7828 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:10.806  3690  3749 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-16 14:31:10.826  3690  3749 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:10.826  3690  3749 I GFX raster: took 0.523125ms for 96*96 texture 0
03-16 14:31:10.826  3690  3749 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8ba16a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ba13d8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:10.826  1020  1234 I WindowState: WIN DEATH: Window{c6445d0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,03-16 14:31:10.836  3690  3749 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-16 14:31:10.836  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
03-16 14:31:10.836  3690  3749 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:10.836  3690  3749 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 14:31:10.836  3690  3749 I AMMetaDataParserService: Resource data:2131034113
,03-16 14:31:10.856  1020  1065 W PackageSettings: Skipping PackageSetting{3e6d6923 com.example.hello/10175} due to missing metadata
,03-16 14:31:10.886  3690  3749 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-16 14:31:10.886  3690  3749 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 14:31:10.886  1020  3134 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:10.886  3690  3749 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-16 14:31:10.886  1020  3134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:10.886  1020  3134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,03-16 14:31:10.886  3690  3749 I GFX raster: took 0.800521ms for 96*96 texture 0
03-16 14:31:10.886  3690  3749 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8ba1320 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8ba8558 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:10.896  1020  1234 D SecContentProvider2: uri = 14 selection = getSealedState
03-16 14:31:10.896  1020  1234 D SecContentProvider2: mCursor = null
03-16 14:31:10.896  1020  1042 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-16 14:31:10.896  1020  1130 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
03-16 14:31:10.896  1020  1130 D SecContentProvider2: mCursor = null
,03-16 14:31:10.896  1950  3772 D GmsModuleFndr: Beginning GMS chimera module scan
,03-16 14:31:10.896  3690  3749 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-16 14:31:10.906  3958  3958 V MTPRx   : sealedState: false
03-16 14:31:10.906  3958  3958 V MTPRx   : sealedUsbMassStorageState: false
,03-16 14:31:10.906  1950  1950 I Kids    : [GCoreUtils] Current gmscore version, 7899436 is smaller than the required version 8400000
,03-16 14:31:10.916  1020  3082 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 14:31:10.916  1950  3930 I GLSUser : [ChannelManager] Attempting to channel bind connection HttpClient.
,03-16 14:31:10.916  1020  1065 I ActivityManager: Force stopping com.test.thalitest appid=10174 user=0: pkg removed
,03-16 14:31:10.916  1950  3772 D GmsModuleFndr: Module pkg com.google.android.apps.kids.familylink not installed, skipping
,03-16 14:31:10.916  1950  3772 D ChimeraCfgMgr: Beginning module configuration check
,03-16 14:31:10.926  1950  3772 D ChimeraCfgMgr: Module APKs unchanged, check complete
,03-16 14:31:10.926  3690  3749 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:10.926  3690  3749 I GFX raster: took 0.824583ms for 96*96 texture 0
03-16 14:31:10.926  3690  3749 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8ba1320 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8baa550 counterpartCT=4 counterpartW=96 counterparth=96
03-16 14:31:10.926  1193  1193 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-16 14:31:10.926  1193  1193 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-16 14:31:10.926  1193  1193 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 14:31:10.926  1193  1193 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 14:31:10.926  1193  1193 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-16 14:31:10.926  1193  1193 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-16 14:31:10.936  3690  3749 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-16 14:31:10.946  1020  1065 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,03-16 14:31:10.956  3690  3749 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:10.956  3690  3749 I GFX raster: took 0.625313ms for 96*96 texture 0
03-16 14:31:10.956  3690  3749 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8ba5e58 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ba17e0 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:10.966  3690  3749 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-16 14:31:10.976  3690  3749 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:10.976  3690  3749 I GFX raster: took 0.607812ms for 96*96 texture 0
03-16 14:31:10.976  3690  3749 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8baa910 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ba5460 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:10.976  1020  1730 D SettingsProvider: name = mtp_usb_connection_status
,03-16 14:31:10.986  1020  1490 D SettingsProvider: name = media_player_mode
,03-16 14:31:10.986  3690  3749 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-16 14:31:10.986  1193  1193 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 14:31:10.996  3690  3749 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:10.996  3690  3749 I GFX raster: took 0.817656ms for 96*96 texture 0
03-16 14:31:10.996  3690  3749 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8ba72f8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ba17e0 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:10.996  1020  1033 D SettingsProvider: name = mtp_usb_conditions_met
,03-16 14:31:10.996  3690  3749 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-16 14:31:11.006  1193  1193 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 14:31:11.016  1797  1797 E SamsungIME: mOCRHelper is null
,03-16 14:31:11.016  3690  3749 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:11.016  3690  3749 I GFX raster: took 0.713750ms for 96*96 texture 0
03-16 14:31:11.016  1020  1033 D SettingsProvider: name = mtp_running_status
03-16 14:31:11.016  3690  3749 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8baacf0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ba7828 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:11.026  1020  3127 D SettingsProvider: name = media_mount_count
,03-16 14:31:11.036  3690  3749 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-16 14:31:11.036  1020  1106 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-16 14:31:11.036  1193  1193 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 14:31:11.036  1743  2072 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-16 14:31:11.046  1020  1033 D SettingsProvider: name = mtp_sync_alive
,03-16 14:31:11.046  1020  3127 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 14:31:11.056  1020  1132 V NetworkStats: removeUidsLocked() for UIDs [10174]
03-16 14:31:11.056  1020  1132 D NtpTrustedTime: currentTimeMillis() cache hit
03-16 14:31:11.056  1020  1132 V NetworkStats: performPollLocked(flags=0x3)
,03-16 14:31:11.056  1020  1132 D NetworkStatsFactory: UpdateStatsForKnox updated,
03-16 14:31:11.056  1020  1132 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,03-16 14:31:11.056  3690  3749 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:11.056  3690  3749 I GFX raster: took 0.682916ms for 96*96 texture 0
03-16 14:31:11.056  3690  3749 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8ba76d0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ba72a8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:11.066  1020  1130 D SettingsProvider: name = sdcard_launch
,03-16 14:31:11.066  1020  1132 V NetworkStats: performPollLocked() took 15ms
03-16 14:31:11.066  1020  3127 D RCPManagerService: exchangeData() failure , invalid userId
03-16 14:31:11.066  3690  3749 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
03-16 14:31:11.076  1020  1132 D NtpTrustedTime: currentTimeMillis() cache hit
,03-16 14:31:11.076  1493  1493 D MenuAppsGridFragment: onResume
,03-16 14:31:11.076  1193  1193 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 14:31:11.086  1950  3928 I SystemUpdateService: cancelUpdate (empty URL)
03-16 14:31:11.086  1950  3928 I SystemUpdateService: active receiver: disabled
,03-16 14:31:11.086  1020  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:11.086  1950  1950 I ConfigFetchService: service connected
,03-16 14:31:11.086  1020  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:11.086  1950  3913 I CheckinService: Checking schedule, now: 1458135071098 next: 1458225725438
03-16 14:31:11.086  1950  3913 I CheckinService: active receiver: disabled
,03-16 14:31:11.096  1020  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:11.096  1020  1490 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:11.096  1020  1042 D SensorService: [SO] currT = 42241592000, prevT = 41781100000, diff = 460492000, [0.192 0.421 10.266]
03-16 14:31:11.096  1020  1042 D SensorService: [SO] 0.192 0.421 10.266
03-16 14:31:11.096  1020  1042 D SensorService: [SO] [100 -> 255]
,03-16 14:31:11.096  1020  1492 D SettingsProvider: name = boot_time_connected
,03-16 14:31:11.106  4005  4005 E Zygote  : MountEmulatedStorage()
03-16 14:31:11.106  4005  4005 E Zygote  : v2
03-16 14:31:11.106  4005  4005 I libpersona: KNOX_SDCARD checking this for 10072
03-16 14:31:11.106  4005  4005 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:11.106  1020  1490 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4005 uid=10072 gids={50072, 9997} abi=armeabi-v7a,
03-16 14:31:11.106  4005  4005 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-16 14:31:11.106  4005  4005 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
03-16 14:31:11.106  3690  3749 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-16 14:31:11.106  1193  1193 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 14:31:11.106  4005  4005 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
03-16 14:31:11.106  3690  3749 I GFX raster: took 0.585938ms for 96*96 texture 0
03-16 14:31:11.106  3690  3749 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8ba16a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ba9cd8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:11.116  3690  3749 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-16 14:31:11.126  1020  1032 D SettingsProvider: name = mtp_open_session
,03-16 14:31:11.126  1020  1702 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,03-16 14:31:11.126  3690  3749 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-16 14:31:11.126  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
03-16 14:31:11.126  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
03-16 14:31:11.126  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
03-16 14:31:11.126  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
03-16 14:31:11.126  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
03-16 14:31:11.126  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
03-16 14:31:11.126  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
03-16 14:31:11.126  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
03-16 14:31:11.126  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
03-16 14:31:11.126  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
03-16 14:31:11.126  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
03-16 14:31:11.126  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
03-16 14:31:11.126  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
03-16 14:31:11.126  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
03-16 14:31:11.126  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
03-16 14:31:11.126  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
03-16 14:31:11.126  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
03-16 14:31:11.126  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
03-16 14:31:11.126  3690  3749 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:11.126  3690  3749 I AMMetaDataParserService: getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
03-16 14:31:11.126  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.ContactShortcut
03-16 14:31:11.126  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activityalias.DialShortcut
03-16 14:31:11.126  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activityalias.MessageShortcut
03-16 14:31:11.126  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
03-16 14:31:11.126  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
03-16 14:31:11.126  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
03-16 14:31:11.126  3690  3749 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:11.126  3690  3749 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-16 14:31:11.126  3690 , 3749 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 14:31:11.126  3690  3749 I AMMetaDataParserService: Resource data:2131034112
,03-16 14:31:11.146  3690  3749 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_detail
03-16 14:31:11.146  3690  3749 I AMMetaDataParserService: getResourceTypeNamexml
,03-16 14:31:11.146  3690  3749 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:11.146  1020  1702 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:11.146  1020  1702 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-16 14:31:11.146  1020  1702 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,03-16 14:31:11.146  3690  3749 I GFX raster: took 0.677395ms for 96*96 texture 0
03-16 14:31:11.146  3690  3749 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8baa910 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ba41b0 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:11.156  1193  1193 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 14:31:11.166  3690  3749 I AMMetaDataParserService: Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,03-16 14:31:11.166  4005  4005 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:11.166  4005  4005 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:11.176  1193  1193 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 14:31:11.186  1193  1193 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-16 14:31:11.186  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
,03-16 14:31:11.186  1020  1032 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
03-16 14:31:11.186  1020  1032 D SecContentProvider2: mCursor = null
,03-16 14:31:11.186  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:11.186  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:11.186  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:11.186  3690  3749 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:11.196  3690  3749 I GFX raster: took 0.627656ms for 96*96 texture 0
,03-16 14:31:11.196  3690  3749 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8baa910 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ba5460 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:11.206  3690  3749 I AMMetaDataParserService: Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,03-16 14:31:11.216  1452  1452 D RegisteredComponentCache: Collect Tech packages for Knox
,03-16 14:31:11.216  1020  1491 D ActivityManager: handle home activity for 0
,03-16 14:31:11.216  1020  1491 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
03-16 14:31:11.216  1020  1491 D KnoxTimeoutHandler: post home show event for user 0
03-16 14:31:11.216  1020  1491 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-16 14:31:11.216  1020  1491 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-16 14:31:11.216  1020  1491 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-16 14:31:11.216  1493  1493 I Choreographer: Skipped 44 frames!  The application may be doing too much work on its main thread.
,03-16 14:31:11.226  1020  1133 D NtpTrustedTime: currentTimeMillis() cache hit
03-16 14:31:11.226  1020  1133 D NtpTrustedTime: currentTimeMillis() cache hit
,03-16 14:31:11.226  1950  1950 D ConfigFetchService: ConfigApi connection successful.
,03-16 14:31:11.226   257   257 I SurfaceFlinger: id=12 createSurf (720x1280),1 flag=4, Mauncher
,03-16 14:31:11.226  1020  1049 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-16 14:31:11.236  1020  1020 D RCPManagerService: PackageReceiver onReceive()
,03-16 14:31:11.236  1020  1020 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,03-16 14:31:11.236  1020  1020 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
03-16 14:31:11.236  1020  1020 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,03-16 14:31:11.236  1020  1020 D OTPFW   : OtpDbHelper::getInstance New instance created
,03-16 14:31:11.236  1020  1020 D OTPFW   : DBIntegrity::getInstance - New instance created
,03-16 14:31:11.246  1020  1049 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-16 14:31:11.246  1452  1452 D PersonaManager: isKioskContainerExistOnDevice
,03-16 14:31:11.246  1020  1020 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10174 container id = 0
,03-16 14:31:11.246  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3065/cgroup.procs: No such file or directory
,03-16 14:31:11.246  1020  1044 W libprocessgroup: failed to open /acct/uid_10150/pid_3118/cgroup.procs: No such file or directory
,03-16 14:31:11.246  1743  3956 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
03-16 14:31:11.246  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3145/cgroup.procs: No such file or directory
,03-16 14:31:11.246  1020  1020 I OTPFW   : ProvisionData::getAllEntries Enter
,03-16 14:31:11.246  1020  1020 E OTPFW   : ProvisionData::getAllEntries Table is empty
,03-16 14:31:11.256  1020  1020 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-16 14:31:11.256  1020  1020 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
03-16 14:31:11.256  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
03-16 14:31:11.256  1020  1020 V EnterpriseBillingPolicy: uID is 10174
03-16 14:31:11.256  1020  1020 V EnterpriseBillingPolicy: Removed Packageuid is0
03-16 14:31:11.256  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,03-16 14:31:11.256  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-16 14:31:11.256  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-16 14:31:11.256  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-16 14:31:11.256  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-16 14:31:11.256  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-16 14:31:11.256  1020  3082 D InputDispatcher: Focus entered window: 1493
,03-16 14:31:11.266  1493  1493 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-16 14:31:11.266  4005  4005 D BadgeProvider: onCreate
,03-16 14:31:11.266  4005  4005 D BadgeProvider: DatabaseHelper
,03-16 14:31:11.276  1020  1052 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-16 14:31:11.276  1020  1052 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-16 14:31:11.286  1493  1493 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-16 14:31:11.306  3455  3455 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-16 14:31:11.306  3455  3455 I PCWCLIENTTRACE_PushUtil: sales region : global
03-16 14:31:11.306  3455  3455 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-16 14:31:11.306  3455  3455 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.BOOT_COMPLETED
03-16 14:31:11.306  3455  3455 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Version: 4.82
03-16 14:31:11.306  3455  3455 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Push type: [SPP, GCM]
,03-16 14:31:11.316  3690  3749 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:11.316  3690  3749 I GFX raster: took 0.670573ms for 96*96 texture 0
03-16 14:31:11.316  3690  3749 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8ba6f78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8baa0e0 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:11.326  3690  3749 I AMMetaDataParserService: Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,03-16 14:31:11.336  3455  3455 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,03-16 14:31:11.336  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,03-16 14:31:11.346  1020  1020 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1020  tag : ACTIVITY_RESUME_BOOSTER@11
,03-16 14:31:11.346  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
03-16 14:31:11.346  1020  1020 V EnterpriseBillingPolicy: uID is 10174
03-16 14:31:11.346  1020  1020 V EnterpriseBillingPolicy: Removed Packageuid is0
03-16 14:31:11.346  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
03-16 14:31:11.346  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
03-16 14:31:11.346  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
03-16 14:31:11.346  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
03-16 14:31:11.346  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,03-16 14:31:11.346  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,03-16 14:31:11.346  1020  2775 D SSRM:aZ : MSG_TYPE_APP_REMOVED::,
03-16 14:31:11.346  1020  1020 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
03-16 14:31:11.346  1020  1020 D PersonaManagerService: getPersonasForUser(): returning null!
03-16 14:31:11.346  1020  1020 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
,03-16 14:31:11.346  1020  1020 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-16 14:31:11.346  3690  3749 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:11.346  3690  3749 I GFX raster: took 0.635625ms for 96*96 texture 0
03-16 14:31:11.346  3690  3749 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b469f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb89167c8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:11.356  4005  4013 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,03-16 14:31:11.356  3690  3749 I AMMetaDataParserService: Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,03-16 14:31:11.366  1020  2957 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:11.366  1020  2957 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:11.366  1020  2957 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:11.366  1020  2957 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:11.376  1020  3082 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-16 14:31:11.386  4034  4034 E Zygote  : MountEmulatedStorage()
03-16 14:31:11.386  1020  3082 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 3361 uid 10174
03-16 14:31:11.386  4034  4034 E Zygote  : v2
03-16 14:31:11.386  4034  4034 I libpersona: KNOX_SDCARD checking this for 10104
03-16 14:31:11.386  4034  4034 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:11.386  4034  4034 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-16 14:31:11.386  1020  2957 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=4034 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
03-16 14:31:11.386  4034  4034 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-16 14:31:11.386  4034  4034 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-16 14:31:11.396  1193  1193 D PanelView: There is/are notification(s) 
,03-16 14:31:11.396  1797  1797 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-16 14:31:11.406  3455  3455 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
,03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
,03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.s,amsung.contacts.activities.GroupListActivity
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
,03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 14:31:11.406  3690  3749 I AMMetaDataParserService: Resource data:2131034113
,03-16 14:31:11.416  3690  3749 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main,
03-16 14:31:11.416  3690  3749 I AMMetaDataParserService: getResourceTypeNamexml,
,03-16 14:31:11.416  3690  3749 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-16 14:31:11.416  1020  4033 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
03-16 14:31:11.416  3690  3749 I GFX raster: took 0.855208ms for 96*96 texture 0
03-16 14:31:11.416  3690  3749 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8baa0e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b9bfa8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:11.426  3455  3455 I ReactiveServiceManager: Supported : 1
,03-16 14:31:11.426  3690  3749 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-16 14:31:11.426  1020  1702 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
,03-16 14:31:11.426  1020  1702 D QSEECOMAPI: : App is not loaded in QSEE
,03-16 14:31:11.436  4034  4034 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:11.436  4034  4034 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:11.436  1020  1052 D PersonaManager: isKioskContainerExistOnDevice
,03-16 14:31:11.436  3102  3141 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,03-16 14:31:11.446  1950  3930 I GLSUser : [ChannelManager] Checking whether channelId is enabled. isEnabledGmsCore? false, isEnabledSdk? true, isAtLeastKitKat? true
,03-16 14:31:11.446  1452  1452 D PersonaManager: isKioskContainerExistOnDevice
,03-16 14:31:11.446  3690  3749 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:11.456  3690  3749 I GFX raster: took 0.937343ms for 96*96 texture 0
03-16 14:31:11.456  3690  3749 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8baa0e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b6ca60 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:11.476  1020  1702 D QSEECOMAPI: : Loaded image: APP id = 10
,03-16 14:31:11.476  1452  1452 D RegisteredServicesCache: empty dynamic service
,03-16 14:31:11.486  3690  3749 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-16 14:31:11.486  1020  1702 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-16 14:31:11.486  1020  1702 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 10
,03-16 14:31:11.486  1020  1702 E terrier : handleString: Failed to handle string(-4)
03-16 14:31:11.486  1020  1702 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
,03-16 14:31:11.506  3690  3749 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:11.506  3690  3749 I GFX raster: took 0.612135ms for 96*96 texture 0
03-16 14:31:11.506  3690  3749 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb88efa38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b892e8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:11.506  4005  4013 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
,03-16 14:31:11.506  4005  4013 D BadgeProvider: sendNotify, [notify] : null
,03-16 14:31:11.506  4005  4013 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
,03-16 14:31:11.506  4005  4013 D BadgeProvider: update, [BadgeCount] : badgecount=0
,03-16 14:31:11.506  4005  4013 D BadgeProvider: update, [UpdateCount] : 1
,03-16 14:31:11.506  3455  3455 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
,03-16 14:31:11.506  3690  3749 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-16 14:31:11.516  1020  1044 D EnterpriseDeviceManagerService: Package has changed for user 0
,03-16 14:31:11.516  1020  1044 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,03-16 14:31:11.516  1020  1044 W TextServicesManagerService: no available spell checker services found
,03-16 14:31:11.516  3455  3455 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
,03-16 14:31:11.526  1020  2957 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:11.526  1020  2957 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:11.526  1020  2957 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:11.526  1020  2957 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:11.546  1020  2957 I ActivityManager: Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4057 uid=10146 gids={50146, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,03-16 14:31:11.546  1020  1065 I art     : Explicit concurrent mark sweep GC freed 42061(2MB) AllocSpace objects, 13(208KB) LOS objects, 33% free, 30MB/45MB, paused 3.769ms total 589.922ms
,03-16 14:31:11.546  1020  2957 I ActivityManager: Killing 3216:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,03-16 14:31:11.546  4057  4057 E Zygote  : MountEmulatedStorage()
03-16 14:31:11.546  4057  4057 I libpersona: KNOX_SDCARD checking this for 10146
03-16 14:31:11.546  4057  4057 E Zygote  : v2
03-16 14:31:11.546  4057  4057 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:11.546  4057  4057 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-16 14:31:11.546  1020  2957 I ActivityManager: Killing 3085:com.google.android.configupdater/u0a86 (adj 15): empty #32
,03-16 14:31:11.556  4057  4057 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-16 14:31:11.556  4057  4057 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:11.556  1020  1065 D PackageManager: delete codoeFile: 
,03-16 14:31:11.556  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,03-16 14:31:11.556  1020  1065 I AASA_removePackage: UID=10174 Target=com.test.thalitest
03-16 14:31:11.556  1020  1065 D AASAuninstall: userId = 0, info.removedAppID = 10174, info.uid = 10174, packageName = com.test.thalitest
,03-16 14:31:11.556  1020  1033 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
03-16 14:31:11.556  1020  1065 D PackageManager: result of delete: 1{682601548}
,03-16 14:31:11.556  1020  3127 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-16 14:31:11.556  1020  3127 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:11.556  1020  3127 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:11.556  1020  3127 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:11.556  1020  1052 I ActivityManager: Displayed Component not be shown by security: +1s356ms
,03-16 14:31:11.566  1020  1130 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
03-16 14:31:11.566  1020  1130 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,03-16 14:31:11.566  3455  3455 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-16 14:31:11.566  3455  3455 I PCWCLIENTTRACE_PushUtil: sales region : global
03-16 14:31:11.566  3455  3455 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-16 14:31:11.566  3455  3455 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,03-16 14:31:11.576  1020  1047 D SecurityLogAgent:SEDenialService: Got CLOSE_WRITE Event sk.log
,03-16 14:31:11.576   257   435 I SurfaceFlinger: id=11 Removed NainActivit (6/8)
,03-16 14:31:11.586   257   441 I SurfaceFlinger: id=11 Removed NainActivit (-2/8)
,03-16 14:31:11.596  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:11.596  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:11.596  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:11.596  1020  1032 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:11.596  3974  3974 D AndroidRuntime: Shutting down VM,
,03-16 14:31:11.596  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 14:31:11.606  1020  1047 D SecurityLogAgent:SEDenialService: Got CLOSE_WRITE Event sk.log
,03-16 14:31:11.606  4057  4057 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:11.606  4057  4057 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:11.606  4072  4072 E Zygote  : MountEmulatedStorage()
03-16 14:31:11.606  4072  4072 E Zygote  : v2
03-16 14:31:11.606  4072  4072 I libpersona: KNOX_SDCARD checking this for 10031
03-16 14:31:11.606  4072  4072 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:11.616  4072  4072 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-16 14:31:11.616  4072  4072 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-16 14:31:11.616  1020  1032 I ActivityManager: Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=4072 uid=10031 gids={50031, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,03-16 14:31:11.616  4072  4072 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-16 14:31:11.616  1020  3127 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,03-16 14:31:11.626  1020  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,03-16 14:31:11.626  1020  1065 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
03-16 14:31:11.626  1020  1065 D PackageManager: userId{-1}
03-16 14:31:11.626  1020  1065 D PackageManager: andCode{true}
,03-16 14:31:11.626  1020  1032 I ActivityManager: Killing 3259:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,03-16 14:31:11.636  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 14:31:11.646  1020  1065 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,03-16 14:31:11.656  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 14:31:11.656  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 14:31:11.666  4057  4057 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-16 14:31:11.676  4072  4072 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:11.676  1020  1065 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:11.676  1020  1065 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:11.676  4072  4072 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:11.676  4034  4034 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-16 14:31:11.676  1020  1065 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:11.676  1020  1065 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:11.696  4088  4088 E Zygote  : MountEmulatedStorage(),
03-16 14:31:11.696  4088  4088 E Zygote  : v2
03-16 14:31:11.696  4088  4088 I libpersona: KNOX_SDCARD checking this for 10004
03-16 14:31:11.696  4088  4088 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:11.696  4088  4088 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-16 14:31:11.696  4088  4088 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
03-16 14:31:11.696  4088  4088 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:11.706  1020  1065 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=4088 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,03-16 14:31:11.706  1020  1702 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
03-16 14:31:11.706  1020  1130 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,03-16 14:31:11.706  1020  1175 D TaskPersister: removeObsoleteFile: deleting file=236_task.xml
,03-16 14:31:11.706  1020  1175 D TaskPersister: removeObsoleteFile: deleting file=236_task_thumbnail.png
,03-16 14:31:11.706  1950  1950 D SystemUpdateService: onDestroy
,03-16 14:31:11.706  3690  3749 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:11.706  3690  3749 I GFX raster: took 0.621614ms for 96*96 texture 0
,03-16 14:31:11.706  3690  3749 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8baa910 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b9bfa8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:11.716  3690  3749 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-16 14:31:11.736  3690  3749 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:11.736  3690  3749 I GFX raster: took 0.847760ms for 96*96 texture 0
03-16 14:31:11.736  3690  3749 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb89167c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b6ca60 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:11.736  1020  1234 I ActivityManager: Killing 3274:com.sec.factory.camera/1000 (adj 15): empty #31
,03-16 14:31:11.746  4088  4088 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:11.746  1950  3930 I AuthZen : Fetching signing key...
,03-16 14:31:11.746  4088  4088 D ActivityThread: Added TimaKeyStore provider
03-16 14:31:11.746  3690  3749 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-16 14:31:11.756  1020  3137 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-16 14:31:11.766  3455  3464 D PCWCLIENTTRACE_AccountAppFacade2_0: unregister AuthInfo UpdateReceiver v2.0
,03-16 14:31:11.766  1950  3930 I AuthZen : Signing key fetched successfully!
,03-16 14:31:11.766  1020  3137 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:11.766  1020  3137 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-16 14:31:11.776  1020  3137 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:11.776  1020  1032 W ActivityManager: getTasks: caller 10145 does not hold GET_TASKS; limiting output
,03-16 14:31:11.776  3835  4022 I Process : Sending signal. PID: 3835 SIG: 9
,03-16 14:31:11.786  1950  3930 W BaseAppContext: Using Auth Proxy for data requests.
,03-16 14:31:11.796  4072  4072 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,03-16 14:31:11.796  1020  1032 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-16 14:31:11.796  1950  3930 I AuthZen : Starting Enrollment...
,03-16 14:31:11.796  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:11.796  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:11.796  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-16 14:31:11.816  3974  3974 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,03-16 14:31:11.826  1020  3134 I ActivityManager: Killing 3297:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,03-16 14:31:11.846  1950  3930 D AuthZen : getting auth token. Attempt 0
,03-16 14:31:11.846  1020  1491 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,03-16 14:31:11.846  1020  1491 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:11.846  1020  1491 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:11.846  1020  1491 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-16 14:31:11.856  1020  1702 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 14:31:11.866  1020  1130 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-16 14:31:11.866  1020  1130 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:11.866  1020  1130 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:11.866  1020  1130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-16 14:31:11.876  1020  1044 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,03-16 14:31:11.876  1020  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.exchange/com.android.exchange.service.ExchangeBroadcastProcessorService; callingUser = 0; userId(target) = 0
,03-16 14:31:11.876  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:11.876  1020  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:11.876  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,03-16 14:31:11.876  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 14:31:11.876  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 14:31:11.886  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 14:31:11.886  1020  1044 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-16 14:31:11.886  1020  1044 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 14:31:11.886  1020  1044 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-16 14:31:11.886  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 14:31:11.886  1020  3114 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:11.886  1020  3114 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:11.886  1020  3114 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:11.886  1020  3114 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:11.896  3800  3800 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,03-16 14:31:11.906  4108  4108 E Zygote  : MountEmulatedStorage()
,03-16 14:31:11.906  4108  4108 E Zygote  : v2
03-16 14:31:11.906  4108  4108 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:11.906  4108  4108 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:11.906  4108  4108 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-16 14:31:11.906  4108  4108 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-16 14:31:11.906  1020  3114 I ActivityManager: Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4108 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-16 14:31:11.906  4108  4108 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:11.916  1696  1705 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cryptauth
03-16 14:31:11.916  1696  1705 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cryptauth without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-16 14:31:11.916  1696  1705 I GLSUser : [GLSUser] Extracting token using key: Auth
03-16 14:31:11.916  1696  1705 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-16 14:31:11.926  1020  1404 I ActivityManager: Process com.android.email (pid 3835)(adj 9) has died(108,1094)
,03-16 14:31:11.926  1696  1705 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-16 14:31:11.926  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 14:31:11.936  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 14:31:11.936  1020  2957 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,03-16 14:31:11.946  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 14:31:11.946  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-16 14:31:11.946  1020  2957 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:11.946  1020  2957 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:11.946  1020  2957 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,03-16 14:31:11.946  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 14:31:11.946  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 14:31:11.946  1020  1130 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
03-16 14:31:11.946  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-16 14:31:11.946  1020  1130 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:11.946  1020  1130 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-16 14:31:11.946  1020  1130 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-16 14:31:11.956  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-16 14:31:11.956  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-16 14:31:11.956  1020  1044 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-16 14:31:11.956  1020  1492 I ActivityManager: Killing 3323:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31
03-16 14:31:11.956  4108  4108 D TimaKeyStoreProvider: TimaSignature is unavailable
03-16 14:31:11.956  4108  4108 D ActivityThread: Added TimaKeyStore provider
03-16 14:31:11.956  1020  1044 D UsbSettingsManager: clearDefaults: com.test.thalitest
03-16 14:31:11.966  1020  1044 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,03-16 14:31:11.976   291   291 E SMD     : DCD OFF
,03-16 14:31:11.986  1020  1044 W libprocessgroup: failed to open /acct/uid_10003/pid_3259/cgroup.procs: No such file or directory
03-16 14:31:11.986  1020  1044 W libprocessgroup: failed to open /acct/uid_10094/pid_3216/cgroup.procs: No such file or directory
03-16 14:31:11.986  1020  1044 W libprocessgroup: failed to open /acct/uid_10086/pid_3085/cgroup.procs: No such file or directory
,03-16 14:31:11.996  1020  1052 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3863cd9a u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t235} time:43143
,03-16 14:31:12.016  1020  1234 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:12.016  1020  1234 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:12.016  1020  1234 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:12.016  1020  1234 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:12.036  4125  4125 E Zygote  : MountEmulatedStorage()
03-16 14:31:12.036  4125  4125 E Zygote  : v2
03-16 14:31:12.036  4125  4125 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:12.036  4125  4125 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:12.036  4125  4125 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-16 14:31:12.036  4125  4125 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
03-16 14:31:12.036  4125  4125 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 14:31:12.036  1020  1234 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4125 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-16 14:31:12.036  1020  1234 I ActivityManager: Killing 3335:com.samsung.helphub/1000 (adj 15): empty #31
,03-16 14:31:12.046  1020  1404 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:12.046  1020  1404 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:12.046  1020  1404 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:12.046  1020  1404 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:12.056  4125  4125 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:12.056  4125  4125 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:12.056  4138  4138 E Zygote  : MountEmulatedStorage()
03-16 14:31:12.056  4138  4138 E Zygote  : v2
03-16 14:31:12.056  4138  4138 I libpersona: KNOX_SDCARD checking this for 10145
03-16 14:31:12.056  4138  4138 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:12.066  4138  4138 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-16 14:31:12.066  1020  2818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-16 14:31:12.066  4138  4138 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-16 14:31:12.066  4138  4138 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 14:31:12.066  1020  1404 I ActivityManager: Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=4138 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,03-16 14:31:12.086  4138  4138 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:12.086  4138  4138 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:12.086   309   309 I art     : Explicit concurrent mark sweep GC freed 8758(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 640us total 23.728ms
,03-16 14:31:12.096  1020  3082 I ActivityManager: Killing 3382:com.fmm.dm/1000 (adj 15): empty #31
,03-16 14:31:12.096  1020  2775 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,03-16 14:31:12.106   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 640us total 18.655ms
,03-16 14:31:12.116  4138  4138 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-16 14:31:12.116  4138  4138 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 14:31:12.116  4138  4138 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-16 14:31:12.116  4138  4138 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 14:31:12.116  4138  4138 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-16 14:31:12.126  4125  4125 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,03-16 14:31:12.126  4125  4125 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-16 14:31:12.126  4125  4125 D SecurityLogAgent: StateMachine : Current State = 1
03-16 14:31:12.126  4125  4125 D SecurityLogAgent: BootReceiver : completed task. Failed to return wakelock . 
,03-16 14:31:12.126  1020  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:12.126  1020  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:12.126  1020  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:12.126  1020  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:12.126   309   309 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 725us total 19.894ms,
,03-16 14:31:12.146  1950  3930 E AuthZen : Error getting auth token
03-16 14:31:12.146  1950  3930 E AuthZen : com.google.android.gms.auth.ad: BadAuthentication
03-16 14:31:12.146  1950  3930 E AuthZen : 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-16 14:31:12.146  1950  3930 E AuthZen : 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-16 14:31:12.146  1950  3930 E AuthZen : 	at com.google.android.gms.auth.p.a(SourceFile:318)
03-16 14:31:12.146  1950  3930 E AuthZen : 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:381)
03-16 14:31:12.146  1950  3930 E AuthZen : 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:132)
03-16 14:31:12.146  1950  3930 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
03-16 14:31:12.146  1950  3930 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
03-16 14:31:12.146  1950  3930 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
03-16 14:31:12.146  1950  3930 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
03-16 14:31:12.146  1950  3930 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
03-16 14:31:12.146  1950  3930 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
03-16 14:31:12.146  1950  3930 E AuthZen : 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
03-16 14:31:12.146  1950  3930 E AuthZen : 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
03-16 14:31:12.146  1950  3930 E AuthZen : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-16 14:31:12.146  1950  3930 E AuthZen : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 14:31:12.146  1950  3930 E AuthZen : 	at android.os.Looper.loop(Looper.java:145)
03-16 14:31:12.146  1950  3930 E AuthZen : 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-16 14:31:12.156  3690  3749 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:12.156  1950  3930 E AuthZen : Failed to do enrollment for account: thalitester@gmail.com
03-16 14:31:12.156  1950  3930 E AuthZen : com.google.android.gms.auth.authzen.b.b: Failed to get a token for authzen enrollment
03-16 14:31:12.156  1950  3930 E AuthZen : 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:139)
03-16 14:31:12.156  1950  3930 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
03-16 14:31:12.156  1950  3930 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
03-16 14:31:12.156  1950  3930 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
03-16 14:31:12.156  1950  3930 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
03-16 14:31:12.156  1950  3930 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
03-16 14:31:12.156  1950  3930 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
03-16 14:31:12.156  1950  3930 E AuthZen : 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
03-16 14:31:12.156  1950  3930 E AuthZen : 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
03-16 14:31:12.156  1950  3930 E AuthZen : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-16 14:31:12.156  1950  3930 E AuthZen : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 14:31:12.156  1950  3930 E AuthZen : 	at android.os.Looper.loop(Looper.java:145)
03-16 14:31:12.156  1950  3930 E AuthZen : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-16 14:31:12.156  3690  3749 I GFX raster: took 0.817916ms for 96*96 texture 0
03-16 14:31:12.156  3690  3749 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b469f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b892e8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:12.156  1493  1493 I Choreographer: Skipped 45 frames!  The application may be doing too much work on its main thread.
,03-16 14:31:12.156  1493  1493 D Launcher.Model: reloadBadges entered.
,03-16 14:31:12.166  1493  1493 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-16 14:31:12.166  1493  1493 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
03-16 14:31:12.166  3690  3749 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-16 14:31:12.176  4158  4158 E Zygote  : MountEmulatedStorage(),
03-16 14:31:12.176  4158  4158 E Zygote  : v2
03-16 14:31:12.176  4158  4158 I libpersona: KNOX_SDCARD checking this for 10152
03-16 14:31:12.176  4158  4158 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:12.186  4158  4158 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
03-16 14:31:12.186  3690  3749 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:12.186  3690  3749 I GFX raster: took 1.008281ms for 96*96 texture 0
03-16 14:31:12.186  3690  3749 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8b6ca60 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b9bfa8 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:12.186  4158  4158 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-16 14:31:12.186  1493  1493 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2cd6ed9b time:43335
,03-16 14:31:12.186  4158  4158 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:12.186  1020  1702 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=4158 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
,03-16 14:31:12.186  1020  1702 I ActivityManager: Killing 3398:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
,03-16 14:31:12.196  3690  3749 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-16 14:31:12.226  1020  3082 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 14:31:12.226  1950  3930 D a       : Opening database auth.proximity.permit_store...
,03-16 14:31:12.226  4158  4158 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:12.226  4158  4158 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:12.236  1020  1702 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 14:31:12.256  1020  1730 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 14:31:12.256  1020  1702 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 14:31:12.296  4005  4013 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,03-16 14:31:12.296  1020  1702 W ActivityManager: getTasks: caller 10146 does not hold GET_TASKS; limiting output
,03-16 14:31:12.296  1020  3134 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 14:31:12.296  4057  4123 I Process : Sending signal. PID: 4057 SIG: 9
,03-16 14:31:12.306  1020  1404 D RCPManagerService: exchangeData() failure , invalid userId
,03-16 14:31:12.306  1950  3930 D AuthZenTransactionCache: Initialized cache in: /data/data/com.google.android.gms/files
03-16 14:31:12.306  1950  3930 D AuthZenTransactionCache: Clearing transaction cache
,03-16 14:31:12.306  4158  4158 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
,03-16 14:31:12.316  1020  1044 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,03-16 14:31:12.316  1020  1702 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
,03-16 14:31:12.326  1020  1702 W ActivityManager: userId = 0, bbcId = -10000
03-16 14:31:12.326  1020  1702 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:12.326  1020  1702 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
,03-16 14:31:12.326  1020  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:12.326  1020  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:12.326  1020  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:12.326  1020  1730 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:12.346  4184  4184 E Zygote  : MountEmulatedStorage(),
03-16 14:31:12.346  4184  4184 E Zygote  : v2,
03-16 14:31:12.346  4184  4184 I libpersona: KNOX_SDCARD checking this for 1000,
03-16 14:31:12.346  4184  4184 I libpersona: KNOX_SDCARD not a persona,
03-16 14:31:12.346  4184  4184 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-16 14:31:12.346  4005  4167 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
03-16 14:31:12.346  4005  4167 D BadgeProvider: sendNotify, [notify] : null
03-16 14:31:12.346  4005  4167 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
03-16 14:31:12.346  4005  4167 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-16 14:31:12.346  4005  4167 D BadgeProvider: update, [UpdateCount] : 1
,03-16 14:31:12.346  1493  1493 D Launcher.Model: reloadBadges entered.
,03-16 14:31:12.346  1020  1730 I ActivityManager: Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=4184 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-16 14:31:12.346  4184  4184 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-16 14:31:12.356   254   254 E lowmemorykiller: Error writing /proc/4057/oom_score_adj; errno=22
,03-16 14:31:12.356  4184  4184 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:12.356  1743  3956 I GCoreUlr: WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,03-16 14:31:12.356  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3274/cgroup.procs: No such file or directory
03-16 14:31:12.356  1020  1044 W libprocessgroup: failed to open /acct/uid_10100/pid_3297/cgroup.procs: No such file or directory
03-16 14:31:12.356  1020  1044 W libprocessgroup: failed to open /acct/uid_10060/pid_3323/cgroup.procs: No such file or directory
03-16 14:31:12.356  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3382/cgroup.procs: No such file or directory
03-16 14:31:12.356  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3335/cgroup.procs: No such file or directory
,03-16 14:31:12.366  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3398/cgroup.procs: No such file or directory
,03-16 14:31:12.366   254   254 E lowmemorykiller: Error writing /proc/4057/oom_score_adj; errno=22
,03-16 14:31:12.376  1020  1234 I ActivityManager: Killing 3418:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,03-16 14:31:12.386  1020  1404 I ActivityManager: Process com.android.exchange (pid 4057)(adj 13) has died(91,1106)
,03-16 14:31:12.386  4184  4184 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:12.386  4184  4184 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:12.386  1743  3956 I GCoreUlr: Unbound from all location providers
,03-16 14:31:12.416  1020  1044 W libprocessgroup: failed to open /acct/uid_10062/pid_3418/cgroup.procs: No such file or directory
,03-16 14:31:12.416  1020  1234 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:12.416  1020  1234 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:12.416  1020  1234 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:12.416  1020  1234 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:12.436  4202  4202 E Zygote  : MountEmulatedStorage()
03-16 14:31:12.436  4202  4202 I libpersona: KNOX_SDCARD checking this for 1101
03-16 14:31:12.436  4202  4202 E Zygote  : v2
03-16 14:31:12.436  4202  4202 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:12.436  4202  4202 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-16 14:31:12.436  1020  1234 I ActivityManager: Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=4202 uid=1101 gids={41101, 9997} abi=armeabi-v7a
,03-16 14:31:12.436  4202  4202 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-16 14:31:12.436  4202  4202 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:12.446  1696  1696 E SQLiteLog: (10) POSIX Error : 11 SQLite Error : 3850
,03-16 14:31:12.446  3102  3141 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,03-16 14:31:12.456  1743  1743 I GCoreUlr: DispatchingService.onDestroy()
,03-16 14:31:12.456  1743  1743 I GCoreUlr: Unbound from all location providers
,03-16 14:31:12.466  4202  4202 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:12.466  4202  4202 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:12.486  4202  4202 W ResourcesManager: Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
,03-16 14:31:12.496  4202  4202 V SmartcardService: main Received broadcast
03-16 14:31:12.496  4202  4202 V SmartcardService: Starting smartcard service after boot completed
,03-16 14:31:12.496  1020  2957 D ActivityManager: retrieveServiceLocked(): component = org.simalliance.openmobileapi.service/org.simalliance.openmobileapi.service.SmartcardService; callingUser = 0; userId(target) = 0
,03-16 14:31:12.496  1020  2957 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:12.496  1020  2957 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:12.496  1020  2957 W ActivityManager: NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
,03-16 14:31:12.496  1020  1130 I ActivityManager: Killing 3471:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,03-16 14:31:12.506  4072  4072 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.40254', coreVersion = '2.6.3.16956', ro.csc.sales_code=XEO
,03-16 14:31:12.506  1020  1490 D ActivityManager: retrieveServiceLocked(): component = com.android.stk/com.android.stk.StkAppService; callingUser = 0; userId(target) = 0
,03-16 14:31:12.506  1020  1490 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:12.506  1020  1490 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:12.506  1020  1490 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,03-16 14:31:12.506  1020  3082 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:12.516  1020  3082 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:12.516  1020  3082 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:12.516  1020  3082 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:12.526  4219  4219 E Zygote  : MountEmulatedStorage()
,03-16 14:31:12.526  1020  2775 D SSRM:n  : SIOP:: AP = 410
03-16 14:31:12.526  4219  4219 E Zygote  : v2
03-16 14:31:12.526  4219  4219 I libpersona: KNOX_SDCARD checking this for 1000
03-16 14:31:12.526  4219  4219 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:12.526  4219  4219 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-16 14:31:12.526  1020  3082 I ActivityManager: Start proc com.sec.android.app.sysscope for broadcast com.sec.android.app.sysscope/.receiver.BootCompleteReceiver: pid=4219 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-16 14:31:12.526  4219  4219 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-16 14:31:12.536  4219  4219 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-16 14:31:12.546  1020  2957 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
03-16 14:31:12.546  1020  2957 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,03-16 14:31:12.556  1020  1404 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,03-16 14:31:12.556  1020  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,03-16 14:31:12.566  4219  4219 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:12.566  4219  4219 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:12.586  4072  4072 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.3.16956, SDK: 2.0.2173, EDM:16956
,03-16 14:31:12.596  4219  4219 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
,03-16 14:31:12.596  1020  3134 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.sysscope/com.sec.android.app.sysscope.service.SysScopeService; callingUser = 0; userId(target) = 0
,03-16 14:31:12.596  1020  3134 W ActivityManager: userId = 0, bbcId = -10000
,03-16 14:31:12.596  1020  3134 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-16 14:31:12.596  1020  3134 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.sysscope, destAppInfo.processName = com.sec.android.app.sysscope
,03-16 14:31:12.606  1020  3082 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:12.606  1020  3082 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:12.606  1020  3082 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:12.606  1020  3082 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:12.606  1020  1044 W libprocessgroup: failed to open /acct/uid_1000/pid_3471/cgroup.procs: No such file or directory
,03-16 14:31:12.616  3690  3749 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-16 14:31:12.626  4236  4236 I libpersona: KNOX_SDCARD checking this for 10157
03-16 14:31:12.626  3690  3749 I GFX raster: took 0.621146ms for 96*96 texture 0
03-16 14:31:12.626  4236  4236 I libpersona: KNOX_SDCARD not a persona
03-16 14:31:12.626  3690  3749 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8ba1170 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ba1228 counterpartCT=4 counterpartW=96 counterparth=96
03-16 14:31:12.626  1020  3082 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=4236 uid=10157 gids={50157, 9997} abi=armeabi-v7a
03-16 14:31:12.626  4236  4236 E Zygote  : MountEmulatedStorage()
03-16 14:31:12.626  4236  4236 E Zygote  : v2
03-16 14:31:12.626  4236  4236 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-16 14:31:12.626  4236  4236 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-16 14:31:12.626  4236  4236 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-16 14:31:12.626  3690  3749 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-16 14:31:12.636  1696  1728 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
03-16 14:31:12.636  1696  1728 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,03-16 14:31:12.636  1696  1728 E DatabaseUtils: Writing exception to parcel
03-16 14:31:12.636  1696  1728 E DatabaseUtils: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-16 14:31:12.636  1696  1728 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
03-16 14:31:12.636  1696  1728 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
03-16 14:31:12.636  1696  1728 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
03-16 14:31:12.636  1696  1728 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
03-16 14:31:12.636  1696  1728 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
03-16 14:31:12.636  1696  1728 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
03-16 14:31:12.636  1696  1728 E DatabaseUtils: 	at com.google.android.gsf.subscribedfeeds.AbstractSyncableContentProvider.delete(AbstractSyncableContentProvider.java:312)
03-16 14:31:12.636  1696  1728 E DatabaseUtils: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:324)
03-16 14:31:12.636  1696  1728 E DatabaseUtils: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:206)
03-16 14:31:12.636  1696  1728 E DatabaseUtils: 	at android.os.Binder.execTransact(Binder.java:461)
,03-16 14:31:12.656  4236  4236 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:12.656  4236  4236 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:12.666  4236  4236 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-16 14:31:12.686  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
03-16 14:31:12.686  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
03-16 14:31:12.686  3690  3749 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:12.686  3690  3749 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-16 14:31:12.686  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
03-16 14:31:12.686  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
03-16 14:31:12.686  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
03-16 14:31:12.686  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
03-16 14:31:12.686  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
03-16 14:31:12.686  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
03-16 14:31:12.686  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
03-16 14:31:12.686  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
03-16 14:31:12.686  3690  3749 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-16 14:31:12.686  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
03-16 14:31:12.686  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
03-16 14:31:12.686  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
03-16 14:31:12.686  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
03-16 14:31:12.686  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
03-16 14:31:12.686  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
03-16 14:31:12.686  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
03-16 14:31:12.686  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
03-16 14:31:12.686  3690  3749 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:12.686  3690  3749 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-16 14:31:12.686  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
03-16 14:31:12.686  3690  3749 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:12.686  3690  3749 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-16 14:31:12.686  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
03-16 14:31:12.,686  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,03-16 14:31:12.696  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
,03-16 14:31:12.696  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
,03-16 14:31:12.696  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
03-16 14:31:12.706  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.Welcome
03-16 14:31:12.706  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
03-16 14:31:12.706  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
03-16 14:31:12.706  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
03-16 14:31:12.706  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
03-16 14:31:12.706  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
03-16 14:31:12.706  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
03-16 14:31:12.706  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
03-16 14:31:12.706  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
03-16 14:31:12.706  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
03-16 14:31:12.706  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
03-16 14:31:12.706  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
03-16 14:31:12.706  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
03-16 14:31:12.706  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.DataConnection
03-16 14:31:12.706  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
03-16 14:31:12.706  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
03-16 14:31:12.706  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
03-16 14:31:12.706  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
03-16 14:31:12.706  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
03-16 14:31:12.706  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
03-16 14:31:12.706  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
03-16 14:31:12.706  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
03-16 14:31:12.706  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
03-16 14:31:12.706  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
03-16 14:31:12.706  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
03-16 14:31:12.706  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
03-16 ,14:31:12.706  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.Debug
03-16 14:31:12.706  3690  3749 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageListXL
03-16 14:31:12.706  3690  3749 I AMMetaDataParserService: Resource data:Inside bundle  check
03-16 14:31:12.706  3690  3749 I AMMetaDataParserService: getResourcePackageName:assistant
03-16 14:31:12.706  3690  3749 I AMMetaDataParserService: Resource data:2131165203
,03-16 14:31:12.706  3690  3749 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-16 14:31:12.706  3690  3749 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-16 14:31:12.706  3690  3749 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-16 14:31:12.706  3690  3749 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-16 14:31:12.706  3690  3749 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-16 14:31:12.716  1020  1404 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:12.716  1020  1404 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:12.716  1020  1404 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-16 14:31:12.716  1020  1404 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-16 14:31:12.726  4255  4255 E Zygote  : MountEmulatedStorage()
,03-16 14:31:12.726  4255  4255 E Zygote  : v2
03-16 14:31:12.726  4255  4255 I libpersona: KNOX_SDCARD checking this for 10159
03-16 14:31:12.726  4255  4255 I libpersona: KNOX_SDCARD not a persona
,03-16 14:31:12.726  4255  4255 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-16 14:31:12.726  1020  1404 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=4255 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-16 14:31:12.736  4255  4255 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-16 14:31:12.736  1020  1404 I ActivityManager: Killing 3490:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
03-16 14:31:12.736  3690  3749 I AMMetaDataParserService: getResourceName:com.android.email:xml/email_assistant_menu
03-16 14:31:12.736  3690  3749 I AMMetaDataParserService: getResourceTypeNamexml
03-16 14:31:12.736  4255  4255 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,03-16 14:31:12.736  3690  3749 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-16 14:31:12.736  3690  3749 I GFX construct_block_size_descriptor_2d second part: took 2.756510ms for 0*0 texture 0
,03-16 14:31:12.756  4255  4255 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-16 14:31:12.756  4255  4255 D ActivityThread: Added TimaKeyStore provider
,03-16 14:31:12.766  3690  3749 I GFX generate_partition_tables: took 10.782134ms for 0*0 texture 0
,03-16 14:31:12.766  3690  3749 I GFX raster: took 14.497446ms for 96*96 texture 0
03-16 14:31:12.766  3690  3749 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8d59a78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8d59ab0 counterpartCT=4 counterpartW=96 counterparth=96
,03-16 14:31:12.786  3690  3749 I AMMetaDataParserService: Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,03-16 14:31:12.786  3690  3749 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu" with flag (131138) and mode_t (0) due to error (30)
,03-16 14:31:12.786  3690  3749 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.app.assistantmenu/databases/AssistantMenu'.
03-16 14:31:12.786  3690  3749 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-16 14:31:12.786  3690  3749 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-16 14:31:12.786  3690  3749 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-16 14:31:12.786  3690  3749 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-16 14:31:12.786  3690  3749 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-16 14:31:12.786  3690  3749 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-16 14:31:12.786  3690  3749 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-16 14:31:12.786  3690  3749 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-16 14:31:12.786  3690  3749 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-16 14:31:12.786  3690  3749 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-16 14:31:12.786  3690  3749 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-16 14:31:12.786  3690  3749 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-16 14:31:12.786  3690  3749 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-16 14:31:12.786  3690  3749 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-16 14:31:12.786  3690  3749 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:63)
03-16 14:31:12.786  3690  3749 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
03-16 14:31:12.786  3690  3749 E SQLiteDatabase: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
03-16 14:31:12.786  3690  3749 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-16 14:31:12.786  3690  3749 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 14:31:12.786  3690  3749 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
03-16 14:31:12.786  3690  3749 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-16 14:31:12.786  3690  3749 W System.err: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-16 14:31:12.786  3690  3749 W System.err: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-16 14:31:12.786  3690  3749 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
03-16 14:31:12.786  3690  3749 W System.err: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
03-16 14:31:12.786  3690  3749 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
03-16 14:31:12.786  3690  3749 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
03-16 14:31:12.786  3690  3749 W System.err: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-16 14:31:12.786  3690  3749 W System.err: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
03-16 14:31:12.786  3690  3749 W System.err: 	at andro,id.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
03-16 14:31:12.786  3690  3749 W System.err: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
03-16 14:31:12.786  3690  3749 W System.err: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
03-16 14:31:12.786  3690  3749 W System.err: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
03-16 14:31:12.786  3690  3749 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-16 14:31:12.786  3690  3749 W System.err: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-16 14:31:12.786  3690  3749 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.DatabaseHandler.addAMData(DatabaseHandler.java:63)
03-16 14:31:12.786  3690  3749 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.constructDBdata(AMMetaDataParserService.java:197)
03-16 14:31:12.786  3690  3749 W System.err: 	at com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent(AMMetaDataParserService.java:87)
03-16 14:31:12.786  3690  3749 W System.err: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-16 14:31:12.786  3690  3749 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-16 14:31:12.786  3690  3749 W System.err: 	at android.os.Looper.loop(Looper.java:145)
03-16 14:31:12.786  3690  3749 W System.err: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-16 14:31:12.796  4255  4255 I Intent to TravelDirActivity: inside TravelBroadcastReceiver
,03-16 14:31:12.796  1950  4193 E AndroidRuntime: FATAL EXCEPTION: SyncAdapterThread-2
03-16 14:31:12.796  1950  4193 E AndroidRuntime: Process: com.google.android.gms, PID: 1950
03-16 14:31:12.796  1950  4193 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
03-16 14:31:12.796  1950  4193 E AndroidRuntime: 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:179)
03-16 14:31:12.796  1950  4193 E AndroidRuntime: 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
03-16 14:31:12.796  1950  4193 E AndroidRuntime: 	at android.content.ContentProviderProxy.delete(ContentProviderNative.java:543)
03-16 14:31:12.796  1950  4193 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1352)
03-16 14:31:12.796  1950  4193 E AndroidRuntime: 	at com.google.android.gms.auth.api.credentials.sync.a.a(SourceFile:91)
03-16 14:31:12.796  1950  4193 E AndroidRuntime: 	at com.google.android.gms.common.j.a.onPerformSync(SourceFile:81)
03-16 14:31:12.796  1950  4193 E AndroidRuntime: 	at android.content.AbstractThreadedSyncAdapter$SyncThread.run(AbstractThreadedSyncAdapter.java:259)
,03-16 14:31:12.796  1020  1492 I ActivityManager: Killing 3511:com.sec.android.app.mt/1000 (adj 15): empty #31
,03-16 14:31:12.806  4072  4072 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,03-16 14:31:12.806  1020  1491 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms
,03-16 14:31:12.806  4072  4072 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,03-16 14:31:12.816  4072  4072 D DialogFlow: initQueue()
,03-16 14:31:12.816  1020  4273 E DropBoxManagerService: Can't write: system_app_crash
03-16 14:31:12.816  1020  4273 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop170.tmp: open failed: EROFS (Read-only file system)
03-16 14:31:12.816  1020  4273 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
03-16 14:31:12.816  1020  4273 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
03-16 14:31:12.816  1020  4273 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
03-16 14:31:12.816  1020  4273 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
03-16 14:31:12.816  1020  4273 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
03-16 14:31:12.816  1020  4273 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$25.run(ActivityManagerService.java:15884)
03-16 14:31:12.816  1020  4273 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
03-16 14:31:12.816  1020  4273 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
03-16 14:31:12.816  1020  4273 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
03-16 14:31:12.816  1020  4273 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-16 14:31:12.816  1020  4273 E DropBoxManagerService: 	... 5 more
,03-16 14:31:12.816  1020  3082 I ActivityManager: Killing 3528:com.fmm.ds/1000 (adj 15): empty #31
,03-16 14:31:12.826  1020  1045 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-16 14:31:12.826  1020  1045 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-16 14:31:12.836  1020  1045 D PhoneWindow: *FMB* installDecor mIsFloating : true
03-16 14:31:12.836  1020  1045 D PhoneWindow: *FMB* installDecor flags : 8519682

```
