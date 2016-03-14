#### Test 62509094588eeb1_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3879): took 0.688750ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8b065c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b06478 counterpartCT=4 counterpartW=96 counterparth=96
D/FileApkUtils( 2070): Optimizing (staging complete)
D/FileApkUtils( 2070): Optimizing: DynamiteModules-prod.apk [0224a548494bce36274e23f9f1b42d4fbe3d4d8de53a7872e503f8974e43c3c3]
I/art     ( 2070): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000000@DynamiteModules-prod.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk': Failed to open oat filename for reading: No such file or directory
D/DexOptUtils( 2070): Module /data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk appears to be unoptimized.
D/DexOptUtils( 2070): Lollipop platform, using <isa> directory.
D/DexOptUtils( 2070): Instantiating DexClassLoader to force creation of odex.
D/DexOptUtils( 2070): Primary ABI of odexing process is armeabi-v7a
I/AMMetaDataParserService( 3879): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
I/Babel   ( 4043): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 4043): MmsConfig.loadMmsSettings
I/Babel   ( 4043): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
I/Babel   ( 4043): MmsConfig.loadFromDatabase
D/Finsky  ( 3966): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
D/Finsky  ( 3966): [1] Libraries$2.run: Finished loading 1 libraries.
E/Babel   ( 4043): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 4043): MmsConfig.loadFromResources
,--------- beginning of system
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
E/Babel   ( 4043): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 4043): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.policydm, hostingType: broadcast
E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3879): took 0.530468ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8b0ad88 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b04ce8 counterpartCT=4 counterpartW=96 counterparth=96
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3879): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
D/Finsky  ( 3966): [1] GmsCoreHelper.cleanupNlp: result=false type=4
I/dex2oat ( 4129): ----------------------------------------------------
I/libpersona( 4135): KNOX_SDCARD checking this for 1000
I/dex2oat ( 4129): <SS>: S T A R T I N G . . .
I/libpersona( 4135): KNOX_SDCARD not a persona
I/dex2oat ( 4129): <SS>: Zip is absent. Canceled.
I/dex2oat ( 4129): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk --oat-fd=40 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
E/Zygote  ( 4135): MountEmulatedStorage()
I/ActivityManager( 1018): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4135 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 4135): v2
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
D/ActivityManager( 1018): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3879): getResourcePackageName:assistant
I/AMMetaDataParserService( 3879): Resource data:2131034113
I/AMMetaDataParserService( 3879): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3879): getResourceTypeNamexml
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.service.recording.FitRecordingBroker; callingUser = 0; userId(target) = 0
I/SELinux ( 4135): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/GFX raster( 3879): took 0.864688ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8b01b38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b07bb8 counterpartCT=4 counterpartW=96 counterparth=96
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
I/SELinux ( 4135): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4135): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 3879): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
D/ActivityManager( 1018): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
V/GLSActivity( 1868): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
D/TimaKeyStoreProvider( 4135): TimaSignature is unavailable
D/ActivityThread( 4135): Added TimaKeyStore provider
W/Settings( 4043): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
D/Finsky  ( 3966): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3879): took 0.806510ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8b01b38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b078b0 counterpartCT=4 counterpartW=96 counterparth=96
I/ActivityManager( 1018): Killing 3366:com.dropbox.android/u0a92 (adj 15): empty #31
I/AMMetaDataParserService( 3879): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
D/ChimeraCfgMgr( 1868): Reading stored module config
I/Babel_StickerModule( 4043): App launched.
D/WearableService( 1868): callingUid 10012, callindPid: 1868
E/GmsWearableNodeHelper( 1868): GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
E/SMD     (  287): DCD OFF
W/art     ( 2637): Suspending all threads took: 18.069ms
D/AndroidRuntime( 4142): 
D/AndroidRuntime( 4142): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4142): CheckJNI is OFF
D/AndroidRuntime( 4142): readGMSProperty: start
D/AndroidRuntime( 4142): readGMSProperty: already setted!!
D/AndroidRuntime( 4142): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 4142): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 4142): readGMSProperty: end
D/AndroidRuntime( 4142): addProductProperty: start
W/art     ( 4043): Suspending all threads took: 18.349ms
W/libprocessgroup( 1018): failed to open /acct/uid_10092/pid_3366/cgroup.procs: No such file or directory
V/Babel   ( 4043): babel boot account: SMS
E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3879): took 0.660781ms for 96*96 texture 0
I/DBG_POLICYDM( 4135): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8b06760 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b078b0 counterpartCT=4 counterpartW=96 counterparth=96
I/DBG_POLICYDM( 4135): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
I/AMMetaDataParserService( 3879): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
I/DBG_POLICYDM( 4135): [com.policydm.eng.core.XDMMsg(70/xdmSendMessage)] waiting for DM_TaskHandler create
W/Babel   ( 4043): EsDatabaseHelper.static should not be called on main thread [called on main thread]
W/InstanceID/Rpc( 2070): Found 10012
W/Babel   ( 4043): java.lang.Exception
W/Babel   ( 4043): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 4043): 	at aes.<clinit>(SourceFile:95)
W/Babel   ( 4043): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 4043): 	at ckh.a(SourceFile:67)
W/Babel   ( 4043): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 4043): 	at bhn.a(SourceFile:301)
W/Babel   ( 4043): 	at bhn.a(SourceFile:137)
W/Babel   ( 4043): 	at bhn.a(SourceFile:126)
W/Babel   ( 4043): 	at bhn.a(SourceFile:159)
W/Babel   ( 4043): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 4043): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 4043): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 4043): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 4043): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 4043): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 4043): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 4043): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 4043): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 4043): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 4043): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
W/Babel   ( 4043): EsDatabaseHelper.getDatabaseHelper() [called on main thread]
W/Babel   ( 4043): java.lang.Exception
W/Babel   ( 4043): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 4043): 	at aes.a(SourceFile:145)
W/Babel   ( 4043): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 4043): 	at ckh.a(SourceFile:67)
W/Babel   ( 4043): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 4043): 	at bhn.a(SourceFile:301)
W/Babel   ( 4043): 	at bhn.a(SourceFile:137)
W/Babel   ( 4043): 	at bhn.a(SourceFile:126)
W/Babel   ( 4043): 	at bhn.a(SourceFile:159)
W/Babel   ( 4043): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 4043): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 4043): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 4043): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 4043): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 4043): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 4043): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 4043): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 4043): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 4043): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 4043): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/PCWCLIENTTRACE_AccountAppFacade2_0( 3468): unregister AuthInfo UpdateReceiver v2.0
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
E/AffinityControl( 4142): AffinityControl: registerfunction enter
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3879): took 0.593750ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8b0b130 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b078b0 counterpartCT=4 counterpartW=96 counterparth=96
D/ActivityManager( 1018): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
D/AndroidRuntime( 4142): Calling main entry com.android.commands.am.Am
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
V/Babel   ( 4043): babel boot account: thalitester@gmail.com
I/AMMetaDataParserService( 3879): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
E/PersonaManagerService( 1018): inState():  stateMachine is null !!
I/PersonaManagerService( 1018): PersonaId don't exist
I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3879): took 0.818489ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8b07c30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b078b0 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3879): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
D/CustomFrequencyManagerService( 1018): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3879): took 1.266719ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8b06f38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b078b0 counterpartCT=4 counterpartW=96 counterparth=96
W/ActivityManager( 1018): mDVFSHelper.acquire()
I/AMMetaDataParserService( 3879): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
D/FocusedStackFrame( 1018): Set to : 0
D/Launcher.HomeView( 1490): onPause
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/Launcher( 1490): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
D/PhoneWindow( 1018): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1018): *FMB* installDecor flags : -2122120936
D/InputDispatcher( 1018): Focused application set to: xxxx
D/InputDispatcher( 1018): Focus left window: 1490
D/AndroidRuntime( 4142): Shutting down VM
W/Babel   ( 4043): EsDatabaseHelper.getDatabaseHelper() [called on main thread]
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/Babel   ( 4043): java.lang.Exception
W/Babel   ( 4043): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 4043): 	at aes.a(SourceFile:145)
W/Babel   ( 4043): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 4043): 	at ckh.a(SourceFile:67)
W/Babel   ( 4043): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 4043): 	at bhn.a(SourceFile:301)
W/Babel   ( 4043): 	at bhn.a(SourceFile:137)
W/Babel   ( 4043): 	at bhn.a(SourceFile:126)
W/Babel   ( 4043): 	at bhn.a(SourceFile:159)
W/Babel   ( 4043): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 4043): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 4043): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 4043): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 4043): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 4043): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 4043): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 4043): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 4043): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 4043): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 4043): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  257): id=10 createSurf (1x1),1 flag=404, uhalitest
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
E/Zygote  ( 4179): MountEmulatedStorage()
I/libpersona( 4179): KNOX_SDCARD checking this for 10155
E/Zygote  ( 4179): v2
I/libpersona( 4179): KNOX_SDCARD not a persona
I/SELinux ( 4179): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1018): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4179 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 4179): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4179): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3879): took 0.705677ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8b078b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ac8aa0 counterpartCT=4 counterpartW=96 counterparth=96
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
V/ActivityThread( 1490): updateVisibility : ActivityRecord{320e0558 token=android.os.BinderProxy@13e337dd {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 4179): TimaSignature is unavailable
D/ActivityThread( 4179): Added TimaKeyStore provider
V/WindowOrientationListener( 1018): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1018): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1018): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
I/AMMetaDataParserService( 3879): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
D/Launcher.HomeView( 1490): onStop
V/ActivityThread( 1490): updateVisibility : ActivityRecord{320e0558 token=android.os.BinderProxy@13e337dd {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1018): isKioskContainerExistOnDevice
E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3879): took 0.668541ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb888b6c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ae8bb0 counterpartCT=4 counterpartW=96 counterparth=96
D/ActivityManager( 1018): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
D/ActivityManager( 1018): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
D/ActivityManager( 1018): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
D/SensorService( 1018): [SO] activate (ident=0xb924a730, enabled=0)
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
I/DBG_DM  ( 3216): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/SensorManager( 1018): unregisterListener ::   
I/Sensors ( 1018): AccelerometerSensor(0) setDelay : 66000000(ns)
D/SensorService( 1018): [SO] changed settle time [1]
D/SensorService( 1018): [SO] setDelay [66000000]
D/SensorService( 1018): [SO] activate (ident=0xb924a730, enabled=1)
D/SensorService( 1018): [SO] AR_init
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
E/Zygote  ( 4195): MountEmulatedStorage()
E/Zygote  ( 4195): v2
I/libpersona( 4195): KNOX_SDCARD checking this for 1000
I/libpersona( 4195): KNOX_SDCARD not a persona
I/SELinux ( 4195): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4195): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4195): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=4195 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/SensorManager( 1018): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
I/AMMetaDataParserService( 3879): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/art     ( 4142): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,D/Launcher( 1490): onTrimMemory. Level: 20
,D/GCM     ( 2070): COMPAT: Multi user not supported
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4195): TimaSignature is unavailable
,D/ActivityThread( 4195): Added TimaKeyStore provider
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/QCamera2Factory(  282): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  282): getCameraInfo: X
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/QCamera2Factory(  282): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  282): getCameraInfo: X
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SensorService( 1018): [SO] Reset Rotation Old [100], Init [1]
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3879): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3879): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 3879): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3879): getResourcePackageName:assistant
I/AMMetaDataParserService( 3879): Resource data:2131034112
,I/AMMetaDataParserService( 3879): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 3879): getResourceTypeNamexml
E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3879): took 0.611667ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8ac8aa0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ae97b0 counterpartCT=4 counterpartW=96 counterparth=96
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/GCoreUlr( 2070): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
I/AMMetaDataParserService( 3879): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 4135): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/DBG_POLICYDM( 4135): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,I/DBG_POLICYDM( 4135): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,D/SensorService( 1018): [SO] currT = 44440394253, prevT = 44130142899, diff = 310251354, [0.134 0.402 10.151]
,D/SensorService( 1018): [SO] 0.134 0.402 10.151
D/SensorService( 1018): [SO] [100 -> 255]
,I/DBG_POLICYDM( 4135): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,I/WebViewFactory( 4179): Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,I/LibraryLoader( 4179): Time to load native libraries: 2 ms (timestamps 4474-4476)
,I/LibraryLoader( 4179): Expected native library version number "",actual native library version number ""
,W/VideoCapabilities( 4043): Unrecognized profile 2130706433 for video/avc
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3879): took 0.611562ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8ac8aa0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ae8a48 counterpartCT=4 counterpartW=96 counterparth=96
,W/AudioCapabilities( 4043): Unsupported mime audio/evrc
,V/WebViewChromiumFactoryProvider( 4179): Binding Chromium to main looper Looper (main, tid 1) {9855d62}
,I/LibraryLoader( 4179): Expected native library version number "",actual native library version number ""
I/chromium( 4179): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
I/CheckinService( 2070): Disabling old GoogleServicesFramework version
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
,D/ChimeraCfgMgr( 2070): Reading stored module config
,W/AudioCapabilities( 4043): Unsupported mime audio/qcelp
,W/AudioCapabilities( 4043): Unsupported mime audio/mpeg-L1
,I/AMMetaDataParserService( 3879): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,I/BrowserStartupController( 4179): Initializing chromium process, singleProcess=true
,W/art     ( 4179): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 4179): ApplicationContext is null in ApplicationStatus
,W/AudioCapabilities( 4043): Unsupported mime audio/mpeg-L2
,W/AudioCapabilities( 4043): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 4043): Unsupported mime audio/x-ima
,W/AudioCapabilities( 4043): Unsupported mime audio/qcelp
,W/AudioCapabilities( 4043): Unsupported mime audio/evrc
,W/chromium( 4179): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 4179): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,I/chromium( 4179): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
W/VideoCapabilities( 4043): Unsupported mime video/wvc1
D/BootCompletedReceiver( 2070): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
D/BootCompletedReceiver( 2070): Got an BootCompleted event.
W/VideoCapabilities( 4043): Unsupported mime video/x-ms-wmv
I/Adreno-EGL( 4179): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 4179): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 4179): Build Date: 04/06/15 Mon
I/Adreno-EGL( 4179): Local Branch: 
I/Adreno-EGL( 4179): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 4179): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 4179):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
I/DBG_POLICYDM( 4135): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,D/BootCompletedReceiver( 2070): Will NOT schedule AdAttestation signal task because it's disabled.
,I/DBG_POLICYDM( 4135): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
D/SystemUpdateService( 2070): onCreate
,I/DBG_POLICYDM( 4135): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 4135): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,I/DBG_POLICYDM( 4135): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,I/SurfaceFlinger(  257): id=8 Removed Mauncher (5/8)
,I/SurfaceFlinger(  257): id=8 Removed Mauncher (-2/8)
,I/DBG_POLICYDM( 4135): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3879): took 0.657812ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8ae9ad8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8ae97b0 counterpartCT=4 counterpartW=96 counterparth=96
,D/SystemUpdateService( 2070): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,W/VideoCapabilities( 4043): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities( 4043): Unsupported mime video/wvc1
,W/VideoCapabilities( 4043): Unsupported mime video/x-ms-wmv
,I/AMMetaDataParserService( 3879): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,V/AuthZen ( 2070): Handling intent: android.intent.action.BOOT_COMPLETED
,W/VideoCapabilities( 4043): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities( 4043): Unsupported mime video/x-ms-wmv8
,W/chromium( 4179): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,W/VideoCapabilities( 4043): Unsupported mime video/mp43
,W/VideoCapabilities( 4043): Unsupported mime video/sorenson
,D/AuthZenEventHandler( 2070): Handling event: android.intent.action.BOOT_COMPLETED
,W/VideoCapabilities( 4043): Unsupported mime video/mp4v-esdp
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3879): took 0.632500ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8b06f38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ae8a48 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3879): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,I/ActivityManager( 1018): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4243 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 4243): MountEmulatedStorage()
E/Zygote  ( 4243): v2
I/libpersona( 4243): KNOX_SDCARD checking this for 10035
I/libpersona( 4243): KNOX_SDCARD not a persona
,I/SELinux ( 4243): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4243): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,I/ActivityManager( 1018): Killing 3273:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
,E/SELinux ( 4243): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4243): TimaSignature is unavailable
,D/ActivityThread( 4243): Added TimaKeyStore provider
E/Zygote  ( 4260): MountEmulatedStorage(),
E/Zygote  ( 4260): v2
I/libpersona( 4260): KNOX_SDCARD checking this for 1000
I/libpersona( 4260): KNOX_SDCARD not a persona
I/SELinux ( 4260): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4260): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1018): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=4260 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
,I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.s,amsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:assistant
I/AMMetaDataParserService( 3879): Resource data:2131034113
I/AMMetaDataParserService( 3879): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3879): getResourceTypeNamexml
I/ActivityManager( 1018): Killing 3436:com.fmm.dm/1000 (adj 15): empty #31
E/SELinux ( 4260): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/SSRM:n  ( 1018): SIOP:: AP = 380
D/TimaKeyStoreProvider( 4260): TimaSignature is unavailable
D/ActivityThread( 4260): Added TimaKeyStore provider
W/art     ( 4179): Attempt to remove local handle scope entry from IRT, ignoring
,I/GFX raster( 3879): took 0.951302ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8ae8bb0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b0af48 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3879): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,I/VideoCapabilities( 4043): Unsupported profile 4 for video/mp4v-es
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3879): took 0.863177ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8ae8bb0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8ae97b0 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_POLICYDM( 4135): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/AMMetaDataParserService( 3879): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,W/AwContents( 4179): onDetachedFromWindow called when already detached. Ignoring
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 4135): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
D/PhoneWindow( 4179): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 4179): *FMB* installDecor flags : -2139027200
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3879): took 0.605104ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8ae8a48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b0af48 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3436/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10057/pid_3273/cgroup.procs: No such file or directory
,D/SystemWebViewEngine( 4179): CordovaWebView is running on device made by: samsung
,W/art     ( 4179): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 4179): Attempt to remove local handle scope entry from IRT, ignoring
I/AMMetaDataParserService( 3879): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,I/SystemUpdateService( 2070): cancelUpdate (empty URL)
,I/SystemUpdateService( 2070): active receiver: disabled
,I/CheckinService( 2070): Checking schedule, now: 1457959157795 next: 1458246240395
I/CheckinService( 2070): active receiver: disabled
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,I/DBG_POLICYDM( 4135): [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
,D/KnoxSetupWizardDbHelper( 4260): dbMigrationFlag : false
I/DBG_POLICYDM( 4135): [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
,I/DBG_POLICYDM( 4135): [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
,I/DBG_POLICYDM( 4135): [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ShortcutReceiver( 4260):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,I/DBG_POLICYDM( 4135): [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,I/DBG_POLICYDM( 4135): [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
,I/DBG_POLICYDM( 4135): [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
D/KnoxShortcutUtil( 4260): getIsShortcutMigrationFor_2_3_0_Done true
,D/ShortcutReceiver( 4260):  KnoxContainerVersion 2.4.0
D/ShortcutReceiver( 4260):  shortcut migration not required 
,I/DBG_POLICYDM( 4135): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 4135): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 4135): [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
,I/DBG_POLICYDM( 4135): [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
,I/DBG_POLICYDM( 4135): [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.knox.knoxsetupwizardclient, hostingType: broadcast
,I/DBG_POLICYDM( 4135): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,I/DBG_POLICYDM( 4135): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,I/DBG_POLICYDM( 4135): [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,W/BaseAppContext( 2070): Using Auth Proxy for data requests.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/DBG_POLICYDM( 4135): [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/03/18/16:12:11
,I/DBG_POLICYDM( 4135): [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] ,
,I/DBG_POLICYDM( 4135): [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0,
,I/DBG_POLICYDM( 4135): [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0,
,I/ActivityManager( 1018): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4285 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,I/ActivityManager( 1018): Killing 3452:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31
,I/DBG_POLICYDM( 4135): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/03/14/13:39:17,
,E/Zygote  ( 4285): MountEmulatedStorage(),
E/Zygote  ( 4285): v2
,I/libpersona( 4285): KNOX_SDCARD checking this for 1000
I/SELinux ( 4285): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 4285): KNOX_SDCARD not a persona,
,I/SELinux ( 4285): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4285): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/OpenGLRenderer( 4179): Render dirty regions requested: true
,I/DBG_DM  ( 3216): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3879): took 0.603802ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8ac8aa0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ae97b0 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4285): TimaSignature is unavailable
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
D/ActivityThread( 4285): Added TimaKeyStore provider
D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
,D/PhoneWindow( 4179): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 4179): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  257): id=11 createSurf (1x1),1 flag=404, NainActivit
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/SPPClientService( 4243): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 4243): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService( 4243): [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,D/InputDispatcher( 1018): Focus entered window: 4179
,I/AMMetaDataParserService( 3879): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 4179): log_dcs ThreadedRenderer::initialize entered! 
I/OpenGLRenderer( 4179): Initialized EGL, version 1.4
,I/DBG_POLICYDM( 4135): [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
,I/DBG_POLICYDM( 4135): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
,I/DBG_POLICYDM( 4135): [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
,D/OpenGLRenderer( 4179): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 4179): Enabling debug mode 0
E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3879): took 0.824427ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8b07c30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b0af48 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3879): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/BaseAppContext( 2070): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,D/SPPClientService( 4243): PushLog.txt file is not deleted.
,D/SPPClientService( 4243): PushLog.txt file is not deleted.
D/SPPClientService( 4243): ============PushLog. stop!
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/PanelView( 1190): There is/are notification(s) 
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/Timeline( 4179): Timeline: Activity_idle id: android.os.BinderProxy@386c23f time:45476
,I/ActivityManager( 1018): Displayed Component not be shown by security: +1s386ms
,I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{cda4741 u0 com.test.thalitest/.MainActivity t12} time:45492
D/CustomFrequencyManagerService( 1018): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
I/SamsungIME( 1815): getCurrentCandidateView
W/ActivityManager( 1018): mDVFSHelper.release()
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4316): MountEmulatedStorage()
E/Zygote  ( 4316): v2
I/libpersona( 4316): KNOX_SDCARD checking this for 10041
I/libpersona( 4316): KNOX_SDCARD not a persona
,I/SELinux ( 4316): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/SELinux ( 4316): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1018): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4316 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 3484:com.dropbox.android:crash_uploader/u0a92 (adj 15): empty #31
,E/SELinux ( 4316): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/CustomFrequencyManagerService( 1018): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@11
,E/KnoxSetupWizardClient( 4285): isShipMode : 1
I/KnoxSetupWizardClient( 4285): onReceive : android.intent.action.BOOT_COMPLETED
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/SecDataIO(  256): Write to block
,I/GFX raster( 3879): took 0.782031ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8b06f38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ae97b0 counterpartCT=4 counterpartW=96 counterparth=96
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 40241(2MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 27MB/41MB, paused 2.915ms total 245.391ms
,D/TimaKeyStoreProvider( 4316): TimaSignature is unavailable
,D/ActivityThread( 4316): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3879): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,W/ContextImpl( 2637): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,I/DBG_POLICYDM( 4135): [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:2, health:2, present:true, voltage: 4305, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,W/BindingManager( 4179): Cannot call determinedVisibility() - never saw a connection for the pid: 4179
,I/DBG_DM  ( 3216): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/DBG_DM  ( 3216): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,E/DBG_DM  ( 3216): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
,I/DBG_POLICYDM( 4135): [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
,D/SecurityLogAgent:SEDenialService( 1018): Got CLOSE_WRITE Event sk.log
,D/KeyguardUpdateMonitor( 1190): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1190): handleBatteryUpdate
,V/EmergencyMode( 1429): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1429): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3879): took 0.680209ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8b078b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8b0af48 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3879): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,I/SurfaceFlinger(  257): id=10 Removed uhalitest (7/8)
,I/SurfaceFlinger(  257): id=10 Removed uhalitest (-2/8)
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:2 health:2,
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,I/DBG_POLICYDM( 4135): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
,D/BatteryMeterView( 1190): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,V/HeadsetService( 2690): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2690): Disconnected process message: 10
,W/art     ( 4043): Suspending all threads took: 28.214ms
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/SQLiteLog( 4043): (284) automatic index on conversation_participants_view(conversation_id)
,W/System.err( 4285): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub,
W/System.err( 4285): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 4285): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 4285): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4212)
W/System.err( 4285): ,	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1948)
W/System.err( 4285): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 4285): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3879): took 0.533125ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb888b6c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ae97b0 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4340): MountEmulatedStorage()
I/libpersona( 4340): KNOX_SDCARD checking this for 10107
E/Zygote  ( 4340): v2
I/libpersona( 4340): KNOX_SDCARD not a persona
,I/SELinux ( 4340): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4340): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4340): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/SamsungIME( 1815): Dismiss ExpandCandiate
,D/CustomFrequencyManagerService( 1018): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@11
,I/AMMetaDataParserService( 3879): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/ActivityManager( 1018): Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=4340 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 3500:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31
,I/DBG_DM  ( 3216): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,I/DBG_POLICYDM( 4135): [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,D/TimaKeyStoreProvider( 4340): TimaSignature is unavailable
,D/ActivityThread( 4340): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
W/ContextImpl( 3879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,I/Process ( 2637): Sending signal. PID: 2637 SIG: 9
,D/JsMessageQueue( 4179): Set native->JS mode to OnlineEventsBridgeMode
,I/SA      ( 4316): [SSP] onCreated
,I/DBG_POLICYDM( 4135): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 4135): [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,I/ActivityManager( 1018): Process com.sec.android.app.sysscope (pid 2637)(adj 0) has died(43,1149)
,I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:assistant
I/AMMetaDataParserService( 3879,): Resource data:2131165203
W/ResourcesManager( 3879): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3879): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3879): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3879): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3879): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/SystemUpdateService( 2070): onDestroy
E/SQLiteLog( 4043): (284) automatic index on conversation_participants_view(conversation_id)
W/libprocessgroup( 1018): failed to open /acct/uid_10003/pid_3452/cgroup.procs: No such file or directory
I/AMMetaDataParserService( 3879): getResourceName:com.android.email:xml/email_assistant_menu
I/AMMetaDataParserService( 3879): getResourceTypeNamexml
D/jxcore_app_log( 4179): JniHelper::setJavaVM(0xb872d450), pthread_self() = -1194867528
,E/SQLiteLog( 4043): (284) automatic index on conversation_participants_view(conversation_id)
,W/libprocessgroup( 1018): failed to open /acct/uid_10092/pid_3484/cgroup.procs: No such file or directory
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4179): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4179):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4179):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4179):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4179):     - Handshake required: true
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4179): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fba9a1a added. We now have 1 listener(s)
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4179): setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4179): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"7C:F9:0E:37:96:AB"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4179): setIdentityString: {"name":"<no peer name>","address":"7C:F9:0E:37:96:AB"}
D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4179): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4179): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4179): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4179):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4179):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4179):     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4179):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4179):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4179):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4179):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4179):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4179):     - Scan report delay in milliseconds: 500
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4179): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dd03441 added. We now have 1 listener(s)
,I/GFX construct_block_size_descriptor_2d second part( 3879): took 3.304481ms for 0*0 texture 0
,W/libprocessgroup( 1018): failed to open /acct/uid_10060/pid_3500/cgroup.procs: No such file or directory
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4179): addListener: New listener added - the number of listeners is now 1
,I/DBG_DM  ( 3216): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,I/SA      ( 4316): [TPM] There is no property file
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4179): isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4179): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4179): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4179): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4179): setScanMode: 1 -> 2
,I/DBG_DM  ( 3216): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3216): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,I/SA      ( 4316): [SCU] isHaveSA() - false
,I/DBG_DM  ( 3216): [IIlIIIlllllIIlIIIlII(91/llllIIIllIlIIIIllllI)] 
,I/SA      ( 4316): [TPM] getModelProperty : null
I/SA      ( 4316): [TPM] getCSCProperty : null
,I/SA      ( 4316): [DM] FLOATING AMOLED FEATURE: true
I/SA      ( 4316): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 4316): [DM] TFT FEATURE: false
,I/chromium( 4179): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,I/AuthZen ( 2070): Fetching signing key...
,I/SA      ( 4316): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
I/SA      ( 4316): [DM] init START
,E/SQLiteLog( 4043): (284) automatic index on conversation_participants_view(conversation_id)
,I/GFX generate_partition_tables( 3879): took 18.336873ms for 0*0 texture 0
,I/GFX raster( 3879): took 23.016824ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8ae5bf8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8ae5ca0 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_DM  ( 3216): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/SA      ( 4316): [DM] This device is not a Vodafone
,W/ResourceType( 4316): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 4316): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
W/ResourceType( 4316): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 4316): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 4316): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 4316): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 4316): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,D/EnterpriseController(  277): uids 10012
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10012
W/ResourceType( 4316): No package identifier when getting value for resource number 0x00000000,
,W/ResourceType( 4316): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
W/ResourceType( 4316): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75),
W/ResourceType( 4316): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 4316): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75),
W/ResourceType( 4316): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 4316): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
W/ResourceType( 4316): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,W/ResourceType( 4316): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
W/ResourceType( 4316): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75),
W/ResourceType( 4316): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 4316): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
W/ResourceType( 4316): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
W/ResourceType( 4316): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,I/art     ( 1651): Explicit concurrent mark sweep GC freed 4078(156KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 7MB/12MB, paused 850us total 26.753ms
,I/DBG_DM  ( 3216): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,E/SQLiteLog( 4043): (284) automatic index on conversation_participants_view(conversation_id)
,W/ResourceType( 4316): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,I/ActivityManager( 1018): Killing 3515:com.fmm.ds/1000 (adj 15): empty #31
,W/ResourceType( 4316): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,W/ResourceType( 4316): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,W/ResourceType( 4316): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,I/SA      ( 4316): [SCU] isHaveSA() - false
I/SA      ( 4316): support phone number id : false
I/SA      ( 4316): [DM] Supports Ref Jpn : true
,I/SA      ( 4316): [DM] init END
,I/SA      ( 4316): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 4316): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,D/ActivityManager( 1018): startService callerProcessName:com.osp.app.signin, calleePkgName: com.osp.app.signin
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,I/SA      ( 4316): [OR] onReceive END
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4369): MountEmulatedStorage(),
I/ActivityManager( 1018): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=4369 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/Zygote  ( 4369): v2
I/libpersona( 4369): KNOX_SDCARD checking this for 10042
I/libpersona( 4369): KNOX_SDCARD not a persona
,I/SELinux ( 4369): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/GCoreUlr( 1868): DispatchingService.onCreate(),
,I/SELinux ( 4369): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4369): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4369): TimaSignature is unavailable
,D/ActivityThread( 4369): Added TimaKeyStore provider
,W/dex2oat ( 4129): Verification of void maps.ax.e.a(java.util.Map) took 225.376ms
,I/SA      ( 4316): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 4316): [ODM] queryOpenData(key= GEO_IP )
,I/AuthZen ( 2070): Signing key fetched successfully!
,D/GCM     ( 1868): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,W/ResourcesManager( 4369): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,I/SA      ( 4316): getMccForGalaxyJpn step2 GEO_IP MCC : 260
I/SA      ( 4316): [LBE] REF_JPN : true
,I/SA      ( 4316): [BDC] create
,W/dex2oat ( 4129): Verification of com.google.android.gms.ads.internal.request.AdResponseParcel maps.ax.b.a(android.content.Context, maps.ak.d, maps.ad.a, maps.ax.a, com.google.android.gms.ads.internal.request.AdRequestInfoParcel) took 310.201ms
,W/BaseAppContext( 2070): Using Auth Proxy for data requests.,
,I/DBG_DM  ( 3216): [com.wssyncmldm.db.file.XDB(6236/IlIIlIIlIllllIlllIII)] Initiated Type: 2
,I/SA      ( 4316): [DBMV2] getEmailID
,I/SA      ( 4316): [DBMV2] getDataV02ForItems
I/SA      ( 4316): [SSP] query invoked
,I/SA      ( 4316): [SCU] get signed id from samsung account2.0 DB.
,I/GCM     ( 1868): GCM config loaded
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,I/DBG_DM  ( 3216): [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,I/DBG_DM  ( 3216): [IlIlllIlllllIlIllllI(251/lllIlIlIIIllIIlIllIl)] XDL_STATE_READY_TO_UPDATE
,I/DBG_DM  ( 3216): [IlIIlIIlIllllIlllIII(274/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,I/DBG_DM  ( 3216): [llllIIIllIllIlllIIlI(772/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1018): Waited long enough for: ServiceRecord{8fbe4dc u0 com.samsung.hs20settings/.WifiHs20UtilityService}
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/SA      ( 4316): [SCU] get signed id from samsung account1.0 DB.
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3515/cgroup.procs: No such file or directory
,I/SA      ( 4316): [BDC] destroy
,I/DBG_DM  ( 3216): [IlIIlIIlIllllIlllIII(1901/llllIIIllIlIIIIllllI)] 
,I/DBG_DM  ( 3216): [llllIlllIIIlIlIlIIII(49/llIIIIlllllIIllIIllI)] 
,I/ActivityManager( 1018): Killing 3547:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,I/DBG_DM  ( 3216): [com.wssyncmldm.DMSecBroadcastReceiver(572/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,E/SMD     (  287): DCD OFF
,I/GAV2    ( 3814): Thread[GAThread,5,main]: No campaign data found.
I/DBG_DM  ( 3216): [IIllIIIIlIlIlIlIllII(49/IIIlIIllIlIIllIlllII)] FirmwareObjectSize:308289685
I/DBG_DM  ( 3216): [IIllIIIIlIlIlIlIllII(1715/llllllIllIlIlllIIlIl)] 
I/CalendarProvider2( 4369): CalendarProvider2.onCreate() called
I/DBG_DM  ( 3216): [com.wssyncmldm.db.file.XDB(5178/IIIIlIllIlllIlIIIIlI)] Data Margin : 500
,I/DBG_DM  ( 3216): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Data App Weight : 0.0
,I/DBG_DM  ( 3216): [com.wssyncmldm.db.file.XDB(5258/llllIIlIlIIIIllIlIIl)] Delta Weight : 0.5
,I/DBG_DM  ( 3216): [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(194/llIIIIlllllIIllIIllI)] ### Data Margin only: 678432842
,I/DBG_DM  ( 3216): [com.wssyncmldm.llIIllllIIlllIIIIlll(1125/handleMessage)] event ->220
,I/art     ( 1868): Explicit concurrent mark sweep GC freed 30010(2MB) AllocSpace objects, 39(816KB) LOS objects, 39% free, 12MB/20MB, paused 1.507ms total 105.573ms
,I/DBG_DM  ( 3216): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 3216): [com.wssyncmldm.XDMService(712/lllIIIIllIlIlllllllI)] 
,I/DBG_DM  ( 3216): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(503/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,I/DBG_DM  ( 3216): [com.wssyncmldm.db.file.XDB(5018/IIllIIllIIIlllIlIIll)] Get Autoinstall status : false
,W/Auth    ( 1868): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,I/GCoreUlr( 1868): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_DM  ( 3216): [com.wssyncmldm.XDMService(468/lIllIllllIIIlllIlllI)] 
,W/dex2oat ( 4129): Verification of void maps.bk.b.requestInterstitialAd(android.content.Context, maps.bj.f, android.os.Bundle, maps.bj.a, android.os.Bundle) took 104.406ms
,E/DBG_DM  ( 3216): [com.wssyncmldm.XDMService(476/lIllIllllIIIlllIlllI)] didn't register
,E/DBG_DM  ( 3216): [com.wssyncmldm.XDMService(477/lIllIllllIIIlllIlllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@297c95ed
,W/libprocessgroup( 1018): failed to open /acct/uid_10062/pid_3547/cgroup.procs: No such file or directory
,I/DBG_DM  ( 3216): [llllIIIllIllIlllIIlI(726/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
,V/GLSActivity( 1868): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/dex2oat ( 4129): Verification of void maps.bi.f.onPause() took 121.646ms
,I/AMMetaDataParserService( 3879): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,D/a       ( 2070): Opening database auth.proximity.permit_store...
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3879): took 0.809843ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb87c1018 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8ac6468 counterpartCT=4 counterpartW=96 counterparth=96
,D/AuthZenTransactionCache( 2070): Initialized cache in: /data/data/com.google.android.gms/files
,D/AuthZenTransactionCache( 2070): Clearing transaction cache
,I/AMMetaDataParserService( 3879): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,I/DBG_DM  ( 3216): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,I/DBG_DM  ( 3216): [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : false
,I/DBG_DM  ( 3216): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(649/IIIIllIlIIlIIIIlllIl)] nWidgetStatus : 2
,W/GCoreFlp( 1868): No location to return for getLastLocation()
,W/FusedLocationProvider( 1868): location=null
,W/ContextImpl( 3216): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.wssyncmldm.ui.llllIIIllIlIIIIllllI.IIIIllIlIIlIIIIlllIl:652 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:172 llllIIIllIllIlllIIlI.llIIIIlllllIIllIIllI:732 
,W/GCoreFlp( 1868): No location to return for getLastLocation()
,W/FusedLocationProvider( 1868): location=null
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3879): took 0.774010ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb87c1018 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8ae8a48 counterpartCT=4 counterpartW=96 counterparth=96
,D/SettingsProvider( 1018): name = SOFTWARE_UPDATE_NOTIFICATION_STATUS
,D/PersistentNotificationBroadcastReceiver( 1868): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/AMMetaDataParserService( 3879): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,I/SecKeyguardClockSingleView( 1190): Ignore. Because it is same clock text
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/DBG_DM  ( 3216): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,I/GFX raster( 3879): took 0.919375ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb87c1018 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8b078b0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3879): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,I/ActivityManager( 1018): Killing 3334:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
,I/DBG_DM  ( 3216): [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.sync.focus.ContactsSyncIntentService; callingUser = 0; userId(target) = 0
,I/GFX raster( 3879): took 0.697658ms for 96*96 texture 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8ae8bb0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb888b6c0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3879): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,D/ActivityManager( 1018): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ApplicationPolicy( 1018): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/WindowManager( 1018): showStatusBarByNotification() mOpenByNotification=false
,W/libprocessgroup( 1018): failed to open /acct/uid_10009/pid_3334/cgroup.procs: No such file or directory
,W/NotificationService( 1018): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,I/DBG_DM  ( 3216): [com.wssyncmldm.ui.XUIFotaPostponeActivity(337/llIIIIlllllIIllIIllI)] 
,W/ResourcesManager( 1190): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/DBG_DM  ( 3216): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityEnabledState
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravity
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityXOffset
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1018): mCursor = null
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3879): took 0.604115ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8ae8bb0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8ac8aa0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3879): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,D/SecContentProvider2( 1018): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1018): mCursor = null
,D/KnoxNotification( 1190): ----- inflateViews : modified publicViewLocal -----
,D/KnoxNotification( 1190): ----- inflateViews : modified KnoxViewLocal -----
,I/DBG_DM  ( 3216): [com.wssyncmldm.db.file.XDB(5457/lllIIIIllIlIlllllllI)] Set Download Postpone status : 8
,I/DBG_DM  ( 3216): [com.wssyncmldm.ui.XUIFotaPostponeActivity(386/llIIIIlllllIIllIIllI)] No idle Postpone
,I/DBG_DM  ( 3216): [com.wssyncmldm.ui.XUIFotaPostponeActivity(474/llIIIIlllllIIllIIllI)] 
,I/SamsungIME( 1815): getDebugLevel  : 0x4f4c
,I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
W/ContextImpl( 3879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3879): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3879): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3879): getResourcePackageName:assistant
I/AMMetaDataParserService( 3879): Resource data:2131099648
,D/ActivityManager( 1018): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncService; callingUser = 0; userId(target) = 0
,W/ResourcesManager( 3879): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 3879): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3879): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 3879): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3879): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 3879): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3879): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3879): getResourceTypeNamexml
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3879): took 0.730469ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8e67e10 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8e67e48 counterpartCT=4 counterpartW=96 counterparth=96
,D/OpenGLRenderer( 3216): Render dirty regions requested: true
,D/PersonaManager( 1190): PersonaID is invalid or persona doesn't exists. : 0
,D/PersonaManager( 1190): isKioskContainerExistOnDevice
,D/PersonaManager( 1190): isKioskContainerExistOnDevice
,I/AMMetaDataParserService( 3879): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/PanelView( 1190): There is/are notification(s) 
,I/SamsungIME( 1815): getDebugLevel  : 0x4f4c
,D/PanelView( 1190): kidsfalse mQsExpansionEnabled:true
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3879): took 2.337864ms for 0*0 texture 0
,I/GFX generate_partition_tables( 3879): took 8.700157ms for 0*0 texture 0
,I/GFX raster( 3879): took 12.006200ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8af0190 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8af01c8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3879): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3879): took 0.652343ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8aec488 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8aec7c8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3879): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3879): took 0.670938ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8aeffa0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8e67dd0 counterpartCT=4 counterpartW=96 counterparth=96
,I/SamsungIME( 1815): KeybaordView init() : load resources
,D/PersonaManager( 1190): isKioskContainerExistOnDevice
,D/PanelView( 1190): There is/are notification(s) 
D/PanelView( 1190): kidsfalse mQsExpansionEnabled:true
,I/SurfaceFlinger(  257): id=12 createSurf (1x1),1 flag=4, Uoast
,I/AMMetaDataParserService( 3879): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/ActivityManager( 1018): Killing 3574:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,D/PowerManagerService( 1018): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018
,I/GFX raster( 3879): took 0.924374ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8e66e28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8e67dd0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3879): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/SRIB_DCS( 3216): log_dcs ThreadedRenderer::initialize entered! 
,I/Adreno-EGL( 3216): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 3216): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 3216): Build Date: 04/06/15 Mon
I/Adreno-EGL( 3216): Local Branch: 
I/Adreno-EGL( 3216): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 3216): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 3216):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,D/StrictMode( 4340): StrictMode policy violation; ~duration=1415 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4340): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4340): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4340): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4340): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4340): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4340): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4340): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 4340): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
D/StrictMode( 4340): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4340): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4340): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4340): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4340): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4340): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4340): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4340): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4340): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4340): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4340): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4340): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4340): StrictMode policy violation; ~duration=1393 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4340): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4340): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4340): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4340): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4340): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4340): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4340): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4340): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4340): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4340): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4340): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4340): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4340): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4340): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4340),: 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4340): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4340): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4340): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4340): StrictMode policy violation; ~duration=730 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4340): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4340): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4340): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4340): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4340): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 4340): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 4340): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
D/StrictMode( 4340): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4340): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4340): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4340): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4340): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4340): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4340): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4340): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4340): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4340): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4340): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4340): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4340): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4340): StrictMode policy violation; ~duration=729 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4340): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4340): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4340): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 4340): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4340): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 4340): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4340): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4340): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4340): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4340): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4340): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4340): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4340): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4340): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4340): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4340): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4340): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4340): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4340): StrictMode policy violation; ~duration=728 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4340): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4340): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 4340): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 4340): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4340): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 4340): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4340): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4340): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4340): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4340): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4340): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4340): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4340): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4340): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4340): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4340): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4340): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4340): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4340): StrictMode policy violation; ~duration=725 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4340): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4340): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4340): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4340): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4340): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4340): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4340): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 4340): 	at com.google.r.k.a(PG:2107)
D/StrictMode( 4340): 	at com.google.v.a.a.eq.<init>(PG:23)
D/StrictMode( 4340): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 4340): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 4340): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 4340): 	at com.google.r.e.b(PG:170)
D/StrictMode( 4340): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4340): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4340): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4340): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4340): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4340): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4340): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4340): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4340): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4340): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4340): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4340): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4340): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4340): StrictMode policy violation; ~duration=724 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4340): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4340): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4340): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4340): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4340): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4340): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4340): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 4340): 	at com.google.r.k.b(PG:14147)
D/StrictMode( 4340): 	at com.google.r.k.c(PG:583)
D/StrictMode( 4340): 	at com.google.v.a.a.eq.<init>(PG:40)
D/StrictMode( 4340): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 4340): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 4340): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 4340): 	at com.google.r.e.b(PG:170)
D/StrictMode( 4340): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4340): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4340): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4340): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4340): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4340): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4340): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4340): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4340): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4340): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4340): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4340): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4340): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4340): StrictMode policy violation; ~duration=692 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4340): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4340): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4340): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4340): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4340): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 4340): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 4340): 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
D/StrictMode( 4340): 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
D/StrictMode( 4340): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4340): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4340): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4340): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4340): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4340): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4340): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4340): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4340): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4340): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4340): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4340): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4340): StrictMode policy violation; ~duration=692 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4340): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4340): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4340): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4340): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.map.l.s.a(PG:7692)
D/StrictMode( 4340): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
,D/StrictMode( 4340): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4340): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4340): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4340): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4340): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4340): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4340): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4340): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4340): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4340): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4340): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4340): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4340): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.app.mt, hostingType: broadcast
D/PanelView( 1190): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/OpenGLRenderer( 3216): Initialized EGL, version 1.4
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4416): MountEmulatedStorage()
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4416): v2
I/SELinux ( 4416): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 4416): KNOX_SDCARD checking this for 1000
I/SELinux ( 4416): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/libpersona( 4416): KNOX_SDCARD not a persona
E/SELinux ( 4416): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/OpenGLRenderer( 3216): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
I/ActivityManager( 1018): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4416 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
D/OpenGLRenderer( 3216): Enabling debug mode 0
I/ActivityManager( 1018): Killing 3583:com.google.android.onetimeinitializer/u0a14 (adj 15): empty #31
I/SamsungIME( 1815): getCurrentKeyboard
I/SamsungIME( 1815): getTextKeyboard
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/ActivityManager( 1018): bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
I/GFX raster( 3879): took 0.869847ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8af5018 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8e67dd0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3879): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,D/SamsungIME( 1815): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/ActivityManager( 1018): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:assistant
I/AMMetaDataParserService( 3879): Resource data:2131099648
,I/GCoreUlr( 1868): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,D/TimaKeyStoreProvider( 4416): TimaSignature is unavailable
,D/ActivityThread( 4416): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/AMMetaDataParserService( 3879): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3879): getResourceTypeNamexml
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3879): took 0.694271ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8e67e10 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8e67dd0 counterpartCT=4 counterpartW=96 counterparth=96
,I/GCoreUlr( 1868): Unbound from all location providers
,I/GCoreUlr( 1868): Place inference reporting - stopped
,I/AMMetaDataParserService( 3879): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/dex2oat ( 4129): Verification of void maps.dz.ar$g.f() took 114.440ms
,D/StatusChecker( 4416): onReceive : android.intent.action.BOOT_COMPLETED
,D/StatusBar.NetworkController( 1190): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020543/com.android.systemui:drawable/stat_sys_signal_out mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1190): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1190): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1190): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1190): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1190): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3879): took 0.650469ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8af0190 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8abe688 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3574/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10014/pid_3583/cgroup.procs: No such file or directory
,I/GCoreUlr( 1868): DispatchingService.onDestroy()
I/GCoreUlr( 1868): Stopping handler for UlrDispSvcFast
,I/StatusChecker( 4416): onReceive : net.mt.init : DONE
,W/art     ( 4179): Suspending all threads took: 10.163ms
D/PowerManagerService( 1018): [s] UserActivityState : 1 -> 2
,W/jxcore-log( 4179): Initializing JXcore engine
,W/jxcore-log( 4179): JXcore engine is ready
,I/GCoreUlr( 1868): Unbound from all location providers
,I/GCoreUlr( 1868): Place inference reporting - stopped
,I/AMMetaDataParserService( 3879): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/art     ( 4179): Background sticky concurrent mark sweep GC freed 25700(2MB) AllocSpace objects, 0(0B) LOS objects, 0% free, 24MB/24MB, paused 11.277ms total 53.551ms
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.pagebuddynotisvc, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,I/GFX raster( 3879): took 0.619114ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8aec488 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8e67dd0 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4440): MountEmulatedStorage()
,I/libpersona( 4440): KNOX_SDCARD checking this for 10116
E/Zygote  ( 4440): v2
I/libpersona( 4440): KNOX_SDCARD not a persona
,I/SELinux ( 4440): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4440): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 4440): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1018): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4440 uid=10116 gids={50116, 9997} abi=armeabi-v7a,
,I/AMMetaDataParserService( 3879): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/GFX raster( 3879): took 0.673177ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8aeffa0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8abe688 counterpartCT=4 counterpartW=96 counterparth=96,
,I/art     (  306): Explicit concurrent mark sweep GC freed 8756(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 730us total 36.274ms
,I/AMMetaDataParserService( 3879): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/TimaKeyStoreProvider( 4440): TimaSignature is unavailable
D/ActivityThread( 4440): Added TimaKeyStore provider
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 624us total 21.658ms
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3879): took 0.682136ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8e66e28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8e67dd0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3879): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/art     (  306): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 700us total 19.032ms
,E/audit   ( 1937): type=1400 msg=audit(1457959160.891:205): avc:  denied  { ioctl } for  pid=4360 comm="Thread-643" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
E/audit   ( 1937):  SEPF_SM-A500FU_5.0.2-1_0038
E/audit   ( 1937): type=1300 msg=audit(1457959160.891:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=4 a3=9ad998f8 items=0 ppid=306 ppcomm=main pid=4360 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-643" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1937): type=1320 msg=audit(1457959160.891:205): 
,I/PageBuddyNotiSvc( 4440): Intent received : action=android.intent.action.BOOT_COMPLETED
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3879): took 0.718125ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8af5018 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8abe688 counterpartCT=4 counterpartW=96 counterparth=96
,W/jxcore-log( 4179): Starting JXcore engine
,W/ContextImpl( 4440): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3879): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:assistant
I/AMMetaDataParserService( 3879): Resource data:2131099648
,I/AMMetaDataParserService( 3879): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3879): getResourceTypeNamexml
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3879): took 0.710938ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8e67e10 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8e67dd0 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/PageBuddyNotiSvc( 4440): onCreate mCpBitFlag=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3879): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,E/Zygote  ( 4456): MountEmulatedStorage()
I/libpersona( 4456): KNOX_SDCARD checking this for 10125
E/Zygote  ( 4456): v2
I/libpersona( 4456): KNOX_SDCARD not a persona
I/GFX raster( 3879): took 0.658646ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8af0190 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8e67b20 counterpartCT=4 counterpartW=96 counterparth=96
I/ActivityManager( 1018): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4456 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 4456): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/AMMetaDataParserService( 3879): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/SELinux ( 4456): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4456): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3879): took 0.658698ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8aec488 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8e67b20 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4456): TimaSignature is unavailable
,D/ActivityThread( 4456): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3879): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/ResourcesManager( 4456): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4456): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4456): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3879): took 0.667292ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8aeffa0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8e67b20 counterpartCT=4 counterpartW=96 counterparth=96
W/jxcore-log( 4179): Platform android
W/jxcore-log( 4179): 
W/jxcore-log( 4179): Process ARCH arm
W/jxcore-log( 4179): 
,I/AMMetaDataParserService( 3879): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,W/dex2oat ( 4129): Verification of void maps.ei.bg$e.<init>(android.content.res.Resources, int) took 145.219ms
,W/ActivityThread( 4340): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/QuickConnect( 4456): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3879): took 0.626406ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8e66e28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8e67b20 counterpartCT=4 counterpartW=96 counterparth=96
,D/QuickConnect( 4456): Util.setSCRunningSetting - [value]0
,I/AMMetaDataParserService( 3879): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/SettingsProvider( 1018): name = scon_is_running
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10125
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,I/System.out( 4340): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,I/System.out( 4340): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 4340): (HTTPLog)-Static: isShipBuild true
I/System.out( 4340): (HTTPLog)-Thread-659-50979241: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 4340): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  277): uids 10107
D/EnterpriseController(  277): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  277): getNetworkForDns: using netid 502 for uid 10107,
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10125
,I/SecKeyguardClockSingleView( 1190): Ignore. Because it is same clock text
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3879): took 0.849323ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8af5018 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8e67b20 counterpartCT=4 counterpartW=96 counterparth=96
,I/QuickConnect( 4456): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,I/QuickConnect( 4456): PeriphStartReceiver.onReceive - no need to start
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.app.sbrowser, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3879): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/ActivityManager( 1018): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4473 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,E/Zygote  ( 4473): MountEmulatedStorage()
I/ActivityManager( 1018): Killing 3611:com.wssnps/1000 (adj 15): empty #31
,E/Zygote  ( 4473): v2
,I/libpersona( 4473): KNOX_SDCARD checking this for 10131
,I/libpersona( 4473): KNOX_SDCARD not a persona
,I/SELinux ( 4473): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4473): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4473): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/System.out( 4340): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/TimaKeyStoreProvider( 4473): TimaSignature is unavailable
,D/ActivityThread( 4473): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
,I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:assistant
I/AMMetaDataParserService( 3879): Resource data:2131099648
W/dex2oat ( 4129): Verification of void maps.k.b$b.a(byte[], byte[]) took 114.429ms
,I/AMMetaDataParserService( 3879): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3879): getResourceTypeNamexml
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3879): took 0.694741ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8e67e10 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8e67b20 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3879): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/ResourcesManager( 4473): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4473): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 4473): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 4473): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3879): took 0.637291ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8af0190 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8e67b20 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3879): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3879): took 0.803646ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8aec488 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8e67b20 counterpartCT=4 counterpartW=96 counterparth=96
,W/com.google.a.a.b.d.a( 4340): Application name is not set. Call Builder#setApplicationName.
,I/AMMetaDataParserService( 3879): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3879): took 0.757448ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8aeffa0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8e67b20 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/SBrowserFeatureFlag( 4473): initialized in static block : loadCscFeatureValue() succeed! 
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3879): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/ManifestProvider( 4473): onCreate()
,E/NetworkSettingsReceiver( 4473): onReceive: android.intent.action.BOOT_COMPLETED
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3879): took 0.781302ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8e66e28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8e67b20 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3879): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,W/art     ( 4340): Suspending all threads took: 8.594ms
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3611/cgroup.procs: No such file or directory
,I/jxcore-log( 4179): JXcore Cordova bridge is ready!
I/jxcore-log( 4179): 
,W/jxcore-log( 4179): JXcore engine is started
,I/org.thaliproject.p2p.ThaliPermissions( 4179): execute: REQUEST_ACCESS_COARSE_LOCATION
,E/SBrowserFeatureFlag( 4473): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@2ddfedae
,D/SBrowserFeatureFlag( 4473): initialize : initSupportedPkg() succeed! 
I/VerificationLog( 4473): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,I/chromium( 4179): [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/jxcore  ( 4179): Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js,
E/jxcore  ( 4179): Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
E/Zygote  ( 4492): MountEmulatedStorage(),
E/Zygote  ( 4492): v2
I/GFX raster( 3879): took 0.917396ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8af5018 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8e67b20 counterpartCT=4 counterpartW=96 counterparth=96
,I/libpersona( 4492): KNOX_SDCARD checking this for 10135,
I/ActivityManager( 1018): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4492 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/libpersona( 4492): KNOX_SDCARD not a persona,
I/ActivityManager( 1018): Killing 2789:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,I/SELinux ( 4492): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4492): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4492): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/chromium( 4179): [INFO:CONSOLE(62)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (62)
,I/chromium( 4179): [INFO:CONSOLE(33)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (33)
,D/FocusedStackFrame( 1018): Set to : 0
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/InputDispatcher( 1018): Focused application set to: xxxx
I/AMMetaDataParserService( 3879): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
D/InputDispatcher( 1018): Focus left window: 4179
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
D/PermissionCache(  257): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (785 us)
,D/TimaKeyStoreProvider( 4492): TimaSignature is unavailable
,D/ActivityThread( 4492): Added TimaKeyStore provider
,I/CalendarProvider2( 4369): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/PluginManager( 4179): THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 62ms. Plugin should use CordovaInterface.getThreadPool().
,D/CustomFrequencyManagerService( 1018): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1018): mDVFSHelper.acquire()
,V/WindowOrientationListener( 1018): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1018): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1018): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,W/ResourcesManager( 4492): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4492): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4492): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3879): getResourcePackageName:assistant
I/AMMetaDataParserService( 3879): Resource data:2131099648
,I/AMMetaDataParserService( 3879): getResourceName:com.android.mms:xml/assistant_messaging,
I/AMMetaDataParserService( 3879): getResourceTypeNamexml
E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/GFX raster( 3879): took 0.708698ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8e67e10 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8e67b20 counterpartCT=4 counterpartW=96 counterparth=96,
,D/Launcher( 1490): onRestart, Launcher: 769650094
,I/AMMetaDataParserService( 3879): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523,
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,D/StatusBar.NetworkController( 1190): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1190): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1190): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1190): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1190): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1190): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
I/DBG_POLICYDM( 4135): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 4135): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,D/Launcher( 1490): onStart, Launcher: 769650094
,D/Launcher.HomeView( 1490): onStart
I/ActivityManager( 1018): Killing 3704:com.android.managedprovisioning/u0a22 (adj 15): empty #31
,D/Launcher( 1490): onResume, Launcher: 769650094
,D/SettingsProvider( 1018): name = kids_home_mode
,D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
,D/SettingsProvider( 1018): selectionArgs: 10007
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
,D/SettingsProvider( 1018): ret = -1
,D/Launcher.HomeView( 1490): onResume
,I/DBG_POLICYDM( 4135): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts,
,I/DBG_POLICYDM( 4135): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 4135): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,D/SensorService( 1018): [SO] activate (ident=0xb924a730, enabled=0)
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,I/DBG_POLICYDM( 4135): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,D/Launcher( 1490): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/MenuAppsGridFragment( 1490): onResume
,D/ActivityManager( 1018): handle home activity for 0
I/WallpaperManagerService( 1018): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1018): post home show event for user 0
D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
,I/SurfaceFlinger(  257): id=13 createSurf (720x1280),1 flag=4, Mauncher
,D/SensorManager( 1018): unregisterListener ::   
,I/Sensors ( 1018): AccelerometerSensor(0) setDelay : 200000000(ns)
,D/SensorService( 1018): [SO] changed settle time [0]
D/SensorService( 1018): [SO] setDelay [200000000]
D/SensorService( 1018): [SO] activate (ident=0xb8eb4db0, enabled=1)
D/SensorService( 1018): [SO] AR_init
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,I/DBG_POLICYDM( 4135): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/SensorManager( 1018): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,D/WallpaperManagerService( 1018):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 1018): handleHomeShow for 0 and current 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3879): took 0.754844ms for 96*96 texture 0
,D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8af0190 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8e67b20 counterpartCT=4 counterpartW=96 counterparth=96
,W/libprocessgroup( 1018): failed to open /acct/uid_10120/pid_2789/cgroup.procs: No such file or directory
,D/InputDispatcher( 1018): Focus entered window: 1490
,D/SRIB_DCS( 1490): log_dcs ThreadedRenderer::initialize entered! 
,I/AMMetaDataParserService( 3879): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519,
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
I/GFX raster( 3879): took 0.669843ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8aec488 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8e67b20 counterpartCT=4 counterpartW=96 counterparth=96
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,I/AMMetaDataParserService( 3879): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/daemonapp( 1329): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/ActivityManager( 1018): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/Launcher( 1490): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,W/libprocessgroup( 1018): failed to open /acct/uid_10022/pid_3704/cgroup.procs: No such file or directory
D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/PanelView( 1190): There is/are notification(s) 
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/IInputConnectionWrapper( 4179): showStatusIcon on inactive InputConnection
,D/SamsungIME( 1815): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,I/Timeline( 1490): Timeline: Activity_idle id: android.os.BinderProxy@13e337dd time:49176
,D/PersonaManager( 1018): isKioskContainerExistOnDevice
,I/dex2oat ( 4129): dex2oat took 5.566s (threads: 4)
,D/ActivityManager( 1018): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3879): took 0.807188ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8aeffa0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb900b0d0 counterpartCT=4 counterpartW=96 counterparth=96
D/DexOptUtils( 2070): Odex created at:/data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.dex
D/DexOptUtils( 2070): Set odex to world readable.
,D/DexOptUtils( 2070): Renamed odex to /data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.odex
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,I/AMMetaDataParserService( 3879): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3879): took 0.629322ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8e66e28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8e67b20 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3879): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/Zygote  ( 4519): MountEmulatedStorage()
,E/Zygote  ( 4519): v2
I/libpersona( 4519): KNOX_SDCARD checking this for 10139
I/libpersona( 4519): KNOX_SDCARD not a persona
,I/SELinux ( 4519): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4519): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4519): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/SensorService( 1018): [SO] Reset Rotation Old [100], Init [1],
I/ActivityManager( 1018): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4519 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
I/ActivityManager( 1018): Displayed Component not be shown by security: +338ms
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3879): took 0.787135ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8af5018 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb900b0d0 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4519): TimaSignature is unavailable
,D/ActivityThread( 4519): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3879): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
,I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3879): getResourcePackageName:assistant
,I/AMMetaDataParserService( 3879): Resource data:2131099648
,I/AMMetaDataParserService( 3879): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3879): getResourceTypeNamexml
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/AndroidRuntime( 4507): 
D/AndroidRuntime( 4507): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,I/GFX raster( 3879): took 0.934686ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8e67e10 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8e67b20 counterpartCT=4 counterpartW=96 counterparth=96
,D/AndroidRuntime( 4507): CheckJNI is OFF
,D/AndroidRuntime( 4507): readGMSProperty: start
D/AndroidRuntime( 4507): readGMSProperty: already setted!!
D/AndroidRuntime( 4507): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 4507): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 4507): readGMSProperty: end
D/AndroidRuntime( 4507): addProductProperty: start
,D/SamsungIME( 1815): [SwiftkeyWrapper] currentLangauge : 1701729619
,I/AMMetaDataParserService( 3879): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3879): took 0.837344ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8af0190 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb900b0d0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3879): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3879): took 0.762552ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8aec488 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8e67b20 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3879): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
D/CustomFrequencyManagerService( 1018): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
I/art     ( 1018): Explicit concurrent mark sweep GC freed 32806(1718KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 30MB/45MB, paused 2.671ms total 184.491ms
W/ActivityManager( 1018): mDVFSHelper.release()
D/CustomFrequencyManagerService( 1018): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@11
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3879): took 0.664687ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8aeffa0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb900b0d0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3879): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/Watchdog( 1018): !@Sync 1
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SensorService( 1018): [SO] currT = 49470097532, prevT = 48990149876, diff = 479947656, [0.134 0.402 10.151]
D/SensorService( 1018): [SO] 0.134 0.402 10.151
D/SensorService( 1018): [SO] [100 -> 255]
E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3879): took 0.629635ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8e66e28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8e67b20 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023,
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 3879): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,W/ResourcesManager( 4519): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 4519): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4519): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4519): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 4519): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,V/Herrevad( 2070): NQAS connected
,I/ActivityManager( 1018): Killing 3374:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SettingsProvider( 1018): name = audio_safe_volume_state
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3879): took 0.749166ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb8af5018 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb900b0d0 counterpartCT=4 counterpartW=96 counterparth=96
,E/AffinityControl( 4507): AffinityControl: registerfunction enter
,W/libprocessgroup( 1018): failed to open /acct/uid_10015/pid_3374/cgroup.procs: No such file or directory
I/AMMetaDataParserService( 3879): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
W/ContextImpl( 3879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
I/AMMetaDataParserService( 3879): Resource data:Loop for ,running activitycom.android.mms.saverestore.RestorePreviewActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3879): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
,I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
,I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
,I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
,I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
,E/Zygote  ( 4551): MountEmulatedStorage()
E/Zygote  ( 4551): v2
I/libpersona( 4551): KNOX_SDCARD checking this for 10145
I/libpersona( 4551): KNOX_SDCARD not a persona
I/SELinux ( 4551): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
D/AndroidRuntime( 4507): Calling main entry com.android.commands.pm.Pm
,I/SELinux ( 4551): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4551): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1018): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4551 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,D/PackageManager( 1018): START PACKAGE DELETE: observer{458158156}
D/PackageManager( 1018): pkg{<packageName>}
D/PackageManager( 1018): user{0}
D/PackageManager( 1018): caller{2000}
D/PackageManager( 1018): flags{2}
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved : true
,D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved before exit: true
,D/PackageManager( 1018): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
D/PackageManager( 1018): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,D/PackageManagerService( 1018): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManager( 1018): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManagerService( 1018): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled :  enabled true
,I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:assistant
I/AMMetaDataParserService( 3879): Resource data:2131165197
,D/TimaKeyStoreProvider( 4551): TimaSignature is unavailable
,D/ActivityThread( 4551): Added TimaKeyStore provider
D/PackageManager( 1018): !@killApplicatoin: 10155, uninstall pkg
,I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10155 user=-1: uninstall pkg
I/ActivityManager( 1018): Killing 4179:com.test.thalitest/u0a155 (adj 1): stop com.test.thalitest cause uninstall pkg
,W/ResourcesManager( 3879): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3879): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3879): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3879): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3879): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3879): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 3879): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3879): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3879): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3879): getResourceTypeNamexml
,I/SurfaceFlinger(  257): id=11 Removed NainActivit (7/9),
I/SurfaceFlinger(  257): id=11 Removed NainActivit (-2/9)
,I/AMMetaDataParserService( 3879): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/AMMetaDataParserService( 3879): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/AMMetaDataParserService( 3879): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/AMMetaDataParserService( 3879): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3879): getResourcePackageName:assistant
I/AMMetaDataParserService( 3879): Resource data:2131165197
,I/AMMetaDataParserService( 3879): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3879): getResourceTypeNamexml
,I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{e913a20 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t11} time:49725
,I/AMMetaDataParserService( 3879): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/ActivityManager( 1018): Force stopping com.test.thalitest appid=10155 user=0: pkg removed
,D/CustomFrequencyManagerService( 1018): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@11
,W/ActivityManager( 1018): CustomStartingWindow se packge removed so remove capture also
,I/AMMetaDataParserService( 3879): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,W/ResourcesManager( 4551): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4551): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4551): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4551): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4551): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3879): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/AMMetaDataParserService( 3879): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,E/SamsungIME( 1815): mOCRHelper is null
,I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.cooliris.media.Gallery
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:assistant
I/AMMetaDataParserService( 3879): Resource data:2131165197
,W/GeofencerStateMachine( 1868): Ignoring removeGeofence because network location is disabled.
,I/AMMetaDataParserService( 3879): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 3879): getResourceTypeNamexml
,I/AMMetaDataParserService( 3879): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,E/SMD     (  287): DCD OFF
,V/NetworkStats( 1018): removeUidsLocked() for UIDs [10155]
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,V/NetworkStats( 1018): performPollLocked(flags=0x3)
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
,D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
,I/AMMetaDataParserService( 3879): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
,I/ActivityManager( 1018): Killing 3684:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,V/NetworkStats( 1018): performPollLocked() took 13ms
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/RegisteredComponentCache( 1453): Collect Tech packages for Knox
,I/AMMetaDataParserService( 3879): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/PersonaManager( 1453): isKioskContainerExistOnDevice
,I/AMMetaDataParserService( 3879): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
W/ContextImpl( 3879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.Pho,toNote
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,I/ConfigService( 1868): onCreate
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
,I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
I/AMMetaDataParserService( 3879): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.keyguard.layout
I/AMMetaDataParserService( 3879): getResourcePackageName:assistant
I/AMMetaDataParserService( 3879): Resource data:2131099648
,W/art     ( 1018): Suspending all threads took: 6.657ms
,W/ResourcesManager( 3879): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 3879): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
D/RCPManagerService( 1018): exchangeData() failure , invalid userId
W/ResourcesManager( 3879): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3879): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 3879): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3879): getResourceName:com.sec.android.app.camera:xml/assistant
I/AMMetaDataParserService( 3879): getResourceTypeNamexml
,D/PersonaManager( 1453): isKioskContainerExistOnDevice
,D/RegisteredServicesCache( 1453): empty dynamic service
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3879): Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,D/RCPManagerService( 1018): PackageReceiver onReceive()
,I/HarmonyEASService( 1018): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/KnoxMUMContainerPolicy( 1018): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/OTPFW   ( 1018): PackageRemovalReceiver::onReceive Enter
,D/OTPFW   ( 1018): OtpDbHelper::getInstance New instance created
,D/OTPFW   ( 1018): DBIntegrity::getInstance - New instance created
,I/AMMetaDataParserService( 3879): Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,D/OTPFW   ( 1018): PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10155 container id = 0
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
W/ContextImpl( 3879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,I/OTPFW   ( 1018): ProvisionData::getAllEntries Enter
,E/OTPFW   ( 1018): ProvisionData::getAllEntries Table is empty
,D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 26559(2017KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 30MB/46MB, paused 10.580ms total 314.764ms
,D/EnterpriseDeviceManagerService( 1018): Package has changed for user 0
D/EnterpriseDeviceManagerService( 1018): Admin package name: com.google.android.gms
,D/ActivityManager( 1018): getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,D/JobSchedulerService( 1018): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1018): uID is 10155
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
,V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.test.thalitest
D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
,E/Zygote  ( 4581): MountEmulatedStorage()
E/Zygote  ( 4581): v2
D/RCPManagerService( 1018): exchangeData() failure , invalid userId
I/libpersona( 4581): KNOX_SDCARD checking this for 10072
I/libpersona( 4581): KNOX_SDCARD not a persona
I/SELinux ( 4581): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/PackageManager( 1018): delete codoeFile: 
,I/ActivityManager( 1018): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4581 uid=10072 gids={50072, 9997} abi=armeabi-v7a
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
W/TextServicesManagerService( 1018): no available spell checker services found
I/SELinux ( 4581): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4581): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
,D/ActivityManager( 1018): startService callerProcessName:com.android.email, calleePkgName: com.android.email
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,D/SSRM:aZ ( 1018): MSG_TYPE_APP_REMOVED::
,V/EnterpriseBillingPolicy( 1018): uID is 10155
,V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
I/AASA_removePackage( 1018): UID=10155 Target=com.test.thalitest
D/AASAuninstall( 1018): userId = 0, info.removedAppID = 10155, info.uid = 10155, packageName = com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.test.thalitest
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
V/AlarmManagerEXT( 1018): com.test.thalitest(10155) is removed.
,D/PackageManager( 1018): result of delete: 1{458158156}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/AndroidRuntime( 4507): Shutting down VM
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/TimaKeyStoreProvider( 4581): TimaSignature is unavailable
,D/ActivityThread( 4581): Added TimaKeyStore provider
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.GridSettings
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:assistant
I/AMMetaDataParserService( 3879): Resource data:2131165220
,D/PackageManager( 1018): [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
D/PackageManager( 1018): userId{-1}
D/PackageManager( 1018): andCode{true}
,W/ResourcesManager( 3879): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ResourcesManager( 3879): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 3879): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3879): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 3879): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
W/ResourcesManager( 3879): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3879): getResourceName:com.android.settings:xml/assistant
,I/AMMetaDataParserService( 3879): getResourceTypeNamexml
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/GFX raster( 3879): took 1.226094ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb9219718 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9219448 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3879): Icon data: ResourceSearch2131363521com.android.settings.Search2130837580
,D/BadgeProvider( 4581): onCreate
,D/BadgeProvider( 4581): DatabaseHelper
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.android.exchange, hostingType: broadcast
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/BadgeProvider( 4581): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,E/        ( 3879): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3879): took 0.899583ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3879): Bitmap=0xb9221058 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9219a98 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3879): Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,E/Zygote  ( 4602): MountEmulatedStorage(),
I/libpersona( 4602): KNOX_SDCARD checking this for 10146
E/Zygote  ( 4602): v2
I/libpersona( 4602): KNOX_SDCARD not a persona
I/SELinux ( 4602): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4602): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4602): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.SubSettings
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/ActivityManager( 1018): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4602 uid=10146 gids={50146, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
I/ActivityManager( 1018): Killing 3738:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAG,MENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageN,ame:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3879): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.TetherSettings
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
W/ContextImpl( 3879): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.LanguageSettings
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3879): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3879): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.DockSettings
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3879): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3879): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.ManageApplications
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 3879): Resourc,e data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/ActivityManager( 1018): Killing 3762:com.sec.factory.camera/1000 (adj 15): empty #31
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.SetProfileOwner
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3879): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
,I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.SViewColor2014
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.SViewStyleClock
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
I/AMMetaDataParserService( 38,79): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
D/TaskPersister( 1018): removeObsoleteFile: deleting file=12_task.xml
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
D/TaskPersister( 1018): removeObsoleteFile: deleting file=12_task_thumbnail.png
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.,NotificationPanelSettings
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
W/ResourcesManager( 1018): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
W/ResourcesManager( 1018): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
W/ResourcesManager( 1018): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.se,ttings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePac,kageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
W/ResourcesManager( 4602): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerAct,ivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 3879): Resourc,e data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
,I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaD,ataParserService( 3879): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
D/UsbSettingsManager( 1018): clearDefaults: com.test.thalitest
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 3879): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3879): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 3879): Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
D/TimaKeyStoreProvider( 4602): TimaSignature is unavailable
D/ActivityThread( 4602): Added TimaKeyStore provider
W/ResourceType( 1018): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/libprocessgroup( 1018): failed to open /acct/uid_10094/pid_3684/cgroup.procs: No such file or directory
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/art     ( 4507): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3762/cgroup.procs: No such file or directory
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3738/cgroup.procs: No such file or directory
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/CrashAnrDetector( 1018): onPackageRemoved : com.test.thalitest
,I/ActivityManager( 1018): Killing 3781:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,D/BadgeProvider( 4581): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 4581): sendNotify, [notify] : null
D/BadgeProvider( 4581): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4581): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4581): update, [UpdateCount] : 1
,D/Launcher.Model( 1490): reloadBadges entered.
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,D/WallpaperManager( 1490): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1490): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1490): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,E/SQLiteLog( 2070): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 2070): (3850) statement aborts at 43: [INSERT INTO local_reports(ssid,bssid,network_type,package,api,timestamp_millis,version_code,security_type,throughput_bps,latency_micros) VALUES (?,?,?,?,?,?,?,?,?,?)] disk I/O error
,D/ActivityManager( 1018): startService callerProcessName:com.android.exchange, calleePkgName: com.android.exchange
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.exchange/com.android.exchange.service.ExchangeBroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1018): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1018): startProcessLocked calleePkgName: com.sec.android.app.SecSetupWizard, hostingType: broadcast
,E/SQLiteDatabase( 2070): Error inserting ssid=NG700 bssid=f4:f2:6d:22:99:3e network_type=1 package=com.google.android.apps.maps api=1 timestamp_millis=1457959163206 version_code=909010123 security_type=4 throughput_bps=1406 latency_micros=249325
E/SQLiteDatabase( 2070): android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
E/SQLiteDatabase( 2070): 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
E/SQLiteDatabase( 2070): 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
E/SQLiteDatabase( 2070): 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
E/SQLiteDatabase( 2070): 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
E/SQLiteDatabase( 2070): 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1609)
E/SQLiteDatabase( 2070): 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1479)
E/SQLiteDatabase( 2070): 	at com.google.android.gms.herrevad.services.g.a(:com.google.android.gms:206)
E/SQLiteDatabase( 2070): 	at com.google.android.gms.herrevad.services.g.a(:com.google.android.gms:38)
E/SQLiteDatabase( 2070): 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
E/SQLiteDatabase( 2070): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 2070): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 2070): 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
E/SQLiteDatabase( 2070): 	at java.lang.Thread.run(Thread.java:818)
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1018): failed to open /acct/uid_10100/pid_3781/cgroup.procs: No such file or directory
,E/SharedPreferencesImpl( 2070): Couldn't rename file /data/data/com.google.android.gms/shared_prefs/herrevad.xml to backup file /data/data/com.google.android.gms/shared_prefs/herrevad.xml.bak
,E/Zygote  ( 4620): MountEmulatedStorage()
,E/Zygote  ( 4620): v2
I/libpersona( 4620): KNOX_SDCARD checking this for 1000
I/libpersona( 4620): KNOX_SDCARD not a persona
,I/ActivityManager( 1018): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4620 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1018): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
I/SELinux ( 4620): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/SELinux ( 4620): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4620): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 1018): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,I/ActivityManager( 1018): Killing 3468:com.sec.pcw.device/1000 (adj 15): empty #31
,E/SQLiteLog( 1868): (28) failed to open "/data/data/com.google.android.gms/databases/playlog.db" with flag (131138) and mode_t (0) due to error (30)
,E/SQLiteDatabase( 1868): Failed to open database '/data/data/com.google.android.gms/databases/playlog.db'.
E/SQLiteDatabase( 1868): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/SQLiteDatabase( 1868): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/SQLiteDatabase( 1868): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/SQLiteDatabase( 1868): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/SQLiteDatabase( 1868): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/SQLiteDatabase( 1868): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/SQLiteDatabase( 1868): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/SQLiteDatabase( 1868): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/SQLiteDatabase( 1868): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/SQLiteDatabase( 1868): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/SQLiteDatabase( 1868): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/SQLiteDatabase( 1868): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 1868): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/SQLiteDatabase( 1868): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/SQLiteDatabase( 1868): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/SQLiteDatabase( 1868): 	at com.google.android.gms.playlog.store.r.d(:com.google.android.gms:97)
E/SQLiteDatabase( 1868): 	at com.google.android.gms.clearcut.service.a.a(:com.google.android.gms:153)
E/SQLiteDatabase( 1868): 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
E/SQLiteDatabase( 1868): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/SQLiteDatabase( 1868): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/SQLiteDatabase( 1868): 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
E/SQLiteDatabase( 1868): 	at java.lang.Thread.run(Thread.java:818)
,E/ClearcutLoggerIntentService( 1868): not an error (code 0): Could not open the database in read/write mode.
E/ClearcutLoggerIntentService( 1868): android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
E/ClearcutLoggerIntentService( 1868): 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
E/ClearcutLoggerIntentService( 1868): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
E/ClearcutLoggerIntentService( 1868): 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
E/ClearcutLoggerIntentService( 1868): 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
E/ClearcutLoggerIntentService( 1868): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
E/ClearcutLoggerIntentService( 1868): 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
E/ClearcutLoggerIntentService( 1868): 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
E/ClearcutLoggerIntentService( 1868): 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
E/ClearcutLoggerIntentService( 1868): 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
E/ClearcutLoggerIntentService( 1868): 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
E/ClearcutLoggerIntentService( 1868): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/ClearcutLoggerIntentService( 1868): 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
E/ClearcutLoggerIntentService( 1868): 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
E/ClearcutLoggerIntentService( 1868): 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
E/ClearcutLoggerIntentService( 1868): 	at com.google.android.gms.playlog.store.r.d(:com.google.android.gms:97)
E/ClearcutLoggerIntentService( 1868): 	at com.google.android.gms.clearcut.service.a.a(:com.google.android.gms:153)
E/ClearcutLoggerIntentService( 1868): 	at com.google.android.gms.common.service.f.run(:com.google.android.gms:176)
E/ClearcutLoggerIntentService( 1868): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
E/ClearcutLoggerIntentService( 1868): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
E/ClearcutLoggerIntentService( 1868): 	at com.google.android.gms.common.util.a.c.run(:com.google.android.gms:17)
E/ClearcutLoggerIntentService( 1868): 	at java.lang.Thread.run(Thread.java:818)
,W/ActivityManager( 1018): getTasks: caller 10145 does not hold GET_TASKS; limiting output
,D/TimaKeyStoreProvider( 4620): TimaSignature is unavailable
,D/ActivityThread( 4620): Added TimaKeyStore provider
,I/Process ( 4551): Sending signal. PID: 4551 SIG: 9

```
