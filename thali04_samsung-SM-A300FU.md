#### Test 845006541a293f3_thali04_samsung-SM-A300FU Logs


```
--------- beginning of system
09-09 16:41:47.007   258   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
09-09 16:41:47.007   258   520 W Vold    : Returning OperationFailed - no handler for errno 0
--------- beginning of main
09-09 16:41:47.017  7091  7091 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
09-09 16:41:47.017  7091  7091 D SLinkSource: Samsung link source created
09-09 16:41:47.047  6998  6998 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@253c4a69: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
09-09 16:41:47.047  6998  6998 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-09 16:41:47.047  6998  6998 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
09-09 16:41:47.057  1020  1221 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
09-09 16:41:47.067  6998  6998 D ChimeraCfgMgr: Reading stored module config
09-09 16:41:47.067  1020  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:47.067  1020  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:47.067  1020  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:41:47.067  1020  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:47.067  1020  1541 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-09 16:41:47.077  7133  7133 E Zygote  : MountEmulatedStorage()
09-09 16:41:47.077  7133  7133 E Zygote  : v2
09-09 16:41:47.077  7133  7133 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 16:41:47.077  7133  7133 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 16:41:47.077  7133  7133 I libpersona: KNOX_SDCARD checking this for 1000
09-09 16:41:47.077  7133  7133 I libpersona: KNOX_SDCARD not a persona
09-09 16:41:47.077  1020  1221 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=7133 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-09 16:41:47.077  1020  1221 I ActivityManager: Killing 6729:com.qualcomm.timeservice/1000 (adj 15): empty #21
09-09 16:41:47.087  7133  7133 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 16:41:47.087  1020  4356 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
09-09 16:41:47.087  1020  4356 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
09-09 16:41:47.097  2007  2007 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
09-09 16:41:47.107  7091  7127 D ContactProvider: getAllContactInfoList Start
09-09 16:41:47.107  1020  1506 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
09-09 16:41:47.107  7091  7091 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
09-09 16:41:47.117  7133  7133 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 16:41:47.117  7133  7133 D ActivityThread: Added TimaKeyStore provider
09-09 16:41:47.137  6998  7012 W art     : Suspending all threads took: 9.488ms
09-09 16:41:47.147  7133  7133 D FilterInstaller: onReceive:android.intent.action.PACKAGE_REMOVED, package:com.test.thalitest
09-09 16:41:47.147  7091  7127 D ContactProvider: getAllContactInfoList End
09-09 16:41:47.147  7133  7133 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
09-09 16:41:47.147  1020  1339 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
09-09 16:41:47.147  1020  1339 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
09-09 16:41:47.147  7091  7127 I syncContacts: thread: 1328, sync time = 98
09-09 16:41:47.147  1020  1339 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:47.147  1020  1339 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:41:47.147  1020  1339 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
09-09 16:41:47.147  1020  1330 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast
09-09 16:41:47.157  1020  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:47.157  1020  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:47.157  1020  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:47.157  1020  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:47.157  7133  7133 I FilterInstaller: FilterPackageService : ACTION_PACKAGE_REMOVED
09-09 16:41:47.157  7133  7153 I FilterInstaller: FilterPackageService : ACTION_REMOVED
09-09 16:41:47.167  7133  7153 D FilterUnInstaller: before removeFromFS
09-09 16:41:47.177  1020  1330 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7154 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
09-09 16:41:47.177  1020  1540 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.provider.filterprovider
09-09 16:41:47.177  7154  7154 E Zygote  : MountEmulatedStorage()
09-09 16:41:47.177  7154  7154 I libpersona: KNOX_SDCARD checking this for 10098
09-09 16:41:47.177  7154  7154 E Zygote  : v2
09-09 16:41:47.177  7154  7154 I libpersona: KNOX_SDCARD not a persona
09-09 16:41:47.187  7154  7154 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 16:41:47.187  1020  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:47.187  1020  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:47.187  1020  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:47.187  1020  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:47.187  7154  7154 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 16:41:47.187  7154  7154 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 16:41:47.197  7166  7166 E Zygote  : MountEmulatedStorage()
09-09 16:41:47.197  7166  7166 E Zygote  : v2
09-09 16:41:47.197  7166  7166 I libpersona: KNOX_SDCARD checking this for 10095
09-09 16:41:47.197  7166  7166 I libpersona: KNOX_SDCARD not a persona
09-09 16:41:47.197  7166  7166 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 16:41:47.207  1020  1540 I ActivityManager: Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=7166 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
09-09 16:41:47.207  7166  7166 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 16:41:47.207  7166  7166 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 16:41:47.217  6175  6175 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
09-09 16:41:47.217  1020  4356 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
09-09 16:41:47.217  1020  4356 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
09-09 16:41:47.227  1020  4356 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:47.227  1020  4356 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:41:47.227  1020  4356 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
09-09 16:41:47.227  6998  7131 D NativeLibraryUtils: Install completed successfully. count=12 extracted=0
09-09 16:41:47.237  7154  7154 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 16:41:47.237  7154  7154 D ActivityThread: Added TimaKeyStore provider
09-09 16:41:47.237  7166  7166 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 16:41:47.237  7166  7166 D ActivityThread: Added TimaKeyStore provider
09-09 16:41:47.257  6175  7181 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
09-09 16:41:47.257  6175  7181 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
09-09 16:41:47.267  1020  1216 I ActivityManager: Killing 6655:com.android.providers.calendar/u0a37 (adj 15): empty #21
09-09 16:41:47.277  6923  7087 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
09-09 16:41:47.277  6923  7087 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
09-09 16:41:47.287  1020  1541 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
09-09 16:41:47.287  1020  1541 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:47.287  1020  1541 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:47.287  1020  1541 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:47.297  1020  1541 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:47.297  7166  7166 D PreloadFilterInstaller: uses FILTER_DB_VER_1
09-09 16:41:47.307  7166  7166 E SQLiteLog: (284) automatic index on titles(filter_id)
09-09 16:41:47.307  7188  7188 E Zygote  : MountEmulatedStorage()
09-09 16:41:47.307  7188  7188 E Zygote  : v2
09-09 16:41:47.307  7188  7188 I libpersona: KNOX_SDCARD checking this for 1000
09-09 16:41:47.307  7188  7188 I libpersona: KNOX_SDCARD not a persona
09-09 16:41:47.307  7188  7188 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 16:41:47.307  7188  7188 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 16:41:47.317  1020  1541 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7188 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-09 16:41:47.317  1020  1541 I ActivityManager: Killing 6769:com.sec.android.widgetapp.SPlannerAppWidget/u0a130 (adj 15): empty #21
09-09 16:41:47.317  7188  7188 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 16:41:47.337  6998  6998 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
09-09 16:41:47.337  6998  6998 I art     : Rejecting re-init on previously-failed class java.lang.Class<irq>
09-09 16:41:47.347  7188  7188 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 16:41:47.347  7188  7188 D ActivityThread: Added TimaKeyStore provider
09-09 16:41:47.367  6923  7087 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
09-09 16:41:47.367  6998  6998 D CAR.SERVICE: com.google.android.projection.gearhead isn't installed.
09-09 16:41:47.367  6998  6998 D CAR.SERVICE: onBind
09-09 16:41:47.367  6998  6998 D CAR.SERVICE: CSB onClientsConnected
09-09 16:41:47.367  7151  7151 D AndroidRuntime: 
09-09 16:41:47.367  7151  7151 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-09 16:41:47.367  7151  7151 D AndroidRuntime: CheckJNI is OFF
09-09 16:41:47.367  7151  7151 D AndroidRuntime: readGMSProperty: start
09-09 16:41:47.367  7151  7151 D AndroidRuntime: readGMSProperty: already setted!!
09-09 16:41:47.367  7151  7151 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-09 16:41:47.367  7151  7151 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-09 16:41:47.367  7151  7151 D AndroidRuntime: readGMSProperty: end
09-09 16:41:47.367  7151  7151 D AndroidRuntime: addProductProperty: start
09-09 16:41:47.387  6998  6998 D CAR.TEL.Service: Binding to InCallService
09-09 16:41:47.437  6923  7087 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
09-09 16:41:47.437  6923  7087 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@7abcbf1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
09-09 16:41:47.437  6923  7087 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
09-09 16:41:47.457  1020  1221 I art     : Explicit concurrent mark sweep GC freed 18748(1096KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 24MB/36MB, paused 2.545ms total 147.781ms
09-09 16:41:47.467  1020  1330 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: local_action
09-09 16:41:47.467  1020  1330 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.car.InCallService2; callingUser = 0; userId(target) = 0
09-09 16:41:47.467  1020  1330 W ActivityManager: Unable to start service Intent { act=local_action cmp=com.google.android.gms/.car.InCallService2 } U=0: not found
09-09 16:41:47.477  6998  6998 E CAR.TEL.Service: Failed to bind to InCallService
09-09 16:41:47.477  7166  7175 E SQLiteLog: (284) automatic index on titles(filter_id)
09-09 16:41:47.477  1020  4354 I ActivityManager: Killing 6605:com.android.calendar/u0a131 (adj 15): empty #21
09-09 16:41:47.497  1020  1540 I ActivityManager: Killing 6754:com.sec.esdk.elm/u0a90 (adj 15): empty #21
09-09 16:41:47.517  7151  7151 E AffinityControl: AffinityControl: registerfunction enter
09-09 16:41:47.527  1020  1221 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
09-09 16:41:47.527  1020  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:47.527  1020  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:47.527  1020  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:47.527  1020  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:47.537  7211  7211 E Zygote  : MountEmulatedStorage()
09-09 16:41:47.537  1020  1221 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7211 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-09 16:41:47.537  7211  7211 E Zygote  : v2
09-09 16:41:47.537  7211  7211 I libpersona: KNOX_SDCARD checking this for 1000
09-09 16:41:47.537  7211  7211 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 16:41:47.537  7211  7211 I libpersona: KNOX_SDCARD not a persona
09-09 16:41:47.547  7151  7151 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-09 16:41:47.547  7211  7211 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 16:41:47.547  7211  7211 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 16:41:47.547  7133  7153 I FilterUnInstaller: FilterUninstaller.java : removeFromDB()
09-09 16:41:47.557  7166  7175 D FilterProvider: delete when PACKAGE_NAME : 2002 
09-09 16:41:47.557  7166  7175 D FilterProvider: packageName : com.test.thalitest
09-09 16:41:47.557  7133  7153 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.filterinstaller.FilterUninstaller.uninstallFilters:48 com.samsung.android.app.filterinstaller.FilterPackageService$ServiceHandler.handleMessage:152 android.os.Handler.dispatchMessage:102 
09-09 16:41:47.557  1020  1330 I ActivityManager: Killing 6808:com.sec.android.app.popupuireceiver/1000 (adj 15): empty #21
09-09 16:41:47.567  1020  1533 E PersonaManagerService: inState():  stateMachine is null !!
09-09 16:41:47.567  1020  1379 I ActivityManager: Killing 6830:com.sec.pcw.device/1000 (adj 15): empty #21
09-09 16:41:47.567  7211  7211 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 16:41:47.567  7211  7211 D ActivityThread: Added TimaKeyStore provider
09-09 16:41:47.567  6998  7007 I DynamiteModule: Considering local module com.google.android.gms.googlecertificates:1 and remote module com.google.android.gms.googlecertificates:1
09-09 16:41:47.567  6998  7007 I DynamiteModule: Selected remote version of com.google.android.gms.googlecertificates, version >= 1
09-09 16:41:47.577  1020  1533 I PersonaManagerService: PersonaId don't exist
09-09 16:41:47.577  1020  1533 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
09-09 16:41:47.577  1020  1533 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-09 16:41:47.577  6998  7007 D ChimeraFileApk: Primary ABI of requesting process is armeabi-v7a
09-09 16:41:47.577  6998  7007 I art     : DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000006@DynamiteModulesA_GmsCore_prodlmp_hdpi_release.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000006/DynamiteModulesA_GmsCore_prodlmp_hdpi_release.apk': Failed to open oat filename for reading: No such file or directory
09-09 16:41:47.577  6998  7007 D ChimeraFileApk: Classloading successful. Optimized code found.
09-09 16:41:47.587  6998  7007 D GoogleCertificates: com.google.android.gms.googlecertificates module is loaded
09-09 16:41:47.607  7211  7211 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:3125 
09-09 16:41:47.607  1020  1533 W ActivityManager: mDVFSHelper.acquire()
09-09 16:41:47.617   259   259 I SurfaceFlinger: id=10 createSurf (16x16),-1 flag=20004, EimLayer(Di
09-09 16:41:47.617   259   259 I SurfaceFlinger: id=11 createSurf (16x16),-1 flag=20004, EimLayer(An
09-09 16:41:47.627  1020  1533 D FocusedStackFrame: Set to : 0
09-09 16:41:47.637  1020  1051 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-09 16:41:47.637  1020  1051 D PhoneWindow: *FMB* installDecor flags : -2122120936
09-09 16:41:47.647  1020  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:47.647  1020  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:47.647  1020  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:47.647  1020  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:47.647  6998  7007 D GoogleCertificatesImpl: Fetched 163 Google release certificates
09-09 16:41:47.647  1020  1051 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-09 16:41:47.647  1020  1051 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
09-09 16:41:47.647  6998  7007 D CAR.SERVICE: Package validated; name: com.android.vending
09-09 16:41:47.657  6998  7007 D CAR.SERVICE: Android Auto doesn't have car home but we  have at least on alias in default or enabled state. Nothing to do.
09-09 16:41:47.657   259   259 I SurfaceFlinger: id=12 createSurf (540x960),1 flag=404, uhalitest
09-09 16:41:47.677  1020  1533 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7231 uid=10171 gids={50171, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-09 16:41:47.677  1020  1533 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
09-09 16:41:47.677  7231  7231 I libpersona: KNOX_SDCARD checking this for 10171
09-09 16:41:47.677  1020  1533 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-09 16:41:47.677  7231  7231 I libpersona: KNOX_SDCARD not a persona
09-09 16:41:47.677  7231  7231 E Zygote  : MountEmulatedStorage()
09-09 16:41:47.677  7231  7231 E Zygote  : v2
09-09 16:41:47.677  1020  1533 D InputDispatcher: Focused application set to: xxxx
09-09 16:41:47.677  1020  1339 D ActivityManager: startService callerProcessName:com.android.keychain, calleePkgName: com.android.keychain
09-09 16:41:47.677  1020  1533 D InputDispatcher: Focus left window: 1497
09-09 16:41:47.677  1020  1339 D ActivityManager: retrieveServiceLocked(): component = com.android.keychain/com.android.keychain.KeyChainService; callingUser = 0; userId(target) = 0
09-09 16:41:47.677  7231  7231 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 16:41:47.677  7151  7151 D AndroidRuntime: Shutting down VM
09-09 16:41:47.677  1020  1339 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:47.677  1020  1339 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:41:47.677  1020  1339 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.keychain, destAppInfo.processName = com.android.keychain
09-09 16:41:47.677  7231  7231 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 16:41:47.677  7231  7231 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
09-09 16:41:47.687  1020  1221 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.mirrorlink, hostingType: broadcast
09-09 16:41:47.687  1020  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:47.687  1020  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:47.687  1020  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:47.687  1020  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:47.707  7247  7247 E Zygote  : MountEmulatedStorage()
09-09 16:41:47.707  7247  7247 E Zygote  : v2
09-09 16:41:47.707  7247  7247 I libpersona: KNOX_SDCARD checking this for 1000
09-09 16:41:47.707  7247  7247 I libpersona: KNOX_SDCARD not a persona
09-09 16:41:47.707  1020  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-09 16:41:47.707  1020  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
09-09 16:41:47.707  7247  7247 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 16:41:47.707  7247  7247 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 16:41:47.707  7247  7247 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 16:41:47.707  1020  1221 I ActivityManager: Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=7247 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-09 16:41:47.717  7231  7231 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 16:41:47.717  7231  7231 D ActivityThread: Added TimaKeyStore provider
09-09 16:41:47.717  1020  4356 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
09-09 16:41:47.717  1020  1020 V ActivityManager: Display changed displayId=0
09-09 16:41:47.727  1020  1049 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-09 16:41:47.737  7247  7247 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 16:41:47.737  7247  7247 D ActivityThread: Added TimaKeyStore provider
09-09 16:41:47.747  1020  4356 D PersonaManager: isKioskContainerExistOnDevice
09-09 16:41:47.757  1020  1032 I ActivityManager: Killing 6798:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
09-09 16:41:47.767  1020  1020 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
09-09 16:41:47.797   259   443 I SurfaceFlinger: id=6 Removed Mauncher (5/9)
09-09 16:41:47.797  1020  1339 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
09-09 16:41:47.797   259  1042 I SurfaceFlinger: id=6 Removed Mauncher (-2/9)
09-09 16:41:47.797  1020  1339 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:47.797  1020  1339 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:47.797  1020  1339 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:47.797  1020  1339 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:47.797  1497  1497 V ActivityThread: updateVisibility : ActivityRecord{23c80b25 token=android.os.BinderProxy@308b7c91 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
09-09 16:41:47.797  1497  1497 D Launcher: onTrimMemory. Level: 20
09-09 16:41:47.797  7247  7264 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_REMOVED
09-09 16:41:47.807  7247  7264 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
09-09 16:41:47.807  7265  7265 E Zygote  : MountEmulatedStorage()
09-09 16:41:47.817  7265  7265 E Zygote  : v2
09-09 16:41:47.817  7265  7265 I libpersona: KNOX_SDCARD checking this for 10117
09-09 16:41:47.817  7265  7265 I libpersona: KNOX_SDCARD not a persona
09-09 16:41:47.817  7265  7265 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 16:41:47.817  7265  7265 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 16:41:47.817  1020  1339 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=7265 uid=10117 gids={50117, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
09-09 16:41:47.827  7265  7265 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
09-09 16:41:47.817  1020  1339 I ActivityManager: Killing 6846:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
09-09 16:41:47.827  1020  1506 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:47.827  1020  1506 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:41:47.827  1020  1506 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
09-09 16:41:47.827  1020  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
09-09 16:41:47.827  1020  1506 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
09-09 16:41:47.827  7247  7247 D AcmsService: Enter Oncreate
09-09 16:41:47.827  7247  7247 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-09 16:41:47.827  7247  7247 D AcmsService: creating AcmsCore
09-09 16:41:47.827  7247  7247 D AcmsCore: AcmsCore.getAcmsCore() - Enter
09-09 16:41:47.827  7247  7247 D AcmsCore: AcmsCore
09-09 16:41:47.837  7247  7247 D AcmsCore: init
09-09 16:41:47.837  7247  7247 D AcmsCore: Looper handler is not null
09-09 16:41:47.837  7247  7247 D AcmsCore: Post to AcmsCoreHandler
09-09 16:41:47.837  7247  7247 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-09 16:41:47.837  7247  7247 D AcmsServiceMonitor: Incrementing - Counter value: 1
09-09 16:41:47.837  7247  7247 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>1
09-09 16:41:47.837  7247  7247 D AcmsService: onStartCommand
09-09 16:41:47.837  7247  7247 D AcmsService: Action: android.intent.action.PACKAGE_REMOVED
09-09 16:41:47.837  7247  7247 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 1
09-09 16:41:47.837  7247  7247 D AcmsServiceMonitor: Incrementing - Counter value: 2
09-09 16:41:47.837  7247  7247 D AcmsService: Incremented Counter Value : onStartCommand
09-09 16:41:47.837  7247  7273 D AcmsCertificateMngr: AcmsCertificateMngr
09-09 16:41:47.847  7247  7273 D AcmsRevocationMngr: AcmsRevocationMngr
09-09 16:41:47.847  1020  1526 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
09-09 16:41:47.857  7247  7247 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
09-09 16:41:47.857  7265  7265 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 16:41:47.857  7265  7265 D ActivityThread: Added TimaKeyStore provider
09-09 16:41:47.887  7151  7151 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,09-09 16:41:47.897  7265  7265 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 16:41:47.907  7247  7247 D AcmsService: Inside handle Intent
09-09 16:41:47.907  7247  7247 D AcmsService: App removed - package name: com.test.thalitest
09-09 16:41:47.907  7247  7247 D AcmsCore: Post to AcmsCoreHandler
09-09 16:41:47.907  7247  7247 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-09 16:41:47.907  7247  7247 D AcmsServiceMonitor: Incrementing - Counter value: 3
09-09 16:41:47.907  7247  7247 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>5
09-09 16:41:47.907  7247  7247 D AcmsService: Decremented Counter Value : handleStartIntent
09-09 16:41:47.907  7247  7247 D AcmsServiceMonitor: Decrementing - Counter value: 2
,09-09 16:41:47.937  7231  7231 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,09-09 16:41:48.017  7231  7231 I cr.library_loader: Time to load native libraries: 19 ms (timestamps 467-486)
,09-09 16:41:48.017  7231  7231 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-09 16:41:48.057  7231  7231 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2b4b211d}
,09-09 16:41:48.057  7231  7231 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-09 16:41:48.067  7231  7231 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-09 16:41:48.117  7231  7231 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,09-09 16:41:48.127  7231  7231 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 16:41:48.137  7231  7231 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-09 16:41:48.197  1020  1330 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,09-09 16:41:48.197  1020  1330 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,09-09 16:41:48.197  1020  1330 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:41:48.197  1020  1330 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:48.197  1020  1330 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,09-09 16:41:48.207  7231  7231 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-09 16:41:48.207  7231  7231 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-09 16:41:48.207  7231  7231 I Adreno-EGL: Build Date: 04/06/15 Mon
09-09 16:41:48.207  7231  7231 I Adreno-EGL: Local Branch: 
09-09 16:41:48.207  7231  7231 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-09 16:41:48.207  7231  7231 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-09 16:41:48.207  7231  7231 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-09 16:41:48.227  1020  1526 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
09-09 16:41:48.227  1020  1526 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,09-09 16:41:48.227  1020  1526 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:41:48.227  1020  1526 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:48.227  1020  1526 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,09-09 16:41:48.237  1020  4354 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_REMOVED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,09-09 16:41:48.247  1461  1461 I HomeSyncInstallReceiver: This pkg do not need BT addr. Do nothing
,09-09 16:41:48.247  1020  1540 I splitIntent: Split this intent : android.intent.action.PACKAGE_ADDED, mSplitNum[0]=12, mSplitNum[1]=20, mSplitNum[2]=32, mBgSplitQueueNum=3 divideNum= 9 r.nextReceiver= 2 receivers.size=41
09-09 16:41:48.247  1020  1540 I splitIntent: finish to split intent : android.intent.action.PACKAGE_ADDED !! Enqueue -> schedule it!!
,09-09 16:41:48.247  1020  1046 W ActivityManager: Activity pause timeout for ActivityRecord{1c4495be u0 com.test.thalitest/.MainActivity t2}
,09-09 16:41:48.257  6347  6347 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_ADDED, package = com.test.thalitest, uid = -1
,09-09 16:41:48.257  6347  6347 I AASAservice-TokenRule: parseToken()
,09-09 16:41:48.257  6347  6347 W System.err: java.io.FileNotFoundException: /data/system/.aasa/aasaRuleFile.xml: open failed: ENOENT (No such file or directory)
,09-09 16:41:48.257  6347  6347 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:456)
09-09 16:41:48.257  6347  6347 W System.err: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
09-09 16:41:48.257  6347  6347 W System.err: 	at java.io.FileInputStream.<init>(FileInputStream.java:103)
09-09 16:41:48.257  6347  6347 W System.err: 	at com.samsung.aasaservice.AASATokenRule.parseToken(AASATokenRule.java:86)
09-09 16:41:48.257  6347  6347 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:55)
09-09 16:41:48.257  6347  6347 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
09-09 16:41:48.257  6347  6347 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
09-09 16:41:48.257  6347  6347 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
09-09 16:41:48.257  6347  6347 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:41:48.257  6347  6347 W System.err: 	at android.os.Looper.loop(Looper.java:145)
09-09 16:41:48.257  6347  6347 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 16:41:48.257  6347  6347 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 16:41:48.257  6347  6347 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 16:41:48.257  6347  6347 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 16:41:48.257  6347  6347 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
09-09 16:41:48.257  6347  6347 W System.err: Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
09-09 16:41:48.257  6347  6347 W System.err: 	at libcore.io.Posix.open(Native Method)
09-09 16:41:48.257  6347  6347 W System.err: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
09-09 16:41:48.257  6347  6347 W System.err: 	at libcore.io.IoBridge.open(IoBridge.java:442)
09-09 16:41:48.257  6347  6347 W System.err: 	... 14 more
09-09 16:41:48.257  6347  6347 E AASAservice-TokenRule: parseToken() : TokenFile is null
09-09 16:41:48.257  6347  6347 E AASAservice-UpdateReceiver: AASARuleUpdateResult() : Rule file is not exist.
,09-09 16:41:48.267  6347  6347 I art     : System.exit called, status: 0
09-09 16:41:48.267  6347  6347 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
09-09 16:41:48.267  1020  1533 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
09-09 16:41:48.267  1020  1533 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
09-09 16:41:48.267  2007  2007 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
09-09 16:41:48.277  6175  6175 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
09-09 16:41:48.287  1020  1540 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
09-09 16:41:48.287  1020  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:48.287  1020  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:48.287  1020  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:48.287  1020  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:48.297  7300  7300 E Zygote  : MountEmulatedStorage()
09-09 16:41:48.297  7300  7300 I libpersona: KNOX_SDCARD checking this for 1000
09-09 16:41:48.297  7300  7300 E Zygote  : v2
09-09 16:41:48.297  7300  7300 I libpersona: KNOX_SDCARD not a persona
09-09 16:41:48.297  1020  1540 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.PackageEventReceiver: pid=7300 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-09 16:41:48.297  7300  7300 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 16:41:48.297  1020  1032 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms,
09-09 16:41:48.297  7300  7300 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 16:41:48.297  1020  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
,09-09 16:41:48.297  7300  7300 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 16:41:48.297  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:48.297  1020  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 16:41:48.297  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
,09-09 16:41:48.317  1020  1540 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
,09-09 16:41:48.317  6175  7312 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
09-09 16:41:48.317  6175  7312 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
,09-09 16:41:48.317  1020  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:41:48.327  1020  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:48.327  1020  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:48.327  1020  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:41:48.337  7323  7323 E Zygote  : MountEmulatedStorage(),
09-09 16:41:48.337  7323  7323 I libpersona: KNOX_SDCARD checking this for 10042
09-09 16:41:48.337  7323  7323 E Zygote  : v2
09-09 16:41:48.337  7323  7323 I libpersona: KNOX_SDCARD not a persona
,09-09 16:41:48.337  7323  7323 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 16:41:48.337  7323  7323 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 16:41:48.337  7323  7323 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
09-09 16:41:48.337  1020  1540 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=7323 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
09-09 16:41:48.337  1020  1032 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-09 16:41:48.347  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:48.347  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:48.347  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
09-09 16:41:48.347  7300  7300 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 16:41:48.347  7300  7300 D ActivityThread: Added TimaKeyStore provider
09-09 16:41:48.347  1020  1540 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
09-09 16:41:48.357  7231  7231 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-09 16:41:48.357  1020  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:48.357  1020  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:48.357  1020  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:48.357  1020  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:48.357  2751  2751 I DBG_POLICYDM: [com.sec.android.policydm.aasa.AASAUpdater$1(79/onServiceDisconnected)] AASA: onServiceDisconnected
,09-09 16:41:48.367  7338  7338 E Zygote  : MountEmulatedStorage(),
09-09 16:41:48.367  7338  7338 E Zygote  : v2
09-09 16:41:48.367  7338  7338 I libpersona: KNOX_SDCARD checking this for 1000,
,09-09 16:41:48.377  1020  1540 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7338 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-09 16:41:48.377  7338  7338 I libpersona: KNOX_SDCARD not a persona
,09-09 16:41:48.377  7338  7338 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-09 16:41:48.387  7338  7338 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 16:41:48.387  7338  7338 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 16:41:48.387  7231  7231 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,09-09 16:41:48.387  7231  7231 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,09-09 16:41:48.387  7323  7323 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 16:41:48.387   304   304 I art     : Explicit concurrent mark sweep GC freed 8744(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 628us total 19.404ms
,09-09 16:41:48.387  7323  7323 D ActivityThread: Added TimaKeyStore provider
,09-09 16:41:48.397  1020  1533 I ActivityManager: Process com.samsung.aasaservice (pid 6347)(adj 0) has died(84,723)
,09-09 16:41:48.397  1020  1533 W ActivityManager: Scheduling restart of crashed service com.samsung.aasaservice/.AASAService in 1000ms
,09-09 16:41:48.397  1020  1046 D ActivityManager: startProcessLocked calleePkgName: com.google.android.partnersetup, hostingType: broadcast
,09-09 16:41:48.397  7231  7231 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
09-09 16:41:48.397  1020  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:48.397  7231  7231 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
09-09 16:41:48.397  1020  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:48.397  1020  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:48.397  1020  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:41:48.407   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 585us total 17.292ms
,09-09 16:41:48.417  7338  7338 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 16:41:48.417  7338  7338 D ActivityThread: Added TimaKeyStore provider
,09-09 16:41:48.427  7300  7300 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,09-09 16:41:48.427   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 588us total 16.816ms
,09-09 16:41:48.437  7077  7088 E SQLiteLog: (283) recovered 412 frames from WAL file /data/user/0/com.google.android.gsf/databases/googlesettings.db-wal
,09-09 16:41:48.437  7355  7355 E Zygote  : MountEmulatedStorage()
09-09 16:41:48.437  7355  7355 E Zygote  : v2
09-09 16:41:48.437  7355  7355 I libpersona: KNOX_SDCARD checking this for 10014
09-09 16:41:48.437  7355  7355 I libpersona: KNOX_SDCARD not a persona
,09-09 16:41:48.437  7355  7355 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 16:41:48.447  7355  7355 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
09-09 16:41:48.447  1020  1046 I ActivityManager: Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=7355 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
09-09 16:41:48.447  7355  7355 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 16:41:48.447  7300  7300 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.bbc.bbcagent.bbccontroller.receiver.PackageEventReceiver.onReceive:182 android.app.ActivityThread.handleReceiver:3125 
,09-09 16:41:48.457  1020  4354 D ActivityManager: startService callerProcessName:com.samsung.android.bbc.bbcagent, calleePkgName: com.samsung.android.bbc.bbcagent
09-09 16:41:48.457  1020  4354 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.service.BBCAgentService; callingUser = 0; userId(target) = 0
,09-09 16:41:48.457  1020  4354 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:48.457  1020  4354 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:41:48.457  1020  4354 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.bbc.bbcagent, destAppInfo.processName = com.samsung.android.bbc.bbcagent
09-09 16:41:48.457  1020  1506 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
09-09 16:41:48.457  1020  1506 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
09-09 16:41:48.467  2007  2007 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-09 16:41:48.477  7355  7355 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 16:41:48.477  7355  7355 D ActivityThread: Added TimaKeyStore provider
,09-09 16:41:48.477  6977  6977 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
,09-09 16:41:48.477  6977  6977 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
09-09 16:41:48.477  7323  7323 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 16:41:48.477  7323  7323 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-09 16:41:48.477  7323  7323 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-09 16:41:48.487  6977  6977 I TapandpayWidget:Utils: Clear T&P info.
,09-09 16:41:48.497  6977  6977 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,09-09 16:41:48.497  1020  4355 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,09-09 16:41:48.497  1020  4355 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:48.497  1020  4355 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:48.497  1020  4355 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:48.497  1020  4355 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:41:48.507  7368  7368 E Zygote  : MountEmulatedStorage(),
09-09 16:41:48.507  7368  7368 E Zygote  : v2
09-09 16:41:48.507  7368  7368 I libpersona: KNOX_SDCARD checking this for 10009
09-09 16:41:48.507  7368  7368 I libpersona: KNOX_SDCARD not a persona
,09-09 16:41:48.507  7368  7368 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 16:41:48.507  1020  4355 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=7368 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
09-09 16:41:48.507  7368  7368 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 16:41:48.507  7368  7368 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-09 16:41:48.507  1020  4356 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 16:41:48.517  1020  4356 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:48.517  1020  4356 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:48.517  1020  4356 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,09-09 16:41:48.517  7338  7338 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:3125 
,09-09 16:41:48.527  7323  7323 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,09-09 16:41:48.527  1020  1541 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,09-09 16:41:48.527  1020  1541 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,09-09 16:41:48.527  1020  1541 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:41:48.527  1020  1541 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:41:48.527  1020  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,09-09 16:41:48.547   285   285 E installd: system dir 0 : /system/app/
09-09 16:41:48.547   285   285 E installd: system dir 1 : /system/priv-app/
09-09 16:41:48.547   285   285 E installd: system dir 2 : /vendor/app/
09-09 16:41:48.547   285   285 E installd: system dir 3 : /oem/app/
,09-09 16:41:48.557  1020  1339 I TactileAssist: enable value -1
09-09 16:41:48.557  1020  1339 I TactileAssist: internal enable value -1
09-09 16:41:48.557  1020  1339 I TactileAssist: intensity value -1
09-09 16:41:48.557  1020  1339 I TactileAssist: saveAppList value true
,09-09 16:41:48.557  1020  1339 I TactileAssist: List of disabled apps :
,09-09 16:41:48.557  7368  7368 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 16:41:48.557  7368  7368 D ActivityThread: Added TimaKeyStore provider
,09-09 16:41:48.557  7133  7133 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
,09-09 16:41:48.557  7133  7133 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
,09-09 16:41:48.557  1020  4355 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
09-09 16:41:48.557  1020  4355 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
,09-09 16:41:48.557  1020  4355 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:48.557  1020  4355 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 16:41:48.567  1020  4355 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
,09-09 16:41:48.567  1020  1061 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,09-09 16:41:48.577  1020  1379 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
09-09 16:41:48.577  1020  1379 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.RlzPingIntentService; callingUser = 0; userId(target) = 0
,09-09 16:41:48.577  1020  1379 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:41:48.577  1020  1379 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:48.577  1020  1379 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,09-09 16:41:48.577  7133  7133 I FilterInstaller: FilterPackageService : ACTION_CHANGED
,09-09 16:41:48.587  7154  7154 D PackageIntentReceiver: ACTION_PACKAGE_ADDED
09-09 16:41:48.587  7154  7154 D PackageIntentReceiver: Not GearManger package! 
,09-09 16:41:48.597  1020  4356 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.soundalive, hostingType: broadcast
,09-09 16:41:48.597  1020  4356 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:48.597  1020  4356 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:48.597  1020  4356 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:48.597  1020  4356 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:41:48.607  7133  7391 E FilterInstaller: installFilters
09-09 16:41:48.607  7133  7391 E FilterInstaller: There is no requred permission
,09-09 16:41:48.617  7393  7393 E Zygote  : MountEmulatedStorage(),
,09-09 16:41:48.617  7393  7393 I libpersona: KNOX_SDCARD checking this for 10048,
09-09 16:41:48.617  7393  7393 E Zygote  : v2
09-09 16:41:48.617  7393  7393 I libpersona: KNOX_SDCARD not a persona
,09-09 16:41:48.617  7393  7393 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 16:41:48.617  1020  4356 I ActivityManager: Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=7393 uid=10048 gids={50048, 9997, 3003, 3002} abi=armeabi-v7a
,09-09 16:41:48.627  1020  1216 D ActivityManager: startService callerProcessName:com.google.android.partnersetup, calleePkgName: com.google.android.partnersetup
09-09 16:41:48.627  1020  1216 D ActivityManager: retrieveServiceLocked(): component = com.google.android.partnersetup/com.google.android.partnersetup.AppInstalledService; callingUser = 0; userId(target) = 0
,09-09 16:41:48.627  7393  7393 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-09 16:41:48.627  1020  1216 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:48.627  1020  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:48.627  1020  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
09-09 16:41:48.627  7393  7393 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-09 16:41:48.637  7231  7231 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 16:41:48.637  1020  4356 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
09-09 16:41:48.637  1020  4356 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:48.637  1020  4356 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:48.637  1020  4356 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:48.637  1020  4356 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:41:48.657  7231  7231 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-09 16:41:48.657  7408  7408 E Zygote  : MountEmulatedStorage(),
09-09 16:41:48.657  7408  7408 I libpersona: KNOX_SDCARD checking this for 1000
09-09 16:41:48.657  7408  7408 E Zygote  : v2
09-09 16:41:48.657  7408  7408 I libpersona: KNOX_SDCARD not a persona
09-09 16:41:48.657  7408  7408 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-09 16:41:48.657  1020  4356 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7408 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-09 16:41:48.657  7408  7408 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 16:41:48.667  7408  7408 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 16:41:48.667  1020  4356 I ActivityManager: Killing 6877:com.sec.android.app.themechooser/u0a145 (adj 15): empty #21
,09-09 16:41:48.667  1020  1533 I ActivityManager: Killing 6862:com.sec.knox.bridge/1000 (adj 15): empty #21
,09-09 16:41:48.677  7231  7231 D PhoneWindow: *FMB* installDecor mIsFloating : false
09-09 16:41:48.677  7231  7231 D PhoneWindow: *FMB* installDecor flags : -2139027200
,09-09 16:41:48.677  7393  7393 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 16:41:48.677  1020  1533 I ActivityManager: Killing 6892:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
09-09 16:41:48.677  7393  7393 D ActivityThread: Added TimaKeyStore provider
,09-09 16:41:48.687  7247  7417 D AcmsPackageEventListener: Received: android.intent.action.PACKAGE_ADDED
09-09 16:41:48.687  7247  7417 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
09-09 16:41:48.687  7231  7231 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,09-09 16:41:48.687  1020  4355 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 16:41:48.687  1020  4355 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chimera.GmsIntentOperationService; callingUser = 0; userId(target) = 0
,09-09 16:41:48.687  1020  4355 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:48.687  1020  4355 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:48.687  1020  4355 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:41:48.697  4831  7051 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
09-09 16:41:48.697  4831  7048 E IntentOperationSvc: Failed to instantiate Chimera operation impl, dropping operation
,09-09 16:41:48.697  1020  4354 D ActivityManager: startService callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
09-09 16:41:48.697  1020  4354 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.api.AcmsService; callingUser = 0; userId(target) = 0
,09-09 16:41:48.697  1020  4354 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:48.697  1020  4354 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:41:48.697  1020  4354 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.mirrorlink, destAppInfo.processName = com.samsung.android.app.mirrorlink
,09-09 16:41:48.707  7247  7247 D AcmsService: onStartCommand
09-09 16:41:48.707  7247  7247 D AcmsService: Action: android.intent.action.PACKAGE_ADDED
09-09 16:41:48.707  7247  7247 D AcmsServiceMonitor: Enter incrementSvcCounter with startId 2
09-09 16:41:48.707  7247  7247 D AcmsServiceMonitor: Incrementing - Counter value: 3
09-09 16:41:48.707  7247  7247 D AcmsService: Incremented Counter Value : onStartCommand
09-09 16:41:48.707  7247  7247 D AcmsService: Inside handle Intent
09-09 16:41:48.707  7247  7247 D AcmsService: App added - package name: com.test.thalitest
09-09 16:41:48.707  7247  7247 D AcmsCore: Post to AcmsCoreHandler
09-09 16:41:48.707  7247  7247 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-09 16:41:48.707  7247  7247 D AcmsServiceMonitor: Incrementing - Counter value: 4
09-09 16:41:48.707  7247  7247 D AcmsCore: Incremented Counter Value: postToAcmsCoreHandler =>2
09-09 16:41:48.707  7247  7247 D AcmsService: Decremented Counter Value : handleStartIntent
09-09 16:41:48.707  7247  7247 D AcmsServiceMonitor: Decrementing - Counter value: 3
,09-09 16:41:48.707  4831  7051 D AuthPkgBcIntentOp: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
09-09 16:41:48.707  1020  1379 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
09-09 16:41:48.707  1020  1379 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PackagesMediaMonitor$AsyncService; callingUser = 0; userId(target) = 0
,09-09 16:41:48.707  7231  7231 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-09 16:41:48.707  7231  7231 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 16:41:48.707  1020  1379 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:48.707  1020  1379 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:48.707  1020  1379 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,09-09 16:41:48.717  1020  1526 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 16:41:48.717  1020  1526 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-09 16:41:48.717  1020  1526 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:48.717  1020  1526 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 16:41:48.717  1020  1526 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:41:48.727  4831  4831 D AsyncTaskServiceImpl: Submit a task: nzm
,09-09 16:41:48.727  1020  1033 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 16:41:48.727  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:48.727  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:48.727  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:41:48.727  7408  7408 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 16:41:48.727  7393  7393 D Compatibility: onReceive() it will make start service
,09-09 16:41:48.727  1020  1541 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 16:41:48.727  1020  1541 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
,09-09 16:41:48.727  7408  7408 D ActivityThread: Added TimaKeyStore provider
09-09 16:41:48.727  1020  1541 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:48.727  1020  1541 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 16:41:48.737  1020  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:41:48.737  1020  1540 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
,09-09 16:41:48.737  1020  1540 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,09-09 16:41:48.737  1020  1540 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:48.737  1020  1540 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:41:48.737  1020  1540 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,09-09 16:41:48.737  1020  4356 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 16:41:48.737  1020  4356 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-09 16:41:48.737  1020  4356 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:48.737  1020  4356 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:48.737  1020  4356 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:41:48.747  1020  1216 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 16:41:48.747  1020  1216 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-09 16:41:48.747  1020  1216 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:48.747  1020  1216 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:48.747  1020  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:41:48.757  4831  7051 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,09-09 16:41:48.757  4831  7051 D WearableController: Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,09-09 16:41:48.757  7393  7431 D Compatibility: onHandleIntent()
,09-09 16:41:48.767  1020  4354 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
,09-09 16:41:48.767  1020  4354 D ActivityManager: retrieveServiceLocked(): component = com.google.android.apps.plus/com.google.android.apps.plus.service.PhotosAppTransitionService; callingUser = 0; userId(target) = 0
,09-09 16:41:48.767  4831  5067 D nzm     : Processing package: com.test.thalitest
09-09 16:41:48.767  1020  4354 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:41:48.767  1020  4354 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:48.767  1020  4354 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.plus, destAppInfo.processName = com.google.android.apps.plus
,09-09 16:41:48.767  7393  7431 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10171, android.intent.extra.REPLACING=true, android.intent.extra.user_handle=0}]
,09-09 16:41:48.777  7393  7431 D Compatibility: found: 2
,09-09 16:41:48.787  7393  7431 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,09-09 16:41:48.787  7408  7408 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
09-09 16:41:48.787  7408  7408 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
09-09 16:41:48.787  7408  7408 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,09-09 16:41:48.797  1020  1541 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 16:41:48.797  1020  1541 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.wearable.service.WearableControlService; callingUser = 0; userId(target) = 0
,09-09 16:41:48.797  7393  7431 D Compatibility: skipping ResolveInfo{1da01beb com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
09-09 16:41:48.797  7393  7431 D Compatibility: considering ResolveInfo{286fad48 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
09-09 16:41:48.797  7393  7431 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,09-09 16:41:48.797  4831  5067 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
09-09 16:41:48.797  4831  5067 D nzm     : Found info for package com.test.thalitest in db.
,09-09 16:41:48.797  7393  7431 D Compatibility: enabling receiver ResolveInfo{c08e7e1 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,09-09 16:41:48.807  1020  1541 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:48.807  1020  1541 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:48.807  1020  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:41:48.807  7393  7431 D Compatibility: enabling receiver ResolveInfo{f777906 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,09-09 16:41:48.817  7393  7431 D Compatibility: enabling receiver ResolveInfo{1d628bc7 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,09-09 16:41:48.817  7393  7431 D Compatibility: enabling receiver ResolveInfo{2c7655f4 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,09-09 16:41:48.817  1020  1339 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 16:41:48.817  1020  1339 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chimera.GmsIntentOperationService; callingUser = 0; userId(target) = 0
,09-09 16:41:48.817  1020  1339 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:48.817  1020  1339 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:48.817  1020  1339 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:41:48.817  1020  1221 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-09 16:41:48.817  1020  1221 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:48.817  1020  1221 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:48.817  1020  1221 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:41:48.827  7408  7408 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-09 16:41:48.827  7408  7408 I PCWCLIENTTRACE_PushUtil: sales region : global
09-09 16:41:48.827  7408  7408 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-09 16:41:48.827  7408  7408 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_ADDED
,09-09 16:41:48.827  1020  4356 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-09 16:41:48.827  1020  4356 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-09 16:41:48.837  1020  4356 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:41:48.837  7393  7431 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,09-09 16:41:48.837  1020  4356 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 16:41:48.837  1020  4356 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-09 16:41:48.837  1020  1032 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-09 16:41:48.837  1020  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-09 16:41:48.837  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:48.837  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:48.837  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-09 16:41:48.847  1020  1216 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,09-09 16:41:48.857  1020  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:41:48.857  1020  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:48.857  1020  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:41:48.857  1020  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:41:48.867  7231  7441 D OpenGLRenderer: Render dirty regions requested: true
,09-09 16:41:48.867  7442  7442 E Zygote  : MountEmulatedStorage(),
09-09 16:41:48.867  7442  7442 I libpersona: KNOX_SDCARD checking this for 10029
09-09 16:41:48.867  7442  7442 E Zygote  : v2,
09-09 16:41:48.867  7442  7442 I libpersona: KNOX_SDCARD not a persona
,09-09 16:41:48.867  1020  1216 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=7442 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,09-09 16:41:48.877  1020  1379 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 16:41:48.877  1020  1379 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:48.877  1020  1379 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:48.877  1020  1379 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:41:48.877  1020  1541 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-09 16:41:48.877  1020  1541 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-09 16:41:48.877  1020  1020 D PersonaManagerService: getPersonasForUser(): returning null!
09-09 16:41:48.877  1020  1541 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-09 16:41:48.877  1020  1020 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,09-09 16:41:48.887  1020  4355 I ActivityManager: Killing 6960:com.sec.spp.push/u0a32 (adj 15): empty #21
,09-09 16:41:48.887  7231  7231 V ActivityThread: updateVisibility : ActivityRecord{385bde54 token=android.os.BinderProxy@5e7f266 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
09-09 16:41:48.887  7231  7309 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,09-09 16:41:48.897  1020  1033 I ActivityManager: Killing 7016:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #21
,09-09 16:41:48.897  1020  4356 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
09-09 16:41:48.897  1020  4356 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.wear.WearSupportService; callingUser = 0; userId(target) = 0
,09-09 16:41:48.897  1020  4356 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:41:48.897  1020  4356 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:48.897  1020  4356 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
09-09 16:41:48.897  7231  7231 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
09-09 16:41:48.897  7231  7231 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,09-09 16:41:48.917  1020  4354 I ActivityManager: Killing 7030:com.sec.spp.push:RemoteNotiProcess/u0a32 (adj 15): empty #21
,09-09 16:41:48.927   259   259 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,09-09 16:41:48.937  1020  1339 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
09-09 16:41:48.937  1020  1339 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.utils.ExternalReferrer$ExternalReferrerService; callingUser = 0; userId(target) = 0
,09-09 16:41:48.937  7442  7442 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 16:41:48.937  7442  7442 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 16:41:48.937  7442  7442 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 16:41:48.937  1020  1540 D InputDispatcher: Focus entered window: 7231
,09-09 16:41:48.947  1020  1339 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:41:48.947  1020  1339 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:48.957  1020  1339 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,09-09 16:41:48.957  1020  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-09 16:41:48.957  7231  7231 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,09-09 16:41:48.957  7231  7441 I OpenGLRenderer: Initialized EGL, version 1.4
,09-09 16:41:48.957  1020  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-09 16:41:48.967  6034  6034 I Finsky  : [1] com.google.android.finsky.utils.bm.run(1302): Package state data is missing for com.test.thalitest
,09-09 16:41:48.967  7231  7441 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,09-09 16:41:48.967  7231  7441 D OpenGLRenderer: Enabling debug mode 0
,09-09 16:41:48.987  7442  7442 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 16:41:48.987  7442  7442 D ActivityThread: Added TimaKeyStore provider
,09-09 16:41:48.997  1020  1339 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 16:41:48.997  1020  1339 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:41:48.997  1020  1339 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:48.997  1020  1339 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,09-09 16:41:49.007  1020  1033 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 16:41:49.007  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:49.007  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:49.007  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:41:49.007  2007  2007 D WearableService: callingUid 10011, callindPid: 2007
,09-09 16:41:49.027  1020  1540 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-09 16:41:49.027  1020  1339 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 16:41:49.027  1020  1339 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-09 16:41:49.027  1020  1339 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:49.027  1020  1339 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:49.027  1020  1339 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:41:49.037  1175  1175 I StatusBar: Icon Only
,09-09 16:41:49.037  1175  1175 D PanelView: There is/are notification(s) 
,09-09 16:41:49.037  1020  7464 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-09 16:41:49.047  1020  1051 I ActivityManager: Displayed Component not be shown by security: +1s294ms (total +1s402ms)
,09-09 16:41:49.047  1020  1051 W ActivityManager: mDVFSHelper.release()
,09-09 16:41:49.047  1020  1051 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1c4495be u0 com.test.thalitest/.MainActivity t2} time:91514
,09-09 16:41:49.057  1020  4355 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 16:41:49.057  1020  4355 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-09 16:41:49.057   259   443 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,09-09 16:41:49.057  1020  4355 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:49.057   259   447 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
09-09 16:41:49.057  1020  4355 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:49.057  1020  4355 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:41:49.067  7231  7231 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,09-09 16:41:49.077  7231  7231 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@5e7f266 time:91544
,09-09 16:41:49.077  7231  7231 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7231
,09-09 16:41:49.087  1020  1379 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-09 16:41:49.087  1020  1379 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:41:49.087  1020  1379 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 16:41:49.087  1020  1379 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:41:49.097  1020  4356 W ActivityManager: getRunningAppProcesses: caller 10029 is using old GET_TASKS but privileged; allowing
,09-09 16:41:49.107  1871  1871 I SamsungIME: getCurrentCandidateView
,09-09 16:41:49.117  7442  7469 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,09-09 16:41:49.177  7442  7469 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,09-09 16:41:49.177  7442  7469 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 16:41:49.177  7442  7469 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-09 16:41:49.177  7442  7469 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-09 16:41:49.177  7442  7469 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,09-09 16:41:49.187  7442  7469 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
09-09 16:41:49.187  7442  7469 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-09 16:41:49.187  7442  7469 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-09 16:41:49.187  7442  7469 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 16:41:49.187  7442  7469 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 16:41:49.187  7442  7469 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-09 16:41:49.207  7442  7469 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-09 16:41:49.207  7442  7469 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 16:41:49.207  7442  7469 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-09 16:41:49.217  7442  7469 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,09-09 16:41:49.217  7442  7469 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 16:41:49.217  7442  7469 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,09-09 16:41:49.227  7442  7469 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-09 16:41:49.227  7442  7469 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 16:41:49.227  7442  7469 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 16:41:49.227  7442  7469 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
09-09 16:41:49.227  7442  7469 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-09 16:41:49.227  7442  7469 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-09 16:41:49.227  7442  7469 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-09 16:41:49.227  7247  7273 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
,09-09 16:41:49.237  7442  7469 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 16:41:49.237  7442  7469 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-09 16:41:49.237  7442  7469 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-09 16:41:49.237  7442  7469 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
09-09 16:41:49.237  7442  7469 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-09 16:41:49.237  7442  7469 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 16:41:49.237  7442  7469 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-09 16:41:49.257  7442  7469 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
09-09 16:41:49.257  7442  7469 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 16:41:49.257  7442  7469 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-09 16:41:49.257  7442  7469 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-09 16:41:49.267  1020  1339 I art     : Explicit concurrent mark sweep GC freed 24984(1366KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 24MB/37MB, paused 2.550ms total 167.424ms
,09-09 16:41:49.267  1020  4354 I ActivityManager: Killing 7091:com.sec.android.gallery3d/u0a39 (adj 15): empty #21
,09-09 16:41:49.277  1020  4355 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 16:41:49.277  1020  4355 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-09 16:41:49.277  1020  4355 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:41:49.277  1020  4355 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:49.277  1020  4355 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:41:49.277  2751  2751 I DBG_POLICYDM: [com.policydm.XSPPReceiver(52/onReceive)] ACTION_PACKAGE_ADDED. mPkgName:com.test.thalitest
,09-09 16:41:49.287  1020  1526 D LocationManagerService: getProviders()=[passive]
,09-09 16:41:49.297  7247  7273 I AcmsKeyStoreHelper: Key Store exist
,09-09 16:41:49.297  1020  4354 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,09-09 16:41:49.297  7247  7273 I AcmsKeyStoreHelper: Hence loading the keystore file
,09-09 16:41:49.297  1020  4354 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:49.297  1020  4354 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:49.297  1020  4354 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:49.297  1020  4354 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:41:49.307  7442  7469 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,09-09 16:41:49.307  7442  7469 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 16:41:49.307  7442  7469 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 16:41:49.307  7442  7469 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-09 16:41:49.317  7476  7476 E Zygote  : MountEmulatedStorage()
,09-09 16:41:49.317  7476  7476 E Zygote  : v2
,09-09 16:41:49.317  7476  7476 I libpersona: KNOX_SDCARD checking this for 10032,
09-09 16:41:49.317  7476  7476 I libpersona: KNOX_SDCARD not a persona,
,09-09 16:41:49.317  7476  7476 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 16:41:49.317  7476  7476 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 16:41:49.327  1020  4354 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=7476 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 16:41:49.327  7442  7469 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,09-09 16:41:49.337  7476  7476 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,09-09 16:41:49.337  1020  1330 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 16:41:49.337  1020  1330 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:41:49.337  1020  1330 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:49.337  1020  1330 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:41:49.367  7442  7469 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
09-09 16:41:49.367  7442  7469 W ResourcesManager: Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
09-09 16:41:49.367  7442  7469 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-09 16:41:49.367  7442  7469 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 16:41:49.367  7442  7469 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,09-09 16:41:49.387  7476  7476 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 16:41:49.387  1871  1871 D SamsungIME: Dismiss ExpandCandiate
,09-09 16:41:49.387  7476  7476 D ActivityThread: Added TimaKeyStore provider
,09-09 16:41:49.397  1020  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:49.397  1020  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:49.397  1020  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:49.397  1020  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:41:49.407  7442  7469 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,09-09 16:41:49.407  7442  7469 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-09 16:41:49.417  7494  7494 E Zygote  : MountEmulatedStorage()
09-09 16:41:49.417  7494  7494 E Zygote  : v2
09-09 16:41:49.417  7494  7494 I libpersona: KNOX_SDCARD checking this for 1000
09-09 16:41:49.417  7494  7494 I libpersona: KNOX_SDCARD not a persona
,09-09 16:41:49.417  7494  7494 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 16:41:49.427  7494  7494 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 16:41:49.427  1020  1046 I ActivityManager: Start proc com.samsung.aasaservice for service com.samsung.aasaservice/.AASAService: pid=7494 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-09 16:41:49.427  7494  7494 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 16:41:49.427  7442  7469 W GalaxyFinderApplication: system/finder_cp/cpdata.xml file not found
,09-09 16:41:49.437  1020  4356 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
09-09 16:41:49.437  1020  4356 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:49.437  1020  4356 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:49.437  1020  4356 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:41:49.457  1020  1033 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 16:41:49.457  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService$LightweightWorkerService; callingUser = 0; userId(target) = 0
09-09 16:41:49.457  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:49.457  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:49.457  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:41:49.457  4831  7467 W IcingInternalCorpora: getNumBytesRead when not calculated.
,09-09 16:41:49.497  7247  7273 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
09-09 16:41:49.497  7247  7273 I AcmsCertificateMngr: getKeyStoreForApplication success 
09-09 16:41:49.497  7247  7273 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
09-09 16:41:49.497  7247  7273 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-09 16:41:49.497  7247  7273 D AcmsServiceMonitor: Decrementing - Counter value: 2
09-09 16:41:49.497  7247  7273 D AcmsCertificateMngr: handleAppRemoved() Enter com.test.thalitest
,09-09 16:41:49.507  7494  7494 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 16:41:49.507  1020  1330 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.mirrorlink, calleePkgName: com.samsung.android.app.mirrorlink
,09-09 16:41:49.507  7494  7494 D ActivityThread: Added TimaKeyStore provider
,09-09 16:41:49.517  7247  7273 D ActivityThread: Loading provider com.samsung.mirrorlink.acms.provider: com.samsung.android.mirrorlink.acms.provider.AcmsDbProvider
,09-09 16:41:49.517  6913  7440 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,09-09 16:41:49.527  1020  1541 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 16:41:49.527  1020  1541 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService$LightweightWorkerService; callingUser = 0; userId(target) = 0
,09-09 16:41:49.527  1020  1541 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:49.527  1020  1541 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:49.527  1020  1541 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:41:49.527  7476  7511 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
09-09 16:41:49.527  7476  7511 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
09-09 16:41:49.527  1020  1540 I ActivityManager: Killing 7166:com.samsung.android.provider.filterprovider/u0a95 (adj 15): empty #21
,09-09 16:41:49.537  7476  7511 D SPPClientService: PushLog.txt file is not deleted.
09-09 16:41:49.537  7476  7511 D SPPClientService: PushLog.txt file is not deleted.
09-09 16:41:49.537  7476  7511 D SPPClientService: ============PushLog. stop!
,09-09 16:41:49.537  7247  7273 D AcmsAppEntryInterface: App not found in DB Hence ignore
09-09 16:41:49.537  7247  7273 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>5
09-09 16:41:49.537  7247  7273 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
09-09 16:41:49.537  7247  7273 D AcmsServiceMonitor: Decrementing - Counter value: 1
09-09 16:41:49.537  7247  7273 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
,09-09 16:41:49.547  1020  1330 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,09-09 16:41:49.547  7247  7273 D AcmsCore: This is NOT a valid MirrorLink app
,09-09 16:41:49.547  1020  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:49.547  1020  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:49.547  7247  7273 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
09-09 16:41:49.547  1020  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:49.547  7247  7273 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
,09-09 16:41:49.547  1020  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:49.547  7247  7273 D AcmsServiceMonitor: Decrementing - Counter value: 0
09-09 16:41:49.547  7247  7273 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
,09-09 16:41:49.567  7513  7513 E Zygote  : MountEmulatedStorage(),
09-09 16:41:49.567  7513  7513 I libpersona: KNOX_SDCARD checking this for 10039
09-09 16:41:49.567  7513  7513 E Zygote  : v2
09-09 16:41:49.567  7513  7513 I libpersona: KNOX_SDCARD not a persona,
09-09 16:41:49.567  1020  1330 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=7513 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,09-09 16:41:49.567  7513  7513 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-09 16:41:49.567  7513  7513 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-09 16:41:49.577  7513  7513 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 16:41:49.587  7247  7247 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
,09-09 16:41:49.587  7247  7247 D AcmsService: Enter onDestroy
09-09 16:41:49.587  7247  7247 I AcmsService: cleanUp(): inside service clean up
09-09 16:41:49.587  7247  7247 D AcmsCore: AcmsCore: inside DeInit
,09-09 16:41:49.587  7247  7247 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
09-09 16:41:49.587  7247  7247 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
,09-09 16:41:49.597  7247  7247 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
09-09 16:41:49.597  7247  7247 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
09-09 16:41:49.597  7247  7247 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
09-09 16:41:49.597  7247  7247 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
09-09 16:41:49.597  7247  7247 D AcmsService: killing acms process
09-09 16:41:49.597  7247  7247 I Process : Sending signal. PID: 7247 SIG: 9
,09-09 16:41:49.597  7513  7513 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 16:41:49.597  7513  7513 D ActivityThread: Added TimaKeyStore provider
,09-09 16:41:49.607  7231  7231 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
09-09 16:41:49.617   289   289 E SMD     : DCD OFF
,09-09 16:41:49.647  7494  7494 D AASAservice: onCreate()
,09-09 16:41:49.667  7494  7494 E AASAservice: getConfirmRuleVersion() : Version File is not exist.
,09-09 16:41:49.667  2751  2751 I DBG_POLICYDM: [com.sec.android.policydm.aasa.AASAUpdater$1(72/onServiceConnected)] AASA: onServiceConnected
,09-09 16:41:49.677  1020  1216 I ActivityManager: Process ACMS.Process (pid 7247)(adj 0) has died(41,751)
,09-09 16:41:49.687  7513  7513 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,09-09 16:41:49.687  7513  7513 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 16:41:49.687  7513  7513 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 16:41:49.687  7513  7513 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,09-09 16:41:49.687  7513  7513 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
09-09 16:41:49.687  7513  7513 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-09 16:41:49.687  7513  7513 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-09 16:41:49.727  1020  1330 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
09-09 16:41:49.727  1020  1330 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,09-09 16:41:49.727  1020  1330 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:49.727  1020  1330 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:41:49.727  1020  1330 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,09-09 16:41:49.747  7231  7462 D jxcore_app_log: JniHelper::setJavaVM(0xb792a2b0), pthread_self() = -1209280768
,09-09 16:41:49.757  6034  6034 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,09-09 16:41:49.757  6034  6034 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,09-09 16:41:49.757  7231  7462 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-09 16:41:49.757  7231  7462 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-09 16:41:49.757  7231  7462 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-09 16:41:49.757  7231  7462 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-09 16:41:49.757  7231  7462 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-09 16:41:49.757  7231  7462 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d895dbb added. We now have 1 listener(s)
,09-09 16:41:49.767  7231  7462 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:76:27
,09-09 16:41:49.767  7231  7462 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:76:27"
,09-09 16:41:49.777  7231  7462 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-09 16:41:49.777  7231  7462 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-09 16:41:49.777  7231  7462 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-09 16:41:49.777  7231  7462 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-09 16:41:49.777  7231  7462 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-09 16:41:49.777  7231  7462 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:76:27
09-09 16:41:49.777  7231  7462 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-09 16:41:49.777  7231  7462 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-09 16:41:49.777  7231  7462 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-09 16:41:49.777  7231  7462 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-09 16:41:49.777  7231  7462 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-09 16:41:49.777  7231  7462 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-09 16:41:49.777  7231  7462 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-09 16:41:49.777  7231  7462 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-09 16:41:49.777  7231  7462 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-09 16:41:49.777  7231  7462 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-09 16:41:49.777  7231  7462 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e47c116 added. We now have 1 listener(s)
,09-09 16:41:49.777  7231  7462 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-09 16:41:49.787  7231  7462 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-09 16:41:49.787  7231  7462 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-09 16:41:49.787  7231  7462 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-09 16:41:49.787  7231  7462 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-09 16:41:49.787  7231  7462 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,09-09 16:41:49.797  7231  7462 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-09 16:41:49.797  7231  7462 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:76:27
,09-09 16:41:49.807  7231  7462 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,09-09 16:41:49.807  7231  7462 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-09 16:41:49.807  7231  7462 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-09 16:41:49.807  7231  7462 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
09-09 16:41:49.807  7231  7462 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-09 16:41:49.807  7231  7462 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-09 16:41:49.807  7231  7462 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-09 16:41:49.807  7231  7462 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-09 16:41:49.807  7231  7462 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,09-09 16:41:49.807  7231  7462 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-09 16:41:49.807  7231  7462 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-09 16:41:49.817  7231  7462 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-09 16:41:49.817  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:41:49.817  7231  7231 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-09 16:41:49.837  1871  1871 I SamsungIME: getDebugLevel  : 0x4f4c
,09-09 16:41:49.857  7231  7231 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-09 16:41:49.857  1020  1033 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 16:41:49.857  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:49.857  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:49.857  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,09-09 16:41:49.907  6034  6034 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 16:41:49.917  1871  1871 I SamsungIME: getDebugLevel  : 0x4f4c
,09-09 16:41:49.927  1871  1871 I SamsungIME: KeybaordView init() : load resources
,09-09 16:41:49.977  1871  1871 I SamsungIME: getCurrentKeyboard
,09-09 16:41:49.977  1871  1871 I SamsungIME: getTextKeyboard
,09-09 16:41:49.987  7513  7513 D NearbySource: Nearby Source Create!
,09-09 16:41:49.987  7513  7513 D NearbyContext: Nearby Context Create!
,09-09 16:41:49.997  2007  2160 I art     : Explicit concurrent mark sweep GC freed 45329(2MB) AllocSpace objects, 11(176KB) LOS objects, 39% free, 10MB/17MB, paused 1.270ms total 70.972ms
,09-09 16:41:49.997  1020  1339 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 16:41:49.997  1020  1339 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService$LightweightWorkerService; callingUser = 0; userId(target) = 0
09-09 16:41:49.997  1020  1339 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:41:49.997  1020  1339 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 16:41:49.997  1020  1339 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:41:50.017  1871  1871 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,09-09 16:41:50.057  6913  7440 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 534 ms] updated apps [took 534 ms] 
,09-09 16:41:50.057  1020  1533 I ActivityManager: Killing 7211:com.android.keychain/1000 (adj 15): empty #21
,09-09 16:41:50.057   258   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
09-09 16:41:50.057   258   520 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 16:41:50.067  7513  7513 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,09-09 16:41:50.067  7513  7513 D SLinkSource: Samsung link source created
,09-09 16:41:50.097  1020  1339 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,09-09 16:41:50.097  1020  1339 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.wear.WearSupportService; callingUser = 0; userId(target) = 0
,09-09 16:41:50.097  1020  1339 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:50.097  1020  1339 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:50.097  1020  1339 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,09-09 16:41:50.107  6034  6034 I Finsky  : [1] com.google.android.finsky.services.DailyHygiene.d(743): Logging device features
,09-09 16:41:50.117  1020  4354 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 16:41:50.117  1020  4354 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:50.117  1020  4354 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:50.117  1020  4354 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,09-09 16:41:50.117  1020  1099 V AlarmManager: waitForAlarm result :4
,09-09 16:41:50.147  7513  7536 D ContactProvider: getAllContactInfoList Start
,09-09 16:41:50.157  6034  6034 I Finsky  : [1] com.google.android.finsky.selfupdate.SelfUpdateCheckerScheduler.a(59): Cancelling accelerated self-Update check
,09-09 16:41:50.157  1020  1339 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 16:41:50.167  1020  4354 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,09-09 16:41:50.167  7513  7513 I PackagesMonitor: PackagesMonitor onReceive :com.test.thalitest
,09-09 16:41:50.167  6034  6034 W InstanceID/Rpc: Found 10011
,09-09 16:41:50.187  7513  7536 D ContactProvider: getAllContactInfoList End
,09-09 16:41:50.187  7513  7536 I syncContacts: thread: 1423, sync time = 51
,09-09 16:41:50.197  1020  1330 I splitIntent: Queue : background intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart  false.
,09-09 16:41:50.197  7408  7408 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-09 16:41:50.197  7408  7408 I PCWCLIENTTRACE_PushUtil: sales region : global
09-09 16:41:50.197  7408  7408 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-09 16:41:50.197  7408  7408 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REPLACED
09-09 16:41:50.197  7408  7408 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_PACKAGE_REPLACED_START
,09-09 16:41:50.207  2007  2024 D DeviceConnectionService: client connected with version: 9080000
,09-09 16:41:50.207  6034  6034 E Finsky  : [1] com.google.android.finsky.wear.bo.a(838): onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,09-09 16:41:50.207  1020  1506 I splitIntent: Split this intent : android.intent.action.PACKAGE_REPLACED, mSplitNum[0]=5, mSplitNum[1]=9, mSplitNum[2]=13, mBgSplitQueueNum=3 divideNum= 4 r.nextReceiver= 1 receivers.size=17
09-09 16:41:50.207  1020  1506 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REPLACED !! Enqueue -> schedule it!!
,09-09 16:41:50.207  6034  6034 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6396): Dropping command=send_installed_apps due to Gms not connected
,09-09 16:41:50.217  7393  7393 D Compatibility: onReceive() it will make start service
,09-09 16:41:50.217  1020  1046 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,09-09 16:41:50.217  1020  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:41:50.217  1020  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:50.217  1020  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:41:50.217  1020  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:41:50.227  7538  7538 E Zygote  : MountEmulatedStorage(),
09-09 16:41:50.227  7538  7538 E Zygote  : v2
,09-09 16:41:50.227  7538  7538 I libpersona: KNOX_SDCARD checking this for 10110
09-09 16:41:50.227  7538  7538 I libpersona: KNOX_SDCARD not a persona
09-09 16:41:50.227  1020  1046 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.app.receiver.FirstInstallNotificationReceiver: pid=7538 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 16:41:50.227  7538  7538 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 16:41:50.237  7538  7538 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 16:41:50.237  7538  7538 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 16:41:50.237  1020  1221 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
09-09 16:41:50.237  1020  1221 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
,09-09 16:41:50.237  1020  1221 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:50.237  1020  1221 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 16:41:50.237  1020  1221 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
,09-09 16:41:50.247  6034  6034 I Finsky  : [1] com.google.android.finsky.wear.WearSupportService.a(6396): Dropping command=hygiene due to Gms not connected
,09-09 16:41:50.247  7393  7546 D Compatibility: onHandleIntent()
,09-09 16:41:50.257  7538  7538 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 16:41:50.257  7538  7538 D ActivityThread: Added TimaKeyStore provider
,09-09 16:41:50.257  7393  7546 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REPLACED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10171, android.intent.extra.REPLACING=true, android.intent.extra.user_handle=0}]
,09-09 16:41:50.267  7393  7546 D Compatibility: found: 2
,09-09 16:41:50.267  7393  7546 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
09-09 16:41:50.267  7393  7546 D Compatibility: skipping ResolveInfo{35f21d63 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
09-09 16:41:50.267  7393  7546 D Compatibility: considering ResolveInfo{1a9cdd60 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
09-09 16:41:50.267  7393  7546 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,09-09 16:41:50.267  1020  1330 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 16:41:50.267  7393  7546 D Compatibility: enabling receiver ResolveInfo{387db219 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
09-09 16:41:50.267  1020  1330 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chimera.GmsIntentOperationService; callingUser = 0; userId(target) = 0
,09-09 16:41:50.267  1020  1330 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:50.267  1020  1330 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:50.267  1020  1330 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:41:50.277  1020  4354 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 16:41:50.277  4831  7051 D PkgBroadcastIntentOp: Received broadcast action=android.intent.action.PACKAGE_REPLACED and uri=com.test.thalitest
,09-09 16:41:50.277  7393  7546 D Compatibility: enabling receiver ResolveInfo{321ea2de com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,09-09 16:41:50.277  1020  4354 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:41:50.277  1020  4354 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:50.277  1020  4354 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:41:50.287  7393  7546 D Compatibility: enabling receiver ResolveInfo{25f2cbf com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,09-09 16:41:50.287  1020  4356 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 16:41:50.287  1020  4356 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-09 16:41:50.287  7393  7546 D Compatibility: enabling receiver ResolveInfo{1ce26f8c com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,09-09 16:41:50.297  1020  4356 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:50.297  1020  4356 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 16:41:50.297  1020  4356 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:41:50.297  1020  1032 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 16:41:50.297  1020  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.AppsMonitorIntentService; callingUser = 0; userId(target) = 0
,09-09 16:41:50.307  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:41:50.307  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 16:41:50.307  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:41:50.307  7393  7546 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,09-09 16:41:50.307  1020  4354 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 16:41:50.307  1020  4354 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-09 16:41:50.307  1020  4354 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:50.307  1020  4354 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:50.307  1020  4354 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:41:50.317  4831  7051 D MS_IntentHandler: Package broadcast action=android.intent.action.PACKAGE_REPLACED and uri=com.test.thalitest
,09-09 16:41:50.327  1020  1221 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
09-09 16:41:50.327  1020  1221 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chimera.GmsIntentOperationService; callingUser = 0; userId(target) = 0
,09-09 16:41:50.327  1020  1221 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:41:50.327  1020  1221 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:50.327  1020  1221 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:41:50.327  4831  4831 D AsyncTaskServiceImpl: Submit a task: nzm
,09-09 16:41:50.337  1020  1339 I ActivityManager: Killing 6940:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
,09-09 16:41:50.337  1020  1379 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 16:41:50.347  1020  1379 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:50.347  1020  1379 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:50.347  1020  1379 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:41:50.357  7338  7338 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:168 android.app.ActivityThread.handleReceiver:3125 
,09-09 16:41:50.357  4831  5067 D nzm     : Processing package: com.test.thalitest
09-09 16:41:50.357  1020  1339 I ActivityManager: Killing 6175:com.android.mms/u0a41 (adj 15): empty #21
,09-09 16:41:50.357  1020  4356 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
,09-09 16:41:50.357  1020  4356 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,09-09 16:41:50.357  1020  4356 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:50.357  1020  4356 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:41:50.357  1020  4356 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,09-09 16:41:50.357  4831  5067 D GassUtils: Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
09-09 16:41:50.357  4831  5067 D nzm     : Found info for package com.test.thalitest in db.
,09-09 16:41:50.367  2007  2007 E NetworkScheduler.SR: Invalid parameter app
,09-09 16:41:50.377  2007  2007 E NetworkScheduler.SR: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,09-09 16:41:50.387  1020  1032 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 16:41:50.387  1020  1032 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService$LightweightWorkerService; callingUser = 0; userId(target) = 0
,09-09 16:41:50.387  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:50.387  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:50.387  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:41:50.397  1020  1330 I ActivityManager: Killing 7323:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,09-09 16:41:50.427  1020  1032 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
09-09 16:41:50.427  1020  1032 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,09-09 16:41:50.427  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:50.427  1020  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:41:50.427  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
,09-09 16:41:50.447  1020  1033 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,09-09 16:41:50.447  1020  1033 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.LightweightIndexService$LightweightWorkerService; callingUser = 0; userId(target) = 0
,09-09 16:41:50.447  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:41:50.447  1020  1033 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:50.447  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:41:50.487  1020  1526 D CountryDetector: No listener is left
,09-09 16:41:50.507  1020  1541 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-09 16:41:50.527  4831  5037 I Icing   : Indexing F5F81CF6796F0674BFD4891EB30D9087E2AF40AA from com.google.android.gms
,09-09 16:41:50.537  1020  3366 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,09-09 16:41:50.657  4831  5037 I Icing   : Indexing done F5F81CF6796F0674BFD4891EB30D9087E2AF40AA
,09-09 16:41:50.657  1020  1053 I PowerManagerService: [PWL] Off : 30s ago
09-09 16:41:50.657  1020  1053 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
09-09 16:41:50.657  1020  1053 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
09-09 16:41:50.657  1020  1053 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'wake:com.google.android.gms/.auth.account.be.accountstate.LoginAccountsChangedIntentService' (uid=10011, pid=4831, ws=null) (elapsedTime=43416)
09-09 16:41:50.657  1020  1053 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'Icing' (uid=10011, pid=4831, ws=WorkSource{10011 com.google.android.gms, 10052 com.google.android.googlequicksearchbox}) (elapsedTime=1373)
09-09 16:41:50.657  1020  1053 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              '*alarm*' (uid=1000, pid=1020, ws=WorkSource{10026}) (elapsedTime=535)
,09-09 16:41:50.677   258   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-09 16:41:50.677   258   520 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 16:41:50.677  7538  7560 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-09 16:41:50.677   258   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-09 16:41:50.677   258   520 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 16:41:50.687  7538  7560 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-09 16:41:50.697   258   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
09-09 16:41:50.697   258   520 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 16:41:50.697  7538  7561 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,09-09 16:41:50.707   258   520 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
09-09 16:41:50.707   258   520 W Vold    : Returning OperationFailed - no handler for errno 0
,09-09 16:41:50.707  7538  7561 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,09-09 16:41:50.717  7538  7538 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
09-09 16:41:50.717  7538  7538 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
09-09 16:41:50.717  7538  7538 I GAv4    :   adb logcat -s GAv4
,09-09 16:41:50.737  7538  7538 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,09-09 16:41:50.747  1020  1339 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-09 16:41:50.757  7538  7538 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,09-09 16:41:50.757  1020  1099 V AlarmManager: waitForAlarm result :4
,09-09 16:41:50.777  7538  7563 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,09-09 16:41:50.887  1020  3340 D SSRM:n  : SIOP:: AP = 460
,09-09 16:41:50.937  7231  7532 W jxcore-log: Initializing JXcore engine
09-09 16:41:50.937  7231  7532 W jxcore-log: JXcore engine is ready
,09-09 16:41:51.017  2004  2004 E audit   : type=1400 msg=audit(1473432111.017:205): avc:  denied  { ioctl } for  pid=7532 comm="Thread-1380" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2069 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,09-09 16:41:51.017  2004  2004 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
09-09 16:41:51.017  2004  2004 E audit   : type=1300 msg=audit(1473432111.017:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9d7f08f8 items=0 ppid=304 ppcomm=main pid=7532 auid=4294967295 uid=10171 gid=10171 euid=10171 suid=10171 fsuid=10171 egid=10171 sgid=10171 fsgid=10171 ses=4294967295 tty=(none) comm="Thread-1380" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
,09-09 16:41:51.017  2004  2004 E audit   : type=1320 msg=audit(1473432111.017:205): 
,09-09 16:41:51.037  7231  7532 W jxcore-log: Starting JXcore engine,
,09-09 16:41:51.057  4831  5037 I Icing   : Indexing D2B2F813CD55909B17D100D9886DFA4C4B449F6E from com.google.android.googlequicksearchbox
,09-09 16:41:51.067  1020  1330 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,09-09 16:41:51.067  1020  1330 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:41:51.067  1020  1330 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 16:41:51.067  1020  1330 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,09-09 16:41:51.097  7538  7538 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
,09-09 16:41:51.137  7538  7538 I cr.library_loader: Time to load native libraries: 13 ms (timestamps 3588-3601)
09-09 16:41:51.137  7538  7538 I cr.library_loader: Expected native library version number "", actual native library version number ""
,09-09 16:41:51.157  7231  7532 W jxcore-log: Platform android
09-09 16:41:51.157  7231  7532 W jxcore-log: 
09-09 16:41:51.157  7231  7532 W jxcore-log: Process ARCH arm
09-09 16:41:51.157  7231  7532 W jxcore-log: 
,09-09 16:41:51.157  7538  7538 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {10aaae52}
,09-09 16:41:51.157  7538  7538 I cr.library_loader: Expected native library version number "", actual native library version number ""
09-09 16:41:51.157  7538  7538 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,09-09 16:41:51.187  7538  7538 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,09-09 16:41:51.187  7538  7538 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-09 16:41:51.197  7538  7538 E SysUtils: ApplicationContext is null in ApplicationStatus
,09-09 16:41:51.207  4831  5037 I Icing   : Indexing done D2B2F813CD55909B17D100D9886DFA4C4B449F6E
,09-09 16:41:51.217  7538  7538 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
09-09 16:41:51.217  7538  7538 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
09-09 16:41:51.217  7538  7538 I Adreno-EGL: Build Date: 04/06/15 Mon
09-09 16:41:51.217  7538  7538 I Adreno-EGL: Local Branch: 
09-09 16:41:51.217  7538  7538 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
09-09 16:41:51.217  7538  7538 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
09-09 16:41:51.217  7538  7538 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,09-09 16:41:51.277  7538  7538 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,09-09 16:41:51.287  7538  7594 W cr.media: Requires BLUETOOTH permission
,09-09 16:41:51.287  7538  7538 I NSApplication: Starting up...
,09-09 16:41:51.287  1020  1526 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-09 16:41:51.297  1020  4356 W ActivityManager: getRunningAppProcesses: caller 10110 does not hold REAL_GET_TASKS; limiting output
,09-09 16:41:51.297  1020  1216 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,09-09 16:41:51.297  1020  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:41:51.297  1020  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:41:51.297  1020  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:51.297  1020  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:41:51.317  7599  7599 E Zygote  : MountEmulatedStorage(),
,09-09 16:41:51.317  7599  7599 E Zygote  : v2,
09-09 16:41:51.317  7599  7599 I libpersona: KNOX_SDCARD checking this for 10121
,09-09 16:41:51.317  7599  7599 I libpersona: KNOX_SDCARD not a persona
,09-09 16:41:51.317  7599  7599 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 16:41:51.327  7599  7599 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 16:41:51.327  1020  1216 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7599 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
09-09 16:41:51.327  7599  7599 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 16:41:51.327  1020  1216 I ActivityManager: Killing 7300:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
,09-09 16:41:51.347  7599  7599 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 16:41:51.347  7599  7599 D ActivityThread: Added TimaKeyStore provider
,09-09 16:41:51.367  7599  7599 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-09 16:41:51.367  7599  7599 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
09-09 16:41:51.367  7599  7599 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,09-09 16:41:51.377  7599  7599 D QuickConnect: PeriphStartReceiver.onReceive - android.intent.action.PACKAGE_REPLACED
,09-09 16:41:51.387  6977  6977 I TapandpayWidget:TapandpayAppWidgetProvider: onReceive()
,09-09 16:41:51.387  6977  6977 D TapandpayWidget:TapandpayAppWidgetProvider: onReceive() - action : android.intent.action.PACKAGE_REPLACED / mCurIndex :-10
,09-09 16:41:51.387  6977  6977 I TapandpayWidget:Utils: Clear T&P info.
,09-09 16:41:51.387  6977  6977 D TapandpayWidget:TapandpayAppWidgetProvider: Widget is not attached.
,09-09 16:41:51.387  1020  1379 I ActivityManager: Killing 6923:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,09-09 16:41:51.397  2602  2602 D daemonapp: [MSC_Daemon]>>> AWDCDS:28 [0:0] AWD CD Act : androidintentactionPACKAGE_REPLACED
,09-09 16:41:51.407  1020  1540 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_REPLACED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,09-09 16:41:51.407  1020  1046 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:41:51.407  1020  1046 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:51.407  1020  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,09-09 16:41:51.417  1020  1032 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,09-09 16:41:51.417  1020  1032 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService; callingUser = 0; userId(target) = 0
,09-09 16:41:51.417  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:41:51.417  1020  1032 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,09-09 16:41:51.417  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,09-09 16:41:51.427  1020  4354 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:41:51.427  1020  4354 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:51.427  1020  4354 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,09-09 16:41:51.447  7231  7532 I jxcore-log: JXcore Cordova bridge is ready!
09-09 16:41:51.447  7231  7532 I jxcore-log: 
,09-09 16:41:51.447  7231  7532 W jxcore-log: JXcore engine is started
,09-09 16:41:51.447  6034  7614 I Finsky  : [1090] com.google.android.finsky.receivers.FlushLogsReceiver$FlushLogsService.onHandleIntent(163): Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,09-09 16:41:51.457  1020  1045 W libprocessgroup: failed to kill pid 7300: No such process
,09-09 16:41:51.457  7231  7462 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,09-09 16:41:51.457  6034  6148 I PlayCommon: [1072] com.google.android.play.a.l.e(787): Preparing logs for uploading
,09-09 16:41:51.457  7231  7231 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-09 16:41:51.467  1020  1540 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
09-09 16:41:51.467  1020  1540 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.account.authenticator.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,09-09 16:41:51.467  4831  5037 I Icing   : Indexing F5F81CF6796F0674BFD4891EB30D9087E2AF40AA from com.google.android.gms
,09-09 16:41:51.467  4831  5037 I Icing   : Indexing done F5F81CF6796F0674BFD4891EB30D9087E2AF40AA
,09-09 16:41:51.467  6034  7615 I PlayCommon: [1091] com.google.android.play.a.l.e(787): Preparing logs for uploading
,09-09 16:41:51.477  7231  7532 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
09-09 16:41:51.477  7231  7532 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,09-09 16:41:51.477  6034  7615 I PlayCommon: [1091] com.google.android.play.a.l.e(789): No file ready to send
,09-09 16:41:51.477  7231  7231 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (57)
09-09 16:41:51.477  7231  7231 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,09-09 16:41:51.487  1020  4356 D FocusedStackFrame: Set to : 0
09-09 16:41:51.487  1020  4356 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
09-09 16:41:51.487  1020  4356 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
09-09 16:41:51.487  1020  4356 D InputDispatcher: Focused application set to: xxxx
09-09 16:41:51.487  1020  4356 D InputDispatcher: Focus left window: 7231
09-09 16:41:51.487  1020  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-09 16:41:51.487  1020  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
09-09 16:41:51.497  7231  7231 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-09 16:41:51.497  7231  7231 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
09-09 16:41:51.497  7231  7231 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-09 16:41:51.497  7231  7231 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,09-09 16:41:51.497  7231  7231 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-09 16:41:51.497  7231  7231 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-09 16:41:51.497  7231  7231 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d895dbb removed from the list
09-09 16:41:51.497  7231  7231 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-09 16:41:51.497  7231  7231 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1e47c116 removed from the list
09-09 16:41:51.497  7231  7231 D io.jxcore.node.ConnectivityMonitor: stop
09-09 16:41:51.497  7231  7231 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,09-09 16:41:51.507  7231  7231 I io.jxcore.node.LifeCycleMonitor: stop: OK
,09-09 16:41:51.517  1020  4355 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,09-09 16:41:51.517  1020  4355 W ActivityManager: userId = 0, bbcId = -10000,
,09-09 16:41:51.517  1020  4355 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
,09-09 16:41:51.517  1020  4355 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
09-09 16:41:51.517   259  1042 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
09-09 16:41:51.517   259   443 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,09-09 16:41:51.527  2007  2007 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-09 16:41:51.527  1020  1033 W ActivityManager: mDVFSHelper.acquire()
,09-09 16:41:51.537  1020  1033 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,09-09 16:41:51.557  1497  1497 D Launcher: onRestart, Launcher: 446487904
,09-09 16:41:51.557  1497  1497 D Launcher: onStart, Launcher: 446487904,
09-09 16:41:51.557  1497  1497 D Launcher.HomeView: onStart
09-09 16:41:51.557  1497  1497 D Launcher: onResume, Launcher: 446487904
,09-09 16:41:51.557  1020  4354 D SettingsProvider: name = kids_home_mode
09-09 16:41:51.567  1020  4354 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
09-09 16:41:51.567  1020  4354 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,09-09 16:41:51.567  1020  4354 D SettingsProvider: selectionArgs: false
09-09 16:41:51.567  1020  4354 D SettingsProvider: selectionArgs: 10006
,09-09 16:41:51.567  1020  4354 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
09-09 16:41:51.567  1020  4354 D SettingsProvider: ret = -1
,09-09 16:41:51.567  6034  6148 I PlayCommon: [1072] com.google.android.play.a.l.a(927): Connecting to server: https://play.googleapis.com/play/log?format=raw&proto_v2=true
,09-09 16:41:51.567  1497  1497 D Launcher.HomeView: onResume
,09-09 16:41:51.577  1497  1497 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,09-09 16:41:51.577  6034  6148 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
09-09 16:41:51.577  6034  6148 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
09-09 16:41:51.577  6034  6148 I System.out: (HTTPLog)-Static: isShipBuild true
09-09 16:41:51.577  6034  6148 I System.out: (HTTPLog)-Thread-1072-300766532: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,09-09 16:41:51.577  6034  6148 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,09-09 16:41:51.577   279  1009 D EnterpriseController: mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
09-09 16:41:51.577   279  1009 D Netd    : getNetworkForDns: using netid 502 for uid 10026
,09-09 16:41:51.577  1020  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:51.577  1020  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:41:51.577  1020  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
09-09 16:41:51.587  1497  1497 D MenuAppsGridFragment: onResume
,09-09 16:41:51.587  1020  1221 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=7, mSplitNum[2]=9, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=11
,09-09 16:41:51.587  1497  1497 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,09-09 16:41:51.587  1020  1221 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,09-09 16:41:51.587  1497  1497 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
09-09 16:41:51.587  1020  1221 W ActivityManager: userId = 0, bbcId = -10000,
09-09 16:41:51.587  1020  1221 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:41:51.587  1020  1221 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,09-09 16:41:51.597  1020  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:51.597  1020  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:41:51.597  1020  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,09-09 16:41:51.597  7513  7513 D GalleryCacheReady: Receive : home resume
,09-09 16:41:51.597  1020  1046 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:41:51.597  1020  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 16:41:51.597  1020  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.dualclockdigital
09-09 16:41:51.597  1020  1046 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.dualclockdigital, hostingType: broadcast
,09-09 16:41:51.597  1020  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:51.597  1020  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:51.597  1020  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:51.597  1020  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:41:51.617  7621  7621 E Zygote  : MountEmulatedStorage()
09-09 16:41:51.617  7621  7621 E Zygote  : v2
09-09 16:41:51.617  7621  7621 I libpersona: KNOX_SDCARD checking this for 10089
,09-09 16:41:51.617  7621  7621 I libpersona: KNOX_SDCARD not a persona
,09-09 16:41:51.617  7621  7621 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 16:41:51.617  1020  1046 I ActivityManager: Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=7621 uid=10089 gids={50089, 9997, 3003} abi=armeabi-v7a
,09-09 16:41:51.617  7621  7621 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 16:41:51.627  1020  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:51.627  1020  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:41:51.627  1020  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
09-09 16:41:51.627  1020  1046 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
,09-09 16:41:51.627  7621  7621 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,09-09 16:41:51.627  1020  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:51.627  1020  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0,
09-09 16:41:51.627  1020  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:51.627  1020  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:41:51.627  6034  6148 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,09-09 16:41:51.647   304   304 I art     : Explicit concurrent mark sweep GC freed 8683(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 628us total 23.400ms
,09-09 16:41:51.647  7621  7621 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 16:41:51.647  7621  7621 D ActivityThread: Added TimaKeyStore provider
,09-09 16:41:51.657   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 576us total 16.373ms
,09-09 16:41:51.677   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 568us total 16.182ms,
,09-09 16:41:51.687  7636  7636 E Zygote  : MountEmulatedStorage()
09-09 16:41:51.687  7636  7636 E Zygote  : v2
,09-09 16:41:51.687  7636  7636 I libpersona: KNOX_SDCARD checking this for 10139,
09-09 16:41:51.687  7636  7636 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 16:41:51.687  7636  7636 I libpersona: KNOX_SDCARD not a persona
09-09 16:41:51.687  1020  1046 I ActivityManager: Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=7636 uid=10139 gids={50139, 9997, 1028, 1015} abi=armeabi-v7a
,09-09 16:41:51.687  7636  7636 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 16:41:51.687  1020  1221 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:51.687  1020  1221 D ActivityManager: startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast,
09-09 16:41:51.687  1020  1221 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:41:51.697  1020  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:51.687  1020  1221 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
09-09 16:41:51.697  1020  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:51.687  7636  7636 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 16:41:51.697  1020  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:41:51.697  1020  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:41:51.707  7651  7651 E Zygote  : MountEmulatedStorage()
,09-09 16:41:51.707  7651  7651 E Zygote  : v2
09-09 16:41:51.707  7651  7651 I libpersona: KNOX_SDCARD checking this for 10041
09-09 16:41:51.707  7651  7651 I libpersona: KNOX_SDCARD not a persona
,09-09 16:41:51.707  7651  7651 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 16:41:51.707  1020  1221 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.UIEventReceiver: pid=7651 uid=10041 gids={50041, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,09-09 16:41:51.717  7651  7651 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 16:41:51.717  7651  7651 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,09-09 16:41:51.717  7636  7636 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 16:41:51.717  7636  7636 D ActivityThread: Added TimaKeyStore provider
,09-09 16:41:51.717  1020  1033 D ActivityManager: handle home activity for 0
09-09 16:41:51.717  1020  1020 D PersonaManagerService: getPersonasForUser(): returning null!
09-09 16:41:51.717  1020  1033 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
09-09 16:41:51.717  1020  1033 D KnoxTimeoutHandler: post home show event for user 0
09-09 16:41:51.717  1020  1033 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
09-09 16:41:51.717  1020  1020 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
09-09 16:41:51.717  1020  1033 D KnoxTimeoutHandler: postActiveUserChange for user 0
09-09 16:41:51.717  1020  1033 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
09-09 16:41:51.717  1020  1020 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
09-09 16:41:51.717  1020  1020 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,09-09 16:41:51.727  1497  1497 D Launcher.HomeView: onPause
,09-09 16:41:51.727  1497  1497 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,09-09 16:41:51.747   259   259 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
,09-09 16:41:51.747  7651  7651 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 16:41:51.747  7651  7651 D ActivityThread: Added TimaKeyStore provider
,09-09 16:41:51.747  1020  1049 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-09 16:41:51.757  7621  7621 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 16:41:51.757  7621  7621 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
09-09 16:41:51.757  1020  1049 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,09-09 16:41:51.757  1020  1540 D InputDispatcher: Focus entered window: 1497
,09-09 16:41:51.767  1497  1497 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
09-09 16:41:51.767  1020  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
09-09 16:41:51.767  1020  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
,09-09 16:41:51.777  1020  4355 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:51.777  1020  4355 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1497, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
09-09 16:41:51.777  1020  4355 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:41:51.777  1020  4355 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,09-09 16:41:51.777  7636  7636 V TaskCloserActivity: TaskCloserActivity enter()
,09-09 16:41:51.777  1020  1046 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:51.777  1020  1046 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:41:51.777  1020  1046 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,09-09 16:41:51.777  2550  2550 D Recents_RecreateReceiver: onReceive by home
,09-09 16:41:51.787  1497  1497 V ActivityThread: updateVisibility : ActivityRecord{23c80b25 token=android.os.BinderProxy@308b7c91 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
09-09 16:41:51.787  1497  1497 D Launcher.HomeView: onStop
,09-09 16:41:51.787  1020  1033 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,09-09 16:41:51.787  1020  1533 W ActivityManager: userId = 0, bbcId = -10000
,09-09 16:41:51.787  7616  7616 D AndroidRuntime: 
09-09 16:41:51.787  7616  7616 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-09 16:41:51.787  1020  1533 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:41:51.787  1020  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
09-09 16:41:51.787  1020  1533 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
09-09 16:41:51.787  1175  1175 I StatusBar: Icon Only
,09-09 16:41:51.787  1175  1175 D PanelView: There is/are notification(s) 
09-09 16:41:51.787  7616  7616 D AndroidRuntime: CheckJNI is OFF
,09-09 16:41:51.797  7616  7616 D AndroidRuntime: readGMSProperty: start
09-09 16:41:51.797  1020  7668 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
09-09 16:41:51.797  7616  7616 D AndroidRuntime: readGMSProperty: already setted!!
09-09 16:41:51.797  1020  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:51.797  7616  7616 D AndroidRuntime: propertySet: couldn't set property (it is from app)
09-09 16:41:51.797  1020  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:51.797  7616  7616 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
09-09 16:41:51.797  1020  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:51.797  7616  7616 D AndroidRuntime: readGMSProperty: end
09-09 16:41:51.797  1020  1533 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:51.797  7616  7616 D AndroidRuntime: addProductProperty: start
09-09 16:41:51.797  7636  7636 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,09-09 16:41:51.797  7231  7231 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,09-09 16:41:51.797  7651  7651 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
09-09 16:41:51.797  7651  7651 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 16:41:51.797  7651  7651 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
09-09 16:41:51.797  7651  7651 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
09-09 16:41:51.797  7651  7651 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,09-09 16:41:51.797  1871  1871 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,09-09 16:41:51.817  1020  1533 I ActivityManager: Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=7670 uid=10084 gids={50084, 9997} abi=armeabi-v7a
,09-09 16:41:51.817  7670  7670 E Zygote  : MountEmulatedStorage()
,09-09 16:41:51.817  7670  7670 E Zygote  : v2
09-09 16:41:51.817  7670  7670 I libpersona: KNOX_SDCARD checking this for 10084
09-09 16:41:51.817  7670  7670 I libpersona: KNOX_SDCARD not a persona
,09-09 16:41:51.817  7670  7670 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 16:41:51.827  1020  1032 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:51.827  1020  1032 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:41:51.827  1020  1032 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,09-09 16:41:51.837  1020  1020 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
09-09 16:41:51.837  7670  7670 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 16:41:51.837  7670  7670 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,09-09 16:41:51.867  1020  4355 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:51.867  1020  4355 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
09-09 16:41:51.867  1020  4355 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:41:51.867  1020  4355 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,09-09 16:41:51.867  1020  4355 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:51.867  1020  4355 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:51.867  1020  4355 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:51.867  1020  4355 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:41:51.877  1497  1497 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@308b7c91 time:94342
,09-09 16:41:51.887  7692  7692 E Zygote  : MountEmulatedStorage()
09-09 16:41:51.887  7692  7692 I libpersona: KNOX_SDCARD checking this for 10135
09-09 16:41:51.887  7692  7692 E Zygote  : v2
09-09 16:41:51.887  7692  7692 I libpersona: KNOX_SDCARD not a persona
,09-09 16:41:51.887  7692  7692 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 16:41:51.887  7670  7670 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 16:41:51.887  7670  7670 D ActivityThread: Added TimaKeyStore provider,
,09-09 16:41:51.887  7692  7692 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 16:41:51.887  7692  7692 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 16:41:51.887  1020  4355 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=7692 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
09-09 16:41:51.897  1020  4355 I ActivityManager: Killing 7133:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,09-09 16:41:51.907  1020  1051 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{383eae4b u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t1} time:94370
09-09 16:41:51.907  1020  1051 W ActivityManager: mDVFSHelper.release()
,09-09 16:41:51.907  7651  7651 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
,09-09 16:41:51.917  7670  7670 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-09 16:41:51.927  7692  7692 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 16:41:51.927  7692  7692 D ActivityThread: Added TimaKeyStore provider
,09-09 16:41:51.937  7616  7616 E AffinityControl: AffinityControl: registerfunction enter
,09-09 16:41:51.937  1020  1330 I ActivityManager: Killing 7154:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
,09-09 16:41:51.947  6034  6148 I PlayCommon: [1072] com.google.android.play.a.l.a(1002): Successfully uploaded logs.
,09-09 16:41:51.957  6034  6148 I PlayCommon: [1072] com.google.android.play.a.l.e(787): Preparing logs for uploading
09-09 16:41:51.957  6034  6148 I PlayCommon: [1072] com.google.android.play.a.l.e(789): No file ready to send
,09-09 16:41:51.957  7692  7692 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
09-09 16:41:51.957  7692  7692 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-09 16:41:51.957  7692  7692 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
09-09 16:41:51.957  7692  7692 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
09-09 16:41:51.957  7692  7692 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,09-09 16:41:51.967  7616  7616 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-09 16:41:51.977  1020  1032 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000,
09-09 16:41:51.977  1020  1032 D PackageManager: START PACKAGE DELETE: observer{482000969}
09-09 16:41:51.977  1020  1032 D PackageManager: pkg{<packageName>}
09-09 16:41:51.977  1020  1032 D PackageManager: user{0}
09-09 16:41:51.977  1020  1032 D PackageManager: caller{2000}
09-09 16:41:51.977  1020  1032 D PackageManager: flags{2},
09-09 16:41:51.977  1020  1032 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
09-09 16:41:51.977  1020  1061 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
09-09 16:41:51.977  1020  1032 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
09-09 16:41:51.977  1020  1032 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
09-09 16:41:51.977  1020  1032 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,09-09 16:41:51.977  1020  1061 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
09-09 16:41:51.977  1020  1061 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
09-09 16:41:51.977  1020  1061 D ApplicationPolicy: getApplicationUninstallationEnabled
09-09 16:41:51.977  1020  1061 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,09-09 16:41:51.997  1020  1379 D PersonaManager: isKioskContainerExistOnDevice
,09-09 16:41:52.007  1020  1032 I ActivityManager: Killing 7355:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,09-09 16:41:52.017  1020  1061 D PackageManager: !@killApplicatoin: 10171, uninstall pkg
,09-09 16:41:52.017  1020  1046 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=-1: uninstall pkg
,09-09 16:41:52.017  1020  1046 I ActivityManager: Killing 7231:com.test.thalitest/u0a171 (adj 15): stop com.test.thalitest cause uninstall pkg
,09-09 16:41:52.047  1020  1221 I ActivityManager: Killing 7188:com.samsung.helphub/1000 (adj 15): empty #21
,09-09 16:41:52.057  7651  7651 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 102.893ms
,09-09 16:41:52.107  1020  1061 W PackageSettings: Skipping PackageSetting{2e34c22d com.example.hello/10168} due to missing metadata
,09-09 16:41:52.127  7651  7709 D Mms/ArtClassLoader: init before art
,09-09 16:41:52.127  7651  7651 D Mms/TelephonyPermission: start operation mode monitor
,09-09 16:41:52.137  7651  7651 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,09-09 16:41:52.137  1020  1061 I ActivityManager: Force stopping com.test.thalitest appid=10171 user=0: pkg removed
,09-09 16:41:52.167  1020  1061 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,09-09 16:41:52.187  2636  2636 I art     : Explicit concurrent mark sweep GC freed 2497(121KB) AllocSpace objects, 0(0B) LOS objects, 50% free, 3MB/7MB, paused 833us total 24.636ms
,09-09 16:41:52.197  1020  1102 I InputReader: Reconfiguring input devices.  changes=0x00000010
,09-09 16:41:52.207  1020  1020 D RCPManagerService: PackageReceiver onReceive()
,09-09 16:41:52.207  1020  1020 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,09-09 16:41:52.217  1020  1020 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
09-09 16:41:52.217  1020  1020 I OTPFW   : PackageRemovalReceiver::onReceive Enter
09-09 16:41:52.217  1020  1020 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10171 container id = 0
,09-09 16:41:52.217  1871  1871 E SamsungIME: mOCRHelper is null
,09-09 16:41:52.217  2007  2156 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,09-09 16:41:52.227  4831  4831 I art     : Explicit concurrent mark sweep GC freed 37453(2MB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 12MB/20MB, paused 1.262ms total 72.216ms
,09-09 16:41:52.237  1020  1020 I OTPFW   : ProvisionData::getAllEntries Enter
,09-09 16:41:52.237  1020  1020 E OTPFW   : ProvisionData::getAllEntries Table is empty
,09-09 16:41:52.277  7651  7651 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
09-09 16:41:52.277  7651  7651 D Mms/TelephonyPermission: isDefault true
,09-09 16:41:52.277  7651  7651 D Mms/MmsApp: onCreate() com.android.mms
,09-09 16:41:52.287  1461  1461 D PersonaManager: isKioskContainerExistOnDevice
,09-09 16:41:52.307  7651  7651 D Mms/MmsApp: [start]    initCountryIso consume time = 407.04849
,09-09 16:41:52.317  1020  1339 D CountryDetector: The first listener is added
,09-09 16:41:52.337  7651  7651 D Mms/MmsApp: [end]    initCountryIso consume time = 28.828281
09-09 16:41:52.337  7651  7651 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.15901
,09-09 16:41:52.347  1020  1128 V NetworkStats: removeUidsLocked() for UIDs [10171]
09-09 16:41:52.347  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
09-09 16:41:52.347  1020  1128 V NetworkStats: performPollLocked(flags=0x3)
,09-09 16:41:52.347  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox updated
,09-09 16:41:52.347  1020  1128 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,09-09 16:41:52.357  1461  1461 D RegisteredServicesCache: empty dynamic service
,09-09 16:41:52.367  7651  7651 D Mms/MmsConfig: before partial update
,09-09 16:41:52.377  1020  1128 V NetworkStats: performPollLocked() took 30ms
09-09 16:41:52.377  1020  1128 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 16:41:52.377  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 16:41:52.377  1020  1129 D NtpTrustedTime: currentTimeMillis() cache hit
,09-09 16:41:52.387  1020  1339 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,09-09 16:41:52.387  1020  1339 D SecContentProvider2: mCursor = null
,09-09 16:41:52.387  1461  1461 D RegisteredComponentCache: Collect Tech packages for Knox
,09-09 16:41:52.387  1461  1461 D PersonaManager: isKioskContainerExistOnDevice
,09-09 16:41:52.397  7651  7651 D Mms/MmsConfig: Load Resize quality : 80
,09-09 16:41:52.397  7651  7651 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
,09-09 16:41:52.397  7651  7651 D EasySignUpManager_1.0.1: isAuth is false
,09-09 16:41:52.397  7651  7651 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,09-09 16:41:52.437  1476  1843 D TP/MmsSmsProvider: query,matched:2117, calling pid = 7651
,09-09 16:41:52.447  1476  1843 D TP/MmsSmsProvider: match 2117:Elapsed time : 2.959 ms
,09-09 16:41:52.447  1020  1045 D EnterpriseDeviceManagerService: Package has changed for user 0
,09-09 16:41:52.447  1020  1045 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,09-09 16:41:52.457  1020  1045 W TextServicesManagerService: no available spell checker services found
,09-09 16:41:52.457  1020  1020 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-09 16:41:52.467  1020  1020 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,09-09 16:41:52.467  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
09-09 16:41:52.467  1020  1020 V EnterpriseBillingPolicy: uID is 10171
,09-09 16:41:52.467  1020  1020 V EnterpriseBillingPolicy: Removed Packageuid is0
09-09 16:41:52.467  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-09 16:41:52.467  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-09 16:41:52.467  7651  7651 D EasySignUpManager_1.0.1: isAuth is false
09-09 16:41:52.467  7651  7651 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
,09-09 16:41:52.467  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
,09-09 16:41:52.467  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
,09-09 16:41:52.467  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
09-09 16:41:52.467  7651  7651 E CscParser: mps_code.dat does not exist
09-09 16:41:52.467  7651  7651 E CscParser: customer_path =/system/csc/customer.xml
09-09 16:41:52.467  7651  7651 E CscParser: fileName + /system/csc/customer.xml
,09-09 16:41:52.467  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-09 16:41:52.477  1020  1020 V AlarmManagerEXT: com.test.thalitest(10171) is removed.
,09-09 16:41:52.487  7651  7651 E CscParser: mps_code.dat does not exist
09-09 16:41:52.487  7651  7651 E CscParser: customer_path =/system/csc/customer.xml
09-09 16:41:52.487  7651  7651 E CscParser: fileName + /system/csc/customer.xml
,09-09 16:41:52.487  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 16:41:52.497  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 16:41:52.497  7651  7651 D CscParser: getInstance fileName =/system/csc/customer.xml
,09-09 16:41:52.497  7651  7651 D Mms/MmsConfig:  enable multiwindow = false
,09-09 16:41:52.507  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 16:41:52.507  1020  1020 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,09-09 16:41:52.507  7651  7709 D Mms/ArtClassLoader: init [DONE] art
,09-09 16:41:52.507  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
09-09 16:41:52.507  1020  1020 V EnterpriseBillingPolicy: uID is 10171
09-09 16:41:52.507  1020  1020 V EnterpriseBillingPolicy: Removed Packageuid is0
09-09 16:41:52.507  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,09-09 16:41:52.507  1020  3340 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,09-09 16:41:52.507  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 16:41:52.507  1020  1163 D TaskPersister: removeObsoleteFile: deleting file=2_task.xml
09-09 16:41:52.517  1020  1020 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
09-09 16:41:52.517  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
09-09 16:41:52.517  1020  1020 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
09-09 16:41:52.517  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,09-09 16:41:52.517  1020  1020 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,09-09 16:41:52.527  7651  7651 E Mms/MessageUtils: setCountryDetector : update country detector info 
09-09 16:41:52.527  7651  7651 E Mms/MessageUtils: updateCountryIso : update country iso info 
,09-09 16:41:52.537  7651  7651 D Mms/MmsConfig: [end]    init() consume time = 193.694063
,09-09 16:41:52.547  7651  7651 D Mms/Contact: [start]    init() consume time = 7.539635,
,09-09 16:41:52.587  1476  1843 D TP/MmsSmsProvider: query,matched:13, calling pid = 7651
,09-09 16:41:52.587  7651  7651 D Mms/Contact: [end]    init consume time = 46.016875
,09-09 16:41:52.587  1476  1843 D TP/MmsSmsProvider: match 13:Elapsed time : 3.240 ms
,09-09 16:41:52.597  7651  7715 D Mms/DraftCache: [start]    rebuildCache consume time = 11.984271
,09-09 16:41:52.607  1020  1045 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,09-09 16:41:52.607  1476  4005 D TP/MmsSmsProvider: query,matched:12, calling pid = 7651
,09-09 16:41:52.607  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 16:41:52.617  1476  4005 D TP/MmsSmsProvider: match 12:Elapsed time : 3.302 ms
,09-09 16:41:52.617   289   289 E SMD     : DCD OFF
,09-09 16:41:52.617  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 16:41:52.617  7651  7651 D Mms/MethodReflector: getSubId is called
09-09 16:41:52.617  7651  7651 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,09-09 16:41:52.617  7651  7715 D Mms/DraftCache: [end]    rebuildCache consume time = 18.528437
,09-09 16:41:52.617  7651  7651 D Mms/MethodReflector: getTelephonyProperty is called
09-09 16:41:52.617  7651  7651 D Mms/DownloadManager: roaming -> false (slotId = 0)
,09-09 16:41:52.617  7651  7651 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
09-09 16:41:52.617  7651  7651 D Mms/DownloadManager: auto download without roaming -> true
09-09 16:41:52.617  7651  7651 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
09-09 16:41:52.617  7651  7651 D Mms/MethodReflector: getSubId is called
,09-09 16:41:52.617  7651  7651 D Mms/MethodReflector: getDefaultSmsSubId is called
09-09 16:41:52.617  7651  7651 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
09-09 16:41:52.617  7651  7651 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
09-09 16:41:52.617  7651  7651 D Mms/MethodReflector: getTelephonyProperty is called
09-09 16:41:52.617  7651  7651 D Mms/DownloadManager: roaming -> false (slotId = 1)
09-09 16:41:52.617  7651  7651 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
09-09 16:41:52.617  7651  7651 D Mms/DownloadManager: auto download without roaming -> true
09-09 16:41:52.617  7651  7651 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
09-09 16:41:52.617  7651  7651 D Mms/DownloadManager: auto download during roaming secondary -> false
09-09 16:41:52.617  7651  7651 D Mms/DownloadManager: mAutoDownload ------> true
,09-09 16:41:52.627  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 16:41:52.627  1020  1045 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
09-09 16:41:52.627  1020  1045 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-09 16:41:52.637  1020  1045 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-09 16:41:52.637  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 16:41:52.637  1020  1061 I art     : Explicit concurrent mark sweep GC freed 57934(3MB) AllocSpace objects, 14(224KB) LOS objects, 33% free, 25MB/37MB, paused 3.031ms total 334.118ms
,09-09 16:41:52.647  1020  1061 D PackageManager: delete codoeFile: 
,09-09 16:41:52.657  1020  1061 D AASAuninstall: userId = 0, info.removedAppID = 10171, info.uid = 10171, packageName = com.test.thalitest
,09-09 16:41:52.657  1020  1061 I AASA_removePackage: UID=10171 Target=com.test.thalitest
,09-09 16:41:52.657  1020  1061 D PackageManager: result of delete: 1{482000969}
,09-09 16:41:52.667  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 16:41:52.667  7651  7651 D ComposerPerformance: 1473432112673 ms / [DONE] Composer constructor
,09-09 16:41:52.667  7651  7651 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
,09-09 16:41:52.667  7616  7616 D AndroidRuntime: Shutting down VM
,09-09 16:41:52.667  7651  7651 I Mms/ReservationManager: ReservationManager()
09-09 16:41:52.667  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 16:41:52.667  7651  7651 I Mms/ReservationManager: resetAfterConnected()
,09-09 16:41:52.667  7651  7717 D Mms/Conversation: [start]    init() consume time = 51.617657
,09-09 16:41:52.677  1476  1490 D TP/MmsSmsProvider: query,matched:7, calling pid = 7651
,09-09 16:41:52.677  1020  1061 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
09-09 16:41:52.677  1020  1061 D PackageManager: userId{-1}
09-09 16:41:52.677  1020  1061 D PackageManager: andCode{true}
,09-09 16:41:52.677  1476  1490 D TP/MmsSmsProvider: match 7:Elapsed time : 1.611 ms
,09-09 16:41:52.677  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 16:41:52.677  1020  1061 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,09-09 16:41:52.677  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-09 16:41:52.677  1476  1495 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
,09-09 16:41:52.677  7651  7651 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,09-09 16:41:52.677  1476  1495 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
09-09 16:41:52.677  1476  1495 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,09-09 16:41:52.677  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 16:41:52.677  1476  1495 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
,09-09 16:41:52.687  7651  7651 D Mms/MmsApp: [end]    onCreate() consume time = 14.187239
,09-09 16:41:52.687  7651  7651 D Mms/UIEventReceiver: ui event
09-09 16:41:52.687  1476  1495 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
09-09 16:41:52.687  1476  1495 D TP/MmsSmsProvider: need read changed broadcast:false
09-09 16:41:52.687  7651  7651 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=744]
,09-09 16:41:52.687  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 16:41:52.687  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-09 16:41:52.687  7651  7651 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
,09-09 16:41:52.687  1020  1033 I splitIntent: Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
,09-09 16:41:52.687  7651  7651 D Mms/MethodReflector: getSubId is called
09-09 16:41:52.687  7651  7651 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
09-09 16:41:52.687  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
09-09 16:41:52.687  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,09-09 16:41:52.687  7651  7651 D Mms/MethodReflector: getTelephonyProperty is called
09-09 16:41:52.687  7651  7651 D Mms/DownloadManager: roaming -> false (slotId = 0)
09-09 16:41:52.687  7651  7651 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
09-09 16:41:52.687  7651  7651 D Mms/DownloadManager: auto download without roaming -> true
09-09 16:41:52.687  7651  7651 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : true, roaming : false
09-09 16:41:52.687  7651  7651 D Mms/DownloadManager: mAutoDownload ------> true
,09-09 16:41:52.697  7651  7717 D Mms/Conversation: [end]    init consume time = 7.798594
,09-09 16:41:52.697  1020  1045 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,09-09 16:41:52.697  1020  1033 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:52.697  1020  1033 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:41:52.697  1020  1033 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,09-09 16:41:52.697  7651  7717 D Mms/MessagingNotification: [start]    init() consume time = 3.585417
,09-09 16:41:52.697  1020  1045 D UsbSettingsManager: clearDefaults: com.test.thalitest
09-09 16:41:52.697  1020  1045 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,09-09 16:41:52.697  7636  7636 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,09-09 16:41:52.697  7651  7717 D Mms/MessagingNotification: [end]    init consume time = 5.669114
,09-09 16:41:52.707  1020  1540 I ActivityManager: Killing 7265:com.google.android.apps.plus/u0a117 (adj 15): empty #21
,09-09 16:41:52.707  7651  7718 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 5.470313
,09-09 16:41:52.707  2870  2870 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Sep 09 16:41:52 GMT+02:00 2016
,09-09 16:41:52.707  1020  1221 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
09-09 16:41:52.707  1020  1221 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,09-09 16:41:52.707  1476  1495 D TP/MmsSmsProvider: query,matched:0, calling pid = 7651
09-09 16:41:52.707  1476  1495 V TP/MmsSmsProvider: getSimpleConversations entered.
09-09 16:41:52.707  1020  1221 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:52.707  1020  1221 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:41:52.707  1020  1221 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,09-09 16:41:52.707  1476  1495 D TP/MmsSmsProvider: match 0:Elapsed time : 1.120 ms
,09-09 16:41:52.717  7651  7719 D Mms/Synchronizer: [start]    doSync consume time = 5.84526
,09-09 16:41:52.717  1476  4005 D TP/MmsSmsProvider: query,matched:400, calling pid = 7651
,09-09 16:41:52.717  2870  2870 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,09-09 16:41:52.717  7651  7718 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 7.137604
,09-09 16:41:52.717  1020  1330 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=11, mSplitNum[1]=21, mSplitNum[2]=31, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=41
,09-09 16:41:52.717  1020  1330 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,09-09 16:41:52.727  1020  1330 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,09-09 16:41:52.727  1020  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:41:52.727  1020  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:41:52.727  1020  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:52.727  1020  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,09-09 16:41:52.727  2870  2870 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,09-09 16:41:52.727  2870  2870 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,09-09 16:41:52.727  2870  2870 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,09-09 16:41:52.737  2870  7721 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,09-09 16:41:52.737  2870  7721 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,09-09 16:41:52.737  7722  7722 E Zygote  : MountEmulatedStorage()
,09-09 16:41:52.737  7722  7722 E Zygote  : v2,
09-09 16:41:52.737  2870  7721 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,09-09 16:41:52.737  7722  7722 I libpersona: KNOX_SDCARD checking this for 10090,
09-09 16:41:52.737  7722  7722 I libpersona: KNOX_SDCARD not a persona
,09-09 16:41:52.737  7722  7722 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 16:41:52.747  2870  7721 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,09-09 16:41:52.747  1020  1330 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7722 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
,09-09 16:41:52.747  1020  1221 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
,09-09 16:41:52.747  7722  7722 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 16:41:52.747  7722  7722 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 16:41:52.757  1020  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:52.757  1020  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:52.757  1020  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:52.757  1020  1221 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:41:52.767  7722  7722 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 16:41:52.767  7722  7722 D ActivityThread: Added TimaKeyStore provider
,09-09 16:41:52.767  7737  7737 E Zygote  : MountEmulatedStorage()
,09-09 16:41:52.777  7737  7737 E Zygote  : v2,
09-09 16:41:52.777  7737  7737 I libpersona: KNOX_SDCARD checking this for 10068
,09-09 16:41:52.777  7737  7737 I libpersona: KNOX_SDCARD not a persona
,09-09 16:41:52.777  7737  7737 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 16:41:52.777  1020  1221 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=7737 uid=10068 gids={50068, 9997} abi=armeabi-v7a
,09-09 16:41:52.787  7737  7737 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 16:41:52.787  7737  7737 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,09-09 16:41:52.797  1020  1033 I TactileAssist: enable value -1
09-09 16:41:52.797  1020  1033 I TactileAssist: internal enable value -1
09-09 16:41:52.797  1020  1033 I TactileAssist: intensity value -1
09-09 16:41:52.797  1020  1033 I TactileAssist: saveAppList value true
,09-09 16:41:52.797  7338  7338 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:3125 
,09-09 16:41:52.797  1020  1033 I TactileAssist: List of disabled apps :
,09-09 16:41:52.807  2870  7721 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,09-09 16:41:52.807  1020  1046 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
,09-09 16:41:52.817  1020  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:41:52.817  1020  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:52.817  1020  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:52.817  1020  1046 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:41:52.817  2870  7721 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,09-09 16:41:52.827  2870  7721 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
09-09 16:41:52.827  7737  7737 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 16:41:52.827  7737  7737 D ActivityThread: Added TimaKeyStore provider
,09-09 16:41:52.827  7751  7751 E Zygote  : MountEmulatedStorage()
09-09 16:41:52.827  7751  7751 E Zygote  : v2
09-09 16:41:52.827  7751  7751 I libpersona: KNOX_SDCARD checking this for 1000
09-09 16:41:52.827  7751  7751 I libpersona: KNOX_SDCARD not a persona
,09-09 16:41:52.827  7751  7751 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
09-09 16:41:52.827  7722  7722 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,09-09 16:41:52.837  7722  7722 D elm:15121: ELMEngine.ELMEngine( context ).,
,09-09 16:41:52.837  7722  7722 D elm:15121: MDMBridge.setEnterpriseBridge()
,09-09 16:41:52.837  7751  7751 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 16:41:52.837  7751  7751 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 16:41:52.837  1020  1046 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=7751 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
09-09 16:41:52.837  1020  1216 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:52.837  1020  1216 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,09-09 16:41:52.837  1020  1216 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:41:52.837  1020  1216 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
09-09 16:41:52.837  1020  1216 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,09-09 16:41:52.837  7722  7722 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,09-09 16:41:52.837  1476  2454 D TP/MmsSmsProvider: update, matched:300, calling pid = 7651
09-09 16:41:52.837  1476  2454 V TP/MmsSmsProvider: syncDBData start
,09-09 16:41:52.847  1476  2454 V TP/MmsSmsProvider: syncDBData sms end
09-09 16:41:52.847  7722  7722 D elm:15121: ElmAgentService : onCreate()
09-09 16:41:52.847  1476  2454 V TP/MmsSmsProvider: syncDBData mms end
09-09 16:41:52.847  7722  7760 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,09-09 16:41:52.847  1476  2454 V TP/MmsSmsProvider: syncDBData end
09-09 16:41:52.847  7722  7760 D elm:15121: MainReceiver.listeningToPackageRemoved()
09-09 16:41:52.847  7722  7760 D elm:15121: MDMBridge.getInstance()
09-09 16:41:52.847  7722  7760 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,09-09 16:41:52.847  2870  2870 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,09-09 16:41:52.847  7722  7760 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,09-09 16:41:52.847  1020  4355 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
09-09 16:41:52.847  1020  4355 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
,09-09 16:41:52.847  1020  4355 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:52.847  1020  4355 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:41:52.847  1020  4355 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,09-09 16:41:52.857  7651  7719 D Mms/Synchronizer: [end]    doSync consume time = 138.854375
,09-09 16:41:52.857  6998  6998 D CAR.SERVICE: onUnbind
09-09 16:41:52.857  6998  6998 D CAR.SERVICE: CSB onClientsDisconnected
09-09 16:41:52.857  6998  6998 D CAR.SERVICE: tearDown
09-09 16:41:52.857  6998  6998 D CAR.SERVICE: tearDownCarState
09-09 16:41:52.857  6998  6998 D CAR.SERVICE: Skip, car not connected.
09-09 16:41:52.857  6998  6998 D CAR.SERVICE: tearDownClientState
,09-09 16:41:52.867  6998  6998 D CAR.SERVICE: requestStop
,09-09 16:41:52.867  7737  7737 D BadgeProvider: onCreate
09-09 16:41:52.867  7737  7737 D BadgeProvider: DatabaseHelper
,09-09 16:41:52.867  7408  7408 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
09-09 16:41:52.867  7408  7408 I PCWCLIENTTRACE_PushUtil: sales region : global
09-09 16:41:52.867  7408  7408 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
09-09 16:41:52.867  7408  7408 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,09-09 16:41:52.877  7393  7393 D Compatibility: onReceive() it will make start service
,09-09 16:41:52.877  1020  1540 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.bridge, hostingType: broadcast
,09-09 16:41:52.877  7751  7751 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 16:41:52.877  7616  7616 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
09-09 16:41:52.877  1020  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:41:52.877  7751  7751 D ActivityThread: Added TimaKeyStore provider
09-09 16:41:52.877  1020  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:41:52.887  1020  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:52.887  1020  1540 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:41:52.897  7770  7770 E Zygote  : MountEmulatedStorage()
,09-09 16:41:52.897  7770  7770 E Zygote  : v2
09-09 16:41:52.897  7770  7770 I libpersona: KNOX_SDCARD checking this for 1000
09-09 16:41:52.897  7770  7770 I libpersona: KNOX_SDCARD not a persona
,09-09 16:41:52.897  7770  7770 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 16:41:52.897  1020  1540 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=7770 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,09-09 16:41:52.897  7770  7770 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 16:41:52.897  1020  4355 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
09-09 16:41:52.897  1020  4355 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.soundalive/com.sec.android.app.soundalive.compatibility.Compatibility$Service; callingUser = 0; userId(target) = 0
09-09 16:41:52.897  7722  7722 D elm:15121: ElmAgentService : onDestroy().
,09-09 16:41:52.897  1020  4355 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:52.897  1020  4355 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
09-09 16:41:52.897  1020  4355 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.soundalive, destAppInfo.processName = com.sec.android.app.soundalive
09-09 16:41:52.897  7770  7770 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 16:41:52.907  7393  7777 D Compatibility: onHandleIntent()
09-09 16:41:52.907  7393  7777 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10171, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,09-09 16:41:52.907  7393  7777 D Compatibility: found: 2
,09-09 16:41:52.907  7393  7777 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
,09-09 16:41:52.907  7393  7777 D Compatibility: skipping ResolveInfo{1463d5db com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
09-09 16:41:52.907  7393  7777 D Compatibility: considering ResolveInfo{1c0cf878 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
09-09 16:41:52.907  7393  7777 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,09-09 16:41:52.917  6998  6998 D CAR.SERVICE: onDestroy
,09-09 16:41:52.917  7393  7777 D Compatibility: enabling receiver ResolveInfo{a0a8b51 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,09-09 16:41:52.917  6998  6998 D CAR.SERVICE: tearDown
09-09 16:41:52.917  6998  6998 D CAR.SERVICE: tearDownCarState
09-09 16:41:52.917  6998  6998 D CAR.SERVICE: Skip, car not connected.
09-09 16:41:52.917  6998  6998 D CAR.SERVICE: tearDownClientState
09-09 16:41:52.917  6998  6998 D CAR.SERVICE: requestStop
,09-09 16:41:52.927  1020  1379 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-09 16:41:52.927  1020  1379 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,09-09 16:41:52.927  1020  1379 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:52.927  1020  1379 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:52.927  1020  1379 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-09 16:41:52.927  7393  7777 D Compatibility: enabling receiver ResolveInfo{e962fb6 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,09-09 16:41:52.927  7770  7770 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 16:41:52.927  7770  7770 D ActivityThread: Added TimaKeyStore provider
09-09 16:41:52.937  7751  7751 D PopupuiReceiver: onReceive() getAction : android.intent.action.PACKAGE_REMOVED
,09-09 16:41:52.937  7393  7777 D Compatibility: enabling receiver ResolveInfo{153ff4b7 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,09-09 16:41:52.937  6998  6998 E ActivityThread: Service com.google.android.gms.car.CarService has leaked ServiceConnection fmj@25bf9fd9 that was originally bound here
09-09 16:41:52.937  6998  6998 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection fmj@25bf9fd9 that was originally bound here
09-09 16:41:52.937  6998  6998 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
09-09 16:41:52.937  6998  6998 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
09-09 16:41:52.937  6998  6998 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
09-09 16:41:52.937  6998  6998 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
09-09 16:41:52.937  6998  6998 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
09-09 16:41:52.937  6998  6998 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
09-09 16:41:52.937  6998  6998 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
09-09 16:41:52.937  6998  6998 E ActivityThread: 	at ivw.a(:com.google.android.gms:120)
09-09 16:41:52.937  6998  6998 E ActivityThread: 	at ivw.a(:com.google.android.gms:137)
09-09 16:41:52.937  6998  6998 E ActivityThread: 	at fmj.h(:com.google.android.gms:76)
09-09 16:41:52.937  6998  6998 E ActivityThread: 	at fmj.<init>(:com.google.android.gms:64)
09-09 16:41:52.937  6998  6998 E ActivityThread: 	at fpn.i(:com.google.android.gms:551)
09-09 16:41:52.937  6998  6998 E ActivityThread: 	at com.google.android.gms.car.CarChimeraService.onBind(:com.google.android.gms:165)
09-09 16:41:52.937  6998  6998 E ActivityThread: 	at com.google.android.chimera.container.ServiceProxy.onBind(:com.google.android.gms:165)
09-09 16:41:52.937  6998  6998 E ActivityThread: 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3312)
09-09 16:41:52.937  6998  6998 E ActivityThread: 	at android.app.ActivityThread.access$2000(ActivityThread.java:181)
09-09 16:41:52.937  6998  6998 E ActivityThread: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1570)
09-09 16:41:52.937  6998  6998 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
09-09 16:41:52.937  6998  6998 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
09-09 16:41:52.937  6998  6998 E ActivityThread: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
09-09 16:41:52.937  6998  6998 E ActivityThread: 	at java.lang.reflect.Method.invoke(Native Method)
09-09 16:41:52.937  6998  6998 E ActivityThread: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-09 16:41:52.937  6998  6998 E ActivityThread: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
09-09 16:41:52.937  6998  6998 E ActivityThread: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,09-09 16:41:52.947  1020  1506 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
09-09 16:41:52.947  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:52.947  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:52.947  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:52.947  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:52.947  7393  7777 D Compatibility: enabling receiver ResolveInfo{5552424 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
09-09 16:41:52.957  7393  7777 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
09-09 16:41:52.957  7787  7787 E Zygote  : MountEmulatedStorage()
09-09 16:41:52.957  7787  7787 E Zygote  : v2
09-09 16:41:52.957  7787  7787 I libpersona: KNOX_SDCARD checking this for 10032
09-09 16:41:52.957  7787  7787 I libpersona: KNOX_SDCARD not a persona
09-09 16:41:52.957  7787  7787 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 16:41:52.967  7787  7787 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 16:41:52.967  1020  1506 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7787 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
09-09 16:41:52.967  7787  7787 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
09-09 16:41:52.967  1020  1379 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@1895bbc9
09-09 16:41:52.967  1020  1533 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:52.967  1020  1533 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-09 16:41:52.967  1020  1533 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:52.967  1020  1533 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
09-09 16:41:52.967  1020  1533 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-09 16:41:52.977  7651  7717 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,09-09 16:41:52.977  1020  1541 I ActivityManager: Killing 7368:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,09-09 16:41:52.987  1020  1506 D SecContentProvider2: uri = -1 selection = getSealedState
09-09 16:41:52.987  1020  1541 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
09-09 16:41:52.987  1020  1506 D SecContentProvider2: mCursor = null
09-09 16:41:52.987  1020  1541 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:52.987  1476  1843 D TP/SmsProvider: query,matched:26, calling pid = 7651
09-09 16:41:52.987  1020  1541 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:52.987  1476  1843 D TP/SmsProvider: match 26:Elapsed time : 1.821 ms
09-09 16:41:52.987  1020  1541 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:52.987  1020  1541 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:41:52.997  7751  7751 I PopupuiReceiver_KNOX: getSealedState : true
,09-09 16:41:52.997  1020  1533 D SecContentProvider2: uri = 15 selection = getSealedHideNotificationMessages
09-09 16:41:52.997  1020  1533 D SecContentProvider2: mCursor = null
,09-09 16:41:52.997  7751  7751 I PopupuiReceiver_KNOX: getSealedHideNotificationMessages : 1
,09-09 16:41:52.997  1020  1033 D SecContentProvider2: uri = 15 selection = getCheckCoverPopupState
09-09 16:41:52.997  1020  1033 D SecContentProvider2: mCursor = null
,09-09 16:41:52.997  7787  7787 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 16:41:52.997  7770  7770 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,09-09 16:41:52.997  7787  7787 D ActivityThread: Added TimaKeyStore provider
,09-09 16:41:53.007  7803  7803 E Zygote  : MountEmulatedStorage()
09-09 16:41:53.007  7803  7803 E Zygote  : v2
,09-09 16:41:53.007  7803  7803 I libpersona: KNOX_SDCARD checking this for 10055
09-09 16:41:53.007  7803  7803 I libpersona: KNOX_SDCARD not a persona
,09-09 16:41:53.007  7803  7803 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
09-09 16:41:53.007  7751  7751 I PopupuiReceiver_KNOX: getCheckCoverPopupState : true
,09-09 16:41:53.007  7751  7751 D PopupuiReceiver: Action package removed
,09-09 16:41:53.007  1020  1541 I ActivityManager: Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=7803 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
,09-09 16:41:53.007  7803  7803 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
09-09 16:41:53.007  1020  1216 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.themechooser, hostingType: broadcast
,09-09 16:41:53.007  6913  7795 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
09-09 16:41:53.007  1020  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:53.007  1020  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:53.007  1020  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:53.007  1020  1216 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:41:53.007  7803  7803 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,09-09 16:41:53.017  7770  7770 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,09-09 16:41:53.037  7817  7817 E Zygote  : MountEmulatedStorage()
09-09 16:41:53.037  7817  7817 I libpersona: KNOX_SDCARD checking this for 10145
09-09 16:41:53.037  7817  7817 E Zygote  : v2
09-09 16:41:53.037  7817  7817 I libpersona: KNOX_SDCARD not a persona
09-09 16:41:53.037  7817  7817 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,09-09 16:41:53.037  7803  7803 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 16:41:53.037  7817  7817 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,09-09 16:41:53.037  7803  7803 D ActivityThread: Added TimaKeyStore provider
,09-09 16:41:53.047  7817  7817 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
09-09 16:41:53.047  1020  1216 I ActivityManager: Start proc com.sec.android.app.themechooser for broadcast com.sec.android.app.themechooser/.CustomBroadCastReceiver: pid=7817 uid=10145 gids={50145, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,09-09 16:41:53.047  1020  1216 I ActivityManager: Killing 7538:com.google.android.apps.magazines/u0a110 (adj 15): empty #21
,09-09 16:41:53.057  7817  7817 D TimaKeyStoreProvider: TimaSignature is unavailable
09-09 16:41:53.057  7817  7817 D ActivityThread: Added TimaKeyStore provider
,09-09 16:41:53.067  1020  1541 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
09-09 16:41:53.067  1020  1541 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,09-09 16:41:53.067  1020  1541 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.docs, hostingType: broadcast
,09-09 16:41:53.077  1020  1541 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:41:53.077  1476  4005 D TP/MmsSmsProvider: query,matched:6, calling pid = 7651
09-09 16:41:53.077  1020  1541 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:53.077  1476  4005 D TP/MmsSmsProvider: match 6:Elapsed time : 0.860 ms
09-09 16:41:53.077  1020  1541 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:53.077  1020  1541 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:41:53.077  6913  7795 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
09-09 16:41:53.077  6913  7795 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,09-09 16:41:53.087   304   304 I art     : Explicit concurrent mark sweep GC freed 8662(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 618us total 38.095ms
,09-09 16:41:53.097  7803  7803 D UserAnalysis.PlaceProvider: PlaceProvider onCreate()
09-09 16:41:53.097   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 593us total 17.097ms
,09-09 16:41:53.117   304   304 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 583us total 16.757ms
,09-09 16:41:53.127  7833  7833 E Zygote  : MountEmulatedStorage(),
09-09 16:41:53.127  7833  7833 E Zygote  : v2
09-09 16:41:53.127  7833  7833 I libpersona: KNOX_SDCARD checking this for 10087
09-09 16:41:53.127  7833  7833 I libpersona: KNOX_SDCARD not a persona
09-09 16:41:53.127  1020  1541 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7833 uid=10087 gids={50087, 9997, 1028, 3003, 1015} abi=armeabi-v7a
,09-09 16:41:53.127  1020  1541 I ActivityManager: Killing 7057:com.samsung.android.sm/1000 (adj 15): empty #21
,09-09 16:41:53.137  7833  7833 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,09-09 16:41:53.137  7833  7833 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,09-09 16:41:53.137  7833  7833 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,09-09 16:41:53.137  7803  7803 D UserAnalysis.SecureDbManager: Key for secure DB is newly created
,09-09 16:41:53.137  7803  7803 D UserAnalysis.SecurePlaceDbHelper: SecurePlaceDbHelper() 
09-09 16:41:53.137  7803  7803 D UserAnalysis: Create SecureDbHelper
09-09 16:41:53.147  1020  1526 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
09-09 16:41:53.147  1020  1526 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.galaxyfinder/com.samsung.android.app.galaxyfinder.tag.TagReadyService; callingUser = 0; userId(target) = 0
,09-09 16:41:53.147  1020  1526 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:53.147  1020  1526 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,09-09 16:41:53.147  1020  1526 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.galaxyfinder, destAppInfo.processName = com.samsung.android.app.galaxyfinder
09-09 16:41:53.147  1020  1506 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
09-09 16:41:53.147  1020  1506 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService; callingUser = 0; userId(target) = 0
,09-09 16:41:53.147  1020  1506 W ActivityManager: userId = 0, bbcId = -10000
09-09 16:41:53.147  1020  1506 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
09-09 16:41:53.147  1020  1506 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,09-09 16:41:53.147  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:53.147  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:53.147  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
09-09 16:41:53.147  1020  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
,09-09 16:41:53.167  7833  7833 D TimaKeyStoreProvider: TimaSignature is unavailable
,09-09 16:41:53.167  7833  7833 D ActivityThread: Added TimaKeyStore provider

```
