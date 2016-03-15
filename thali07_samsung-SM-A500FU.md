#### Test 6275440391a6bae_thali07_samsung-SM-A500FU Logs


```
--------- beginning of main
03-15 20:34:54.413  1017  3014 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
03-15 20:34:54.413  1017  3014 D QSEECOMAPI: : App is not loaded in QSEE
03-15 20:34:54.423  3708  3761 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
03-15 20:34:54.423  3916  3916 E Zygote  : MountEmulatedStorage()
03-15 20:34:54.423  3916  3916 E Zygote  : v2
--------- beginning of system
03-15 20:34:54.423  3916  3916 I libpersona: KNOX_SDCARD checking this for 1000
03-15 20:34:54.423  3916  3916 I libpersona: KNOX_SDCARD not a persona
03-15 20:34:54.433  3916  3916 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-15 20:34:54.433  3916  3916 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-15 20:34:54.433  3916  3916 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 20:34:54.433  1017  3822 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:34:54.433  1017  3822 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:34:54.433  1017  3822 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
03-15 20:34:54.433  1017  3754 I ActivityManager: Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=3916 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-15 20:34:54.433  1017  3822 D ActivityManager: retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
03-15 20:34:54.443  1017  1042 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
03-15 20:34:54.443  3901  3901 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 20:34:54.443  3901  3901 D ActivityThread: Added TimaKeyStore provider
03-15 20:34:54.443  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-15 20:34:54.453  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-15 20:34:54.453  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-15 20:34:54.453  2689  2689 D FactoryTestApp: [DummyFtClient$onDestroy](2689) Destroy DummyFtClient service
03-15 20:34:54.463  2689  2689 D FactoryTestApp: [Support$Values.getString](2689) id=MODEL_COMMUNICATION_MODE, value=gsm
03-15 20:34:54.463  2689  2689 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2689) mConnectionMode = gsm
03-15 20:34:54.463  2689  2689 I FactoryTestApp: [ModuleCommon$isRunningFtClient](2689) RUNNING_FTCLIENT : false
03-15 20:34:54.463  2689  2689 D FactoryTestApp: [DummyFtClient$onDestroy](2689) kill process
03-15 20:34:54.463  2689  2689 I Process : Sending signal. PID: 2689 SIG: 9
03-15 20:34:54.463  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-15 20:34:54.463  1017  1042 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-15 20:34:54.463  1017  1042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 20:34:54.463  1017  1042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 20:34:54.473  1695  1708 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.gms, service: oauth2:https://www.googleapis.com/auth/cryptauth
03-15 20:34:54.473  1695  1708 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/cryptauth without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-15 20:34:54.473  1695  1708 I GLSUser : [GLSUser] Extracting token using key: Auth
03-15 20:34:54.473  1695  1708 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
03-15 20:34:54.473  1775  3818 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
03-15 20:34:54.473  3916  3916 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 20:34:54.473  3836  3836 D F_PHONE : [[com.sec.bcservice]] onServiceConnected()
03-15 20:34:54.473  3836  3836 I F_PHONE : default registerAction()
03-15 20:34:54.473  3836  3836 I F_PHONE : [[com.sec.bcservice]] sendPendingMessage()
03-15 20:34:54.473  3916  3916 D ActivityThread: Added TimaKeyStore provider
03-15 20:34:54.473  3901  3901 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
03-15 20:34:54.493  1695  1708 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-15 20:34:54.493  3884  3884 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-15 20:34:54.493  3884  3884 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-15 20:34:54.493  3884  3884 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-15 20:34:54.493  3884  3884 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-15 20:34:54.503  3884  3884 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-15 20:34:54.503  1017  1400 I ActivityManager: Process com.sec.factory (pid 2689)(adj 0) has died(147,1047)
03-15 20:34:54.503  1017  3822 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
03-15 20:34:54.503  1017  3822 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:34:54.503  1017  3822 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:34:54.503  1017  3822 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
03-15 20:34:54.513  3916  3916 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
03-15 20:34:54.513  3663  3663 I dex2oat : dex2oat took 2.268s (threads: 4)
,03-15 20:34:54.533  1017  3014 D QSEECOMAPI: : Loaded image: APP id = 10
03-15 20:34:54.533  1964  3552 D DexOptUtils: Odex created at:/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.dex
03-15 20:34:54.533  1964  3552 D DexOptUtils: Set odex to world readable.
03-15 20:34:54.533  1964  3552 D DexOptUtils: Renamed odex to /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc/arm/MapsModule.odex
03-15 20:34:54.533  1964  3552 D FileApkUtils: Keeping up-to-date module: module-d5b20f1a6029cea405dc44dd827a138ee4ccf8cc
03-15 20:34:54.533  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 20:34:54.543  1017  3014 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-15 20:34:54.543  1017  3014 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 10
03-15 20:34:54.543  1017  3014 E terrier : handleString: Failed to handle string(-4)
03-15 20:34:54.543  1017  3014 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
03-15 20:34:54.543  3436  3436 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
03-15 20:34:54.543  3436  3436 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
03-15 20:34:54.543  3436  3436 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-15 20:34:54.543  3436  3436 I PCWCLIENTTRACE_PushUtil: sales region : global
03-15 20:34:54.543  3436  3436 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-15 20:34:54.543  3436  3436 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
03-15 20:34:54.543  3708  3761 I GFX raster: took 0.682031ms for 96*96 texture 0
03-15 20:34:54.543  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fc1b50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fbd240 counterpartCT=4 counterpartW=96 counterparth=96
03-15 20:34:54.543  3916  3916 D BluetoothBDAdrressReceiver: onReceive(), action: android.intent.action.BOOT_COMPLETED
03-15 20:34:54.543  3916  3916 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
03-15 20:34:54.553  1964  3816 E AuthZen : Error getting auth token
03-15 20:34:54.553  1964  3816 E AuthZen : com.google.android.gms.auth.ad: BadAuthentication
03-15 20:34:54.553  1964  3816 E AuthZen : 	at com.google.android.gms.auth.p.b(SourceFile:442)
03-15 20:34:54.553  1964  3816 E AuthZen : 	at com.google.android.gms.auth.p.a(SourceFile:365)
03-15 20:34:54.553  1964  3816 E AuthZen : 	at com.google.android.gms.auth.p.a(SourceFile:318)
03-15 20:34:54.553  1964  3816 E AuthZen : 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:381)
03-15 20:34:54.553  1964  3816 E AuthZen : 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:132)
03-15 20:34:54.553  1964  3816 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
03-15 20:34:54.553  1964  3816 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
03-15 20:34:54.553  1964  3816 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
03-15 20:34:54.553  1964  3816 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
03-15 20:34:54.553  1964  3816 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
03-15 20:34:54.553  1964  3816 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
03-15 20:34:54.553  1964  3816 E AuthZen : 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
03-15 20:34:54.553  1964  3816 E AuthZen : 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
03-15 20:34:54.553  1964  3816 E AuthZen : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-15 20:34:54.553  1964  3816 E AuthZen : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 20:34:54.553  1964  3816 E AuthZen : 	at android.os.Looper.loop(Looper.java:145)
03-15 20:34:54.553  1964  3816 E AuthZen : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-15 20:34:54.553  1964  3816 E AuthZen : Failed to do enrollment for account: thalitester@gmail.com
03-15 20:34:54.553  1964  3816 E AuthZen : com.google.android.gms.auth.authzen.b.b: Failed to get a token for authzen enrollment
03-15 20:34:54.553  1964  3816 E AuthZen : 	at com.google.android.gms.auth.authzen.b.a.a(SourceFile:139)
03-15 20:34:54.553  1964  3816 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:200)
03-15 20:34:54.553  1964  3816 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:153)
03-15 20:34:54.553  1964  3816 E AuthZen : 	at com.google.android.gms.auth.authzen.b.d.a(SourceFile:103)
03-15 20:34:54.553  1964  3816 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:256)
03-15 20:34:54.553  1964  3816 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:207)
03-15 20:34:54.553  1964  3816 E AuthZen : 	at com.google.android.gms.auth.be.cryptauth.sync.b.a(SourceFile:200)
03-15 20:34:54.553  1964  3816 E AuthZen : 	at com.google.android.gms.auth.authzen.a.a(SourceFile:122)
03-15 20:34:54.553  1964  3816 E AuthZen : 	at com.google.android.gms.auth.authzen.GcmReceiverService.onHandleIntent(SourceFile:30)
03-15 20:34:54.553  1964  3816 E AuthZen : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-15 20:34:54.553  1964  3816 E AuthZen : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 20:34:54.553  1964  3816 E AuthZen : 	at android.os.Looper.loop(Looper.java:145)
03-15 20:34:54.553  1964  3816 E AuthZen : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-15 20:34:54.553  1017  1372 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:54.553  1017  1372 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:54.553  1017  1372 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:54.553  1017  1372 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:54.563  3708  3761 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
03-15 20:34:54.563  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-15 20:34:54.563  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-15 20:34:54.573  3937  3937 E Zygote  : MountEmulatedStorage()
03-15 20:34:54.573  3937  3937 I libpersona: KNOX_SDCARD checking this for 10031
03-15 20:34:54.573  3937  3937 E Zygote  : v2
03-15 20:34:54.573  3937  3937 I libpersona: KNOX_SDCARD not a persona
03-15 20:34:54.573  1017  1372 I ActivityManager: Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3937 uid=10031 gids={50031, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
03-15 20:34:54.573  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 20:34:54.573  1017  1129 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-15 20:34:54.573  3937  3937 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-15 20:34:54.573  3708  3761 I GFX raster: took 0.852500ms for 96*96 texture 0
03-15 20:34:54.573  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fc46b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fc49c8 counterpartCT=4 counterpartW=96 counterparth=96
03-15 20:34:54.573  1017  1129 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:34:54.573  1017  1129 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:34:54.573  1017  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-15 20:34:54.573  3937  3937 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-15 20:34:54.573  1017  3754 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.bluetoothtest/com.sec.android.app.bluetoothtest.BluetoothBDTestService; callingUser = 0; userId(target) = 0
03-15 20:34:54.573  3937  3937 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-15 20:34:54.583  1017  3754 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:34:54.583  1017  3754 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:34:54.583  1017  3754 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
03-15 20:34:54.583  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-15 20:34:54.583  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
03-15 20:34:54.583  1017  1372 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:54.583  1017  1372 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:54.583  1017  1372 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:54.583  1017  1372 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:54.583  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-15 20:34:54.593  3708  3761 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
03-15 20:34:54.593  1506  1506 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
03-15 20:34:54.593  1506  1506 D BluetoothBDTestService: onCreate()
03-15 20:34:54.593  1506  1506 E BluetoothBDTestService: onStart(), extra_type: BOOT_COMPLETED
03-15 20:34:54.593  1506  1506 E BluetoothBDTestService: bd_address_path: /efs/bluetooth/bt_addr
03-15 20:34:54.593  1506  1506 E BluetoothBDTestService: already exist!( /efs/bluetooth/bt_addr ), file length: 17
03-15 20:34:54.603  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-15 20:34:54.603  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
03-15 20:34:54.603  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-15 20:34:54.603  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
03-15 20:34:54.603  3954  3954 I libpersona: KNOX_SDCARD checking this for 1000
03-15 20:34:54.603  3954  3954 E Zygote  : MountEmulatedStorage()
03-15 20:34:54.603  3954  3954 I libpersona: KNOX_SDCARD not a persona
03-15 20:34:54.603  3954  3954 E Zygote  : v2
03-15 20:34:54.603  3954  3954 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-15 20:34:54.603  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-15 20:34:54.603  1017  1372 I ActivityManager: Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.receiver.ServiceStartReceiver: pid=3954 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-15 20:34:54.603  3954  3954 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-15 20:34:54.603  3954  3954 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 20:34:54.603  1017  1372 I ActivityManager: Killing 3139:com.google.android.configupdater/u0a86 (adj 15): empty #31
03-15 20:34:54.613  1017  1042 I CrashAnrDetector: onPackageAdded : com.test.thalitest
03-15 20:34:54.613  1964  3552 D GmsModuleFndr: Beginning GMS chimera module scan
03-15 20:34:54.613  1775  1775 V GmsNetworkLocationProvi: DISABLE
03-15 20:34:54.613  1017  1042 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
03-15 20:34:54.623  1017  1042 W libprocessgroup: failed to open /acct/uid_10150/pid_3124/cgroup.procs: No such file or directory
03-15 20:34:54.623  3937  3937 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 20:34:54.633  1017  3823 I ActivityManager: Killing 3201:com.sec.esdk.elm/u0a94 (adj 15): empty #31
03-15 20:34:54.633  3954  3954 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 20:34:54.633  3937  3937 D ActivityThread: Added TimaKeyStore provider
03-15 20:34:54.633  3954  3954 D ActivityThread: Added TimaKeyStore provider
03-15 20:34:54.643  1017  3823 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:54.643  1017  3823 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:54.643  1017  3823 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:54.643  1017  3823 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:54.663  3970  3970 E Zygote  : MountEmulatedStorage()
03-15 20:34:54.663  3970  3970 I libpersona: KNOX_SDCARD checking this for 10145
03-15 20:34:54.663  3970  3970 E Zygote  : v2
03-15 20:34:54.663  3970  3970 I libpersona: KNOX_SDCARD not a persona
03-15 20:34:54.663  3970  3970 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-15 20:34:54.663  3970  3970 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-15 20:34:54.663  1017  3823 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=3970 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
03-15 20:34:54.663  3970  3970 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 20:34:54.683  1964  3816 D a       : Opening database auth.proximity.permit_store...
03-15 20:34:54.683  3901  3901 I CalendarProvider2: CalendarProvider2.onCreate() called
03-15 20:34:54.693  3970  3970 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 20:34:54.693  3970  3970 D ActivityThread: Added TimaKeyStore provider
03-15 20:34:54.703  3954  3954 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 20:34:54.703  3937  3937 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-15 20:34:54.713  3970  3970 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-15 20:34:54.713  3970  3970 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 20:34:54.713  3970  3970 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-15 20:34:54.723  3970  3970 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 20:34:54.723  3970  3970 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-15 20:34:54.743  1017  1531 D PersonaManagerService: getPersonasForUser(): returning null!
03-15 20:34:54.773  1017  1042 W libprocessgroup: failed to open /acct/uid_10012/pid_2051/cgroup.procs: No such file or directory
03-15 20:34:54.783  1964  3552 D GmsModuleFndr: Module pkg com.google.android.apps.kids.familylink not installed, skipping
03-15 20:34:54.783  1964  3552 D ChimeraCfgMgr: Beginning module configuration check
03-15 20:34:54.783  1964  3552 D ChimeraCfgMgr: Module APKs unchanged, check complete
03-15 20:34:54.793  1964  3816 D AuthZenTransactionCache: Initialized cache in: /data/data/com.google.android.gms/files
03-15 20:34:54.793  1964  3816 D AuthZenTransactionCache: Clearing transaction cache
03-15 20:34:54.793  1017  1017 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-15 20:34:54.803  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 20:34:54.803  3708  3761 I GFX raster: took 0.700311ms for 96*96 texture 0
03-15 20:34:54.803  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fc0810 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fc0ad0 counterpartCT=4 counterpartW=96 counterparth=96
03-15 20:34:54.803  1187  1187 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-15 20:34:54.803  1187  1187 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-15 20:34:54.803  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 20:34:54.803  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 20:34:54.813  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 20:34:54.813  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 20:34:54.813  1775  1775 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
03-15 20:34:54.813  3708  3761 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
03-15 20:34:54.833  3954  3954 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.intent.action.BOOT_COMPLETED myUserId=0
03-15 20:34:54.833  3954  3954 I KnoxUsageLogPro: premStatus:2
03-15 20:34:54.833  3954  3954 I KnoxUsageLogPro: isEulaShown : false
03-15 20:34:54.833  3954  3954 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
03-15 20:34:54.843  1017  1746 I ActivityManager: Killing 3218:com.policydm/1000 (adj 15): empty #31
03-15 20:34:54.843  3954  3987 I KnoxUsageLogPro: savePreference: key = previous_sys_time value = 1458070494851
03-15 20:34:54.853  1017  1341 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-15 20:34:54.853  1017  1341 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:34:54.853  1017  1341 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:34:54.853  1017  1341 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-15 20:34:54.863  1017  1079 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-15 20:34:54.863  1017  1079 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:34:54.863  1017  1079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:34:54.863  1017  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
03-15 20:34:54.903  1017  1746 D RCPManagerService: exchangeData() failure , invalid userId
03-15 20:34:54.903  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 20:34:54.903  3708  3761 I GFX raster: took 0.722448ms for 96*96 texture 0
03-15 20:34:54.903  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fc16f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fbd240 counterpartCT=4 counterpartW=96 counterparth=96
03-15 20:34:54.913  3954  3987 I KnoxUsageLogPro: savePreference: key = previous_elapsed_time value = 42601
03-15 20:34:54.913  3708  3761 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
03-15 20:34:54.923  1017  1372 D RCPManagerService: exchangeData() failure , invalid userId
03-15 20:34:54.933  3937  3937 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.40254', coreVersion = '2.6.3.16956', ro.csc.sales_code=XEO
03-15 20:34:54.943  1017  1555 D RCPManagerService: exchangeData() failure , invalid userId
03-15 20:34:54.943  1017  1341 D RCPManagerService: exchangeData() failure , invalid userId
03-15 20:34:54.963  3937  3937 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.3.16956, SDK: 2.0.2173, EDM:16956
03-15 20:34:55.023  1017  1746 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:55.023  1017  1746 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:55.023  1017  1746 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:55.023  1017  1746 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:55.023  1017  3015 D RCPManagerService: exchangeData() failure , invalid userId
03-15 20:34:55.033  4005  4005 E Zygote  : MountEmulatedStorage()
03-15 20:34:55.033  4005  4005 E Zygote  : v2
03-15 20:34:55.033  1017  1746 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4005 uid=10072 gids={50072, 9997} abi=armeabi-v7a
03-15 20:34:55.033  4005  4005 I libpersona: KNOX_SDCARD checking this for 10072
03-15 20:34:55.033  4005  4005 I libpersona: KNOX_SDCARD not a persona
03-15 20:34:55.033  4005  4005 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-15 20:34:55.043  4005  4005 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-15 20:34:55.043  4005  4005 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-15 20:34:55.043  1017  1042 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
03-15 20:34:55.053  1017  1341 D RCPManagerService: exchangeData() failure , invalid userId
03-15 20:34:55.063  1017  1042 D LocationProviderProxy: applying state to connected service
03-15 20:34:55.063  1017  1531 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
03-15 20:34:55.063  1017  1531 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:34:55.063  1017  1042 W libprocessgroup: failed to open /acct/uid_10086/pid_3139/cgroup.procs: No such file or directory
03-15 20:34:55.063  1017  1531 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:34:55.063  1017  1042 W libprocessgroup: failed to open /acct/uid_10094/pid_3201/cgroup.procs: No such file or directory
03-15 20:34:55.063  1017  1531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
03-15 20:34:55.073  4005  4005 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 20:34:55.073  1017  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3218/cgroup.procs: No such file or directory
03-15 20:34:55.073  4005  4005 D ActivityThread: Added TimaKeyStore provider
03-15 20:34:55.093  3937  3937 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
03-15 20:34:55.093  3937  3937 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
03-15 20:34:55.103  3937  3937 D DialogFlow: initQueue()
03-15 20:34:55.103  4005  4005 D BadgeProvider: onCreate
03-15 20:34:55.103  4005  4005 D BadgeProvider: DatabaseHelper
03-15 20:34:55.123  1017  3823 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:55.123  1017  3823 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:55.123  1017  3823 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:55.123  1017  3823 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:55.133  4005  4021 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
03-15 20:34:55.133  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 20:34:55.133  3708  3761 I GFX raster: took 0.663646ms for 96*96 texture 0
03-15 20:34:55.133  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fc1e20 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fc20e0 counterpartCT=4 counterpartW=96 counterparth=96
03-15 20:34:55.133  4029  4029 E Zygote  : MountEmulatedStorage()
03-15 20:34:55.133  4029  4029 E Zygote  : v2
03-15 20:34:55.133  4029  4029 I libpersona: KNOX_SDCARD checking this for 10032
03-15 20:34:55.143  4029  4029 I libpersona: KNOX_SDCARD not a persona
03-15 20:34:55.143  4029  4029 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-15 20:34:55.143  1775  3818 I GCoreUlr: WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=10, mName='AuthError'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
03-15 20:34:55.143  1017  3823 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=4029 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
03-15 20:34:55.143  1017  3823 I ActivityManager: Killing 3251:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
03-15 20:34:55.153  4029  4029 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-15 20:34:55.153  4029  4029 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 20:34:55.153  3708  3761 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
03-15 20:34:55.173  4029  4029 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 20:34:55.183  4029  4029 D ActivityThread: Added TimaKeyStore provider
03-15 20:34:55.193  1528  1528 D Launcher.Model: reloadBadges entered.
03-15 20:34:55.213  4005  4020 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
03-15 20:34:55.213  4005  4020 D BadgeProvider: sendNotify, [notify] : null
03-15 20:34:55.213  4005  4020 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
03-15 20:34:55.213  4005  4020 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-15 20:34:55.213  4005  4020 D BadgeProvider: update, [UpdateCount] : 1
03-15 20:34:55.213  3943  3943 D AndroidRuntime: 
03-15 20:34:55.213  3943  3943 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-15 20:34:55.213  3860  4045 I Babel_SMS: MmsConfig: mnc/mcc: 0/0
03-15 20:34:55.213  3860  4045 I Babel_SMS: MmsConfig.loadMmsSettings
03-15 20:34:55.213  3860  4045 I Babel_SMS: MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
03-15 20:34:55.213  3860  4045 I Babel_SMS: MmsConfig.loadFromDatabase
03-15 20:34:55.213  3943  3943 D AndroidRuntime: CheckJNI is OFF
03-15 20:34:55.213  3943  3943 D AndroidRuntime: readGMSProperty: start
03-15 20:34:55.213  3943  3943 D AndroidRuntime: readGMSProperty: already setted!!
03-15 20:34:55.213  3943  3943 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-15 20:34:55.213  3943  3943 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-15 20:34:55.213  3943  3943 D AndroidRuntime: readGMSProperty: end
03-15 20:34:55.213  3943  3943 D AndroidRuntime: addProductProperty: start
03-15 20:34:55.223  1017  1372 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:55.223  1017  1372 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:55.223  1017  1372 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:55.223  1017  1372 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:55.233  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
03-15 20:34:55.233  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:34:55.233  3708  3761 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 20:34:55.233  3708  3761 I AMMetaDataParserService: Resource data:2131034113
03-15 20:34:55.233  3708  3761 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-15 20:34:55.233  3708  3761 I AMMetaDataParserService: getResourceTypeNamexml
03-15 20:34:55.233  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 20:34:55.233  3708  3761 I GFX raster: took 0.819166ms for 96*96 texture 0
03-15 20:34:55.233  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fa4bc8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8fc02b0 counterpartCT=4 counterpartW=96 counterparth=96
03-15 20:34:55.233  4049  4049 E Zygote  : MountEmulatedStorage()
03-15 20:34:55.233  4049  4049 I libpersona: KNOX_SDCARD checking this for 10146
03-15 20:34:55.233  4049  4049 E Zygote  : v2
03-15 20:34:55.233  4049  4049 I libpersona: KNOX_SDCARD not a persona
03-15 20:34:55.233  4049  4049 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-15 20:34:55.233  1017  1372 I ActivityManager: Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4049 uid=10146 gids={50146, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
03-15 20:34:55.243  4049  4049 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-15 20:34:55.243  4049  4049 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 20:34:55.253  3708  3761 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
03-15 20:34:55.263  1017  1372 I ActivityManager: Killing 3274:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31
03-15 20:34:55.273  1775  3818 I GCoreUlr: Unbound from all location providers
03-15 20:34:55.273  4049  4049 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 20:34:55.273  4049  4049 D ActivityThread: Added TimaKeyStore provider
03-15 20:34:55.273  1017  1531 I ActivityManager: Killing 3324:com.sec.factory.camera/1000 (adj 15): empty #31
03-15 20:34:55.283  3107  3189 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
03-15 20:34:55.293  1017  1042 W libprocessgroup: failed to open /acct/uid_10003/pid_3251/cgroup.procs: No such file or directory
03-15 20:34:55.303  3860  4045 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc 
03-15 20:34:55.303  3860  4045 I Babel_SMS: MmsConfig.loadFromResources
03-15 20:34:55.303  3860  4045 E Babel_SMS: canonicalizeMccMnc: invalid mccmnc nullnull
03-15 20:34:55.303  3860  4045 I Babel_SMS: MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
03-15 20:34:55.323  4049  4049 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-15 20:34:55.383  1017  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3324/cgroup.procs: No such file or directory
03-15 20:34:55.383  1017  1042 W libprocessgroup: failed to open /acct/uid_10060/pid_3274/cgroup.procs: No such file or directory
03-15 20:34:55.393  1695  1695 E SQLiteLog: (10) POSIX Error : 11 SQLite Error : 3850
03-15 20:34:55.413  1017  1622 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
03-15 20:34:55.413  1017  1622 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
03-15 20:34:55.413  1017  1555 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
03-15 20:34:55.413  1017  3015 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
03-15 20:34:55.423  1017  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:55.423  1017  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:55.423  1017  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:55.423  1017  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:55.443  4076  4076 E Zygote  : MountEmulatedStorage()
03-15 20:34:55.443  4076  4076 E Zygote  : v2
03-15 20:34:55.443  4076  4076 I libpersona: KNOX_SDCARD checking this for 10033
03-15 20:34:55.443  4076  4076 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-15 20:34:55.443  4076  4076 I libpersona: KNOX_SDCARD not a persona
03-15 20:34:55.443  4076  4076 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-15 20:34:55.443  4076  4076 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
03-15 20:34:55.453  1017  1079 I ActivityManager: Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=4076 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-15 20:34:55.453  1017  1079 I ActivityManager: Killing 3346:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
03-15 20:34:55.453  1017  1079 W ActivityManager: getTasks: caller 10145 does not hold GET_TASKS; limiting output
03-15 20:34:55.463  3970  4025 I Process : Sending signal. PID: 3970 SIG: 9
03-15 20:34:55.473  4076  4076 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 20:34:55.473  4076  4076 D ActivityThread: Added TimaKeyStore provider
03-15 20:34:55.473  1017  3822 D RCPManagerService: exchangeData() failure , invalid userId
03-15 20:34:55.483  1017  3015 D ActivityManager: retrieveServiceLocked(): component = com.android.exchange/com.android.exchange.service.ExchangeBroadcastProcessorService; callingUser = 0; userId(target) = 0
03-15 20:34:55.483  1017  3015 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:34:55.483  1017  3015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:34:55.483  1017  3015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
03-15 20:34:55.493  1017  1372 I art     : Explicit concurrent mark sweep GC freed 23129(1318KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 27MB/40MB, paused 3.059ms total 156.252ms
03-15 20:34:55.503  1017  1531 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:55.503  1017  1531 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:55.503  1017  1531 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:55.503  1017  1531 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:55.513  1017  1044 D SecurityLogAgent:SEDenialService: Got CLOSE_WRITE Event sk.log
03-15 20:34:55.513  1017  1044 D SecurityLogAgent:SEDenialService: Got CLOSE_WRITE Event sk.log
03-15 20:34:55.523  4092  4092 E Zygote  : MountEmulatedStorage()
03-15 20:34:55.523  4092  4092 E Zygote  : v2
03-15 20:34:55.523  4092  4092 I libpersona: KNOX_SDCARD checking this for 1000
03-15 20:34:55.523  4092  4092 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-15 20:34:55.523  4092  4092 I libpersona: KNOX_SDCARD not a persona
03-15 20:34:55.523  1017  1044 D SecurityLogAgent:SEDenialService: Got CLOSE_WRITE Event sk.log
03-15 20:34:55.533  4092  4092 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-15 20:34:55.533  4092  4092 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 20:34:55.543  1017  1531 I ActivityManager: Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4092 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-15 20:34:55.553  1017  3015 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
03-15 20:34:55.553  1017  3015 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:34:55.553  1017  3015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:34:55.553  1017  3015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
03-15 20:34:55.563   254   254 E lowmemorykiller: Error writing /proc/3970/oom_score_adj; errno=22
03-15 20:34:55.563  1017  3822 I ActivityManager: Killing 3362:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
03-15 20:34:55.573   315   315 I art     : Explicit concurrent mark sweep GC freed 8732(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 777us total 31.653ms
03-15 20:34:55.573  4092  4092 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 20:34:55.573  4092  4092 D ActivityThread: Added TimaKeyStore provider
03-15 20:34:55.583   254   254 E lowmemorykiller: Error writing /proc/3970/oom_score_adj; errno=22
03-15 20:34:55.593  4049  4095 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
03-15 20:34:55.603   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 595us total 28.758ms
03-15 20:34:55.603  3860  3877 W art     : Suspending all threads took: 15.165ms
03-15 20:34:55.613  1017  1042 W libprocessgroup: failed to open /acct/uid_10100/pid_3346/cgroup.procs: No such file or directory
03-15 20:34:55.623   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 622us total 18.362ms
03-15 20:34:55.643  1775  1775 I GCoreUlr: DispatchingService.onDestroy()
03-15 20:34:55.643  1017  3014 I ActivityManager: Process com.android.email (pid 3970)(adj 9) has died(122,1066)
03-15 20:34:55.643  4049  4049 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@e76ab2b
03-15 20:34:55.643  4049  4049 I ActivityThread: Removing dead content provider:android.content.ContentProviderProxy@e76ab2b
03-15 20:34:55.653  1017  1042 W libprocessgroup: failed to open /acct/uid_10062/pid_3362/cgroup.procs: No such file or directory
03-15 20:34:55.653  1775  1775 I GCoreUlr: Unbound from all location providers
03-15 20:34:55.663  1017  1531 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:55.663  1017  1531 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:55.663  1017  1531 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:55.663  1017  1531 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:55.673  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 20:34:55.673  3708  3761 I GFX raster: took 0.855729ms for 96*96 texture 0
03-15 20:34:55.673  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fa4bc8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8fc2110 counterpartCT=4 counterpartW=96 counterparth=96
03-15 20:34:55.673  4109  4109 E Zygote  : MountEmulatedStorage()
03-15 20:34:55.673  4109  4109 E Zygote  : v2
03-15 20:34:55.673  4109  4109 I libpersona: KNOX_SDCARD checking this for 1000
03-15 20:34:55.673  4109  4109 I libpersona: KNOX_SDCARD not a persona
03-15 20:34:55.673  4109  4109 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-15 20:34:55.683  4109  4109 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-15 20:34:55.683  4109  4109 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 20:34:55.683  1017  1531 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4109 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-15 20:34:55.693  3708  3761 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
03-15 20:34:55.693  1017  3014 W ActivityManager: getTasks: caller 10146 does not hold GET_TASKS; limiting output
03-15 20:34:55.703  4049  4095 I Process : Sending signal. PID: 4049 SIG: 9
03-15 20:34:55.713   283   784 W QCamera2Factory: getCameraInfo: E, camera_id = 0
03-15 20:34:55.713   283   784 W QCamera2Factory: getCameraInfo: X
03-15 20:34:55.713   283   283 W QCamera2Factory: getCameraInfo: E, camera_id = 1
03-15 20:34:55.713   283   283 W QCamera2Factory: getCameraInfo: X
03-15 20:34:55.723  3943  3943 E AffinityControl: AffinityControl: registerfunction enter
03-15 20:34:55.723  1017  1531 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
03-15 20:34:55.723  1017  1531 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:34:55.723  1017  1531 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:34:55.723  1017  1531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
03-15 20:34:55.723  4109  4109 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 20:34:55.723  4109  4109 D ActivityThread: Added TimaKeyStore provider
03-15 20:34:55.753  3943  3943 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-15 20:34:55.763  4109  4109 D SecurityLogAgent: KnoxConfiguration : Current State = 1
03-15 20:34:55.763  4109  4109 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-15 20:34:55.763  4109  4109 D SecurityLogAgent: StateMachine : Current State = 1
03-15 20:34:55.763  4109  4109 D SecurityLogAgent: BootReceiver : completed task. Failed to return wakelock . 
03-15 20:34:55.763  1017  3014 I ActivityManager: Process com.android.exchange (pid 4049)(adj 9) has died(119,1068)
03-15 20:34:55.763  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:55.763  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:55.763  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:55.763  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:55.773  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 20:34:55.773  3708  3761 I GFX raster: took 0.612552ms for 96*96 texture 0
03-15 20:34:55.773  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fc19e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fa55e8 counterpartCT=4 counterpartW=96 counterparth=96
03-15 20:34:55.773  3708  3761 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
03-15 20:34:55.783  4128  4128 E Zygote  : MountEmulatedStorage()
03-15 20:34:55.783  4128  4128 E Zygote  : v2
03-15 20:34:55.783  4128  4128 I libpersona: KNOX_SDCARD checking this for 10152
03-15 20:34:55.783  4128  4128 I libpersona: KNOX_SDCARD not a persona
03-15 20:34:55.783  1017  1030 I ActivityManager: Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=4128 uid=10152 gids={50152, 9997, 1023} abi=armeabi-v7a
03-15 20:34:55.793  4128  4128 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-15 20:34:55.793  4128  4128 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-15 20:34:55.793  1017  1555 E PersonaManagerService: inState():  stateMachine is null !!
03-15 20:34:55.793  1017  1555 I PersonaManagerService: PersonaId don't exist
03-15 20:34:55.793  1017  1555 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-15 20:34:55.793  4128  4128 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 20:34:55.793  1017  1555 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-15 20:34:55.803  4076  4076 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-15 20:34:55.803  4076  4076 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 20:34:55.803  4076  4076 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
03-15 20:34:55.813  1187  1187 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-15 20:34:55.813  1187  1187 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-15 20:34:55.813  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 20:34:55.813  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 20:34:55.813  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 20:34:55.813  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 20:34:55.823   291   291 E SMD     : DCD OFF
03-15 20:34:55.823  1017  1555 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-15 20:34:55.823  1017  1555 W ActivityManager: mDVFSHelper.acquire()
03-15 20:34:55.833  1017  1555 D FocusedStackFrame: Set to : 0
03-15 20:34:55.833  1017  1555 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-15 20:34:55.833  1017  1555 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-15 20:34:55.833  1017  1555 D InputDispatcher: Focused application set to: xxxx
03-15 20:34:55.843  1017  1555 D InputDispatcher: Focus left window: 1528
03-15 20:34:55.843  1528  1528 D Launcher.HomeView: onPause
03-15 20:34:55.843  3943  3943 D AndroidRuntime: Shutting down VM
03-15 20:34:55.843  1528  1528 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-15 20:34:55.843  4128  4128 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 20:34:55.843  4128  4128 D ActivityThread: Added TimaKeyStore provider
03-15 20:34:55.843  1017  1048 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-15 20:34:55.853  1017  1048 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-15 20:34:55.853  1017  3015 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:55.853  1017  3015 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:55.853  1017  3015 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:55.853  1017  3015 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:55.853  4076  4076 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-15 20:34:55.853  4076  4076 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 20:34:55.853  4076  4076 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 20:34:55.863  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 20:34:55.863  3708  3761 I GFX raster: took 0.662031ms for 96*96 texture 0
03-15 20:34:55.863  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fc1b50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fc38e8 counterpartCT=4 counterpartW=96 counterparth=96
03-15 20:34:55.873  4076  4076 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-15 20:34:55.873  4076  4076 W ResourcesManager: Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
03-15 20:34:55.873  4076  4076 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
03-15 20:34:55.873  4144  4144 E Zygote  : MountEmulatedStorage()
03-15 20:34:55.873  4144  4144 I libpersona: KNOX_SDCARD checking this for 10174
03-15 20:34:55.873  4144  4144 E Zygote  : v2
03-15 20:34:55.873  4144  4144 I libpersona: KNOX_SDCARD not a persona
03-15 20:34:55.873  4144  4144 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-15 20:34:55.873  1017  3015 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4144 uid=10174 gids={50174, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-15 20:34:55.883  4144  4144 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-15 20:34:55.883  4144  4144 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-15 20:34:55.883  3708  3761 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
03-15 20:34:55.883  3860  3860 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
03-15 20:34:55.883  1017  1372 I ActivityManager: Killing 3380:com.samsung.helphub/1000 (adj 15): empty #31
03-15 20:34:55.893  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 20:34:55.893  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-15 20:34:55.893  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
03-15 20:34:55.893  1017  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-15 20:34:55.893  1017  1048 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-15 20:34:55.903   257   257 I SurfaceFlinger: id=10 createSurf (1x1),1 flag=404, uhalitest
03-15 20:34:55.903  1528  1528 V ActivityThread: updateVisibility : ActivityRecord{120defcf token=android.os.BinderProxy@6e1d76a {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
03-15 20:34:55.903  3708  3761 I GFX raster: took 0.948125ms for 96*96 texture 0
03-15 20:34:55.903  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fc46b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fc49c8 counterpartCT=4 counterpartW=96 counterparth=96
03-15 20:34:55.913  4144  4144 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 20:34:55.913  4144  4144 D ActivityThread: Added TimaKeyStore provider
03-15 20:34:55.923  1017  3754 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-15 20:34:55.923  1017  3754 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-15 20:34:55.923  1017  3754 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-15 20:34:55.923  1528  1528 D Launcher.HomeView: onStop
03-15 20:34:55.923  1528  1528 V ActivityThread: updateVisibility : ActivityRecord{120defcf token=android.os.BinderProxy@6e1d76a {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-15 20:34:55.923  3708  3761 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
03-15 20:34:55.933  3860  3860 I Babel_Crash: startup - clean
03-15 20:34:55.933  1017  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-15 20:34:55.953  1017  1048 D PersonaManager: isKioskContainerExistOnDevice
03-15 20:34:55.953  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
03-15 20:34:55.963  1017  1017 D SensorService: [SO] activate (ident=0xb9337388, enabled=0)
03-15 20:34:55.963  1017  1017 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
03-15 20:34:55.973  4128  4128 E SQLiteLog: (284) automatic index on shooting_modes(title_id)
03-15 20:34:55.983  1017  1017 D SensorManager: unregisterListener ::   
03-15 20:34:55.983  1017  1017 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
03-15 20:34:55.983  1017  1017 D SensorService: [SO] changed settle time [1]
03-15 20:34:55.983  1017  1017 D SensorService: [SO] setDelay [66000000]
03-15 20:34:55.983  1017  1017 D SensorService: [SO] activate (ident=0xb9337388, enabled=1)
03-15 20:34:55.983  1017  1017 D SensorService: [SO] AR_init
03-15 20:34:55.983  1017  1017 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
03-15 20:34:55.993  1017  1017 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
03-15 20:34:55.993  3860  4160 I Babel   : deleted: false for 0
03-15 20:34:55.993  1017  1129 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.ShootingModesService; callingUser = 0; userId(target) = 0
03-15 20:34:56.003  1017  1129 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:34:56.003  1017  1129 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:34:56.003  1017  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.provider.shootingmodeprovider, destAppInfo.processName = com.samsung.android.provider.shootingmodeprovider
03-15 20:34:56.003  1528  1528 D Launcher: onTrimMemory. Level: 20
03-15 20:34:56.003  1017  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:56.003  1017  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:56.003  1017  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:56.013  1017  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:56.023  1017  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3380/cgroup.procs: No such file or directory
03-15 20:34:56.023  4163  4163 E Zygote  : MountEmulatedStorage()
03-15 20:34:56.023  4163  4163 E Zygote  : v2
03-15 20:34:56.023  4163  4163 I libpersona: KNOX_SDCARD checking this for 1000
03-15 20:34:56.023  4163  4163 I libpersona: KNOX_SDCARD not a persona
03-15 20:34:56.023  4163  4163 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-15 20:34:56.033  1017  1555 I ActivityManager: Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=4163 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-15 20:34:56.033  1017  3015 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-15 20:34:56.033  4163  4163 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-15 20:34:56.033  1017  3015 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:34:56.033  1017  3015 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:34:56.033  1017  3015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.gms
03-15 20:34:56.033  4163  4163 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 20:34:56.033  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 20:34:56.043  3708  3761 I GFX raster: took 0.777708ms for 96*96 texture 0
03-15 20:34:56.043  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fc0810 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fc5260 counterpartCT=4 counterpartW=96 counterparth=96
03-15 20:34:56.043  3436  3447 D PCWCLIENTTRACE_AccountAppFacade2_0: unregister AuthInfo UpdateReceiver v2.0
03-15 20:34:56.053  1017  1040 D SensorService: [SO] Reset Rotation Old [100], Init [1]
03-15 20:34:56.053  3943  3943 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
03-15 20:34:56.053  3708  3761 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
03-15 20:34:56.063  4163  4163 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 20:34:56.063  4163  4163 D ActivityThread: Added TimaKeyStore provider
,03-15 20:34:56.073  1017  1043 I ActivityManager: Waited long enough for: ServiceRecord{13140150 u0 com.samsung.hs20settings/.WifiHs20UtilityService}
,03-15 20:34:56.093  1017  1372 I ActivityManager: Killing 3402:com.fmm.dm/1000 (adj 15): empty #31
,03-15 20:34:56.093  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:56.093  3708  3761 I GFX raster: took 0.693750ms for 96*96 texture 0
03-15 20:34:56.093  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fc16f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fc20e0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:56.113  3708  3761 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-15 20:34:56.123  1017  1040 D SensorService: [SO] 0.172 0.402 10.266,
03-15 20:34:56.123  1017  1040 D SensorService: [SO] [100 -> 255]
,03-15 20:34:56.123  1017  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:34:56.123  1017  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:56.123  1017  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:56.123  1017  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,03-15 20:34:56.123  4144  4144 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311700),
,03-15 20:34:56.143  4179  4179 E Zygote  : MountEmulatedStorage()
,03-15 20:34:56.143  4179  4179 E Zygote  : v2
03-15 20:34:56.143  4179  4179 I libpersona: KNOX_SDCARD checking this for 1101
03-15 20:34:56.143  4179  4179 I libpersona: KNOX_SDCARD not a persona
,03-15 20:34:56.143  4179  4179 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-15 20:34:56.143  4179  4179 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-15 20:34:56.143  4179  4179 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-15 20:34:56.143  1017  1129 I ActivityManager: Start proc org.simalliance.openmobileapi.service for broadcast org.simalliance.openmobileapi.service/.SmartcardServiceBootCompletedBroadcastReceiver: pid=4179 uid=1101 gids={41101, 9997} abi=armeabi-v7a
03-15 20:34:56.143  1017  1129 I ActivityManager: Killing 3418:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,03-15 20:34:56.153  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
03-15 20:34:56.153  3708  3761 I GFX raster: took 0.541875ms for 96*96 texture 0
,03-15 20:34:56.153  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fc1e20 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fbfb10 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:56.153  3708  3761 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-15 20:34:56.163  4144  4144 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 3924-3926)
03-15 20:34:56.163  4144  4144 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-15 20:34:56.173  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
,03-15 20:34:56.173  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
,03-15 20:34:56.173  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
03-15 20:34:56.173  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
,03-15 20:34:56.173  4179  4179 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 20:34:56.173  4179  4179 D ActivityThread: Added TimaKeyStore provider
,03-15 20:34:56.173  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
03-15 20:34:56.173  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
,03-15 20:34:56.173  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
03-15 20:34:56.173  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
,03-15 20:34:56.173  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
,03-15 20:34:56.173  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
,03-15 20:34:56.173  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
03-15 20:34:56.183  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
,03-15 20:34:56.183  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
,03-15 20:34:56.193  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
,03-15 20:34:56.193  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
,03-15 20:34:56.193  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
03-15 20:34:56.193  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
,03-15 20:34:56.193  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
03-15 20:34:56.193  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
03-15 20:34:56.193  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 20:34:56.193  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
,03-15 20:34:56.193  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.ContactShortcut
,03-15 20:34:56.193  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activityalias.DialShortcut
03-15 20:34:56.193  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activityalias.MessageShortcut
,03-15 20:34:56.193  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
,03-15 20:34:56.193  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
03-15 20:34:56.193  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
,03-15 20:34:56.193  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 20:34:56.193  3708  3761 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
,03-15 20:34:56.193  3708  3761 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 20:34:56.193  3708  3761 I AMMetaDataParserService: Resource data:2131034112
,03-15 20:34:56.203  3708  3761 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_detail
03-15 20:34:56.203  3708  3761 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 20:34:56.203  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:56.203  3708  3761 I GFX raster: took 1.197136ms for 96*96 texture 0
03-15 20:34:56.203  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fbe9b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fbeb10 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:56.203  4144  4144 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1a9dc146}
,03-15 20:34:56.203  4144  4144 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-15 20:34:56.203  4144  4144 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-15 20:34:56.223  3708  3761 I AMMetaDataParserService: Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,03-15 20:34:56.223  4179  4179 W ResourcesManager: Asset path '/system/framework/org.simalliance.openmobileapi.jar' does not exist or contains no resources.
,03-15 20:34:56.233  4179  4179 V SmartcardService: main Received broadcast
03-15 20:34:56.233  4179  4179 V SmartcardService: Starting smartcard service after boot completed
03-15 20:34:56.243  4144  4144 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-15 20:34:56.243  4144  4144 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-15 20:34:56.243  4144  4144 E SysUtils: ApplicationContext is null in ApplicationStatus
03-15 20:34:56.243  1017  3754 D ActivityManager: retrieveServiceLocked(): component = org.simalliance.openmobileapi.service/org.simalliance.openmobileapi.service.SmartcardService; callingUser = 0; userId(target) = 0
03-15 20:34:56.243  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 20:34:56.243  3708  3761 I GFX raster: took 0.659947ms for 96*96 texture 0
03-15 20:34:56.243  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fbe9b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fa3d58 counterpartCT=4 counterpartW=96 counterparth=96
03-15 20:34:56.243  1017  3754 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:34:56.243  1017  3754 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:34:56.243  1017  3754 W ActivityManager: NORMAL SET : srcAppInfo.processName = org.simalliance.openmobileapi.service, destAppInfo.processName = org.simalliance.openmobileapi.service
,03-15 20:34:56.253  1017  3015 I ActivityManager: Killing 3449:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
,03-15 20:34:56.253  1017  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3402/cgroup.procs: No such file or directory
,03-15 20:34:56.263  1017  1341 D ActivityManager: retrieveServiceLocked(): component = com.android.stk/com.android.stk.StkAppService; callingUser = 0; userId(target) = 0
,03-15 20:34:56.263  1017  1341 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:34:56.263  1017  1341 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:34:56.263  1017  1341 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,03-15 20:34:56.263  1017  3823 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:56.263  1017  3823 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:34:56.273  1017  3823 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-15 20:34:56.273  1017  3823 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:34:56.273  4144  4144 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-15 20:34:56.273  3708  3761 I AMMetaDataParserService: Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,03-15 20:34:56.283  3107  3189 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,03-15 20:34:56.283  4144  4144 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-15 20:34:56.283  4144  4144 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-15 20:34:56.283  4144  4144 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-15 20:34:56.283  4144  4144 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-15 20:34:56.283  4144  4144 I Adreno-EGL: Build Date: 04/06/15 Mon
03-15 20:34:56.283  4144  4144 I Adreno-EGL: Local Branch: 
03-15 20:34:56.283  4144  4144 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-15 20:34:56.283  4144  4144 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-15 20:34:56.283  4144  4144 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-15 20:34:56.283  4207  4207 E Zygote  : MountEmulatedStorage(),
03-15 20:34:56.283  4207  4207 E Zygote  : v2
03-15 20:34:56.283  4207  4207 I libpersona: KNOX_SDCARD checking this for 1000
03-15 20:34:56.283  4207  4207 I libpersona: KNOX_SDCARD not a persona
,03-15 20:34:56.283  4207  4207 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-15 20:34:56.293  4207  4207 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-15 20:34:56.293  1017  3823 I ActivityManager: Start proc com.sec.android.app.sysscope for broadcast com.sec.android.app.sysscope/.receiver.BootCompleteReceiver: pid=4207 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-15 20:34:56.293  4207  4207 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 20:34:56.303  1017  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3418/cgroup.procs: No such file or directory
,03-15 20:34:56.323  4207  4207 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 20:34:56.323  4207  4207 D ActivityThread: Added TimaKeyStore provider
,03-15 20:34:56.333  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:56.333  3708  3761 I GFX raster: took 0.650468ms for 96*96 texture 0
03-15 20:34:56.333  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fa4580 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8d3e250 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:56.333  1017  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3449/cgroup.procs: No such file or directory
,03-15 20:34:56.343  3708  3761 I AMMetaDataParserService: Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,03-15 20:34:56.353  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:56.353  3708  3761 I GFX raster: took 0.790937ms for 96*96 texture 0
03-15 20:34:56.353  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fa3d58 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fa4ca0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:56.353  3708  3761 I AMMetaDataParserService: Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,03-15 20:34:56.363  3860  3860 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-15 20:34:56.373  3860  3860 W AudioCapabilities: Unsupported mime audio/evrc
,03-15 20:34:56.383  3860  3860 W AudioCapabilities: Unsupported mime audio/qcelp
,03-15 20:34:56.383  4207  4207 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.sysscope.receiver.BootCompleteReceiver.onReceive:-1 android.app.ActivityThread.handleReceiver:3125 
,03-15 20:34:56.383  1017  1129 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.sysscope/com.sec.android.app.sysscope.service.SysScopeService; callingUser = 0; userId(target) = 0
,03-15 20:34:56.383  1017  1129 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:34:56.383  1017  1129 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-15 20:34:56.383  1017  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.sysscope, destAppInfo.processName = com.sec.android.app.sysscope,
,03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.em,ergency.InteractionEmergencyMessageActivity
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
,03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 20:34:56.393  3708  3761 I AMMetaDataParserService: Resource data:2131034113
,03-15 20:34:56.403  1017  1372 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:34:56.403   257   446 I SurfaceFlinger: id=8 Removed Mauncher (5/8)
03-15 20:34:56.403  1017  1372 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:56.403  3860  3860 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,03-15 20:34:56.403  3860  3860 W AudioCapabilities: Unsupported mime audio/mpeg-L2
03-15 20:34:56.403   257   448 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
,03-15 20:34:56.413  1017  1372 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:56.413  1017  1372 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:34:56.413  3708  3761 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-15 20:34:56.413  3708  3761 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 20:34:56.413  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:56.413  3708  3761 I GFX raster: took 0.827656ms for 96*96 texture 0
03-15 20:34:56.413  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fa56b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8fa4bc8 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:56.423  3708  3761 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-15 20:34:56.433  4239  4239 E Zygote  : MountEmulatedStorage()
03-15 20:34:56.433  4239  4239 E Zygote  : v2
03-15 20:34:56.433  4239  4239 I libpersona: KNOX_SDCARD checking this for 10157
03-15 20:34:56.433  4239  4239 I libpersona: KNOX_SDCARD not a persona
,03-15 20:34:56.433  4239  4239 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-15 20:34:56.443  4239  4239 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-15 20:34:56.443  4239  4239 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 20:34:56.443  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:56.443  3708  3761 I GFX raster: took 0.818958ms for 96*96 texture 0
,03-15 20:34:56.443  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fa56b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8bf3558 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:56.453  1017  1372 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=4239 uid=10157 gids={50157, 9997} abi=armeabi-v7a
,03-15 20:34:56.453  3708  3761 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-15 20:34:56.453  3860  3860 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,03-15 20:34:56.463  3860  3860 W AudioCapabilities: Unsupported mime audio/x-ima
,03-15 20:34:56.473  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:56.473  4029  4064 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-15 20:34:56.473  3860  3860 W AudioCapabilities: Unsupported mime audio/qcelp
03-15 20:34:56.473  4029  4064 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 20:34:56.473  4029  4064 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-15 20:34:56.473  3708  3761 I GFX raster: took 0.646615ms for 96*96 texture 0
,03-15 20:34:56.473  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fc1e20 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fc0810 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:56.483  3708  3761 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-15 20:34:56.493  3860  3860 W AudioCapabilities: Unsupported mime audio/evrc
,03-15 20:34:56.503  4239  4239 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 20:34:56.513  4239  4239 D ActivityThread: Added TimaKeyStore provider
,03-15 20:34:56.523  3860  3860 W VideoCapabilities: Unsupported mime video/wvc1
,03-15 20:34:56.523  3860  3860 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-15 20:34:56.523  3937  4001 I System.out: INFO:Resource not found:/Common.properties Using default values
,03-15 20:34:56.533  4239  4239 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-15 20:34:56.533  4029  4064 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-15 20:34:56.533  4076  4076 I Process : Sending signal. PID: 4076 SIG: 9
,03-15 20:34:56.533  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:56.533  3708  3761 I GFX raster: took 0.603698ms for 96*96 texture 0
03-15 20:34:56.533  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fbe9b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fa4ca0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:56.543  3860  3860 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,03-15 20:34:56.543  3860  3860 W VideoCapabilities: Unsupported mime video/wvc1
,03-15 20:34:56.553  3860  3860 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-15 20:34:56.563  3860  3860 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,03-15 20:34:56.563  3708  3761 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
03-15 20:34:56.563  3860  3860 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,03-15 20:34:56.563  3860  3860 W VideoCapabilities: Unsupported mime video/mp43
,03-15 20:34:56.563  1017  3754 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:56.573  1017  3754 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:56.573  1017  3754 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:56.573  3901  3901 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
03-15 20:34:56.573  1017  3754 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:34:56.573  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:56.573  3708  3761 I GFX raster: took 0.821041ms for 96*96 texture 0
03-15 20:34:56.573  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fbe4c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8d3e250 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:56.583  3708  3761 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532,
,03-15 20:34:56.583  3860  3860 W VideoCapabilities: Unsupported mime video/sorenson,
,03-15 20:34:56.583  4260  4260 E Zygote  : MountEmulatedStorage(),
03-15 20:34:56.583  4260  4260 E Zygote  : v2
03-15 20:34:56.583  4260  4260 I libpersona: KNOX_SDCARD checking this for 10159
03-15 20:34:56.583  4260  4260 I libpersona: KNOX_SDCARD not a persona
03-15 20:34:56.593  4260  4260 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-15 20:34:56.593  4144  4144 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-15 20:34:56.593  4260  4260 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-15 20:34:56.593  4260  4260 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,03-15 20:34:56.593  1017  3754 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=4260 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
03-15 20:34:56.593  1017  3754 I ActivityManager: Killing 3233:com.google.android.gms:car/u0a12 (adj 15): empty #31
,03-15 20:34:56.603  1017  3754 I ActivityManager: Process com.sec.android.app.sns3 (pid 4076)(adj 0) has died(117,1075)
,03-15 20:34:56.603  1017  1079 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,03-15 20:34:56.613  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 20:34:56.613  3860  3860 W VideoCapabilities: Unsupported mime video/mp4v-esdp
03-15 20:34:56.613  3708  3761 I GFX raster: took 0.638958ms for 96*96 texture 0
03-15 20:34:56.613  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fa3d58 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fa4bc8 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:56.613  1017  1079 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:34:56.613  1017  1079 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:34:56.613  1017  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,03-15 20:34:56.613  4144  4144 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-15 20:34:56.613  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:56.613  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:56.613  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:56.613  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:34:56.623  3708  3761 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-15 20:34:56.623  4144  4144 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-15 20:34:56.623  4144  4144 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-15 20:34:56.633  4272  4272 E Zygote  : MountEmulatedStorage(),
03-15 20:34:56.633  4272  4272 E Zygote  : v2
03-15 20:34:56.633  4272  4272 I libpersona: KNOX_SDCARD checking this for 10034
,03-15 20:34:56.633  4272  4272 I libpersona: KNOX_SDCARD not a persona
,03-15 20:34:56.633  4272  4272 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-15 20:34:56.633  4272  4272 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-15 20:34:56.633  1017  1043 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4272 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
,03-15 20:34:56.633  4272  4272 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 20:34:56.633  1017  1531 I ActivityManager: Killing 3161:com.android.vending/u0a28 (adj 15): empty #31
,03-15 20:34:56.643  4144  4144 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-15 20:34:56.653  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:56.653  3708  3761 I GFX raster: took 0.708855ms for 96*96 texture 0
03-15 20:34:56.653  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fc16f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fa3c60 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:56.653  4144  4144 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-15 20:34:56.653  4144  4144 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-15 20:34:56.663  3708  3761 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-15 20:34:56.663  4260  4260 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 20:34:56.663  4260  4260 D ActivityThread: Added TimaKeyStore provider
,03-15 20:34:56.683  1017  1372 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.car.InCallServiceImpl in 1000ms
,03-15 20:34:56.683  4272  4272 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 20:34:56.683  4272  4272 D ActivityThread: Added TimaKeyStore provider
,03-15 20:34:56.693  3860  3860 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-15 20:34:56.693  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:56.693  3708  3761 I GFX raster: took 0.519896ms for 96*96 texture 0
03-15 20:34:56.693  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fc0810 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8bf3558 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:56.703  3708  3761 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-15 20:34:56.723  4260  4260 I Intent to TravelDirActivity: inside TravelBroadcastReceiver
,03-15 20:34:56.733  1017  3015 I ActivityManager: Killing 3491:com.fmm.ds/1000 (adj 15): empty #31
,03-15 20:34:56.763  3860  3860 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-15 20:34:56.763  3860  3860 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-15 20:34:56.763  3860  3860 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-15 20:34:56.773  3860  3860 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-15 20:34:56.783  1017  2853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-15 20:34:56.813  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
03-15 20:34:56.813  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
03-15 20:34:56.813  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:34:56.813  3708  3761 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-15 20:34:56.813  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
03-15 20:34:56.813  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
03-15 20:34:56.813  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
03-15 20:34:56.813  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
03-15 20:34:56.813  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
03-15 20:34:56.813  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
03-15 20:34:56.813  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
03-15 20:34:56.813  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
03-15 20:34:56.813  3708  3761 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-15 20:34:56.813  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
03-15 20:34:56.813  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
03-15 20:34:56.813  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
03-15 20:34:56.813  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
03-15 20:34:56.813  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
03-15 20:34:56.813  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
03-15 20:34:56.813  1017  1042 W libprocessgroup: failed to open /acct/uid_10012/pid_3233/cgroup.procs: No such file or directory
03-15 20:34:56.813  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
03-15 20:34:56.813  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
03-15 20:34:56.813  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:34:56.813  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-15 20:34:56.813  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
03-15 20:34:56.813  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:34:56.813  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-15 20:34:56.813  3708  3761 I, AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
03-15 20:34:56.813  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,03-15 20:34:56.823  1187  1187 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-15 20:34:56.823  1187  1187 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-15 20:34:56.823  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 20:34:56.823  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 20:34:56.823  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 20:34:56.823  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 20:34:56.833  1017  1042 W libprocessgroup: failed to open /acct/uid_10028/pid_3161/cgroup.procs: No such file or directory
03-15 20:34:56.833  1017  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3491/cgroup.procs: No such file or directory
,03-15 20:34:56.843  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
,03-15 20:34:56.843  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
,03-15 20:34:56.853  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
,03-15 20:34:56.853  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.Welcome
03-15 20:34:56.853  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
03-15 20:34:56.853  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
03-15 20:34:56.853  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
03-15 20:34:56.853  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
03-15 20:34:56.853  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
03-15 20:34:56.853  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
03-15 20:34:56.853  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
03-15 20:34:56.853  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
03-15 20:34:56.853  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
03-15 20:34:56.853  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
03-15 20:34:56.853  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
03-15 20:34:56.853  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
03-15 20:34:56.853  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.DataConnection
03-15 20:34:56.853  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
03-15 20:34:56.853  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
03-15 20:34:56.853  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
03-15 20:34:56.853  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
03-15 20:34:56.853  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
03-15 20:34:56.853  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
03-15 20:34:56.853  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
03-15 20:34:56.853  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
03-15 20:34:56.853  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
03-15 20:34:56.853  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
03-15 20:34:56.853  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
03-15 20:34:56.853  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
03-15 20:34:56.853  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.Debug
03-15 20:34:56.853  3,708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageListXL
03-15 20:34:56.853  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:34:56.853  3708  3761 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 20:34:56.853  3708  3761 I AMMetaDataParserService: Resource data:2131165203
03-15 20:34:56.853  3860  3860 I vclib   : onServiceConnected
03-15 20:34:56.853  3860  3860 W Babel   : Attempted to change video mute state without an active call.
,03-15 20:34:56.863  3708  3761 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-15 20:34:56.863  3708  3761 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 20:34:56.863  3708  3761 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-15 20:34:56.863  3708  3761 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 20:34:56.863  3708  3761 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-15 20:34:56.863  1017  3754 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:56.863  1017  3754 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:56.863  1017  3754 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:56.863  1017  3754 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,03-15 20:34:56.873  1017  2821 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,03-15 20:34:56.873  4295  4295 E Zygote  : MountEmulatedStorage()
,03-15 20:34:56.873  4295  4295 I libpersona: KNOX_SDCARD checking this for 10035
03-15 20:34:56.873  4295  4295 E Zygote  : v2
,03-15 20:34:56.873  4295  4295 I libpersona: KNOX_SDCARD not a persona
,03-15 20:34:56.873  4295  4295 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-15 20:34:56.883  1017  3754 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4295 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
03-15 20:34:56.883  4295  4295 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-15 20:34:56.883  1017  3754 I ActivityManager: Killing 3464:com.wssnps/1000 (adj 15): empty #31
,03-15 20:34:56.883  3708  3761 I AMMetaDataParserService: getResourceName:com.android.email:xml/email_assistant_menu
03-15 20:34:56.883  1017  1531 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 20:34:56.883  3708  3761 I AMMetaDataParserService: getResourceTypeNamexml
03-15 20:34:56.883  4295  4295 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-15 20:34:56.883  1017  1531 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:34:56.883  1017  1531 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:34:56.883  1017  1531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 20:34:56.893  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:56.903  4144  4306 D OpenGLRenderer: Render dirty regions requested: true
,03-15 20:34:56.903  3708  3761 I GFX construct_block_size_descriptor_2d second part: took 3.471250ms for 0*0 texture 0
,03-15 20:34:56.903  4295  4295 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 20:34:56.903  4295  4295 D ActivityThread: Added TimaKeyStore provider
,03-15 20:34:56.913  1017  1555 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,03-15 20:34:56.913  1017  1555 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-15 20:34:56.913  1017  1555 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-15 20:34:56.913  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-15 20:34:56.913  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
,03-15 20:34:56.913  4144  4232 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,03-15 20:34:56.913  4144  4144 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-15 20:34:56.913  4144  4144 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-15 20:34:56.923  1017  1746 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:56.923  1017  1746 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:56.923  1017  1746 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:56.923  1017  1746 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:34:56.923  3708  3761 I GFX generate_partition_tables: took 11.198332ms for 0*0 texture 0
,03-15 20:34:56.923  3708  3761 I GFX raster: took 15.689789ms for 96*96 texture 0,
03-15 20:34:56.923  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8f9cf40 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8fa30b0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:56.933  3708  3761 I AMMetaDataParserService: Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576,
,03-15 20:34:56.933  4312  4312 E Zygote  : MountEmulatedStorage()
,03-15 20:34:56.933  4312  4312 E Zygote  : v2
03-15 20:34:56.933  4312  4312 I libpersona: KNOX_SDCARD checking this for 1000
03-15 20:34:56.933  4312  4312 I libpersona: KNOX_SDCARD not a persona
,03-15 20:34:56.933  4312  4312 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-15 20:34:56.943  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
03-15 20:34:56.943  1017  1746 I ActivityManager: Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4312 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-15 20:34:56.943  4312  4312 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-15 20:34:56.943  3708  3761 I GFX raster: took 0.888073ms for 96*96 texture 0
03-15 20:34:56.943  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8f9a040 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8f9a178 counterpartCT=4 counterpartW=96 counterparth=96,
03-15 20:34:56.943  4312  4312 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 20:34:56.953  3708  3761 I AMMetaDataParserService: Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,03-15 20:34:56.953  1017  1746 I ActivityManager: Killing 3517:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,03-15 20:34:56.953   257   257 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, NainActivit
,03-15 20:34:56.973   315   315 I art     : Explicit concurrent mark sweep GC freed 8733(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 649us total 34.910ms
,03-15 20:34:56.973  1017  1079 D InputDispatcher: Focus entered window: 4144
,03-15 20:34:56.983  4312  4312 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 20:34:56.983  4312  4312 D ActivityThread: Added TimaKeyStore provider
,03-15 20:34:56.983  1017  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3464/cgroup.procs: No such file or directory
,03-15 20:34:56.993   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.313ms total 19.797ms
03-15 20:34:56.993  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:57.003  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-15 20:34:57.003  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
03-15 20:34:57.003  4144  4144 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-15 20:34:57.003  4144  4306 I OpenGLRenderer: Initialized EGL, version 1.4
,03-15 20:34:57.013  3708  3761 I GFX raster: took 0.915157ms for 96*96 texture 0
03-15 20:34:57.013  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8f9a040 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8f96808 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:57.013  4144  4306 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-15 20:34:57.013  4144  4306 D OpenGLRenderer: Enabling debug mode 0
,03-15 20:34:57.013   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 1.158ms total 18.890ms
,03-15 20:34:57.023  3708  3761 I AMMetaDataParserService: Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,03-15 20:34:57.033  1017  2821 D SSRM:n  : SIOP:: AP = 410
,03-15 20:34:57.063  4312  4312 I DBG_POLICYDM: [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,03-15 20:34:57.073  4312  4312 I DBG_POLICYDM: [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,03-15 20:34:57.083  4312  4329 I DBG_POLICYDM: [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
03-15 20:34:57.083  4312  4312 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,03-15 20:34:57.083  4312  4329 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,03-15 20:34:57.083  1017  3823 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-15 20:34:57.093  1017  4335 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-15 20:34:57.093  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:57.093  3708  3761 I GFX raster: took 0.885729ms for 96*96 texture 0
03-15 20:34:57.093  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8f9a040 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9174778 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:57.093  1187  1187 D PanelView: There is/are notification(s) 
03-15 20:34:57.093  4312  4312 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,03-15 20:34:57.103  1017  1048 I ActivityManager: Displayed Component not be shown by security: +1s257ms
,03-15 20:34:57.103  1017  1048 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@7
,03-15 20:34:57.103  1017  1048 W ActivityManager: mDVFSHelper.release()
03-15 20:34:57.103  1017  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{135814a4 u0 com.test.thalitest/.MainActivity t236} time:44866
,03-15 20:34:57.103  1017  1043 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-15 20:34:57.113  4295  4334 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
03-15 20:34:57.113  4295  4334 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,03-15 20:34:57.113  4295  4295 E SPPClientService: [SystemStateMoniter] Action Name : android.intent.action.BOOT_COMPLETED
03-15 20:34:57.113  4295  4295 E SPPClientService: [SystemStateMoniter] Current Time : 44873
,03-15 20:34:57.113  4144  4144 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@f4a74d0 time:44875
,03-15 20:34:57.113  4312  4329 I DBG_POLICYDM: [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,03-15 20:34:57.113  1825  1825 I SamsungIME: getCurrentCandidateView
,03-15 20:34:57.123  4312  4312 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,03-15 20:34:57.123  4312  4312 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,03-15 20:34:57.123  4312  4312 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
,03-15 20:34:57.123  4312  4312 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
,03-15 20:34:57.123  3708  3761 I AMMetaDataParserService: Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,03-15 20:34:57.123  4312  4312 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,03-15 20:34:57.123  4312  4312 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,03-15 20:34:57.133  4295  4334 D SPPClientService: PushLog.txt file is not deleted.
03-15 20:34:57.133  4295  4334 D SPPClientService: PushLog.txt file is not deleted.
03-15 20:34:57.133  4295  4334 D SPPClientService: ============PushLog. stop!
,03-15 20:34:57.133  1017  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3517/cgroup.procs: No such file or directory
,03-15 20:34:57.143  4312  4312 I DBG_POLICYDM: [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,03-15 20:34:57.143  4312  4312 I DBG_POLICYDM: [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,03-15 20:34:57.143  4312  4312 I DBG_POLICYDM: [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,03-15 20:34:57.143  4312  4312 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.intent.action.BOOT_COMPLETED
,03-15 20:34:57.153  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:57.153  3708  3761 I GFX raster: took 0.823386ms for 96*96 texture 0
,03-15 20:34:57.153  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8f99ff0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f99bb0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:57.163  4144  4144 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 4144
,03-15 20:34:57.163  3708  3761 I AMMetaDataParserService: Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,03-15 20:34:57.183  4312  4312 I DBG_POLICYDM: [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,03-15 20:34:57.183  1017  1746 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:57.183  1017  1746 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:57.183  1017  1746 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:57.183  1017  1746 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:34:57.203  4341  4341 E Zygote  : MountEmulatedStorage()
03-15 20:34:57.203  4341  4341 E Zygote  : v2
,03-15 20:34:57.203  4341  4341 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-15 20:34:57.203  4341  4341 I libpersona: KNOX_SDCARD checking this for 10041
03-15 20:34:57.203  4341  4341 I libpersona: KNOX_SDCARD not a persona
,03-15 20:34:57.203  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
03-15 20:34:57.203  4341  4341 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-15 20:34:57.203  3708  3761 I GFX raster: took 0.773750ms for 96*96 texture 0
03-15 20:34:57.203  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8f99ff0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9174778 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:57.203  4341  4341 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL,
03-15 20:34:57.203  1017  1746 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4341 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-15 20:34:57.203  1017  1746 I ActivityManager: Killing 3526:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
,03-15 20:34:57.213  3708  3761 I AMMetaDataParserService: Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,03-15 20:34:57.223  1017  1746 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:57.223  1017  1746 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:57.223  1017  1746 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:57.223  1017  1746 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:34:57.223  4312  4329 I DBG_POLICYDM: [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT,
,03-15 20:34:57.223  4312  4329 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected,
,03-15 20:34:57.233  4312  4329 I DBG_POLICYDM: [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,03-15 20:34:57.243  4353  4353 E Zygote  : MountEmulatedStorage(),
,03-15 20:34:57.243  4353  4353 E Zygote  : v2
03-15 20:34:57.243  4353  4353 I libpersona: KNOX_SDCARD checking this for 10166
,03-15 20:34:57.243  4353  4353 I libpersona: KNOX_SDCARD not a persona
,03-15 20:34:57.243  4353  4353 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
03-15 20:34:57.243  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
03-15 20:34:57.243  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
03-15 20:34:57.243  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
,03-15 20:34:57.243  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
03-15 20:34:57.243  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
03-15 20:34:57.243  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageCompose
03-15 20:34:57.243  3708  3761 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-15 20:34:57.243  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:34:57.243  3708  3761 I AMMetaDataParserService: getResourcePackageName:android.app.spellscroll
,03-15 20:34:57.243  4341  4341 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 20:34:57.243  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
03-15 20:34:57.243  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
03-15 20:34:57.243  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
03-15 20:34:57.243  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
,03-15 20:34:57.243  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
03-15 20:34:57.243  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.DebugActivity
03-15 20:34:57.243  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
03-15 20:34:57.243  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
03-15 20:34:57.243  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
03-15 20:34:57.243  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SearchActivity
03-15 20:34:57.243  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 20:34:57.243  3708  3761 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-15 20:34:57.243  3708  3761 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-15 20:34:57.243  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
03-15 20:34:57.243  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
03-15 20:34:57.243  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
03-15 20:34:57.243  4341  4341 D ActivityThread: Added TimaKeyStore provider
,03-15 20:34:57.253  1825  1825 D SamsungIME: Dismiss ExpandCandiate,
,03-15 20:34:57.253  4312  4329 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,03-15 20:34:57.263  4353  4353 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-15 20:34:57.263  4353  4353 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-15 20:34:57.263  4312  4329 I DBG_POLICYDM: [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
,03-15 20:34:57.273  1017  1746 I ActivityManager: Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=4353 uid=10166 gids={50166, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 20:34:57.273  1017  1746 I ActivityManager: Killing 3559:com.sec.android.app.mt/1000 (adj 15): empty #31,
,03-15 20:34:57.283  1825  1825 I SamsungIME: getDebugLevel  : 0x4f4c
,03-15 20:34:57.283  3107  3189 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,03-15 20:34:57.293  4312  4329 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,03-15 20:34:57.313   257   448 I SurfaceFlinger: id=10 Removed uhalitest (7/8)
,03-15 20:34:57.313   257   446 I SurfaceFlinger: id=10 Removed uhalitest (-2/8)
,03-15 20:34:57.323  4353  4353 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 20:34:57.323  4353  4353 D ActivityThread: Added TimaKeyStore provider
,03-15 20:34:57.333  4312  4329 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,03-15 20:34:57.343  4312  4329 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,03-15 20:34:57.343  4312  4329 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
,03-15 20:34:57.353  4312  4329 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,03-15 20:34:57.353  4312  4330 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,03-15 20:34:57.353  1017  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3526/cgroup.procs: No such file or directory
,03-15 20:34:57.363  4312  4329 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2016/03/18/13:15:33
,03-15 20:34:57.363  4312  4329 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2016/03/15/20:34:57
,03-15 20:34:57.363  4312  4329 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
,03-15 20:34:57.363  4312  4329 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,03-15 20:34:57.373  4312  4330 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-15 20:34:57.373  4144  4144 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
03-15 20:34:57.373  1017  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3559/cgroup.procs: No such file or directory
,03-15 20:34:57.403  4312  4329 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,03-15 20:34:57.403  4312  4330 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-15 20:34:57.403  1825  1825 I SamsungIME: getDebugLevel  : 0x4f4c
,03-15 20:34:57.413  1017  1017 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@11
,03-15 20:34:57.413  4312  4330 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,03-15 20:34:57.413  4312  4330 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,03-15 20:34:57.413  4312  4330 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,03-15 20:34:57.413  4312  4330 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,03-15 20:34:57.413  4312  4330 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
,03-15 20:34:57.423  1695  1695 E SQLiteLog: (10) POSIX Error : 11 SQLite Error : 3850
,03-15 20:34:57.433  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
03-15 20:34:57.433  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
03-15 20:34:57.433  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
03-15 20:34:57.433  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
03-15 20:34:57.433  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
03-15 20:34:57.433  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:34:57.433  3708  3761 I AMMetaDataParserService: getResourcePackageName:android.app.spellscroll
03-15 20:34:57.433  3708  3761 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-15 20:34:57.433  3708  3761 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 20:34:57.433  3708  3761 I AMMetaDataParserService: Resource data:2131099648
,03-15 20:34:57.433  4312  4330 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
,03-15 20:34:57.443  4312  4330 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,03-15 20:34:57.453  3708  3761 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
03-15 20:34:57.453  3708  3761 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 20:34:57.453  3708  3761 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-15 20:34:57.453  3708  3761 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 20:34:57.453  3708  3761 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-15 20:34:57.453  3708  3761 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-15 20:34:57.453  3708  3761 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-15 20:34:57.453  3708  3761 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 20:34:57.453  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:57.453  3708  3761 I GFX raster: took 0.690105ms for 96*96 texture 0
03-15 20:34:57.453  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fb7930 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fc07c8 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:57.463  3708  3761 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-15 20:34:57.473  4312  4330 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,03-15 20:34:57.573  4144  4328 D jxcore_app_log: JniHelper::setJavaVM(0xb8beb450), pthread_self() = -1189787168
,03-15 20:34:57.583  4144  4328 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-15 20:34:57.583  4144  4328 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-15 20:34:57.583  4144  4328 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-15 20:34:57.583  4144  4328 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-15 20:34:57.583  4144  4328 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-15 20:34:57.583  4144  4328 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b3601df added. We now have 1 listener(s)
,03-15 20:34:57.593  4144  4328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:51:18:22
,03-15 20:34:57.593  4144  4328 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"7C:F9:0E:51:18:22"}
,03-15 20:34:57.593  4144  4328 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"7C:F9:0E:51:18:22"}
03-15 20:34:57.593  4144  4328 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
03-15 20:34:57.593  4144  4328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-15 20:34:57.603  4144  4328 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-15 20:34:57.603  4144  4328 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-15 20:34:57.603  4144  4328 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-15 20:34:57.603  4144  4328 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:51:18:22
03-15 20:34:57.603  4144  4328 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-15 20:34:57.603  4144  4328 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-15 20:34:57.603  4144  4328 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-15 20:34:57.603  4144  4328 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-15 20:34:57.603  4144  4328 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-15 20:34:57.603  4144  4328 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-15 20:34:57.603  4144  4328 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27763e8a added. We now have 1 listener(s)
,03-15 20:34:57.603  4144  4328 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-15 20:34:57.603  4144  4328 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,03-15 20:34:57.603  4144  4328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-15 20:34:57.603  4144  4328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,03-15 20:34:57.603  4144  4328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-15 20:34:57.603  4144  4328 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-15 20:34:57.613  1825  1825 I SamsungIME: KeybaordView init() : load resources
,03-15 20:34:57.613  4144  4328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-15 20:34:57.613  4144  4328 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:51:18:22
,03-15 20:34:57.623  4144  4328 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-15 20:34:57.623  4144  4328 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-15 20:34:57.623  4144  4328 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-15 20:34:57.623  4144  4328 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-15 20:34:57.623  4144  4328 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-15 20:34:57.623  4144  4328 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-15 20:34:57.623  4144  4328 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-15 20:34:57.623  4144  4328 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-15 20:34:57.623  4144  4328 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-15 20:34:57.623  4144  4328 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-15 20:34:57.643  4312  4329 I DBG_POLICYDM: [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
,03-15 20:34:57.653  4312  4330 I DBG_POLICYDM: [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
,03-15 20:34:57.653  4341  4341 I SA      : [SSP] onCreated
,03-15 20:34:57.653  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:57.663  4312  4329 I DBG_POLICYDM: [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,03-15 20:34:57.683  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:57.683  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:57.683  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:57.683  1017  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:34:57.683  3708  3761 I GFX construct_block_size_descriptor_2d second part: took 2.969270ms for 0*0 texture 0,
,03-15 20:34:57.693  1825  1825 I SamsungIME: getCurrentKeyboard,
03-15 20:34:57.693  1825  1825 I SamsungIME: getTextKeyboard
,03-15 20:34:57.703  3708  3761 I GFX generate_partition_tables: took 8.808386ms for 0*0 texture 0
,03-15 20:34:57.703  3708  3761 I GFX raster: took 12.766665ms for 96*96 texture 0
03-15 20:34:57.703  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fa52a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8fa5350 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:57.703  4380  4380 E Zygote  : MountEmulatedStorage()
03-15 20:34:57.703  4380  4380 E Zygote  : v2
03-15 20:34:57.703  4380  4380 I libpersona: KNOX_SDCARD checking this for 10012
03-15 20:34:57.703  4380  4380 I libpersona: KNOX_SDCARD not a persona
,03-15 20:34:57.703  4380  4380 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-15 20:34:57.703  1017  1043 I ActivityManager: Start proc com.google.android.gms:car for service com.google.android.gms/.car.InCallServiceImpl: pid=4380 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,03-15 20:34:57.713  3708  3761 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
03-15 20:34:57.713  4380  4380 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-15 20:34:57.713  4380  4380 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-15 20:34:57.723  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 20:34:57.723  3708  3761 I GFX raster: took 0.675573ms for 96*96 texture 0
03-15 20:34:57.723  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8f77a48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8f77a80 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:57.733  3708  3761 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
03-15 20:34:57.733  4380  4380 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 20:34:57.733  4380  4380 D ActivityThread: Added TimaKeyStore provider
03-15 20:34:57.743  4341  4341 I SA      : [TPM] There is no property file
03-15 20:34:57.743  4341  4341 I SA      : [SCU] isHaveSA() - false
03-15 20:34:57.743  4341  4341 I SA      : [TPM] getModelProperty : null
03-15 20:34:57.743  4341  4341 I SA      : [TPM] getCSCProperty : null
03-15 20:34:57.743  4341  4341 I SA      : [DM] FLOATING AMOLED FEATURE: true
03-15 20:34:57.753  4341  4341 I SA      : [DM] PRODUCT AMOLED FEATURE: false
03-15 20:34:57.753  4341  4341 I SA      : [DM] TFT FEATURE: false
,03-15 20:34:57.773  4380  4380 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-15 20:34:57.773  4380  4380 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-15 20:34:57.793  4144  4144 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-15 20:34:57.793  4144  4144 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-15 20:34:57.793  4144  4144 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-15 20:34:57.803  4341  4341 I SA      : [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
03-15 20:34:57.803  4341  4341 I SA      : [DM] init START
,03-15 20:34:57.813  1825  1825 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-15 20:34:57.833  4380  4380 I MultiDex: VM with version 2.1.0 has multidex support
03-15 20:34:57.833  4380  4380 I MultiDex: install
03-15 20:34:57.833  4380  4380 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-15 20:34:57.843  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:57.843  3708  3761 I GFX raster: took 0.655833ms for 96*96 texture 0
,03-15 20:34:57.843  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8f77a80 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8fc5548 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:57.853  3708  3761 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-15 20:34:57.873  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:57.873  3708  3761 I GFX raster: took 0.629792ms for 96*96 texture 0
03-15 20:34:57.873  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fc52a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f9a0c0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:57.883  3708  3761 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-15 20:34:57.883  4341  4341 I SA      : [DM] This device is not a Vodafone
,03-15 20:34:57.893  1017  3822 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,03-15 20:34:57.893  1017  3822 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4285, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
,03-15 20:34:57.893  4341  4341 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
03-15 20:34:57.893  4341  4341 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,03-15 20:34:57.893  4341  4341 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,03-15 20:34:57.893  4341  4341 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
03-15 20:34:57.893  4341  4341 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,03-15 20:34:57.893  4341  4341 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
03-15 20:34:57.893  4341  4341 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,03-15 20:34:57.893  1017  3822 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,03-15 20:34:57.903  1017  1017 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-15 20:34:57.903  4341  4341 W ResourceType: No package identifier when getting value for resource number 0x00000000
,03-15 20:34:57.903  4312  4330 I DBG_POLICYDM: [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,03-15 20:34:57.903  1017  1017 I MotionRecognitionService: Plugged
,03-15 20:34:57.903  1017  1017 I MotionRecognitionService: mGripSensorEnabled= false
,03-15 20:34:57.903  1187  1187 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,03-15 20:34:57.913  1187  1187 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-15 20:34:57.913  1462  1462 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-15 20:34:57.913  1462  1462 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-15 20:34:57.913  4341  4341 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,03-15 20:34:57.923  4380  4380 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-15 20:34:57.923  4341  4341 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,03-15 20:34:57.923  4341  4341 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
,03-15 20:34:57.923  4341  4341 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
03-15 20:34:57.923  4341  4341 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,03-15 20:34:57.923  4341  4341 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
03-15 20:34:57.923  4341  4341 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,03-15 20:34:57.923  4341  4341 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,03-15 20:34:57.933  4341  4341 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,03-15 20:34:57.933  4341  4341 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75),
03-15 20:34:57.933  4341  4341 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,03-15 20:34:57.933  4341  4341 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,03-15 20:34:57.933  4341  4341 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
03-15 20:34:57.933  4341  4341 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
03-15 20:34:57.933  1187  1187 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,03-15 20:34:57.933  4341  4341 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
03-15 20:34:57.933  1187  1187 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-15 20:34:57.933  4341  4341 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,03-15 20:34:57.933  1187  1187 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-15 20:34:57.933  4341  4341 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,03-15 20:34:57.933  2712  2712 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,03-15 20:34:57.943  2712  2826 D HeadsetStateMachine: Disconnected process message: 10
,03-15 20:34:57.943  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:57.943  3708  3761 I GFX raster: took 0.722968ms for 96*96 texture 0
03-15 20:34:57.943  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fc21f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fc2298 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:57.963  4341  4341 I SA      : [SCU] isHaveSA() - false
03-15 20:34:57.963  4341  4341 I SA      : support phone number id : false
03-15 20:34:57.963  4341  4341 I SA      : [DM] Supports Ref Jpn : true
,03-15 20:34:57.963  4341  4341 I SA      : [DM] init END
,03-15 20:34:57.963  3708  3761 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-15 20:34:57.963  4353  4395 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-15 20:34:57.963  4353  4395 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-15 20:34:57.973  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
03-15 20:34:57.973  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
03-15 20:34:57.973  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:34:57.973  3708  3761 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 20:34:57.973  3708  3761 I AMMetaDataParserService: Resource data:2131099648
,03-15 20:34:57.973  3708  3761 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-15 20:34:57.973  3708  3761 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 20:34:57.973  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:57.973  3708  3761 I GFX raster: took 0.678281ms for 96*96 texture 0
03-15 20:34:57.973  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fb7930 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f91258 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:57.983  4341  4341 I SA      : [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
03-15 20:34:57.983  4341  4341 I SA      : [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,03-15 20:34:57.983  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
,03-15 20:34:57.983  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:34:57.983  1017  1029 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
03-15 20:34:57.983  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,03-15 20:34:57.983  4341  4341 I SA      : [OR] onReceive END
,03-15 20:34:57.983  4312  4330 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-15 20:34:57.993  3708  3761 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-15 20:34:58.003  4341  4341 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,03-15 20:34:58.003  4341  4341 I SA      : [ODM] queryOpenData(key= GEO_IP )
,03-15 20:34:58.013  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:58.013  3708  3761 I GFX raster: took 0.634063ms for 96*96 texture 0
03-15 20:34:58.013  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fa52a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8f91258 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:58.023  4341  4341 I SA      : getMccForGalaxyJpn step2 GEO_IP MCC : 260
,03-15 20:34:58.033  4341  4341 I SA      : [LBE] REF_JPN : true
03-15 20:34:58.033  4341  4341 I SA      : [BDC] create
,03-15 20:34:58.043  3708  3761 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
03-15 20:34:58.043  4312  4330 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,03-15 20:34:58.043  4353  4395 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
03-15 20:34:58.053  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 20:34:58.053  3708  3761 I GFX raster: took 0.620469ms for 96*96 texture 0
03-15 20:34:58.053  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8f77a48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8f91258 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:58.063  4341  4341 I SA      : [DBMV2] getEmailID
,03-15 20:34:58.073  4341  4341 I SA      : [DBMV2] getDataV02ForItems
,03-15 20:34:58.073  4341  4341 I SA      : [SSP] query invoked
,03-15 20:34:58.083  4341  4341 I SA      : [SCU] get signed id from samsung account2.0 DB.
,03-15 20:34:58.083  3708  3761 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-15 20:34:58.083  4380  4380 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-15 20:34:58.093  4380  4380 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2635e3a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-15 20:34:58.093  4380  4380 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-15 20:34:58.103  4341  4341 I SA      : [SCU] get signed id from samsung account1.0 DB.
,03-15 20:34:58.113  4341  4341 I SA      : [BDC] destroy
,03-15 20:34:58.113  1017  1079 I ActivityManager: Killing 3575:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,03-15 20:34:58.113  1017  1079 I ActivityManager: Killing 3293:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
,03-15 20:34:58.123  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:58.123  3708  3761 I GFX raster: took 0.735418ms for 96*96 texture 0
,03-15 20:34:58.133  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8f77a80 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8f91258 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:58.143  3708  3761 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-15 20:34:58.153  4353  4395 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-15 20:34:58.163  4353  4395 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@21a378f4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-15 20:34:58.163  4353  4395 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-15 20:34:58.183  1017  1042 W libprocessgroup: failed to open /acct/uid_10069/pid_3575/cgroup.procs: No such file or directory
,03-15 20:34:58.183  1017  1042 W libprocessgroup: failed to open /acct/uid_10009/pid_3293/cgroup.procs: No such file or directory
,03-15 20:34:58.243  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:58.243  3708  3761 I GFX raster: took 0.650521ms for 96*96 texture 0
03-15 20:34:58.243  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fc52a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f91258 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:58.243  3708  3761 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-15 20:34:58.263  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:58.263  3708  3761 I GFX raster: took 0.717969ms for 96*96 texture 0
03-15 20:34:58.263  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fc21f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f91258 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:58.273  3708  3761 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-15 20:34:58.283  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
03-15 20:34:58.283  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
03-15 20:34:58.283  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
03-15 20:34:58.283  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
03-15 20:34:58.283  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:34:58.283  3708  3761 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 20:34:58.283  3708  3761 I AMMetaDataParserService: Resource data:2131099648
,03-15 20:34:58.283  3708  3761 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-15 20:34:58.283  3708  3761 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 20:34:58.283  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:58.283  3708  3761 I GFX raster: took 0.739636ms for 96*96 texture 0
03-15 20:34:58.283  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fb7930 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f91258 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:58.293  3107  3189 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,03-15 20:34:58.293  3708  3761 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-15 20:34:58.313  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:58.323  3708  3761 I GFX raster: took 0.686770ms for 96*96 texture 0
,03-15 20:34:58.323  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fa52a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8f913b0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:58.323  3708  3761 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-15 20:34:58.343  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:58.343  3708  3761 I GFX raster: took 0.641823ms for 96*96 texture 0
03-15 20:34:58.343  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8f77a48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8f91258 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:58.353  3708  3761 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-15 20:34:58.373  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:58.373  3708  3761 I GFX raster: took 0.644479ms for 96*96 texture 0
03-15 20:34:58.373  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8f77a80 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8f913b0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:58.383  3708  3761 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-15 20:34:58.463  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:58.463  3708  3761 I GFX raster: took 0.656459ms for 96*96 texture 0
,03-15 20:34:58.463  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fc52a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f91258 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:58.473  3708  3761 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-15 20:34:58.493  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:58.493  3708  3761 I GFX raster: took 0.727031ms for 96*96 texture 0
,03-15 20:34:58.493  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fc21f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fc12d0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:58.493  3708  3761 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-15 20:34:58.503  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
03-15 20:34:58.503  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 20:34:58.503  3708  3761 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 20:34:58.503  3708  3761 I AMMetaDataParserService: Resource data:2131099648
,03-15 20:34:58.503  3708  3761 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
,03-15 20:34:58.513  3708  3761 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 20:34:58.513  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:58.513  3708  3761 I GFX raster: took 0.883801ms for 96*96 texture 0
,03-15 20:34:58.513  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fb7930 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fc12d0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:58.523  3708  3761 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-15 20:34:58.533  4411  4411 I dex2oat : ----------------------------------------------------
03-15 20:34:58.533  4411  4411 I dex2oat : <SS>: S T A R T I N G . . .
03-15 20:34:58.533  4411  4411 I dex2oat : <SS>: Zip is absent. Canceled.
,03-15 20:34:58.533  4411  4411 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.youtube/cache/ads697746634.jar --oat-fd=31 --art-fd=-1 --oat-location=/data/data/com.google.android.youtube/cache/ads697746634.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,03-15 20:34:58.553  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:58.553  3708  3761 I GFX raster: took 0.632136ms for 96*96 texture 0
03-15 20:34:58.553  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fa52a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8fc12d0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:58.553  3708  3761 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-15 20:34:58.583  4353  4353 E YouTube MDX: Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,03-15 20:34:58.583  1017  1555 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 20:34:58.593  4411  4411 I dex2oat : dex2oat took 57.710ms (threads: 4)
,03-15 20:34:58.593  1017  1555 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:34:58.593  1017  1555 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:34:58.593  1017  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-15 20:34:58.593  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:58.593  3708  3761 I GFX raster: took 0.630885ms for 96*96 texture 0
03-15 20:34:58.593  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8f77a48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8fc12d0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:58.603  3708  3761 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-15 20:34:58.613  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:58.613  3708  3761 I GFX raster: took 0.675105ms for 96*96 texture 0
03-15 20:34:58.613  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8f77a80 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8fc12d0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:58.623  3708  3761 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-15 20:34:58.633  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:58.633  3708  3761 I GFX raster: took 0.643646ms for 96*96 texture 0
03-15 20:34:58.633  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fc52a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fc12d0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:58.633  3708  3761 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-15 20:34:58.643  1017  1079 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 20:34:58.643  1017  1079 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:34:58.643  1017  1079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-15 20:34:58.643  1017  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-15 20:34:58.673   256   514 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-15 20:34:58.673   256   514 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 20:34:58.673  4353  4353 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-15 20:34:58.683  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:58.683  3708  3761 I GFX raster: took 0.715364ms for 96*96 texture 0
03-15 20:34:58.683  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fc21f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fc12d0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:58.693  3708  3761 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-15 20:34:58.743  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
03-15 20:34:58.743  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:34:58.743  3708  3761 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 20:34:58.743  3708  3761 I AMMetaDataParserService: Resource data:2131099648
,03-15 20:34:58.743  3708  3761 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-15 20:34:58.743  3708  3761 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 20:34:58.743  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:58.743  3708  3761 I GFX raster: took 0.724895ms for 96*96 texture 0
03-15 20:34:58.743  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fb7930 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fc12d0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:58.753   277  1011 D EnterpriseController: uids 1000
03-15 20:34:58.753   277  1011 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-15 20:34:58.753   277  1011 D Netd    : getNetworkForDns: using netid 502 for uid 1000
,03-15 20:34:58.753  3708  3761 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-15 20:34:58.793  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:58.793  3708  3761 I GFX raster: took 0.662396ms for 96*96 texture 0
03-15 20:34:58.793  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fa52a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8fc12d0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:58.803  1017  3822 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,03-15 20:34:58.803  1017  3822 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:34:58.803  1017  3822 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:34:58.803  1017  3822 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-15 20:34:58.813  3708  3761 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-15 20:34:58.823  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:58.823  3708  3761 I GFX raster: took 0.620104ms for 96*96 texture 0
03-15 20:34:58.823  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8f77a48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8fc12d0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:58.823   291   291 E SMD     : DCD OFF
,03-15 20:34:58.823  3708  3761 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-15 20:34:58.833  1187  1187 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-15 20:34:58.833  1187  1187 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-15 20:34:58.833  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 20:34:58.833  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 20:34:58.833  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 20:34:58.833  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 20:34:58.853  1017  1102 V AlarmManager: waitForAlarm result :4
,03-15 20:34:58.853  1017  1102 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.libraries.social.mediamonitor.MediaMonitorIntentService; callingUser = 0; userId(target) = 0
,03-15 20:34:58.973  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:58.973  3708  3761 I GFX raster: took 0.755783ms for 96*96 texture 0
,03-15 20:34:58.973  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8f77a80 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8fc12d0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:58.983  3708  3761 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-15 20:34:59.003  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:59.013  3708  3761 I GFX raster: took 0.750001ms for 96*96 texture 0
03-15 20:34:59.013  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fc52a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fc12d0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:59.013  3708  3761 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-15 20:34:59.063   256   514 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-15 20:34:59.063   256   514 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 20:34:59.063  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:59.063  4353  4353 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-15 20:34:59.063  3708  3761 I GFX raster: took 0.911718ms for 96*96 texture 0
03-15 20:34:59.063  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fc21f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fc12d0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:59.073   256   514 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-15 20:34:59.073   256   514 W Vold    : Returning OperationFailed - no handler for errno 0
03-15 20:34:59.073  1017  3754 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 20:34:59.073  4353  4353 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
03-15 20:34:59.073  1017  3754 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:34:59.073  1017  3754 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:34:59.073  1017  3754 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,03-15 20:34:59.073   256   514 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-15 20:34:59.073   256   514 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 20:34:59.073  4353  4353 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,03-15 20:34:59.093  1017  1079 I art     : Explicit concurrent mark sweep GC freed 30418(1794KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/40MB, paused 3.803ms total 216.902ms
,03-15 20:34:59.093  3708  3761 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-15 20:34:59.103  1017  1132 D NtpTrustedTime: requestTime Success from server:north-america.pool.ntp.org mCachedNtpTime : 1458070499531 mCachedNtpElapsedRealtime : 46865 mCachedNtpCertainty : 118
,03-15 20:34:59.113  1017  1132 D NtpTrustedTime: currentTimeMillis() cache hit,
03-15 20:34:59.113  1017  1132 D NtpTrustedTime: currentTimeMillis() cache hit
03-15 20:34:59.113  1017  1132 D NtpTrustedTime: currentTimeMillis() cache hit
03-15 20:34:59.113  1017  1132 D NtpTrustedTime: currentTimeMillis() cache hit
03-15 20:34:59.113  1017  1132 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
03-15 20:34:59.113  1017  1132 D NtpTrustedTime: currentTimeMillis() cache hit
03-15 20:34:59.113  1017  1132 D NtpTrustedTime: currentTimeMillis() cache hit
,03-15 20:34:59.123  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConversationList
,03-15 20:34:59.123  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 20:34:59.123  3708  3761 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 20:34:59.123  3708  3761 I AMMetaDataParserService: Resource data:2131099648
03-15 20:34:59.133  3708  3761 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-15 20:34:59.133  3708  3761 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 20:34:59.133  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 20:34:59.133  4353  4353 W InstanceID/Rpc: Found 10012
,03-15 20:34:59.133  3708  3761 I GFX raster: took 0.717814ms for 96*96 texture 0
,03-15 20:34:59.133  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fb7930 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fc12d0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:59.143  3708  3761 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-15 20:34:59.163  1964  4437 I iu.UploadsManager: End new media; added: 0, uploading: 0, time: 300 ms
,03-15 20:34:59.173  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:59.173  3708  3761 I GFX raster: took 0.632083ms for 96*96 texture 0
03-15 20:34:59.173  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fa52a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8fc12d0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:59.173  3708  3761 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-15 20:34:59.183   256   514 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
03-15 20:34:59.183   256   514 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 20:34:59.183  4353  4353 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,03-15 20:34:59.193  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:59.193  3708  3761 I GFX raster: took 0.636041ms for 96*96 texture 0
03-15 20:34:59.193  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8f77a48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8fc12d0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:59.203  3708  3761 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-15 20:34:59.223  1017  1531 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,03-15 20:34:59.223  1017  1531 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:34:59.223  1017  1531 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:34:59.223  1017  1531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-15 20:34:59.233  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:59.233  3708  3761 I GFX raster: took 0.638333ms for 96*96 texture 0
03-15 20:34:59.233  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8f77a80 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8fc12d0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:59.243  3708  3761 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-15 20:34:59.263  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:59.263  3708  3761 I GFX raster: took 0.637552ms for 96*96 texture 0
03-15 20:34:59.263  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fc52a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fc12d0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:59.263  3708  3761 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-15 20:34:59.293  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:34:59.293  3708  3761 I GFX raster: took 0.799843ms for 96*96 texture 0
,03-15 20:34:59.293  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fc21f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fc12d0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:34:59.303  3107  3189 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 8 sec
,03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android,.mms.ui.PushMessageDialog
03-15 20:34:59.313  3708  3761 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.RestorePreviewActivity
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
,03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
,03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
,03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
,03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
,03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
,03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
,03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
,03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
,03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
,03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
,03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
,03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
03-15 20:34:59.313  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
,03-15 20:34:59.323  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
03-15 20:34:59.323  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:34:59.323  3708  3761 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 20:34:59.323  3708  3761 I AMMetaDataParserService: Resource data:2131165197
,03-15 20:34:59.333  3708  3761 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-15 20:34:59.333  3708  3761 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 20:34:59.333  3708  3761 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-15 20:34:59.333  3708  3761 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 20:34:59.333  3708  3761 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-15 20:34:59.333  3708  3761 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-15 20:34:59.333  3708  3761 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-15 20:34:59.333  3708  3761 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-15 20:34:59.333  3708  3761 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-15 20:34:59.333  3708  3761 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 20:34:59.343  3708  3761 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-15 20:34:59.353  3708  3761 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-15 20:34:59.353  4144  4377 W jxcore-log: Initializing JXcore engine
,03-15 20:34:59.353  4144  4377 W jxcore-log: JXcore engine is ready
,03-15 20:34:59.363  1017  1400 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,03-15 20:34:59.373  3708  3761 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-15 20:34:59.373  1017  1400 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:34:59.373  1017  1400 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:34:59.373  1017  1400 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-15 20:34:59.393  3708  3761 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-15 20:34:59.403  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
03-15 20:34:59.403  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:34:59.403  3708  3761 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-15 20:34:59.403  3708  3761 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 20:34:59.403  3708  3761 I AMMetaDataParserService: Resource data:2131165197
,03-15 20:34:59.403  3708  3761 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-15 20:34:59.403  3708  3761 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 20:34:59.403  1017  1425 D NtpTrustedTime: requestTime Success from server:north-america.pool.ntp.org mCachedNtpTime : 1458070499819 mCachedNtpElapsedRealtime : 47165 mCachedNtpCertainty : 137
,03-15 20:34:59.403  1017  1425 D NtpTrustedTime: currentTimeMillis() cache hit
,03-15 20:34:59.403  1017  1425 D AlarmManagerService: Setting time of day to sec=1458070499
,03-15 20:34:59.403  1017  1425 D AlarmManagerService: Trying to open a file
,03-15 20:34:59.413  3708  3761 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-15 20:34:59.413  1017  1425 D AlarmManagerService: File Open Success
03-15 20:34:59.413  1017  1425 D AlarmManagerService: File Close Success
03-15 20:34:59.413  1017  1425 I AlarmManagerService: DRM_TIME_PATH CHMOD 666 for resetState done 
,03-15 20:34:59.821  1017  1425 W AlarmManagerService: Unable to set rtc to 1458070499: Invalid argument
03-15 20:34:59.821  1017  1102 V AlarmManager: waitForAlarm result :65536
,03-15 20:34:59.821  1017  3823 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
,03-15 20:34:59.821  1017  3823 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:34:59.821  1017  3823 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:34:59.821  1017  3823 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-15 20:34:59.821  1017  1102 V AlarmManager: No more alarm at this time.nowELAPSED=47180 batch.start=47352
,03-15 20:34:59.821  1896  1896 E audit   : type=1400 msg=audit(1458070499.821:205): avc:  denied  { ioctl } for  pid=4377 comm="Thread-651" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-15 20:34:59.821  1896  1896 E audit   :  SEPF_SM-A500FU_5.0.2_0027
03-15 20:34:59.821  1896  1896 E audit   : type=1300 msg=audit(1458070499.821:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=9b5bf8f8 items=0 ppid=315 ppcomm=main pid=4377 auid=4294967295 uid=10174 gid=10174 euid=10174 suid=10174 fsuid=10174 egid=10174 sgid=10174 fsgid=10174 ses=4294967295 tty=(none) comm="Thread-651" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-15 20:34:59.821  1896  1896 E audit   : type=1320 msg=audit(1458070499.821:205): 
,03-15 20:34:59.821  3708  3761 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-15 20:34:59.830  1017  1017 D OTPFW   : OTPTimeChangeLogger :: TimeChangeListener$onReceive | Device Time Changed. Current time = 1458070499846
,03-15 20:34:59.840  1187  1187 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_SET
03-15 20:34:59.840  1187  1187 D KeyguardUpdateMonitor: handleTimeUpdate
,03-15 20:34:59.840  4144  4377 W jxcore-log: Starting JXcore engine
,03-15 20:34:59.840  1641  1641 D accuweather: [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_SET
03-15 20:34:59.840  1641  1641 D accuweather: [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,03-15 20:34:59.840  1641  1641 D accuweather: [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,03-15 20:34:59.840  1017  1017 D WifiStateMachine: android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,03-15 20:34:59.840  1017  1017 I DowntimeConditions: android.intent.action.TIME_SET ignored because schedule turned off.
,03-15 20:34:59.850  1641  1641 D accuweather: [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
03-15 20:34:59.850  1641  1641 D accuweather: [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,03-15 20:34:59.850  1187  1187 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-15 20:34:59.850  1641  1641 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,03-15 20:34:59.850  1641  1641 D accuweather: [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
,03-15 20:34:59.850  3708  3761 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-15 20:34:59.850  1187  1187 D SecKeyguardClockView: HomeTimezone(): 1
,03-15 20:34:59.850  1641  1641 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,03-15 20:34:59.860  1641  1641 D accuweather: [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,03-15 20:34:59.860  1187  1187 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-15 20:34:59.860  1187  1187 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_SET
,03-15 20:34:59.860  1641  1641 E accuweather: [KK AccuPhone]>>> UIM:1488 [0:0] bTM 20 34
,03-15 20:34:59.870  4353  4465 D AndroidHttpClient: [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A500FU Build/LRX22G)
03-15 20:34:59.870  4353  4465 D AndroidHttpClient: [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
,03-15 20:34:59.870  1017  1017 W Settings: Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-15 20:34:59.870  1187  1187 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-15 20:34:59.870  1187  1187 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-15 20:34:59.870  1187  1187 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-15 20:34:59.870  4353  4465 I System.out: Thread-733(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-15 20:34:59.870  1017  1079 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
,03-15 20:34:59.880  1017  1341 D SettingsProvider: name = lockscreen_zoom_panning_effect
03-15 20:34:59.880  1017  1341 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-15 20:34:59.880  1017  1341 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-15 20:34:59.880  1017  1341 D SettingsProvider: selectionArgs: false
03-15 20:34:59.880  1017  1341 D SettingsProvider: selectionArgs: 10054
03-15 20:34:59.880  1017  1341 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-15 20:34:59.880  1017  1341 D SettingsProvider: ret = -1
,03-15 20:34:59.880  1017  1079 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:34:59.880  1017  1079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-15 20:34:59.880  1017  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-15 20:34:59.890   282   282 W SEC_DRM_PLUGIN_Playready: PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK after: 1458070499 after conversion: 1458070499
,03-15 20:34:59.890   282   282 W SEC_DRM_PLUGIN_Playready: PlayreadyPlugIn::onAcquireDrmInfo : case TYPE_UPDATE_SECURE_CLOCK before: 1458070499 after conversion: 1458070499
03-15 20:34:59.890  1017  3822 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,03-15 20:34:59.890  1017  3822 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:34:59.890  1017  3822 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:34:59.890  1017  3822 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-15 20:34:59.900  4353  4465 I System.out: Thread-733(ApacheHTTPLog):isSBSettingEnabled false
03-15 20:34:59.900  4353  4465 I System.out: Thread-733(ApacheHTTPLog):isShipBuild true
03-15 20:34:59.900  4353  4465 I System.out: Thread-733(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-15 20:34:59.900  4353  4465 I System.out: Thread-733(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-15 20:34:59.900  1017  1341 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10054
,03-15 20:34:59.910  1187  1187 D KeyguardEffectViewUtil: isStrongPowerSavingMode() :false
,03-15 20:34:59.910   277  1011 D EnterpriseController: uids 10166
03-15 20:34:59.910   277  1011 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-15 20:34:59.910   277  1011 D Netd    : getNetworkForDns: using netid 502 for uid 10166
,03-15 20:34:59.910  1017  3754 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:34:59.910  1017  3754 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:59.910  1017  3754 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:34:59.910  1017  3754 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:34:59.920  1187  1187 D KeyguardEffectViewController: isPreloadedWallpaper=true
03-15 20:34:59.920  1187  1187 I GeometricMosaic_Keyguard: update
03-15 20:34:59.920  1187  1187 D KeyguardEffectViewUtil: getCurrentWallpaper() mWallpaperPath :null
,03-15 20:34:59.930  3708  3761 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-15 20:34:59.930  4474  4474 E Zygote  : MountEmulatedStorage()
03-15 20:34:59.930  4474  4474 E Zygote  : v2
03-15 20:34:59.930  4474  4474 I libpersona: KNOX_SDCARD checking this for 10101
03-15 20:34:59.930  4474  4474 I libpersona: KNOX_SDCARD not a persona
,03-15 20:34:59.930  4474  4474 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-15 20:34:59.930  1017  3754 I ActivityManager: Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=4474 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 20:34:59.940  4474  4474 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-15 20:34:59.940  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.cooliris.media.Gallery
03-15 20:34:59.940  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
03-15 20:34:59.940  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:34:59.940  3708  3761 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 20:34:59.940  3708  3761 I AMMetaDataParserService: Resource data:2131165197
,03-15 20:34:59.940  4474  4474 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-15 20:34:59.940  3708  3761 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-15 20:34:59.940  3708  3761 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 20:34:59.950  1017  1372 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
,03-15 20:34:59.950  1017  1372 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:34:59.950  1017  1372 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:34:59.950  1017  1372 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,03-15 20:34:59.950  3708  3761 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-15 20:34:59.970  3708  3761 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-15 20:34:59.980  4474  4474 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 20:34:59.980  4474  4474 D ActivityThread: Added TimaKeyStore provider
,03-15 20:34:59.980  3708  3761 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-15 20:34:59.980  4144  4377 W jxcore-log: Platform android
03-15 20:34:59.980  4144  4377 W jxcore-log: 
,03-15 20:34:59.980  4144  4377 W jxcore-log: Process ARCH arm
03-15 20:34:59.980  4144  4377 W jxcore-log: 
,03-15 20:34:59.990  1017  1102 V AlarmManager: waitForAlarm result :8
,03-15 20:35:00.010  1187  1187 I KeyguardEffectViewUtil: set current wallpaper info
,03-15 20:35:00.010  1017  3015 D SettingsProvider: name = keyguard_current_wallpaper_type
03-15 20:35:00.010  1017  3015 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-15 20:35:00.010  1017  3015 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,03-15 20:35:00.010  1017  3015 D SettingsProvider: selectionArgs: false
03-15 20:35:00.010  1017  3015 D SettingsProvider: selectionArgs: 10054
03-15 20:35:00.010  1017  3015 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,03-15 20:35:00.010  1017  3015 D SettingsProvider: ret = -1
,03-15 20:35:00.020  1017  3015 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10054
,03-15 20:35:00.020  1017  3014 D SettingsProvider: name = keyguard_current_wallpaper_file_path
,03-15 20:35:00.020  1017  3014 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-15 20:35:00.020  1017  3014 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-15 20:35:00.020  1017  3014 D SettingsProvider: selectionArgs: false
03-15 20:35:00.020  1017  3014 D SettingsProvider: selectionArgs: 10054
03-15 20:35:00.020  1017  3014 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-15 20:35:00.020  1017  3014 D SettingsProvider: ret = -1
,03-15 20:35:00.030  1017  3014 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10054
,03-15 20:35:00.030  1017  3754 D SettingsProvider: name = keyguard_current_wallpaper_res_id
03-15 20:35:00.030  1017  3754 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-15 20:35:00.030  1017  3754 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-15 20:35:00.030  1017  3754 D SettingsProvider: selectionArgs: false
03-15 20:35:00.030  1017  3754 D SettingsProvider: selectionArgs: 10054
03-15 20:35:00.030  1017  3754 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-15 20:35:00.030  1017  3754 D SettingsProvider: ret = -1
,03-15 20:35:00.030  1017  3754 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10054
,03-15 20:35:00.040  3708  3761 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-15 20:35:00.050  1017  1746 I ActivityManager: Killing 3614:com.google.android.onetimeinitializer/u0a14 (adj 15): empty #31
,03-15 20:35:00.060  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
,03-15 20:35:00.060  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.060  3708  3761 I AMMetaDataParserService: getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
03-15 20:35:00.060  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
03-15 20:35:00.060  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.060  3708  3761 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-15 20:35:00.060  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
03-15 20:35:00.060  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.060  3708  3761 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-15 20:35:00.060  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
03-15 20:35:00.060  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.070  3708  3761 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-15 20:35:00.070  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
03-15 20:35:00.070  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
03-15 20:35:00.070  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
03-15 20:35:00.070  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
03-15 20:35:00.070  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
03-15 20:35:00.070  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
03-15 20:35:00.070  3708  3761 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-15 20:35:00.070  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.070  3708  3761 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-15 20:35:00.070  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
03-15 20:35:00.070  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
03-15 20:35:00.070  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
03-15 20:35:00.070  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
03-15 20:35:00.070  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
03-15 20:35:00.070  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
03-15 20:35:00.070  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
03-15 20:35:00.070  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
03-15 20:35:00.070  3708  3761 I AMMetaDataParserService: Resource data:Loo,p for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
03-15 20:35:00.070  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
03-15 20:35:00.070  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
03-15 20:35:00.070  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
03-15 20:35:00.070  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
03-15 20:35:00.070  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
03-15 20:35:00.070  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
03-15 20:35:00.070  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,03-15 20:35:00.070  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.Camera
03-15 20:35:00.070  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.070  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
03-15 20:35:00.070  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
03-15 20:35:00.070  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.keyguard.layout
03-15 20:35:00.070  3708  3761 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 20:35:00.070  3708  3761 I AMMetaDataParserService: Resource data:2131099648
,03-15 20:35:00.070  3708  3761 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-15 20:35:00.070  3708  3761 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-15 20:35:00.070  3708  3761 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-15 20:35:00.070  3708  3761 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-15 20:35:00.070  3708  3761 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-15 20:35:00.070  3708  3761 I AMMetaDataParserService: getResourceName:com.sec.android.app.camera:xml/assistant
03-15 20:35:00.070  3708  3761 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 20:35:00.080  3708  3761 I AMMetaDataParserService: Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,03-15 20:35:00.110  1187  1632 D TEST    : run!!!
,03-15 20:35:00.120  1187  1187 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-15 20:35:00.120  3708  3761 I AMMetaDataParserService: Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,03-15 20:35:00.120  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-15 20:35:00.130  1017  1042 W libprocessgroup: failed to open /acct/uid_10014/pid_3614/cgroup.procs: No such file or directory
,03-15 20:35:00.130  1187  1187 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,03-15 20:35:00.130  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder,
03-15 20:35:00.130  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
03-15 20:35:00.130  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
03-15 20:35:00.130  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
,03-15 20:35:00.140  3708  3761 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,03-15 20:35:00.140  1187  1632 I GeometricMosaic_Renderer: setBackgroundBitmap
,03-15 20:35:00.140  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-15 20:35:00.140  1017  1050 D PowerManagerService: [s] UserActivityState : 1 -> 2
03-15 20:35:00.140  1017  1050 D DisplayPowerController: getFinalBrightness : Summary is 19 -> 19
03-15 20:35:00.140  1017  1050 D DisplayPowerController: animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-15 20:35:00.140  1017  1050 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,03-15 20:35:00.150  1017  1050 D DisplayPowerController: getFinalBrightness : Summary is 19 -> 19
,03-15 20:35:00.160  1017  1161 D lights  : lcd : 19 +
03-15 20:35:00.160  1017  1050 D DisplayPowerController: animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-15 20:35:00.170  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text,
,03-15 20:35:00.170  1017  1161 D lights  : lcd : 19 -
,03-15 20:35:00.170  1017  1050 D DisplayPowerController: getFinalBrightness : Summary is 19 -> 19
03-15 20:35:00.170  1017  1050 D DisplayPowerController: animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-15 20:35:00.180  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-15 20:35:00.210  1187  1187 D KeyguardEffectViewController: isPreloadedWallpaper=true,
03-15 20:35:00.210  1187  1187 D KeyguardUpdateMonitor: handleTimeUpdate
,03-15 20:35:00.210  1187  1187 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,03-15 20:35:00.220  1187  1187 D SecKeyguardClockView: HomeTimezone(): 1
,03-15 20:35:00.220  1187  1187 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-15 20:35:00.220  1187  1187 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,03-15 20:35:00.220  1187  1187 I KeyguardEffectViewController: *** don't update sliding image ***
,03-15 20:35:00.230  1641  1641 D accuweather: [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK
,03-15 20:35:00.230  1641  1641 D accuweather: [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,03-15 20:35:00.230  1641  1641 D accuweather: [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,03-15 20:35:00.230  1641  1641 D accuweather: [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,03-15 20:35:00.230  1641  1641 D accuweather: [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,03-15 20:35:00.230  1641  1641 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,03-15 20:35:00.230  1641  1641 D accuweather: [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
,03-15 20:35:00.230  1641  1641 D accuweather: [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,03-15 20:35:00.230  1641  1641 D accuweather: [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,03-15 20:35:00.240  1641  1641 E accuweather: [KK AccuPhone]>>> UIM:1488 [0:0] bTM 20 35
,03-15 20:35:00.270  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.GridSettings
03-15 20:35:00.270  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.270  3708  3761 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 20:35:00.270  3708  3761 I AMMetaDataParserService: Resource data:2131165220
,03-15 20:35:00.270  1187  1187 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d,
,03-15 20:35:00.270  3708  3761 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-15 20:35:00.270  3708  3761 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-15 20:35:00.270  3708  3761 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-15 20:35:00.270  3708  3761 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 20:35:00.270  3708  3761 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 20:35:00.270  3708  3761 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-15 20:35:00.270  3708  3761 I AMMetaDataParserService: getResourceName:com.android.settings:xml/assistant
03-15 20:35:00.270  3708  3761 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 20:35:00.280  1187  1187 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-15 20:35:00.280  1187  1187 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,03-15 20:35:00.300  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:35:00.300  3708  3761 I GFX raster: took 0.714010ms for 96*96 texture 0
03-15 20:35:00.300  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb96cad48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb96caa78 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:35:00.310  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-15 20:35:00.310  3708  3761 I AMMetaDataParserService: Icon data: ResourceSearch2131363521com.android.settings.Search2130837580
,03-15 20:35:00.330  3708  3761 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 20:35:00.330  3708  3761 I GFX raster: took 0.672708ms for 96*96 texture 0
,03-15 20:35:00.330  3708  3761 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb96cab98 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb96ddf00 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 20:35:00.340  3708  3761 I AMMetaDataParserService: Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SubSettings
,03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LabelName
,03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Password
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
,03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
,03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity,
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
,03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
,03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
,03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
,03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
,03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
,03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
,03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
,03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
03-15 20:35:00.360  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.TetherSettings
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LanguageSettings
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 20:35:00.390  3708  3761 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.HomeSettings
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DisplaySettings
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DockSettings
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ManageApplications
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RunningServices
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.400  1017  1079 I ActivityManager: Killing 3630:com.samsung.android.sconnect/u0a125 (adj 15): empty #31
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LaunchApplication
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.StorageUse
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SecuritySettings
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CredentialStorage
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SetProfileOwner
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.IccLockSettings
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ApnEditor
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MediaFormat
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MediaFormatSd
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AppPicker
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UsbSettings
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ActivityPicker
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BatteryInfo
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Display
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RadioInfo
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ProxySelector
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BandMode
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.TestingSettings
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeper
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
03-15 20:35:00.370  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
,03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
,03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SoundSettings
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
,03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.GSensorSettings
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
,03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
,03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.InkeffectPreview
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreview
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NewModePreview
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewColor
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewColor2014
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewStyleClock
,03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
,03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.WarrantyLegal
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
,03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
,03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
,03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
,03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PenHelpActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PhoneVibration
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.OneHandHelp
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
,03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I ,AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
03-15 20:35:00.380  3708  3761 I AMMetaDa,taParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MagazineCard
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
03-15 20:35:00.380  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SearchActivity
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.activekey.AppList
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
03-15 20:35:00.390  3708  3761 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
03-15 20:35:00.470  1017  1042 W libprocessgroup: failed to open /acct/uid_10125/pid_3630/cgroup.procs: No such file or directory
03-15 20:35:00.470  1017  1129 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-15 20:35:00.470  1017  1129 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
03-15 20:35:00.490  4353  4465 I System.out: Thread-733 calls detatch()
,03-15 20:35:00.510  4144  4377 I jxcore-log: JXcore Cordova bridge is ready!
03-15 20:35:00.510  4144  4377 I jxcore-log: 
03-15 20:35:00.510  4144  4377 W jxcore-log: JXcore engine is started
03-15 20:35:00.510  4144  4328 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
03-15 20:35:00.530  4144  4377 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-15 20:35:00.530  4144  4377 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,03-15 20:35:00.530  4144  4144 I chromium: [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
,03-15 20:35:00.540  1017  3014 D FocusedStackFrame: Set to : 0
,03-15 20:35:00.540  1017  3014 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-15 20:35:00.540  1017  3014 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-15 20:35:00.540  1017  3014 D InputDispatcher: Focused application set to: xxxx
,03-15 20:35:00.540  1017  3014 D InputDispatcher: Focus left window: 4144
,03-15 20:35:00.540  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-15 20:35:00.540  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-15 20:35:00.540   257   446 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (149 us)
,03-15 20:35:00.570  4144  4328 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 39ms. Plugin should use CordovaInterface.getThreadPool().
,03-15 20:35:00.570  1017  1555 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@7
,03-15 20:35:00.570  1017  1555 W ActivityManager: mDVFSHelper.acquire()
,03-15 20:35:00.580  1017  1555 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-15 20:35:00.580  1017  1555 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-15 20:35:00.580  1017  1555 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,03-15 20:35:00.580  4474  4494 I Gmail   : getAccountsCursor
,03-15 20:35:00.600  1528  1528 D Launcher: onRestart, Launcher: 833304157
03-15 20:35:00.600  1528  1528 D Launcher: onStart, Launcher: 833304157
03-15 20:35:00.600  1528  1528 D Launcher.HomeView: onStart
,03-15 20:35:00.600  1528  1528 D Launcher: onResume, Launcher: 833304157
,03-15 20:35:00.600  1017  1372 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-15 20:35:00.600  1017  1622 D SettingsProvider: name = kids_home_mode
03-15 20:35:00.600  1017  1622 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-15 20:35:00.600  1017  1622 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-15 20:35:00.600  1017  1622 D SettingsProvider: selectionArgs: false
03-15 20:35:00.600  1017  1622 D SettingsProvider: selectionArgs: 10007
03-15 20:35:00.600  1017  1622 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-15 20:35:00.600  1017  1622 D SettingsProvider: ret = -1
03-15 20:35:00.600  1528  1528 D Launcher.HomeView: onResume
,03-15 20:35:00.610  1017  1017 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,03-15 20:35:00.610  1017  1017 D SensorService: [SO] activate (ident=0xb9337388, enabled=0)
03-15 20:35:00.610  1017  1017 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-15 20:35:00.610  1695  1695 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 20:35:00.610  1528  1528 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-15 20:35:00.620  1528  1528 D MenuAppsGridFragment: onResume
,03-15 20:35:00.620  1017  1746 D ActivityManager: handle home activity for 0
,03-15 20:35:00.620  1017  1746 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
03-15 20:35:00.620  1017  1746 D KnoxTimeoutHandler: post home show event for user 0
03-15 20:35:00.620  1017  1746 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-15 20:35:00.620  1017  1746 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-15 20:35:00.620  1017  1746 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-15 20:35:00.620  1017  1017 D SensorManager: unregisterListener ::   
,03-15 20:35:00.620  1017  1017 I Sensors : AccelerometerSensor(0) setDelay : 200000000(ns)
,03-15 20:35:00.620   257   257 I SurfaceFlinger: id=12 createSurf (720x1280),1 flag=4, Mauncher
,03-15 20:35:00.620  1017  1017 D SensorService: [SO] changed settle time [0]
03-15 20:35:00.620  1017  1017 D SensorService: [SO] setDelay [200000000]
03-15 20:35:00.620  1017  1017 D SensorService: [SO] activate (ident=0xb9337388, enabled=1)
03-15 20:35:00.620  1017  1017 D SensorService: [SO] AR_init
03-15 20:35:00.620  1017  1017 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-15 20:35:00.620  1017  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-15 20:35:00.620  1017  1046 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-15 20:35:00.630  1017  1017 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,03-15 20:35:00.630  1017  1017 D PersonaManagerService: getPersonasForUser(): returning null!
03-15 20:35:00.630  1017  1017 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
03-15 20:35:00.630  1017  1017 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
,03-15 20:35:00.630  1017  1017 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-15 20:35:00.630  1017  1029 D InputDispatcher: Focus entered window: 1528
,03-15 20:35:00.640  1017  1048 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-15 20:35:00.640  1528  1528 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
03-15 20:35:00.640  1017  1048 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-15 20:35:00.640  4474  4474 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,03-15 20:35:00.650  1017  1622 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
,03-15 20:35:00.650  1017  1622 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,03-15 20:35:00.650  1528  1528 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-15 20:35:00.650  1017  1372 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-15 20:35:00.660  1187  1187 D PanelView: There is/are notification(s) 
,03-15 20:35:00.660  4144  4144 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
03-15 20:35:00.660  1017  4503 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
03-15 20:35:00.660  1825  1825 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-15 20:35:00.670  4474  4502 I Gmail   : Observing account changes for notifications
,03-15 20:35:00.670  1017  1129 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 20:35:00.680  1017  1129 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-15 20:35:00.690  1017  1372 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
,03-15 20:35:00.690  1017  1372 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:00.690  1017  1372 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:00.690  1017  1372 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-15 20:35:00.700  1017  1341 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GoogleMailSwitchService; callingUser = 0; userId(target) = 0
,03-15 20:35:00.700  1017  1341 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:00.700  1017  1341 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:00.700  1017  1341 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-15 20:35:00.700  1528  1757 W OpenGLRenderer: SFEffectCache::get: create texture(0xa3ea0724): name, size, mSize = 35, 146520, 321432
,03-15 20:35:00.700  3107  3189 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 9 sec
,03-15 20:35:00.710  1528  1528 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@6e1d76a time:48071
,03-15 20:35:00.710  1017  1048 D PersonaManager: isKioskContainerExistOnDevice
03-15 20:35:00.710  1017  1746 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-15 20:35:00.710  1017  1746 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-15 20:35:00.720  1017  1048 I ActivityManager: Displayed Component not be shown by security: +141ms
,03-15 20:35:00.730  1017  1531 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
,03-15 20:35:00.730  1017  1531 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:00.730  1017  1531 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:00.730  1017  1531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-15 20:35:00.730  4474  4508 E Gmail   : Error finding the version of the Email provider.....
03-15 20:35:00.730  4474  4508 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
03-15 20:35:00.730  4474  4508 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
03-15 20:35:00.730  4474  4508 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1279)
03-15 20:35:00.730  4474  4508 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:219)
03-15 20:35:00.730  4474  4508 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-15 20:35:00.730  4474  4508 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 20:35:00.730  4474  4508 E Gmail   : 	at android.os.Looper.loop(Looper.java:145)
03-15 20:35:00.730  4474  4508 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-15 20:35:00.740  4474  4508 W EmailMigration: We do not support migrating this version of the Email provider.
,03-15 20:35:00.740  4474  4510 I Gmail   : getAccountsCursor
,03-15 20:35:00.750  1017  3014 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-15 20:35:00.750  1017  3015 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,03-15 20:35:00.750  1695  1695 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 20:35:00.750  1017  3015 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:00.750  1017  3015 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:00.750  1017  3015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,03-15 20:35:00.760  1017  1400 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:35:00.760  1017  1400 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:35:00.760  1017  1400 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:35:00.760  1017  1400 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:35:00.770  4514  4514 E Zygote  : MountEmulatedStorage()
03-15 20:35:00.770  4514  4514 E Zygote  : v2
03-15 20:35:00.770  4514  4514 I libpersona: KNOX_SDCARD checking this for 10092
03-15 20:35:00.770  4514  4514 I libpersona: KNOX_SDCARD not a persona
,03-15 20:35:00.770  4514  4514 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-15 20:35:00.770  1017  1400 I ActivityManager: Start proc com.dropbox.android for broadcast com.dropbox.android/.service.WakeupReceiver: pid=4514 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 20:35:00.780  4514  4514 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-15 20:35:00.780  4514  4514 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-15 20:35:00.780  1017  1555 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-15 20:35:00.780  1017  1555 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-15 20:35:00.780  1017  3823 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-15 20:35:00.780  1017  1372 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-15 20:35:00.790  1017  1079 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-15 20:35:00.790  1017  1079 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,03-15 20:35:00.800  4514  4514 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 20:35:00.800  4514  4514 D ActivityThread: Added TimaKeyStore provider
,03-15 20:35:00.810  4474  4474 E ActivityThread: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@130e7b32 that was originally bound here
03-15 20:35:00.810  4474  4474 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.am@130e7b32 that was originally bound here
03-15 20:35:00.810  4474  4474 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
03-15 20:35:00.810  4474  4474 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
03-15 20:35:00.810  4474  4474 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
03-15 20:35:00.810  4474  4474 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
03-15 20:35:00.810  4474  4474 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
03-15 20:35:00.810  4474  4474 E ActivityThread: 	at com.android.emailcommon.service.ak.a(SourceFile:181)
03-15 20:35:00.810  4474  4474 E ActivityThread: 	at com.android.emailcommon.service.ak.e(SourceFile:224)
03-15 20:35:00.810  4474  4474 E ActivityThread: 	at com.android.email.service.n.c(SourceFile:177)
03-15 20:35:00.810  4474  4474 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:198)
03-15 20:35:00.810  4474  4474 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:142)
03-15 20:35:00.810  4474  4474 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:349)
03-15 20:35:00.810  4474  4474 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1334)
03-15 20:35:00.810  4474  4474 E ActivityThread: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-15 20:35:00.810  4474  4474 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 20:35:00.810  4474  4474 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-15 20:35:00.810  4474  4474 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-15 20:35:00.810  1017  1341 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@c6c6a3e
,03-15 20:35:00.830  1017  1040 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-15 20:35:00.840  4474  4511 E SQLiteLog: (283) recovered 44 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-15 20:35:01.010  4474  4524 I Gmail   : notifyAccountChanged
03-15 20:35:01.010  4474  4511 E File    : fail readDirectory() errno=2
,03-15 20:35:01.010  4474  4524 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-15 20:35:01.020  4474  4533 I Gmail   : getAccountsCursor
,03-15 20:35:01.020  1017  3014 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-15 20:35:01.030  4474  4524 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing,
03-15 20:35:01.030  1017  1040 D SensorService: [SO] currT = 48391125000, prevT = 47951138000, diff = 439987000, [0.192 0.402 10.266],
,03-15 20:35:01.030  1017  1040 D SensorService: [SO] 0.192 0.402 10.266
03-15 20:35:01.030  1017  1040 D SensorService: [SO] [100 -> 255]
03-15 20:35:01.030  1695  1695 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 20:35:01.040  1017  1079 D ActivityManager: retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.android.exception.CrashUploaderService; callingUser = 0; userId(target) = 0
,03-15 20:35:01.040  1017  1079 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:01.040  1017  1079 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
03-15 20:35:01.040  1017  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,03-15 20:35:01.040  1017  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:35:01.040  1017  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:35:01.040  1017  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:35:01.040  1017  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:35:01.050  4474  4524 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-15 20:35:01.050  4474  4524 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
,03-15 20:35:01.050  4534  4534 E Zygote  : MountEmulatedStorage()
,03-15 20:35:01.050  4534  4534 E Zygote  : v2
03-15 20:35:01.050  4534  4534 I libpersona: KNOX_SDCARD checking this for 10092
03-15 20:35:01.050  4534  4534 I libpersona: KNOX_SDCARD not a persona
,03-15 20:35:01.060  4534  4534 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-15 20:35:01.060  1017  1079 I ActivityManager: Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=4534 uid=10092 gids={50092, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 20:35:01.060  4534  4534 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-15 20:35:01.060  4534  4534 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-15 20:35:01.060  1017  1555 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,03-15 20:35:01.060  1017  1555 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:01.060  1017  1555 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:01.060  1017  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-15 20:35:01.070  4474  4511 I Gmail   : Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_promo (has extras) }
,03-15 20:35:01.070  1017  1043 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@7
03-15 20:35:01.080  1017  1043 W ActivityManager: mDVFSHelper.release()
03-15 20:35:01.080  1017  1043 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-15 20:35:01.080  4312  4329 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-15 20:35:01.080  4474  4511 I Gmail   : Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_social (has extras) }
,03-15 20:35:01.090  1017  1341 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 20:35:01.090  1017  1341 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:01.090  1017  1341 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:01.090  1017  1341 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 20:35:01.090  4534  4534 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 20:35:01.100  4534  4534 D ActivityThread: Added TimaKeyStore provider
,03-15 20:35:01.110  4474  4511 I Gmail   : Sending provider changed intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://gmail-ls/unread/^sq_ig_i_personal (has extras) }
,03-15 20:35:01.110  4312  4329 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-15 20:35:01.120  4312  4329 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-15 20:35:01.120  1017  1372 I ActivityManager: Killing 3686:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
,03-15 20:35:01.130  4312  4329 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,03-15 20:35:01.130  4312  4329 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-15 20:35:01.130  4312  4329 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-15 20:35:01.130  4312  4329 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-15 20:35:01.130  4312  4329 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml,
,03-15 20:35:01.140  1017  1400 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 20:35:01.140  1017  1400 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:01.140  1017  1400 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-15 20:35:01.140  1017  1400 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 20:35:01.150  1017  1048 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{19c64767 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t235} time:48515
,03-15 20:35:01.150  4514  4514 I com.dropbox.android.service.DropboxNetworkReceiver: Setting receiver enabled: false
,03-15 20:35:01.160  1017  1043 I ActivityManager: Killing 3648:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,03-15 20:35:01.160   257  1039 I SurfaceFlinger: id=11 Removed NainActivit (7/8)
,03-15 20:35:01.160   257   448 I SurfaceFlinger: id=11 Removed NainActivit (-2/8)
,03-15 20:35:01.180  4514  4514 E ActivityThread: Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
,03-15 20:35:01.210  4144  4144 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@c4ec118 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-15 20:35:01.210  4144  4144 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@c4ec118 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-15 20:35:01.210  4144  4144 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-15 20:35:01.210  4144  4144 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-15 20:35:01.210  4144  4144 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-15 20:35:01.210  4144  4144 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-15 20:35:01.210  4144  4144 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-15 20:35:01.210  4144  4144 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.initialize(BluetoothManager.java:275)
03-15 20:35:01.210  4144  4144 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.bind(BluetoothManager.java:103)
03-15 20:35:01.210  4144  4144 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:75)
03-15 20:35:01.210  4144  4144 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-15 20:35:01.210  4144  4144 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-15 20:35:01.210  4144  4144 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-15 20:35:01.210  4144  4144 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-15 20:35:01.210  4144  4144 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-15 20:35:01.210  4144  4144 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-15 20:35:01.210  4144  4144 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-15 20:35:01.210  4144  4144 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-15 20:35:01.210  4144  4144 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-15 20:35:01.210  4144  4144 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-15 20:35:01.210  4144  4144 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 20:35:01.210  4144  4144 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-15 20:35:01.210  4144  4144 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-15 20:35:01.220  4144  4144 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@3d22dcfb that was originally registered here. Are you missing a call to unregisterReceiver()?
03-15 20:35:01.220  4144  4144 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@3d22dcfb that was originally registered here. Are you missing a call to unregisterReceiver()?
03-15 20:35:01.220  4144  4144 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-15 20:35:01.220  4144  4144 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-15 20:35:01.220  4144  4144 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-15 20:35:01.220  4144  4144 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-15 20:35:01.220  4144  4144 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-15 20:35:01.220  4144  4144 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:503)
03-15 20:35:01.220  4144  4144 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:67)
03-15 20:35:01.220  4144  4144 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-15 20:35:01.220  4144  4144 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-15 20:35:01.220  4144  4144 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-15 20:35:01.220  4144  4144 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-15 20:35:01.220  4144  4144 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-15 20:35:01.220  4144  4144 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-15 20:35:01.220  4144  4144 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-15 20:35:01.220  4144  4144 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-15 20:35:01.220  4144  4144 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-15 20:35:01.220  4144  4144 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-15 20:35:01.220  4144  4144 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 20:35:01.220  4144  4144 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-15 20:35:01.220  4144  4144 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-15 20:35:01.230  1017  1129 I ActivityManager: Killing 3708:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,03-15 20:35:01.240  4514  4514 I dbxyzptlk.db300200.aw.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_9807ade0d39f04306c7e28de04204d1f53ae2228_armv7a
,03-15 20:35:01.250  1017  1042 W libprocessgroup: failed to open /acct/uid_10015/pid_3648/cgroup.procs: No such file or directory
,03-15 20:35:01.250  1017  1042 W libprocessgroup: failed to open /acct/uid_10131/pid_3686/cgroup.procs: No such file or directory
,03-15 20:35:01.250  4514  4514 D breakpad: breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
,03-15 20:35:01.260  4514  4514 I dbxyzptlk.db300200.aw.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_b492ffd532b8b6365d97439f842c164c3c90fd4e_armv7a
,03-15 20:35:01.260  4514  4514 I dbxyzptlk.db300200.aw.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_e16babc055b114839529ea959e1ce06f2a593b63_armv7a
,03-15 20:35:01.270  4474  4494 I Gmail   : getAccountsCursor
,03-15 20:35:01.270  1017  1622 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-15 20:35:01.270  1695  1695 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 20:35:01.320  1017  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3708/cgroup.procs: No such file or directory
,03-15 20:35:01.360  4514  4514 I libDropboxSync.so: Setting global terminate handler.
,03-15 20:35:01.380  1017  1017 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1017  tag : ACTIVITY_RESUME_BOOSTER@11
,03-15 20:35:01.390  4514  4514 I dbxyzptlk.db300200.aw.h: Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_aa417f8c60b792b71fc3cef90fc4bb8ddba4ea56_armv7a
,03-15 20:35:01.430  4514  4514 I com.dropbox.sync.android.L: Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
,03-15 20:35:01.440  4514  4514 I com.dropbox.sync.android.L: Removing unclaimed file/directory in cache: "local-dbapp_noauth"
,03-15 20:35:01.460  4514  4514 I com.dropbox.sync.android.bf: Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/3.0.2 DropboxSync/3.1+dev (Android; 5.0.2; samsung SM-A500FU armeabi-v7a; en_US))
,03-15 20:35:01.470  4514  4514 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-15 20:35:01.470  4514  4514 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-15 20:35:01.490  4514  4514 I com.dropbox.sync.android.aS: Created NativeDbappNoAuthClientProvider
,03-15 20:35:01.490  1017  1400 D ActivityManager: retrieveServiceLocked(): component = com.dropbox.android/com.dropbox.sync.android.DbxSyncService; callingUser = 0; userId(target) = 0
,03-15 20:35:01.490  1017  1400 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:01.490  1017  1400 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
03-15 20:35:01.490  1017  1400 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
,03-15 20:35:01.540  4514  4556 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
03-15 20:35:01.540  4514  4556 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
03-15 20:35:01.540  4514  4556 I System.out: (HTTPLog)-Static: isShipBuild true
03-15 20:35:01.540  4514  4556 I System.out: (HTTPLog)-Thread-697-573376541: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-15 20:35:01.540  4514  4556 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,03-15 20:35:01.540   277  1011 D EnterpriseController: uids 10092
03-15 20:35:01.540   277  1011 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-15 20:35:01.540   277  1011 D Netd    : getNetworkForDns: using netid 502 for uid 10092
,03-15 20:35:01.630  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:35:01.630  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:35:01.630  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:35:01.630  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:35:01.630  4514  4514 I com.dropbox.sync.android.DbxSyncService: DbxSyncService starting.
,03-15 20:35:01.640  4568  4568 E Zygote  : MountEmulatedStorage(),
03-15 20:35:01.640  4568  4568 E Zygote  : v2
,03-15 20:35:01.640  4568  4568 I libpersona: KNOX_SDCARD checking this for 10057
03-15 20:35:01.640  4568  4568 I libpersona: KNOX_SDCARD not a persona
03-15 20:35:01.640  1017  1029 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=4568 uid=10057 gids={50057, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,03-15 20:35:01.640  4568  4568 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-15 20:35:01.640  4568  4568 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-15 20:35:01.650  4568  4568 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-15 20:35:01.650  1017  1622 I ActivityManager: Killing 3731:com.android.managedprovisioning/u0a22 (adj 15): empty #31
,03-15 20:35:01.650  4514  4556 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,03-15 20:35:01.660  4568  4568 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 20:35:01.660  4568  4568 D ActivityThread: Added TimaKeyStore provider
,03-15 20:35:01.710  3107  3189 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 10 sec
,03-15 20:35:01.760  1017  1042 W libprocessgroup: failed to open /acct/uid_10022/pid_3731/cgroup.procs: No such file or directory
,03-15 20:35:01.850  4514  4556 I com.dropbox.sync.android.aF: Created new socket: SSL socket over Socket[address=api.dropbox.com/108.160.172.237,port=443,localPort=60764]
,03-15 20:35:01.870  1017  1555 D LocationManagerService: getProviders()=[passive]
,03-15 20:35:01.900  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:35:01.900  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:35:01.900  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:35:01.900  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:35:01.920  4589  4589 E Zygote  : MountEmulatedStorage(),
03-15 20:35:01.920  4589  4589 E Zygote  : v2
03-15 20:35:01.920  4589  4589 I libpersona: KNOX_SDCARD checking this for 10015
,03-15 20:35:01.920  4589  4589 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-15 20:35:01.920  4589  4589 I libpersona: KNOX_SDCARD not a persona
03-15 20:35:01.920  4589  4589 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-15 20:35:01.920  4589  4589 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-15 20:35:01.930  1017  1029 I ActivityManager: Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=4589 uid=10015 gids={50015, 9997, 3003} abi=armeabi-v7a
,03-15 20:35:01.940  1017  3823 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.service.BroadcastListenerService; callingUser = 0; userId(target) = 0
,03-15 20:35:01.940  1017  3823 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:01.940  1017  3823 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:01.940  1017  3823 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-15 20:35:01.950  4589  4589 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 20:35:01.950  4589  4589 D ActivityThread: Added TimaKeyStore provider
,03-15 20:35:02.010  1017  1746 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.velvet.VelvetBackgroundTasksImpl$Service; callingUser = 0; userId(target) = 0
,03-15 20:35:02.020  1017  1746 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:02.020  1017  1746 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:02.020  1017  1746 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,03-15 20:35:02.030  1017  1341 I splitIntent: Queue : backgroundsplit_2 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,03-15 20:35:02.030  1017  1043 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:02.030  1017  1043 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:35:02.030  1017  1043 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 20:35:02.030  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:02.030  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:35:02.030  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 20:35:02.040  1017  1531 I ActivityManager: Killing 1283:com.android.defcontainer/u0a4 (adj 15): empty #31
,03-15 20:35:02.040  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:02.040  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:35:02.040  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 20:35:02.050  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:02.050  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:35:02.050  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 20:35:02.060  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:02.060  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:35:02.060  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 20:35:02.060  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:02.060  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:35:02.060  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 20:35:02.070  1017  1372 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 20:35:02.070  1017  1372 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:02.070  1017  1372 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:02.070  1017  1372 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,03-15 20:35:02.070  1017  1400 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,03-15 20:35:02.080  1017  1400 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:02.080  1017  1400 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:02.080  1017  1400 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,03-15 20:35:02.080  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:02.080  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-15 20:35:02.080  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 20:35:02.090  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:02.090  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:35:02.090  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 20:35:02.090  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:02.090  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:35:02.090  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 20:35:02.100  1017  1372 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 20:35:02.100  1017  1372 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:02.100  1017  1372 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-15 20:35:02.100  1017  1372 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 20:35:02.110  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 20:35:02.110  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:02.110  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-15 20:35:02.110  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 20:35:02.120  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:02.120  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:35:02.120  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 20:35:02.130  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:02.130  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:35:02.130  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 20:35:02.140  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:02.140  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:35:02.140  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 20:35:02.140  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:02.140  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:35:02.140  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 20:35:02.150  1017  3015 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:02.150  1017  3015 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-15 20:35:02.160  1017  3015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 20:35:02.160  1695  1708 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:-24588>, callingPkg: com.google.android.googlequicksearchbox, service: oauth2:https://www.googleapis.com/auth/googlenow
,03-15 20:35:02.160  1695  1708 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:-24588> oauth2:https://www.googleapis.com/auth/googlenow without consulting the cloud. [mastertoken: <EMPTY>, password: <NULL>]
03-15 20:35:02.160  1695  1708 I GLSUser : [GLSUser] Extracting token using key: Auth
03-15 20:35:02.160  1695  1708 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
,03-15 20:35:02.160  1695  1708 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 20:35:02.160  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:02.160  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-15 20:35:02.160  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 20:35:02.170  1017  1129 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.DefaultAuthDelegateService; callingUser = 0; userId(target) = 0
,03-15 20:35:02.170  1017  1129 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:02.170  1017  1129 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:02.170  1017  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 20:35:02.180  1017  1372 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-15 20:35:02.180  1017  1372 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:02.180  1017  1372 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:35:02.180  1017  1372 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-15 20:35:02.180  2351  2351 I Hs20UtilService: Starting #4
,03-15 20:35:02.180  1017  2853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-15 20:35:02.190  1348  1348 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-15 20:35:02.190  2351  2366 I Hs20UtilService: Message received 5007
,03-15 20:35:02.190  1348  1348 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,03-15 20:35:02.190  1348  1348 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,03-15 20:35:02.190  1348  1348 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
,03-15 20:35:02.190  1348  1348 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
03-15 20:35:02.190  1348  1348 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-15 20:35:02.200  1017  3754 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:02.200  1017  3754 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:35:02.200  1017  3754 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,03-15 20:35:02.220  1017  1622 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:02.220  1017  1622 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-15 20:35:02.220  1017  1622 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 20:35:02.220   291   291 E SMD     : DCD OFF
,03-15 20:35:02.230  1017  1555 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,03-15 20:35:02.230  4568  4622 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,03-15 20:35:02.230  1017  1555 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:02.230  1017  1555 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:02.230  1017  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 20:35:02.230  1017  1079 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
03-15 20:35:02.230  1017  1079 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
03-15 20:35:02.230  1017  1079 I splitIntent: other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
03-15 20:35:02.230  1017  1079 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,03-15 20:35:02.230  1017  1079 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:02.230  1017  1079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:02.230  1017  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 20:35:02.240  1017  1746 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:02.240  1017  1746 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:02.240  1017  1746 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 20:35:02.240  1506  4626 D SIP     : [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
,03-15 20:35:02.240  1695  1695 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-15 20:35:02.250  1017  3015 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:02.250  1017  3015 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
03-15 20:35:02.250  1017  3015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-15 20:35:02.250  1017  1017 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
03-15 20:35:02.250  1017  1400 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.google.android.gms,userId = 0
03-15 20:35:02.250  1017  1400 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.gms
03-15 20:35:02.250  1695  4627 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-15 20:35:02.250  1506  4626 E File    : fail readDirectory() errno=2
03-15 20:35:02.250  1017  3015 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:02.260  1017  3015 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:02.260  1017  3015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 20:35:02.260  1964  1964 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher },
,03-15 20:35:02.260  1017  1531 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,03-15 20:35:02.260  1187  1187 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,03-15 20:35:02.260  1017  1531 W ActivityManager: userId = 0, bbcId = -10000,
03-15 20:35:02.260  1017  1531 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:02.260  1017  1531 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-15 20:35:02.260  1187  1187 D PersonaManager: isKioskContainerExistOnDevice
03-15 20:35:02.260  1187  1187 D PersonaManager: isKioskContainerExistOnDevice
,03-15 20:35:02.260  1187  1187 D PanelView: There is/are notification(s) 
03-15 20:35:02.260  1187  1187 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-15 20:35:02.270  1017  1400 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:02.270  1017  1400 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:02.270  1017  1400 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-15 20:35:02.270  1187  1187 D PersonaManager: isKioskContainerExistOnDevice
,03-15 20:35:02.270  1187  1187 D PanelView: There is/are notification(s) 
03-15 20:35:02.270  1187  1187 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-15 20:35:02.270  1017  1400 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:02.270  1017  1400 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:02.270  1017  1400 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 20:35:02.280  1017  3822 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:02.280  1017  3822 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:02.280  1017  3822 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 20:35:02.280  1017  3822 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:02.280  1017  3822 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:02.280  1017  3822 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 20:35:02.290  4568  4613 W Search.LoginHelper: User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
03-15 20:35:02.290  4568  4613 W Search.LoginHelper: com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
03-15 20:35:02.290  4568  4613 W Search.LoginHelper: 	at com.google.android.gms.auth.b.c(Unknown Source)
03-15 20:35:02.290  4568  4613 W Search.LoginHelper: 	at com.google.android.gms.auth.b.a(Unknown Source)
03-15 20:35:02.290  4568  4613 W Search.LoginHelper: 	at com.google.android.gms.auth.b.a(Unknown Source)
03-15 20:35:02.290  4568  4613 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
03-15 20:35:02.290  4568  4613 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
03-15 20:35:02.290  4568  4613 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
03-15 20:35:02.290  4568  4613 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
03-15 20:35:02.290  4568  4613 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
03-15 20:35:02.290  4568  4613 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
03-15 20:35:02.290  4568  4613 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-15 20:35:02.290  4568  4613 W Search.LoginHelper: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-15 20:35:02.290  4568  4613 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-15 20:35:02.290  4568  4613 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-15 20:35:02.290  4568  4613 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-15 20:35:02.290  4568  4613 W Search.LoginHelper: 	at java.lang.Thread.run(Thread.java:818)
03-15 20:35:02.290  4568  4613 W Search.LoginHelper: 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
,03-15 20:35:02.290  4568  4614 W Search.LoginHelper: User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
03-15 20:35:02.290  4568  4614 W Search.LoginHelper: com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
03-15 20:35:02.290  4568  4614 W Search.LoginHelper: 	at com.google.android.gms.auth.b.c(Unknown Source)
03-15 20:35:02.290  4568  4614 W Search.LoginHelper: 	at com.google.android.gms.auth.b.a(Unknown Source)
03-15 20:35:02.290  4568  4614 W Search.LoginHelper: 	at com.google.android.gms.auth.b.a(Unknown Source)
03-15 20:35:02.290  4568  4614 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
03-15 20:35:02.290  4568  4614 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
03-15 20:35:02.290  4568  4614 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
03-15 20:35:02.290  4568  4614 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
03-15 20:35:02.290  4568  4614 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
03-15 20:35:02.290  4568  4614 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
03-15 20:35:02.290  4568  4614 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-15 20:35:02.290  4568  4614 W Search.LoginHelper: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-15 20:35:02.290  4568  4614 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-15 20:35:02.290  4568  4614 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-15 20:35:02.290  4568  4614 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-15 20:35:02.290  4568  4614 W Search.LoginHelper: 	at java.lang.Thread.run(Thread.java:818)
03-15 20:35:02.290  4568  4614 W Search.LoginHelper: 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
,03-15 20:35:02.340  1187  1187 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : true
,03-15 20:35:02.340  1017  1042 W libprocessgroup: failed to open /acct/uid_10004/pid_1283/cgroup.procs: No such file or directory
,03-15 20:35:02.340  4568  4622 I LibraryLoader: Time to load native libraries: 59 ms (timestamps 9646-9705)
03-15 20:35:02.340  4568  4622 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-15 20:35:02.360  4568  4622 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-15 20:35:02.450  1017  1030 I art     : Explicit concurrent mark sweep GC freed 35336(2MB) AllocSpace objects, 4(84KB) LOS objects, 33% free, 30MB/45MB, paused 2.504ms total 149.362ms
,03-15 20:35:02.450  1017  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 20:35:02.450  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:02.450  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:02.450  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 20:35:02.450  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:35:02.450  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:35:02.450  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:35:02.450  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:35:02.460  4638  4638 E Zygote  : MountEmulatedStorage()
03-15 20:35:02.460  4638  4638 E Zygote  : v2
03-15 20:35:02.460  4638  4638 I libpersona: KNOX_SDCARD checking this for 10012
03-15 20:35:02.460  4638  4638 I libpersona: KNOX_SDCARD not a persona
03-15 20:35:02.460  1017  1030 I ActivityManager: Start proc com.google.android.gms.wearable for service com.google.android.gms/.wearable.service.WearableService: pid=4638 uid=10012 gids={50012, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
03-15 20:35:02.460  4638  4638 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-15 20:35:02.470  1017  1746 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:02.470  1017  1746 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:02.470  1017  1746 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 20:35:02.470  4638  4638 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-15 20:35:02.470  4638  4638 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-15 20:35:02.470  1017  1079 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:02.470  1017  1079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:02.470  1017  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 20:35:02.480  1017  1622 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 20:35:02.480  1017  1622 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:02.480  1017  1622 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:02.480  1017  1622 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 20:35:02.490  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:02.490  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:02.490  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 20:35:02.500  1017  3014 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,03-15 20:35:02.500  1017  3014 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:02.500  1017  3014 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:02.500  1017  3014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 20:35:02.510  4568  4598 W Search.LoginHelper: User recoverable exception for scope: oauth2:https://www.googleapis.com/auth/googlenow
03-15 20:35:02.510  4568  4598 W Search.LoginHelper: com.google.android.gms.auth.e: User intervention required. Notification has been pushed.
03-15 20:35:02.510  4568  4598 W Search.LoginHelper: 	at com.google.android.gms.auth.b.c(Unknown Source)
03-15 20:35:02.510  4568  4598 W Search.LoginHelper: 	at com.google.android.gms.auth.b.a(Unknown Source)
03-15 20:35:02.510  4568  4598 W Search.LoginHelper: 	at com.google.android.gms.auth.b.a(Unknown Source)
03-15 20:35:02.510  4568  4598 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.m.a(GoogleAuthAdapterImpl.java:29)
03-15 20:35:02.510  4568  4598 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.k.a(FallingBackGoogleAuthAdapter.java:93)
03-15 20:35:02.510  4568  4598 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.g.a(CachingGoogleAuthAdapter.java:72)
03-15 20:35:02.510  4568  4598 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.n.b(LoginHelper.java:827)
03-15 20:35:02.510  4568  4598 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.n$5.abo(LoginHelper.java:713)
03-15 20:35:02.510  4568  4598 W Search.LoginHelper: 	at com.google.android.apps.gsa.search.core.d.b.n$5.call(LoginHelper.java:710)
03-15 20:35:02.510  4568  4598 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-15 20:35:02.510  4568  4598 W Search.LoginHelper: 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
03-15 20:35:02.510  4568  4598 W Search.LoginHelper: 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
03-15 20:35:02.510  4568  4598 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
03-15 20:35:02.510  4568  4598 W Search.LoginHelper: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
03-15 20:35:02.510  4568  4598 W Search.LoginHelper: 	at java.lang.Thread.run(Thread.java:818)
03-15 20:35:02.510  4568  4598 W Search.LoginHelper: 	at com.google.android.apps.gsa.shared.util.c.a.m$1.run(GsaThreadFactory.java:99)
,03-15 20:35:02.510  4568  4607 E VelvetNetworkClient: Failed to get auth token
03-15 20:35:02.510  1964  4648 D LocationInitializer: Restart initialization of location
03-15 20:35:02.510  1017  1555 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
03-15 20:35:02.510  4638  4638 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 20:35:02.510  1017  1555 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:02.510  1017  1555 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:02.510  1017  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-15 20:35:02.510  4638  4638 D ActivityThread: Added TimaKeyStore provider
03-15 20:35:02.530  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:02.530  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:02.530  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-15 20:35:02.540  1017  1622 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-15 20:35:02.540  1017  1622 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:02.540  1017  1622 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:02.540  1017  1622 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 20:35:02.550  1017  3823 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,03-15 20:35:02.550  4638  4638 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
03-15 20:35:02.550  4638  4638 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-15 20:35:02.550  1017  3823 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:02.550  1017  3823 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-15 20:35:02.550  1017  3823 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 20:35:02.560  1017  1746 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,03-15 20:35:02.560  1017  1746 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
03-15 20:35:02.560  1017  1746 I splitIntent: other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
03-15 20:35:02.560  1017  1746 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,03-15 20:35:02.560  1695  4656 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-15 20:35:02.560  4568  4622 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-15 20:35:02.570  1695  1695 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-15 20:35:02.580  4638  4638 I MultiDex: VM with version 2.1.0 has multidex support
03-15 20:35:02.580  4638  4638 I MultiDex: install
03-15 20:35:02.580  4638  4638 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,03-15 20:35:02.590  4638  4638 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-15 20:35:02.620   277  1011 D EnterpriseController: uids 10057
03-15 20:35:02.620   277  1011 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-15 20:35:02.620   277  1011 D Netd    : getNetworkForDns: using netid 502 for uid 10057
,03-15 20:35:02.640  4638  4638 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-15 20:35:02.650  4638  4638 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@2635e3a: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-15 20:35:02.650  4638  4638 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,03-15 20:35:02.680  1964  1964 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-15 20:35:02.680  1017  1555 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,03-15 20:35:02.680  1017  1555 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:02.680  1017  1555 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-15 20:35:02.680  1017  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,03-15 20:35:02.700  4638  4638 D WearableService: callingUid 10012, callindPid: 4638
,03-15 20:35:02.710  1017  1141 D SettingsProvider: name = audio_safe_volume_state
03-15 20:35:02.710  3107  3189 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 11 sec
,03-15 20:35:02.710  1017  1359 E Watchdog: !@Sync 1
,03-15 20:35:02.730  1017  1555 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 20:35:02.740  1017  1555 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:02.740  1017  1555 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-15 20:35:02.740  1017  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 20:35:02.750  1017  1622 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,03-15 20:35:02.750  1017  1622 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:02.750  1017  1622 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:02.750  1017  1622 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 20:35:02.750  1964  4667 D LocationInitializer: Restart initialization of location
,03-15 20:35:02.760  1017  3822 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,03-15 20:35:02.760  1017  3822 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:02.760  1017  3822 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:02.760  1017  3822 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 20:35:02.760  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:02.760  1017  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:35:02.760  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 20:35:02.770  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:02.770  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:35:02.770  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 20:35:02.770  1775  4629 E MDM     : [198] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-15 20:35:02.770  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:02.770  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:35:02.770  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 20:35:02.780  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:02.780  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:35:02.780  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 20:35:02.780  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:02.780  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:35:02.780  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 20:35:02.790  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:02.790  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:35:02.790  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 20:35:02.790  1775  4669 E MDM     : [199] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-15 20:35:02.790  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:02.790  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:35:02.790  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 20:35:02.800  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:02.800  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:35:02.800  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 20:35:02.800  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:02.800  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:35:02.800  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 20:35:02.800  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:02.800  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:35:02.800  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 20:35:02.810  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:02.810  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:35:02.810  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 20:35:02.810  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:02.810  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:35:02.810  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 20:35:02.810  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:02.810  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:35:02.810  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 20:35:02.820  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:02.820  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:35:02.820  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 20:35:02.820  1017  1017 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:02.820  1017  1017 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:35:02.820  1017  1017 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 20:35:02.830  1017  3822 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-15 20:35:02.830  1017  3822 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:02.830  1017  3822 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:35:02.830  1017  3822 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-15 20:35:02.830  2351  2351 I Hs20UtilService: Starting #5
03-15 20:35:02.830  1348  1348 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-15 20:35:02.830  2351  2366 I Hs20UtilService: Message received 5007
,03-15 20:35:02.840  1348  1348 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-15 20:35:02.850  1017  1372 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-15 20:35:02.850  1017  1372 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:02.850  1017  1372 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:35:02.850  1017  1372 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-15 20:35:02.850  2351  2351 I Hs20UtilService: Starting #6
,03-15 20:35:02.850  2351  2366 I Hs20UtilService: Message received 5007
,03-15 20:35:02.850  1348  1348 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-15 20:35:02.850  1348  1348 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,03-15 20:35:02.850  1348  1348 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,03-15 20:35:02.850  1348  1348 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
03-15 20:35:02.850  1348  1348 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
,03-15 20:35:02.850  1348  1348 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-15 20:35:02.870  1017  1372 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-15 20:35:02.870  1017  1372 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:02.870  1017  1372 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:35:02.870  1017  1372 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-15 20:35:02.870  2351  2351 I Hs20UtilService: Starting #7
,03-15 20:35:02.870  2351  2366 I Hs20UtilService: Message received 5007
,03-15 20:35:02.880  1348  1348 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-15 20:35:02.880  1348  1348 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-15 20:35:02.890  1017  3015 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,03-15 20:35:02.890  1017  1030 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,03-15 20:35:02.890  1017  1030 D SecContentProvider2: mCursor = null
,03-15 20:35:02.890  1017  1400 D SecContentProvider2: uri = 15 selection = getToastGravity
,03-15 20:35:02.890  1017  1400 D SecContentProvider2: mCursor = null
,03-15 20:35:02.900  1017  1129 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
,03-15 20:35:02.900  1017  1129 D SecContentProvider2: mCursor = null
,03-15 20:35:02.900  1017  3823 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
,03-15 20:35:02.900  1017  3823 D SecContentProvider2: mCursor = null
,03-15 20:35:02.900  1017  1372 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,03-15 20:35:02.900  1017  1372 D SecContentProvider2: mCursor = null
,03-15 20:35:02.900  1017  1622 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
,03-15 20:35:02.900  1017  1622 D SecContentProvider2: mCursor = null
,03-15 20:35:02.920  3436  3436 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,03-15 20:35:02.920  3436  3436 I PCWCLIENTTRACE_PushUtil: sales region : global
03-15 20:35:02.920  3436  3436 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-15 20:35:02.920  3436  3436 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,03-15 20:35:02.920  1017  1029 I splitIntent: intent=android.net.conn.CONNECTIVITY_CHANGE will be not split. because same process=com.google.android.gms is in other queue. index=22
03-15 20:35:02.920  1017  1029 I splitIntent: base  index=22, name=com.google.android.gms com.google.android.gms.gcm.gmsproc.GmsAutoStarter
03-15 20:35:02.920  1017  1029 I splitIntent: other index=24, name=com.google.android.gms com.google.android.gms.common.status.StatusServiceLauncherBroadcastReceiver
03-15 20:35:02.920  1017  1029 I splitIntent: arrangeSplitReceiver return false!! intent : android.net.conn.CONNECTIVITY_CHANGE !! do not split it!!
,03-15 20:35:02.920  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:35:02.920  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:35:02.920  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:35:02.920  1017  1029 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:35:02.930   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=4, Uoast
,03-15 20:35:02.940  4671  4671 E Zygote  : MountEmulatedStorage()
03-15 20:35:02.940  4671  4671 E Zygote  : v2
03-15 20:35:02.940  4671  4671 I libpersona: KNOX_SDCARD checking this for 10111
03-15 20:35:02.940  4671  4671 I libpersona: KNOX_SDCARD not a persona
03-15 20:35:02.940  4671  4671 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-15 20:35:02.940  4671  4671 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-15 20:35:02.940  1017  1029 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=4671 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
03-15 20:35:02.940  4671  4671 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,03-15 20:35:02.960  1017  3754 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017
,03-15 20:35:02.960  1017  1050 D DisplayPowerController: getFinalBrightness : Summary is 32 -> 32
03-15 20:35:02.960  1017  1050 D DisplayPowerController: animation target = 32, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
03-15 20:35:02.960  1017  1050 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,03-15 20:35:02.960  1187  1187 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-15 20:35:02.970  4671  4671 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 20:35:02.970  4671  4671 D ActivityThread: Added TimaKeyStore provider
,03-15 20:35:02.970  1017  1050 D DisplayPowerController: getFinalBrightness : Summary is 32 -> 32
03-15 20:35:02.970  1017  1161 D lights  : lcd : 32 +
,03-15 20:35:02.970  1017  1050 D DisplayPowerController: animation target = 32, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-15 20:35:02.990  1017  1161 D lights  : lcd : 32 -
,03-15 20:35:02.990  1017  1050 D DisplayPowerController: getFinalBrightness : Summary is 32 -> 32
,03-15 20:35:02.990  1017  1050 D DisplayPowerController: animation target = 32, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-15 20:35:03.200  1017  1400 I ActivityManager: Killing 3782:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,03-15 20:35:03.220  4671  4671 I MusicStore: Database version: 120
,03-15 20:35:03.290  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,03-15 20:35:03.290  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:03.290  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:03.290  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-15 20:35:03.290  1017  1043 I ActivityManager: Waited long enough for: ServiceRecord{294f55f5 u0 com.samsung.android.providers.context/.ContextService}
,03-15 20:35:03.310  1017  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3782/cgroup.procs: No such file or directory
,03-15 20:35:03.320   256   514 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-15 20:35:03.320   256   514 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 20:35:03.330  4671  4671 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-15 20:35:03.350  1017  1341 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,03-15 20:35:03.360  1017  1341 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:03.360  1017  1341 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:03.360  1017  1341 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-15 20:35:03.400   256   514 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-15 20:35:03.400   256   514 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 20:35:03.400  4671  4671 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-15 20:35:03.400   256   514 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-15 20:35:03.400   256   514 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 20:35:03.400  4671  4671 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-15 20:35:03.410  1017  1102 V AlarmManager: waitForAlarm result :4
,03-15 20:35:03.420  1017  1043 I ActivityManager: Waited long enough for: ServiceRecord{17dcda18 u0 com.android.settings/.wifi.WifiCredService}
,03-15 20:35:03.430  4671  4671 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-15 20:35:03.430  4671  4671 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-15 20:35:03.460  4671  4671 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 227 native methods...
,03-15 20:35:03.520  4671  4671 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-15 20:35:03.520  4671  4671 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@afb07f9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,03-15 20:35:03.520  4671  4671 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
03-15 20:35:03.520  4671  4671 D AndroidMusic: GMSCore installation verified
,03-15 20:35:03.530  4671  4671 I ConfigStore: Config Database version: 1
,03-15 20:35:03.600  1017  3014 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,03-15 20:35:03.610  1017  3014 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:03.610  1017  3014 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:03.610  1017  3014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-15 20:35:03.620  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,03-15 20:35:03.620  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:03.620  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:03.620  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-15 20:35:03.640  1017  1079 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-15 20:35:03.640  1017  3015 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-15 20:35:03.650  1017  1029 I AudioService: getStreamVolume 3 index 0
,03-15 20:35:03.650  4671  4671 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,03-15 20:35:03.660  4671  4671 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,03-15 20:35:03.670  4671  4671 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true,
,03-15 20:35:03.700  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,03-15 20:35:03.700  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:03.700  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:03.700  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-15 20:35:03.700  1017  3015 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,03-15 20:35:03.710  1017  3015 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:03.710  1017  3015 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:03.710  1017  3015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-15 20:35:03.710  1017  1400 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,03-15 20:35:03.710  1017  1400 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:03.710  1017  1400 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:03.710  1017  1400 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-15 20:35:03.710  3107  3189 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 12 sec
,03-15 20:35:03.720  1017  1746 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-15 20:35:03.720  4671  4671 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-15 20:35:03.730  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:35:03.730  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:35:03.730  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:35:03.730  1017  1017 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:35:03.740  4702  4702 E Zygote  : MountEmulatedStorage(),
03-15 20:35:03.740  4702  4702 E Zygote  : v2
,03-15 20:35:03.740  1017  1017 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=4702 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-15 20:35:03.740  4702  4702 I libpersona: KNOX_SDCARD checking this for 10002
03-15 20:35:03.740  4702  4702 I libpersona: KNOX_SDCARD not a persona,
,03-15 20:35:03.740  4702  4702 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-15 20:35:03.750  4702  4702 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-15 20:35:03.750  4702  4702 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-15 20:35:03.770   315   315 I art     : Explicit concurrent mark sweep GC freed 8684(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 642us total 24.514ms
,03-15 20:35:03.780  4702  4702 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 20:35:03.780  4702  4702 D ActivityThread: Added TimaKeyStore provider
,03-15 20:35:03.780  4671  4671 I GHttpClientFactory: Using our fixed implementation of GMSCore's GoogleHttpClient
,03-15 20:35:03.780   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 626us total 16.924ms
,03-15 20:35:03.790  1017  1400 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,03-15 20:35:03.790  1017  1400 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:03.790  1017  1400 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-15 20:35:03.790  1017  1400 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,03-15 20:35:03.800  4671  4671 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory,
03-15 20:35:03.800  1017  3015 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-15 20:35:03.800  1017  3015 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:03.800  1017  3015 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
03-15 20:35:03.800  1017  3015 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,03-15 20:35:03.800  1017  3822 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,03-15 20:35:03.800   315   315 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 620us total 16.980ms
,03-15 20:35:03.800  1017  3822 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:03.800  1017  3822 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:03.800  1017  3822 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-15 20:35:03.830  1017  1372 I ActivityManager: Killing 3759:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,03-15 20:35:03.860  1017  1129 I ActivityManager: Killing 3794:com.android.calendar/u0a135 (adj 15): empty #31
,03-15 20:35:03.860  1017  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:35:03.860  1017  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:35:03.860  1017  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:35:03.860  1017  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:35:03.880  4721  4721 E Zygote  : MountEmulatedStorage()
,03-15 20:35:03.880  4721  4721 E Zygote  : v2
03-15 20:35:03.880  4721  4721 I libpersona: KNOX_SDCARD checking this for 1000
03-15 20:35:03.880  4721  4721 I libpersona: KNOX_SDCARD not a persona
,03-15 20:35:03.880  4721  4721 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-15 20:35:03.880  4721  4721 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-15 20:35:03.880  4721  4721 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 20:35:03.880  1017  1129 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=4721 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-15 20:35:03.900  1017  1059 D PackageManager: [MSG] SEND_PENDING_BROADCAST
,03-15 20:35:03.900  4721  4721 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 20:35:03.900  4721  4721 D ActivityThread: Added TimaKeyStore provider
,03-15 20:35:03.920  1017  1105 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-15 20:35:03.920  3598  3598 I PageBuddyNotiSvc: mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
,03-15 20:35:03.940  1488  1488 D RegisteredComponentCache: Collect Tech packages for Knox
,03-15 20:35:03.940  1488  1488 D PersonaManager: isKioskContainerExistOnDevice
,03-15 20:35:03.950  1488  1488 D PersonaManager: isKioskContainerExistOnDevice
,03-15 20:35:03.960  1488  1488 D RegisteredServicesCache: empty dynamic service
,03-15 20:35:03.980  4721  4721 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,03-15 20:35:03.990  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 20:35:03.990  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 20:35:03.990  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 20:35:04.000  1017  1030 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
03-15 20:35:04.000  1017  1030 D SecContentProvider2: mCursor = null
,03-15 20:35:04.000  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 20:35:04.060  1528  1528 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-15 20:35:04.070  1528  1528 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,03-15 20:35:04.100  4721  4721 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,03-15 20:35:04.110  1017  1042 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,03-15 20:35:04.110  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 20:35:04.110  1017  1017 W IntentResolver: resolveIntent: multiple matches, only some with CATEGORY_DEFAULT
,03-15 20:35:04.110  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 20:35:04.110  4721  4721 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,03-15 20:35:04.110  4721  4721 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
03-15 20:35:04.110  4721  4721 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
03-15 20:35:04.110  4721  4721 I DIAGMON_AGENT: ./extraInfo: "NG700"
03-15 20:35:04.110  4721  4721 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
03-15 20:35:04.120  1017  1017 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
03-15 20:35:04.120  1017  1017 I BackupManagerService: Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
03-15 20:35:04.120  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 20:35:04.120  1017  1017 I BackupManagerService: Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
03-15 20:35:04.120  1017  1042 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-15 20:35:04.120  1017  1042 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 20:35:04.120  1017  1042 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 20:35:04.120  1017  1017 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.backup.BackupTransportService; callingUser = 0; userId(target) = 0
,03-15 20:35:04.120  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 20:35:04.140  1017  1017 V BackupManagerService: Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,03-15 20:35:04.140  1017  1017 V BackupManagerService: Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3c6ea48c
,03-15 20:35:04.150  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 20:35:04.150  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 20:35:04.150  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-15 20:35:04.150  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-15 20:35:04.150  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 20:35:04.160  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-15 20:35:04.160  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-15 20:35:04.160  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
03-15 20:35:04.160  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,03-15 20:35:04.160  1017  1042 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,03-15 20:35:04.170  1017  1042 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,03-15 20:35:04.180  1017  1042 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,03-15 20:35:04.180  1017  1042 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,03-15 20:35:04.180  1017  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3759/cgroup.procs: No such file or directory
03-15 20:35:04.180  1017  1042 D LocationProviderProxy: applying state to connected service
03-15 20:35:04.180  1017  1042 W libprocessgroup: failed to open /acct/uid_10135/pid_3794/cgroup.procs: No such file or directory
,03-15 20:35:04.200  4312  4321 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-15 20:35:04.200  4312  4321 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-15 20:35:04.200  4312  4321 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-15 20:35:04.200  4312  4320 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-15 20:35:04.200  4312  4320 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-15 20:35:04.210  4312  4320 I DBG_POLICYDM: [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
,03-15 20:35:04.210  1017  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:35:04.210  1017  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:35:04.210  1017  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,03-15 20:35:04.210  1017  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:35:04.220  4739  4739 E Zygote  : MountEmulatedStorage()
,03-15 20:35:04.220  4739  4739 E Zygote  : v2
03-15 20:35:04.220  4739  4739 I libpersona: KNOX_SDCARD checking this for 10009
03-15 20:35:04.220  4739  4739 I libpersona: KNOX_SDCARD not a persona
,03-15 20:35:04.230  1017  1129 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=4739 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-15 20:35:04.230  4739  4739 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-15 20:35:04.230  4739  4739 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-15 20:35:04.230  4739  4739 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
,03-15 20:35:04.240  1187  1187 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-15 20:35:04.240  1187  1187 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-15 20:35:04.240  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 20:35:04.240  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 20:35:04.240  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 20:35:04.240  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 20:35:04.250  4739  4739 D TimaKeyStoreProvider: TimaSignature is unavailable,
,03-15 20:35:04.250  4739  4739 D ActivityThread: Added TimaKeyStore provider
,03-15 20:35:04.320  1017  1746 I ActivityManager: Killing 3884:com.sec.android.app.camera/u0a139 (adj 15): empty #31
,03-15 20:35:04.320  4739  4739 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...,
,03-15 20:35:04.330  4739  4739 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-15 20:35:04.330  1017  1030 I ActivityManager: Killing 3916:com.sec.android.app.bluetoothtest/1000 (adj 15): empty #31
,03-15 20:35:04.340  3676  3676 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Mar 15 20:35:04 GMT+01:00 2016
,03-15 20:35:04.340  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,03-15 20:35:04.340  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:04.340  1017  1029 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:35:04.340  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-15 20:35:04.350  3676  3676 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,03-15 20:35:04.350  3676  3676 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,03-15 20:35:04.350  3676  3676 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-15 20:35:04.360  3676  3676 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-15 20:35:04.360  3676  4756 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,03-15 20:35:04.360  4312  4312 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,03-15 20:35:04.370  3676  4756 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,03-15 20:35:04.370  4312  4757 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-15 20:35:04.370  4341  4341 I SA      : [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOE6 PSS = 4.978878039476607  ]
,03-15 20:35:04.370  4341  4341 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
03-15 20:35:04.370  4341  4341 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,03-15 20:35:04.370  4312  4757 I DBG_POLICYDM: [com.policydm.XDMApplication(429/isNetworkChanged)] a previous network is 0, current network is 2
,03-15 20:35:04.370  4341  4341 I SA      : [SLFUCHKMGR] constructor called
,03-15 20:35:04.380  3676  4756 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,03-15 20:35:04.380  3676  4756 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().START
,03-15 20:35:04.380  3676  4756 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().START 
,03-15 20:35:04.380  4312  4757 E DBG_POLICYDM: [com.policydm.XDMApplication(431/isNetworkChanged)] network changed.... 
,03-15 20:35:04.380  4341  4341 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
03-15 20:35:04.380  4341  4341 I SA      : [OR] == isSIMCardReady false ==
,03-15 20:35:04.380  4341  4341 I SA      : [SCU] == networkStateCheck == true
,03-15 20:35:04.380  4341  4341 I SA      : [DM] getCountryCodeFromCSC : PL
03-15 20:35:04.380  4341  4341 I SA      : isChinaCountryCode : false
03-15 20:35:04.380  4341  4341 I SA      : [SCU] is ChinestModel Data Restricted   : false
03-15 20:35:04.380  4341  4341 I SA      : [OR] == networkStateCheck true ==
,03-15 20:35:04.390  4341  4341 I SA      : [OR] GetMyCountryZoneTask
,03-15 20:35:04.390  4341  4341 I SA      : [OR] onReceive END
,03-15 20:35:04.390  4312  4757 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,03-15 20:35:04.390  1248  1248 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
03-15 20:35:04.390  4341  4759 I SA      : [SRS] prepareGetMyCountryZone
,03-15 20:35:04.400  1017  1341 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,03-15 20:35:04.400  1017  1341 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:04.400  1017  1341 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:35:04.400  1017  1341 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-15 20:35:04.400  4341  4759 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,03-15 20:35:04.400  3676  4756 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().END 
,03-15 20:35:04.400  4341  4759 I SA      : [SSP] query invoked
,03-15 20:35:04.400  3676  4756 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,03-15 20:35:04.410  3676  3676 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,03-15 20:35:04.410  4341  4759 I SA      : [TPMU] GetMccFromDB : null
03-15 20:35:04.410  4341  4759 I SA      : [SCU] getMccFromPreferece mcc = 260
,03-15 20:35:04.410  4341  4759 I SA      : [TPM] isNoProxy(default) : true
,03-15 20:35:04.410  4312  4757 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-15 20:35:04.410  1641  1641 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,03-15 20:35:04.410  4312  4757 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-15 20:35:04.410  1017  1042 W libprocessgroup: failed to open /acct/uid_10139/pid_3884/cgroup.procs: No such file or directory
03-15 20:35:04.410  1017  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3916/cgroup.procs: No such file or directory
,03-15 20:35:04.410  4312  4757 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,03-15 20:35:04.410  4312  4757 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-15 20:35:04.410  4312  4757 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-15 20:35:04.420  4312  4757 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-15 20:35:04.420  4312  4757 I DBG_POLICYDM: [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-15 20:35:04.420  4312  4757 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,03-15 20:35:04.420  4312  4757 I DBG_POLICYDM: [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,03-15 20:35:04.420  1323  1334 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 3
,03-15 20:35:04.420  1017  1622 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
,03-15 20:35:04.420  4341  4759 E File    : fail readDirectory() errno=2
,03-15 20:35:04.430  1017  1622 D SecContentProvider2: mCursor = null
03-15 20:35:04.430  1641  1641 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
03-15 20:35:04.430  1641  1641 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
,03-15 20:35:04.430  1641  1641 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
03-15 20:35:04.430  1641  1641 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,03-15 20:35:04.430  4312  4757 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(36/xdbGetSpdDeviceRegister)] Device is Registered
,03-15 20:35:04.430  1641  1641 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,03-15 20:35:04.440  1641  1641 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,03-15 20:35:04.440  1017  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:35:04.440  1017  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:35:04.440  1017  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:35:04.440  1017  1079 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:35:04.440  4312  4757 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-15 20:35:04.450  4312  4757 I DBG_POLICYDM: [com.policydm.db.XDB(2176/xdbGetWaitWifiFlag)] bWaitWifi : false
,03-15 20:35:04.450  4762  4762 E Zygote  : MountEmulatedStorage()
,03-15 20:35:04.450  4762  4762 E Zygote  : v2
03-15 20:35:04.450  4762  4762 I libpersona: KNOX_SDCARD checking this for 10125
03-15 20:35:04.450  4762  4762 I libpersona: KNOX_SDCARD not a persona
,03-15 20:35:04.450  4762  4762 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-15 20:35:04.460  1017  1079 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4762 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,03-15 20:35:04.460  4762  4762 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-15 20:35:04.460  4762  4762 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 20:35:04.480  4762  4762 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 20:35:04.480  4762  4762 D ActivityThread: Added TimaKeyStore provider
,03-15 20:35:04.490  4762  4762 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-15 20:35:04.490  4762  4762 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-15 20:35:04.490  4762  4762 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-15 20:35:04.520  4762  4762 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,03-15 20:35:04.520  4762  4762 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,03-15 20:35:04.520  4762  4762 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,03-15 20:35:04.520  1017  3014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:35:04.530  1017  3014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:35:04.530  1017  3014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:35:04.530  1017  3014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:35:04.540  4777  4777 E Zygote  : MountEmulatedStorage()
03-15 20:35:04.540  4777  4777 I libpersona: KNOX_SDCARD checking this for 10145
03-15 20:35:04.540  4777  4777 E Zygote  : v2
03-15 20:35:04.540  4777  4777 I libpersona: KNOX_SDCARD not a persona
03-15 20:35:04.540  4777  4777 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
03-15 20:35:04.540  1017  3014 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=4777 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
03-15 20:35:04.540  1017  3014 I ActivityManager: Killing 3954:com.sec.knox.bridge/1000 (adj 15): empty #31
,03-15 20:35:04.550  4777  4777 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-15 20:35:04.550  4777  4777 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 20:35:04.560  4777  4777 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 20:35:04.570  4777  4777 D ActivityThread: Added TimaKeyStore provider
,03-15 20:35:04.590  4777  4777 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-15 20:35:04.590  4777  4777 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 20:35:04.590  4777  4777 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-15 20:35:04.590  4777  4777 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 20:35:04.590  4777  4777 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-15 20:35:04.660  1017  1029 D RCPManagerService: exchangeData() failure , invalid userId
,03-15 20:35:04.660  1017  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_3954/cgroup.procs: No such file or directory
,03-15 20:35:04.670  1017  1030 D RCPManagerService: exchangeData() failure , invalid userId,
,03-15 20:35:04.670  1017  1129 D RCPManagerService: exchangeData() failure , invalid userId
,03-15 20:35:04.680  1017  1622 D RCPManagerService: exchangeData() failure , invalid userId
,03-15 20:35:04.710  1017  1341 D RCPManagerService: exchangeData() failure , invalid userId
,03-15 20:35:04.710  4005  4021 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,03-15 20:35:04.720  1017  1129 D RCPManagerService: exchangeData() failure , invalid userId
,03-15 20:35:04.720  3107  3189 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 13 sec
,03-15 20:35:04.720  1017  1129 D RCPManagerService: exchangeData() failure , invalid userId
,03-15 20:35:04.730  1017  1400 D RCPManagerService: exchangeData() failure , invalid userId
,03-15 20:35:04.740  4109  4109 D SecurityLogAgent: KnoxConfiguration : Current State = 1,
03-15 20:35:04.740  4109  4109 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-15 20:35:04.740  4109  4109 D SecurityLogAgent: StateMachine : Current State = 1
,03-15 20:35:04.740  4109  4109 D SecurityLogAgent: StateMachine : Changed Current State = 1
,03-15 20:35:04.750  1017  3754 I ActivityManager: Killing 3937:com.vlingo.midas/u0a31 (adj 15): empty #31
,03-15 20:35:04.760  1528  1528 D Launcher.Model: reloadBadges entered.
03-15 20:35:04.760  4005  4019 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
03-15 20:35:04.760  4005  4019 D BadgeProvider: sendNotify, [notify] : null
03-15 20:35:04.760  4005  4019 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
03-15 20:35:04.760  4005  4019 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-15 20:35:04.760  4005  4019 D BadgeProvider: update, [UpdateCount] : 1
,03-15 20:35:04.780  1017  3823 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,03-15 20:35:04.780  1017  3823 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:04.780  1017  3823 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:04.780  1017  3823 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 20:35:04.820  1964  4803 I iu.SyncManager: SYNC; picasa accounts
,03-15 20:35:04.820  1017  1042 W libprocessgroup: failed to open /acct/uid_10031/pid_3937/cgroup.procs: No such file or directory
,03-15 20:35:04.840  1964  1964 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,03-15 20:35:04.840  1964  1964 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,03-15 20:35:04.860  1017  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.snet.SnetAlarmService; callingUser = 0; userId(target) = 0
,03-15 20:35:04.860  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:04.860  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:04.860  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 20:35:04.870  1964  4803 I iu.UploadsManager: num queued entries: 0
,03-15 20:35:04.870  1964  4803 I iu.UploadsManager: num updated entries: 0
,03-15 20:35:04.870  1964  4803 I iu.SyncManager: NEXT; no task
,03-15 20:35:04.870  1964  1964 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,03-15 20:35:04.870  1964  1964 I Kids    : [GCoreUtils] Current gmscore version, 7899436 is smaller than the required version 8400000
,03-15 20:35:04.890  1017  1029 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,03-15 20:35:04.890  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:04.890  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:04.890  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-15 20:35:04.910  1017  1746 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.service.NetworkConnectionCheckingService; callingUser = 0; userId(target) = 0
,03-15 20:35:04.910  1017  1746 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:04.910  4295  4295 E SPPClientService: [SystemStateMoniter] Action Name : android.net.conn.CONNECTIVITY_CHANGE
,03-15 20:35:04.910  4295  4295 E SPPClientService: [SystemStateMoniter] Current Time : 52275
03-15 20:35:04.910  1017  1746 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-15 20:35:04.910  1017  1746 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-15 20:35:04.920  4295  4295 E SPPClientService: [SystemStateMoniter] No Connect : false
,03-15 20:35:04.920  1017  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:35:04.920  1695  3826 I art     : Explicit concurrent mark sweep GC freed 11436(611KB) AllocSpace objects, 3(108KB) LOS objects, 40% free, 10MB/17MB, paused 1.164ms total 42.202ms
,03-15 20:35:04.930  1017  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:35:04.930  1017  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:35:04.930  1017  1555 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:35:04.930  3860  4805 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
03-15 20:35:04.930  3860  4805 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
03-15 20:35:04.930  3860  4805 I System.out: (HTTPLog)-Static: isShipBuild true
03-15 20:35:04.930  3860  4805 I System.out: (HTTPLog)-Thread-566-268097220: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-15 20:35:04.930  3860  4805 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,03-15 20:35:04.930   277  1011 D EnterpriseController: uids 10104
03-15 20:35:04.930   277  1011 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-15 20:35:04.930   277  1011 D Netd    : getNetworkForDns: using netid 502 for uid 10104
,03-15 20:35:04.940  4810  4810 E Zygote  : MountEmulatedStorage()
,03-15 20:35:04.940  4810  4810 I libpersona: KNOX_SDCARD checking this for 10113
03-15 20:35:04.940  4810  4810 E Zygote  : v2
03-15 20:35:04.940  4810  4810 I libpersona: KNOX_SDCARD not a persona
03-15 20:35:04.940  4810  4810 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-15 20:35:04.940  1017  1555 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4810 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 20:35:04.950  1017  1622 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
03-15 20:35:04.950  1017  1622 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
03-15 20:35:04.950  4810  4810 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-15 20:35:04.950  1017  1372 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,03-15 20:35:04.950  4810  4810 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-15 20:35:04.950  1017  1341 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,03-15 20:35:04.970  4810  4810 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 20:35:04.970  4810  4810 D ActivityThread: Added TimaKeyStore provider
,03-15 20:35:05.020  3860  4805 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,03-15 20:35:05.070  4341  4759 I SA      : [RC New] Execute method=[GET] start
,03-15 20:35:05.090   256   514 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
03-15 20:35:05.090   256   514 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 20:35:05.090  4810  4828 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,03-15 20:35:05.090   256   514 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
03-15 20:35:05.090   256   514 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 20:35:05.090  4810  4828 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,03-15 20:35:05.100  4810  4810 I GAv4    : Google Analytics 7.5.71 is starting up. To enable debug logging on a device run:
03-15 20:35:05.100  4810  4810 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
03-15 20:35:05.100  4810  4810 I GAv4    :   adb logcat -s GAv4
,03-15 20:35:05.110   256   514 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
03-15 20:35:05.110   256   514 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 20:35:05.110  4810  4829 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,03-15 20:35:05.110  4341  4759 I SA      : [RC New] Security=[true]
,03-15 20:35:05.110  4341  4759 I System.out: Thread-675(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-15 20:35:05.110  4341  4759 I System.out: Thread-675(ApacheHTTPLog):isSBSettingEnabled false
03-15 20:35:05.110  4341  4759 I System.out: Thread-675(ApacheHTTPLog):isShipBuild true
03-15 20:35:05.110  4341  4759 I System.out: Thread-675(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-15 20:35:05.110  4341  4759 I System.out: Thread-675(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-15 20:35:05.110   277  1011 D EnterpriseController: uids 10041
03-15 20:35:05.110   277  1011 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-15 20:35:05.110   277  1011 D Netd    : getNetworkForDns: using netid 502 for uid 10041
,03-15 20:35:05.110   256   514 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
03-15 20:35:05.110   256   514 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 20:35:05.110  4810  4829 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,03-15 20:35:05.120  4810  4810 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,03-15 20:35:05.130  4810  4810 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,03-15 20:35:05.140  4810  4832 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,03-15 20:35:05.190  3860  4805 I Babel   : connection state changed from UNKNOWN to CONNECTED,
,03-15 20:35:05.220   291   291 E SMD     : DCD OFF
,03-15 20:35:05.240  1187  1187 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,03-15 20:35:05.240  1187  1187 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,03-15 20:35:05.240  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 20:35:05.240  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 20:35:05.240  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 20:35:05.240  1187  1187 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 20:35:05.280  1017  1129 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 20:35:05.280  1017  1129 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:05.280  1017  1129 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-15 20:35:05.280  1017  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,03-15 20:35:05.300  4810  4810 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 240311700)
,03-15 20:35:05.310  4810  4810 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 2675-2676)
,03-15 20:35:05.310  4810  4810 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-15 20:35:05.320  4810  4810 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {12525ac7}
,03-15 20:35:05.320  4810  4810 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-15 20:35:05.320  4810  4810 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,03-15 20:35:05.330  4810  4810 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-15 20:35:05.330  4810  4810 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-15 20:35:05.330  4810  4810 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-15 20:35:05.350  4810  4810 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-15 20:35:05.350  4810  4810 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-15 20:35:05.350  4810  4810 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,03-15 20:35:05.350  4810  4810 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-15 20:35:05.350  4810  4810 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-15 20:35:05.350  4810  4810 I Adreno-EGL: Build Date: 04/06/15 Mon
03-15 20:35:05.350  4810  4810 I Adreno-EGL: Local Branch: 
03-15 20:35:05.350  4810  4810 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-15 20:35:05.350  4810  4810 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-15 20:35:05.350  4810  4810 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-15 20:35:05.410  4810  4810 I NSApplication: Starting up...
,03-15 20:35:05.410  4810  4860 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-15 20:35:05.420  1017  1746 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:35:05.420  1017  1746 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:35:05.420  1017  1746 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:35:05.420  1017  1746 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:35:05.440  4865  4865 E Zygote  : MountEmulatedStorage(),
03-15 20:35:05.440  4865  4865 E Zygote  : v2
03-15 20:35:05.440  1017  1746 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=4865 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
03-15 20:35:05.440  4865  4865 I libpersona: KNOX_SDCARD checking this for 10081
03-15 20:35:05.440  4865  4865 I libpersona: KNOX_SDCARD not a persona
,03-15 20:35:05.440  4865  4865 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-15 20:35:05.440  1017  1746 I ActivityManager: Killing 4092:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,03-15 20:35:05.440  4865  4865 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-15 20:35:05.450  4865  4865 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,03-15 20:35:05.470  4865  4865 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 20:35:05.470  4865  4865 D ActivityThread: Added TimaKeyStore provider
,03-15 20:35:05.550  1017  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_4092/cgroup.procs: No such file or directory
,03-15 20:35:05.720  3107  3189 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 14 sec
,03-15 20:35:05.780  1017  1341 I art     : Explicit concurrent mark sweep GC freed 35434(2MB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 30MB/45MB, paused 2.456ms total 142.920ms
,03-15 20:35:05.780  1017  1341 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,03-15 20:35:05.790  1017  1341 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:05.790  1017  1341 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:05.790  1017  1341 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-15 20:35:05.800  4474  4500 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-15 20:35:05.820  1017  3014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:35:05.820  1017  3014 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:35:05.820  1017  3014 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:35:05.820  1017  3014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:35:05.840  4883  4883 E Zygote  : MountEmulatedStorage(),
03-15 20:35:05.840  4883  4883 E Zygote  : v2
03-15 20:35:05.840  4883  4883 I libpersona: KNOX_SDCARD checking this for 10120
03-15 20:35:05.840  4883  4883 I libpersona: KNOX_SDCARD not a persona
,03-15 20:35:05.840  4883  4883 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-15 20:35:05.840  4883  4883 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
,03-15 20:35:05.840  4883  4883 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-15 20:35:05.850  1017  3014 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=4883 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-15 20:35:05.850  1017  3014 I ActivityManager: Killing 4128:com.samsung.android.provider.shootingmodeprovider/u0a152 (adj 15): empty #31
,03-15 20:35:05.870  4883  4883 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 20:35:05.870  4883  4883 D ActivityThread: Added TimaKeyStore provider
,03-15 20:35:05.890  4883  4883 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-15 20:35:06.000  1017  1042 W libprocessgroup: failed to open /acct/uid_10152/pid_4128/cgroup.procs: No such file or directory
,03-15 20:35:06.030  1017  1040 D SensorService: [SO] 0.172 0.402 10.209
,03-15 20:35:06.030  4341  4759 I SA      : [RC New] [v2liruge] api execute + 925
03-15 20:35:06.030  4341  4759 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,03-15 20:35:06.030  4341  4759 I System.out: AsyncTask #1 calls detatch()
,03-15 20:35:06.060  4341  4759 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,03-15 20:35:06.080  4341  4759 I SA      : [OCP] update openData : PL
,03-15 20:35:06.090  4341  4759 I SA      : [TPMU] getNetworkMcc : 
,03-15 20:35:06.090  4341  4759 I SA      : [SCU] saveMccToPreferece Start
03-15 20:35:06.090  4341  4759 I SA      : [SCU] RegionMCC : 260
03-15 20:35:06.090  4341  4759 I SA      : [SSP] query invoked
,03-15 20:35:06.100  4341  4759 I SA      : [TPMU] GetMccFromDB : null
,03-15 20:35:06.100  4341  4759 I SA      : [SCU] getMccFromPreferece mcc = 260
,03-15 20:35:06.100  4341  4759 I SA      : [SCU] saveMccToPreferece End
,03-15 20:35:06.100  4341  4759 I SA      : [RC New] executeRequest [v2liruge] end. 1031
03-15 20:35:06.100  4341  4759 I SA      : [RC New] Execute end
,03-15 20:35:06.100  4341  4341 I SA      : [OR] GetMyCountryZoneTask mcc = 260
03-15 20:35:06.100  4341  4341 I SA      : [OR] GetMyCountryZoneTask Success
,03-15 20:35:06.140  1017  1050 D PowerManagerService: [s] UserActivityState : 2 -> 4
,03-15 20:35:06.150  1017  1050 I PowerManagerService: [PWL] On : 0 (53510 ms ago)
,03-15 20:35:06.150  1017  1050 I PowerManagerService: [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x4
,03-15 20:35:06.150  1017  1050 I PowerManagerService: [PWL]  SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1017, ws=WorkSource{10054}) (elapsedTime=3191)
,03-15 20:35:06.260  1017  1059 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,03-15 20:35:06.300   327   327 I ServiceManager: Waiting for service AtCmdFwd...,
,03-15 20:35:06.380  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:35:06.380  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:35:06.380  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:35:06.380  1017  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:35:06.390  4904  4904 E Zygote  : MountEmulatedStorage()
03-15 20:35:06.390  4904  4904 E Zygote  : v2
03-15 20:35:06.400  4904  4904 I libpersona: KNOX_SDCARD checking this for 10010
03-15 20:35:06.400  4904  4904 I libpersona: KNOX_SDCARD not a persona
,03-15 20:35:06.400  4904  4904 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27,
,03-15 20:35:06.400  4904  4904 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027,
03-15 20:35:06.400  4904  4904 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-15 20:35:06.410  1017  1030 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=4904 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-15 20:35:06.410  1017  1030 I ActivityManager: Killing 4163:com.sec.modem.settings/1000 (adj 15): empty #31
,03-15 20:35:06.420  1017  1341 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1017) eventTime = 53785
,03-15 20:35:06.420  1017  1341 D PowerManagerService: [s] UserActivityState : 4 -> 1
03-15 20:35:06.420  1017  1341 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1017 (0x0)
03-15 20:35:06.420  1017  1341 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1017, ws=WorkSource{10054}) (elapsedTime=3465)
,03-15 20:35:06.430  4904  4904 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 20:35:06.430  4904  4904 D ActivityThread: Added TimaKeyStore provider
,03-15 20:35:06.520  1017  1042 W libprocessgroup: failed to open /acct/uid_1000/pid_4163/cgroup.procs: No such file or directory
,03-15 20:35:06.580  4904  4904 D WaitQueueForNetworkActivate: notifyNetworkActivated
,03-15 20:35:06.660  4904  4904 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,03-15 20:35:06.660  1017  3823 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 20:35:06.660  1017  3823 W ActivityManager: Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,03-15 20:35:06.730  3107  3189 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 15 sec
,03-15 20:35:06.730  4514  4565 I System.out: Thread-705(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,03-15 20:35:06.730  4514  4565 I System.out: Thread-705(ApacheHTTPLog):isSBSettingEnabled false
03-15 20:35:06.730  4514  4565 I System.out: Thread-705(ApacheHTTPLog):isShipBuild true
03-15 20:35:06.730  4514  4565 I System.out: Thread-705(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-15 20:35:06.730  4514  4565 I System.out: Thread-705(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-15 20:35:06.730   277  1011 D EnterpriseController: uids 10092
03-15 20:35:06.730   277  1011 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-15 20:35:06.730   277  1011 D Netd    : getNetworkForDns: using netid 502 for uid 10092
,03-15 20:35:06.810  1017  1555 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,03-15 20:35:06.810  1017  1555 W ActivityManager: userId = 0, bbcId = -10000,
03-15 20:35:06.810  1017  1555 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
03-15 20:35:06.810  1017  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,03-15 20:35:06.810  1017  1372 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:06.810  1017  1372 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:35:06.810  1017  1372 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,03-15 20:35:06.820  4904  4904 D hcjo    : AutoUpdateManager:IDLE:execute
,03-15 20:35:06.830  1017  3823 D ActivityManager: retrieveServiceLocked(): component = com.android.contacts/com.samsung.contacts.sim.MakeSimDBService; callingUser = 0; userId(target) = 0
03-15 20:35:06.830  4904  4904 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,03-15 20:35:06.830  4904  4904 D InitializeManagerStateMachine: exit::IDLE
03-15 20:35:06.830  4904  4904 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,03-15 20:35:06.830  1017  1102 V AlarmManager: waitForAlarm result :8
03-15 20:35:06.830  1017  3823 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:06.830  1017  3823 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:35:06.830  1017  3823 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,03-15 20:35:06.830  1017  1102 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 20:35:06.830  4904  4904 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
,03-15 20:35:06.830  4904  4904 D InitializeManagerStateMachine: exit::NETWORK_CHECK
03-15 20:35:06.830  4904  4904 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
03-15 20:35:06.830  4904  4904 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,03-15 20:35:06.840  4904  4904 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
03-15 20:35:06.840  4904  4904 D InitializeManagerStateMachine: entry::SUCCESS
03-15 20:35:06.840  4904  4904 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,03-15 20:35:06.840  1017  1129 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:06.840  1017  1129 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:06.840  1017  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 20:35:06.840  1017  1079 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,03-15 20:35:06.840  1017  1079 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:06.840  1017  1079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:06.840  1017  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 20:35:06.850  1017  1129 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
03-15 20:35:06.850  1017  1129 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.subscribedfeeds.ConfigurationReceiver
03-15 20:35:06.850  1017  1129 I splitIntent: other index=4, name=com.google.android.gms com.google.android.gms.common.stats.GmsCoreStatsServiceLauncher
03-15 20:35:06.850  1017  1129 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,03-15 20:35:06.850  1017  1129 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:06.850  1017  1129 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:06.850  1017  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 20:35:06.850  1695  4929 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,03-15 20:35:06.850  4904  4904 D hcjo    : AutoUpdateTriggerManager:IDLE:setInterval:345600000
,03-15 20:35:06.850  1017  1555 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:06.850  1017  1555 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:06.850  1017  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 20:35:06.860  1695  1695 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-15 20:35:06.860  4904  4904 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
,03-15 20:35:06.860  4904  4904 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime,
03-15 20:35:06.870  1017  3014 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:06.870  1017  3014 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:06.870  1017  3014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
03-15 20:35:06.870  4904  4904 D InitializeManagerStateMachine: exit::SUCCESS
03-15 20:35:06.870  4904  4904 D InitializeManagerStateMachine: entry::IDLE
,03-15 20:35:06.870  1017  3014 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:06.880  1017  3014 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:06.880  1017  3014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 20:35:06.880  1964  1964 V GmsCoreStatsServiceLauncher: Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,03-15 20:35:06.880  1017  1622 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,03-15 20:35:06.880  1017  1622 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:06.880  1017  1622 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-15 20:35:06.880  1017  1622 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 20:35:06.890  1017  3014 I ActivityManager: Killing 4179:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
,03-15 20:35:06.890  1017  3014 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:06.890  1017  3014 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:06.890  1017  3014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 20:35:06.890  1017  3014 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:06.890  1017  3014 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:06.890  1017  3014 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 20:35:06.900  1017  1372 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:06.900  1017  1372 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-15 20:35:06.900  1017  1372 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 20:35:06.900  1017  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:06.900  1017  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:06.900  1017  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 20:35:06.910  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:06.910  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:06.910  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 20:35:06.920  1775  4930 E MDM     : [200] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,03-15 20:35:06.920  1017  1029 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:06.920  1017  1029 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:06.920  1017  1029 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 20:35:06.920  1017  1555 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 20:35:06.920  1017  1555 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:06.920  1017  1555 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:06.920  1017  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 20:35:06.930  1017  1372 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:06.930  1017  1372 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:06.930  1017  1372 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 20:35:06.930  1017  3754 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:06.930  1017  3754 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-15 20:35:06.930  1017  3754 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 20:35:06.940  1017  3822 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,03-15 20:35:06.940  1017  3822 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:06.940  1017  3822 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:06.940  1017  3822 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 20:35:06.940  1964  4931 D LocationInitializer: Restart initialization of location
,03-15 20:35:06.940  1017  3823 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,03-15 20:35:06.940  1017  3823 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:06.940  1017  3823 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:06.940  1017  3823 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 20:35:06.950  1017  3754 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:06.950  1017  3754 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:06.950  1017  3754 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,03-15 20:35:06.980   257  1039 I SurfaceFlinger: id=13 Removed Uoast (8/8)
,03-15 20:35:06.980   257   448 I SurfaceFlinger: id=13 Removed Uoast (-2/8)
,03-15 20:35:06.980  1017  1129 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:06.980  1017  1129 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 20:35:06.980  1017  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.talk
,03-15 20:35:07.010  1017  1017 I ValidateNoPeople: mEvictionCount: 0
,03-15 20:35:07.030  1017  3823 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:35:07.030  1017  3823 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:35:07.030  1017  3823 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:35:07.030  1017  3823 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:35:07.050  1017  3823 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=4935 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-15 20:35:07.050  4935  4935 E Zygote  : MountEmulatedStorage()
03-15 20:35:07.050  4935  4935 E Zygote  : v2
03-15 20:35:07.050  4935  4935 I libpersona: KNOX_SDCARD checking this for 1000
03-15 20:35:07.050  4935  4935 I libpersona: KNOX_SDCARD not a persona
,03-15 20:35:07.050  4935  4935 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-15 20:35:07.050  4935  4935 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
,03-15 20:35:07.050  4935  4935 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 20:35:07.080  4935  4935 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 20:35:07.080  4935  4935 D ActivityThread: Added TimaKeyStore provider
,03-15 20:35:07.100  1017  1042 W libprocessgroup: failed to open /acct/uid_1101/pid_4179/cgroup.procs: No such file or directory
,03-15 20:35:07.100  4935  4935 E MTPRx   : In MtpReceiverandroid.hardware.usb.action.USB_STATE
,03-15 20:35:07.100  1017  3015 D SecContentProvider2: uri = 14 selection = getSealedState
,03-15 20:35:07.100  1017  3015 D SecContentProvider2: mCursor = null
,03-15 20:35:07.100  1017  1079 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
03-15 20:35:07.100  1017  1079 D SecContentProvider2: mCursor = null
,03-15 20:35:07.100  4935  4935 V MTPRx   : sealedState: false
03-15 20:35:07.100  4935  4935 V MTPRx   : sealedUsbMassStorageState: false
,03-15 20:35:07.100  4935  4935 E MTPRx   : check value of boot_completed is1
03-15 20:35:07.100  4935  4935 E MTPRx   : check booting is completed_sys.boot_completed
,03-15 20:35:07.110  4935  4935 E MTPRx   : Sd-Card path/storage/extSdCard
,03-15 20:35:07.110  4935  4935 E MTPRx   : Status for mount/Unmount :removed
,03-15 20:35:07.110  4935  4935 E MTPRx   : SDcard is not available
,03-15 20:35:07.110  4935  4935 W MTPRx   : value of connected istrue
,03-15 20:35:07.110  4935  4935 W MTPRx   : value of configured istrue
,03-15 20:35:07.110  4935  4935 W MTPRx   : value of mtpEnabled istrue
03-15 20:35:07.110  4935  4935 W MTPRx   : value of ptpEnabled isfalse
,03-15 20:35:07.110  4935  4935 E MTPRx   : Received USB_STATE with sdCardLaunch = 0
,03-15 20:35:07.110  4935  4935 E MTPRx   : mFirstTime: false
,03-15 20:35:07.120  4935  4935 D         : MTP: reading debug level property
,03-15 20:35:07.120  4935  4935 E MTPJNIInterface: Getting CryptionKey from JAVA
,03-15 20:35:07.120  4935  4935 E MTPRx   : currentUserId is 0
,03-15 20:35:07.130  4935  4935 E MTPRx   : Start observing USB_STATE_MATCH 
,03-15 20:35:07.130  4935  4935 E MTPRx   : cannot open file : /sys/class/android_usb/android0/bcdUSB
,03-15 20:35:07.130  4935  4935 E MTPRx   : is_Privatemode is NOT 1
,03-15 20:35:07.130  1017  1746 D SettingsProvider: name = boot_time_connected
,03-15 20:35:07.140  4935  4935 E MTPRx   : Sending NORMAL_BOOT to stack
03-15 20:35:07.140  4935  4935 E MTPJNIInterface: noti = 17
,03-15 20:35:07.140  1017  1372 D SettingsProvider: name = mtp_usb_conditions_met
,03-15 20:35:07.140  1017  3822 D SecContentProvider: uri = 18 selection = isUsbMediaPlayerAvailable
,03-15 20:35:07.140  4935  4935 E MTPRx   : sending MTP_ICON_ENABLED to stack
,03-15 20:35:07.140  1017  1400 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0,
,03-15 20:35:07.140  1017  1400 W ActivityManager: userId = 0, bbcId = -10000,
03-15 20:35:07.140  1017  1400 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-15 20:35:07.140  1017  1400 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,03-15 20:35:07.150  1017  1129 D SettingsProvider: name = mtp_running_status
,03-15 20:35:07.150  1017  1030 D SettingsProvider: name = mtp_usb_conditions_met
,03-15 20:35:07.150  4935  4935 E MTPRx   : else part ... so first time!!!
03-15 20:35:07.150  4935  4935 E MTPPlaObsrvr: inside setContext()
03-15 20:35:07.150  4935  4935 E MTPPlaObsrvr:  inside createplafiles
,03-15 20:35:07.160  4935  4935 E MTPPlaObsrvr: playlist count is0
03-15 20:35:07.160  4935  4935 E MTPPlaObsrvr:  inside try branch createplafiles
,03-15 20:35:07.160  4935  4935 E MTPPlaObsrvr:  inside deleteing plas createplafiles
,03-15 20:35:07.160  1187  1187 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-15 20:35:07.160  4935  4935 E MTPPlaObsrvr: Inside registerContentObserver
,03-15 20:35:07.160  4935  4935 E MtpAdbObserver: inside setContext()
,03-15 20:35:07.160  4935  4935 E MtpAdbObserver: Inside registerContentObserver
,03-15 20:35:07.170  4935  4935 W Settings: Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,03-15 20:35:07.170  1017  1746 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,03-15 20:35:07.170  1017  1746 W ActivityManager: userId = 0, bbcId = -10000
03-15 20:35:07.170  1017  1746 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:35:07.170  1017  1746 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,03-15 20:35:07.170  1017  3014 D SettingsProvider: name = mtp_running_status
,03-15 20:35:07.170  1017  1372 D SettingsProvider: name = mtp_usb_conditions_met
,03-15 20:35:07.170  4935  4935 E MtpService: onCreate.
,03-15 20:35:07.170  4935  4935 E MtpService: < MTP > Registering BroadCast receiver :::::
,03-15 20:35:07.170  4935  4952 V MtpMediaDBManager: inside deleteAllDB
,03-15 20:35:07.180  1017  1555 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,03-15 20:35:07.180  1017  1555 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:07.180  1017  1555 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:35:07.180  1017  1555 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-15 20:35:07.180  4935  4935 E MtpService: < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,03-15 20:35:07.180  4935  4935 E MtpService: < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,03-15 20:35:07.180  4935  4935 E MtpService: onStartCommand.
,03-15 20:35:07.180  4935  4935 W MTPRx   : calling native method
,03-15 20:35:07.180  4935  4935 E MTPJNIInterface: < MTP > Registering BroadCast receiver :::::
,03-15 20:35:07.180  4935  4953 E MtpService: handleMessage. msg= { when=-5ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,03-15 20:35:07.190  4935  4935 E MTPJNIInterface: < MTP > Registering BroadCast receiver :::::::
,03-15 20:35:07.190  1017  2853 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-15 20:35:07.190  4935  4935 E MTPJNIInterface: noti = 10
,03-15 20:35:07.190  1017  3014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:35:07.190  1017  3014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:35:07.190  1248  1248 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
03-15 20:35:07.190  1017  3014 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 20:35:07.190  1017  3014 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 20:35:07.200  4935  4952 V MtpMediaDBManager: inside Thread updateDB
,03-15 20:35:07.200  4954  4954 E Zygote  : MountEmulatedStorage()
,03-15 20:35:07.210  4954  4954 E Zygote  : v2
03-15 20:35:07.210  4954  4954 I libpersona: KNOX_SDCARD checking this for 1000
03-15 20:35:07.210  4954  4954 I libpersona: KNOX_SDCARD not a persona
,03-15 20:35:07.210  4954  4954 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2 ver=27
,03-15 20:35:07.210  1017  3014 I ActivityManager: Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=4954 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-15 20:35:07.210  4935  4935 E MtpService: onStartCommand.
03-15 20:35:07.210  4935  4935 W MTPRx   : calling native method
03-15 20:35:07.210  4935  4935 E MTPRx   : Checking the driver time out
03-15 20:35:07.210  4935  4935 E MTPJNIInterface: noti = 2
03-15 20:35:07.210  4935  4935 D         : deleting sockets before message queue initialization
03-15 20:35:07.210  4935  4953 E MtpService: handleMessage. msg= { when=0 what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,03-15 20:35:07.210  4935  4935 D         : event handler thread is created, so set the flag
,03-15 20:35:07.210  4954  4954 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2_0027
03-15 20:35:07.220  4935  4935 E MTPRx   : called native method
03-15 20:35:07.220  4935  4935 E MTPJNIInterface: setting Media scanner status0
03-15 20:35:07.220  4935  4935 E MTPJNIInterface: After setting Media scanner status0
03-15 20:35:07.220  4954  4954 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 20:35:07.220  4935  4935 W MTPRx   : notification from stack 1
,03-15 20:35:07.220  4935  4960 E         : Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
03-15 20:35:07.220  4935  4960 E MTPJNIInterface: Getting media scanner status0
03-15 20:35:07.220  4935  4952 E MtpMediaDBManager: count : 27
,03-15 20:35:07.230  4935  4960 E MTPJNIInterface: DeviceName is Thali Test (Galaxy A5)
,03-15 20:35:07.240  4954  4954 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 20:35:07.240  4954  4954 D ActivityThread: Added TimaKeyStore provider
,03-15 20:35:07.240  4935  4952 W MtpMediaDBManager: sending db update complete noti to stack
03-15 20:35:07.240  4935  4952 E MTPJNIInterface: noti = 29
,03-15 20:35:07.260  1017  1043 I ActivityManager: Waited long enough for: ServiceRecord{25472d1 u0 com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvc}
,03-15 20:35:07.260  4935  4960 E MTPJNIInterface: Status for mount/Unmount :removed
,03-15 20:35:07.260  4935  4960 E MTPJNIInterface: SDcard is not available
,03-15 20:35:07.300   327   327 I ServiceManager: Waiting for service AtCmdFwd...
,03-15 20:35:07.320  4935  4960 E         : [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,03-15 20:35:07.320  4954  4954 D TMNetworkReceiver: TMNetworkReceiver.TMNetworkReceiver() Enter 1 main
03-15 20:35:07.320  4954  4954 D TMNetworkReceiver: TMNetworkReceiver.onReceive() Enter
,03-15 20:35:07.320  4954  4954 D TMNetworkReceiver: MirrorLink feauture level: using UEvent
,03-15 20:35:07.320  1017  1341 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:07.320  1017  1341 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 20:35:07.320  1017  1341 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,03-15 20:35:07.330  4935  4960 E MTPJNIInterface: Status for mount/Unmount :removed
03-15 20:35:07.330  4935  4960 E MTPJNIInterface: SDcard is not available
,03-15 20:35:07.330  4935  4960 E SQLiteLog: (21) API call with NULL database connection pointer
03-15 20:35:07.330  4935  4960 E SQLiteLog: (21) misuse at line 106108 of [9491ba7d73]
03-15 20:35:07.330  4935  4960 E SQLiteLog: (21) API call with NULL database connection pointer
03-15 20:35:07.330  4935  4960 E SQLiteLog: (21) misuse at line 100726 of [9491ba7d73]
03-15 20:35:07.330  4935  4960 E SQLiteLog: (21) API call with NULL database connection pointer
03-15 20:35:07.330  4935  4960 E SQLiteLog: (21) misuse at line 100726 of [9491ba7d73]
03-15 20:35:07.330  4935  4960 E SQLiteLog: (21) API call with NULL database connection pointer
03-15 20:35:07.330  4935  4960 E SQLiteLog: (21) misuse at line 106108 of [9491ba7d73]
,03-15 20:35:07.330  4935  4935 W MTPRx   : notification from stack 2
,03-15 20:35:07.330  1017  1341 I ActivityManager: Killing 4239:com.sec.android.app.taskmanager/u0a157 (adj 15): empty #31
,03-15 20:35:07.330  4935  4970 D         : [mtp_init_device] Library open with 32 bits.
03-15 20:35:07.330  4935  4970 D         : [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
,03-15 20:35:07.330  4935  4970 E         : [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
03-15 20:35:07.330  4935  4970 D         : [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
03-15 20:35:07.330  4935  4970 E         :  [sua_support_present:1287] returning false 
03-15 20:35:07.330  4935  4970 D         : [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host,
,03-15 20:35:07.340  1017  1079 W ActivityManager: userId = 0, bbcId = -10000
,03-15 20:35:07.340  1017  1079 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
03-15 20:35:07.340  1017  1079 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms

```
