#### Test 625090943f585e4_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
D/Ads     ( 4002): Skipping gmscore version check
D/FileApkUtils( 2088): Optimizing (staging complete)
D/FileApkUtils( 2088): Optimizing: DynamiteModules-prod.apk [0224a548494bce36274e23f9f1b42d4fbe3d4d8de53a7872e503f8974e43c3c3]
I/art     ( 2088): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000000@DynamiteModules-prod.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk': Failed to open oat filename for reading: No such file or directory
D/DexOptUtils( 2088): Module /data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk appears to be unoptimized.
D/DexOptUtils( 2088): Lollipop platform, using <isa> directory.
D/DexOptUtils( 2088): Instantiating DexClassLoader to force creation of odex.
D/DexOptUtils( 2088): Primary ABI of odexing process is armeabi-v7a
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
--------- beginning of system
D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
V/Babel   ( 3947): babel boot account: thalitester@gmail.com
W/Babel   ( 3947): EsDatabaseHelper.getDatabaseHelper() [called on main thread]
W/Babel   ( 3947): java.lang.Exception
W/Babel   ( 3947): 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
W/Babel   ( 3947): 	at aes.a(SourceFile:145)
W/Babel   ( 3947): 	at ckh.<init>(SourceFile:103)
W/Babel   ( 3947): 	at ckh.a(SourceFile:67)
W/Babel   ( 3947): 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
W/Babel   ( 3947): 	at bhn.a(SourceFile:301)
W/Babel   ( 3947): 	at bhn.a(SourceFile:137)
W/Babel   ( 3947): 	at bhn.a(SourceFile:126)
W/Babel   ( 3947): 	at bhn.a(SourceFile:159)
W/Babel   ( 3947): 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
W/Babel   ( 3947): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/Babel   ( 3947): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/Babel   ( 3947): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/Babel   ( 3947): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/Babel   ( 3947): 	at android.os.Looper.loop(Looper.java:145)
W/Babel   ( 3947): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/Babel   ( 3947): 	at java.lang.reflect.Method.invoke(Native Method)
W/Babel   ( 3947): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/Babel   ( 3947): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/Babel   ( 3947): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3878): took 0.541823ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb76fd960 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76fe270 counterpartCT=4 counterpartW=96 counterparth=96
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.service.recording.FitRecordingBroker; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 3878): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:assistant
I/AMMetaDataParserService( 3878): Resource data:2131034113
I/AMMetaDataParserService( 3878): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3878): getResourceTypeNamexml
E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3878): took 0.816562ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb76f9248 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb76fe100 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3878): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
I/dex2oat ( 4100): ----------------------------------------------------
D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
I/dex2oat ( 4100): <SS>: S T A R T I N G . . .
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
I/dex2oat ( 4100): <SS>: Zip is absent. Canceled.
I/dex2oat ( 4100): /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk --oat-fd=40 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
D/ActivityManager( 1016): startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4109): MountEmulatedStorage()
E/Zygote  ( 4109): v2
I/libpersona( 4109): KNOX_SDCARD checking this for 1000
I/libpersona( 4109): KNOX_SDCARD not a persona
I/SELinux ( 4109): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=4109 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 4109): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4109): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3878): took 0.889323ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb76f9248 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb76ff408 counterpartCT=4 counterpartW=96 counterparth=96
I/ActivityManager( 1016): Killing 3326:com.policydm/1000 (adj 15): empty #31
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
W/QCamera2Factory(  284): getCameraInfo: E, camera_id = 0
W/QCamera2Factory(  284): getCameraInfo: X
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/QCamera2Factory(  284): getCameraInfo: E, camera_id = 1
W/QCamera2Factory(  284): getCameraInfo: X
I/art     (  308): Explicit concurrent mark sweep GC freed 8758(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 634us total 39.807ms
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 630us total 18.389ms
I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 624us total 17.060ms
D/TimaKeyStoreProvider( 4109): TimaSignature is unavailable
D/ActivityThread( 4109): Added TimaKeyStore provider
D/ChimeraCfgMgr( 1842): Reading stored module config
W/VideoCapabilities( 3947): Unrecognized profile 2130706433 for video/avc
D/Finsky  ( 4002): [1] GmsCoreHelper.cleanupNlp: result=false type=4
W/AudioCapabilities( 3947): Unsupported mime audio/evrc
I/DBG_DM  ( 3196): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
D/ActivityManager( 1016): startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
W/AudioCapabilities( 3947): Unsupported mime audio/qcelp
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
W/AudioCapabilities( 3947): Unsupported mime audio/mpeg-L1
W/AudioCapabilities( 3947): Unsupported mime audio/mpeg-L2
D/WearableService( 1842): callingUid 10012, callindPid: 1842
I/AMMetaDataParserService( 3878): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
W/AudioCapabilities( 3947): Unsupported mime audio/x-ms-wma
W/InstanceID/Rpc( 2088): Found 10012
D/Finsky  ( 4002): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
W/AudioCapabilities( 3947): Unsupported mime audio/x-ima
W/AudioCapabilities( 3947): Unsupported mime audio/qcelp
E/GmsWearableNodeHelper( 1842): GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
W/AudioCapabilities( 3947): Unsupported mime audio/evrc
E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3878): took 0.845156ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb76f9210 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76f9890 counterpartCT=4 counterpartW=96 counterparth=96
D/AndroidRuntime( 4106): 
D/AndroidRuntime( 4106): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 4106): CheckJNI is OFF
D/AndroidRuntime( 4106): readGMSProperty: start
D/AndroidRuntime( 4106): readGMSProperty: already setted!!
D/AndroidRuntime( 4106): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 4106): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 4106): readGMSProperty: end
D/AndroidRuntime( 4106): addProductProperty: start
W/VideoCapabilities( 3947): Unsupported mime video/wvc1
W/VideoCapabilities( 3947): Unsupported mime video/x-ms-wmv
I/AMMetaDataParserService( 3878): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
W/VideoCapabilities( 3947): Unrecognized profile/level 32768/2 for video/mp4v-es
W/VideoCapabilities( 3947): Unsupported mime video/wvc1
W/VideoCapabilities( 3947): Unsupported mime video/x-ms-wmv
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/VideoCapabilities( 3947): Unsupported mime video/x-ms-wmv7
W/VideoCapabilities( 3947): Unsupported mime video/x-ms-wmv8
W/VideoCapabilities( 3947): Unsupported mime video/mp43
I/System.out( 3856): INFO:Resource not found:/Common.properties Using default values
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3878): took 0.594687ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb77028a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76f3cf0 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3878): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3326/cgroup.procs: No such file or directory
E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3878): took 0.996146ms for 96*96 texture 0
W/VideoCapabilities( 3947): Unsupported mime video/sorenson
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb76ff2b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7700198 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3878): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/AffinityControl( 4106): AffinityControl: registerfunction enter
E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3878): took 0.869115ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb76f9698 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76f9ad0 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3878): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
E/Zygote  ( 4150): MountEmulatedStorage()
E/Zygote  ( 4150): v2
I/libpersona( 4150): KNOX_SDCARD checking this for 1000
I/libpersona( 4150): KNOX_SDCARD not a persona
I/SELinux ( 4150): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4150): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4150): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/VideoCapabilities( 3947): Unsupported mime video/mp4v-esdp
E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/AndroidRuntime( 4106): Calling main entry com.android.commands.am.Am
I/GFX raster( 3878): took 0.972239ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb76fdd90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76ff408 counterpartCT=4 counterpartW=96 counterparth=96
I/ActivityManager( 1016): Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=4150 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/SMD     (  289): DCD OFF
D/TimaKeyStoreProvider( 4150): TimaSignature is unavailable
D/ActivityThread( 4150): Added TimaKeyStore provider
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
E/PersonaManagerService( 1016): inState():  stateMachine is null !!
I/PersonaManagerService( 1016): PersonaId don't exist
I/ActivityManager( 1016): do not start freezing screen for locked container getKeyguardshowstate = false
I/AMMetaDataParserService( 3878): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3878): took 0.867761ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb76fd960 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76fde78 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3878): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
I/AMMetaDataParserService( 3878): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3878): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 3878): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3878): getResourcePackageName:assistant
I/AMMetaDataParserService( 3878): Resource data:2131034112
I/AMMetaDataParserService( 3878): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 3878): getResourceTypeNamexml
E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3878): took 0.596719ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb77031c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7702598 counterpartCT=4 counterpartW=96 counterparth=96
D/CustomFrequencyManagerService( 1016): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1016): mDVFSHelper.acquire()
I/AMMetaDataParserService( 3878): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
D/FocusedStackFrame( 1016): Set to : 0
D/PhoneWindow( 1016): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1016): *FMB* installDecor flags : -2122120936
D/Launcher.HomeView( 1486): onPause
E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
D/Launcher( 1486): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
I/GFX raster( 3878): took 0.637864ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb77031c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76fff78 counterpartCT=4 counterpartW=96 counterparth=96
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.test.thalitest
D/InputDispatcher( 1016): Focused application set to: xxxx
D/InputDispatcher( 1016): Focus left window: 1486
D/PCWCLIENTTRACE_AccountAppFacade2_0( 3506): unregister AuthInfo UpdateReceiver v2.0
I/VideoCapabilities( 3947): Unsupported profile 4 for video/mp4v-es
D/AndroidRuntime( 4106): Shutting down VM
I/AMMetaDataParserService( 3878): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1016): *FMB* isFloatingMenuEnabled return false
I/SurfaceFlinger(  259): id=10 createSurf (1x1),1 flag=404, uhalitest
I/ActivityManager( 1016): Killing 3382:com.dropbox.android:crash_uploader/u0a92 (adj 15): empty #31
E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3878): took 0.650625ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb76c48c8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7498478 counterpartCT=4 counterpartW=96 counterparth=96
D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3878): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
E/Zygote  ( 4169): MountEmulatedStorage()
E/Zygote  ( 4169): v2
I/libpersona( 4169): KNOX_SDCARD checking this for 10155
I/libpersona( 4169): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=4169 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 4169): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4169): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4169): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3878): took 0.628854ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb76f9698 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76e11b8 counterpartCT=4 counterpartW=96 counterparth=96
I/AMMetaDataParserService( 3878): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
D/TimaKeyStoreProvider( 4169): TimaSignature is unavailable
D/ActivityThread( 4169): Added TimaKeyStore provider
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/KnoxSetupWizardDbHelper( 4150): dbMigrationFlag : false
W/libprocessgroup( 1016): failed to open /acct/uid_10092/pid_3382/cgroup.procs: No such file or directory
V/WindowOrientationListener( 1016): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1016): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1016): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:assistant
I/AMMetaDataParserService( 3878): Resource data:2131034113
I/AMMetaDataParserService( 3878): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3878): getResourceTypeNamexml
D/ChimeraCfgMgr( 2088): Reading stored module config
E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3878): took 0.824532ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb76e11b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7498478 counterpartCT=4 counterpartW=96 counterparth=96
D/StatusBarManagerService( 1016): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1016): isKioskContainerExistOnDevice
D/ShortcutReceiver( 4150):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
I/AMMetaDataParserService( 3878): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
D/KnoxShortcutUtil( 4150): getIsShortcutMigrationFor_2_3_0_Done true
D/ShortcutReceiver( 4150):  KnoxContainerVersion 2.4.0
D/ShortcutReceiver( 4150):  shortcut migration not required 
E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3878): took 0.813698ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb76e11b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7498478 counterpartCT=4 counterpartW=96 counterparth=96
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.knox.knoxsetupwizardclient, hostingType: broadcast
W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3878): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
W/art     ( 4106): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,E/Zygote  ( 4190): MountEmulatedStorage()
,I/ActivityManager( 1016): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4190 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 4190): v2
,I/libpersona( 4190): KNOX_SDCARD checking this for 1000
,I/Process ( 4055): Sending signal. PID: 4055 SIG: 9,
,I/libpersona( 4190): KNOX_SDCARD not a persona,
,I/SELinux ( 4190): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,D/BootCompletedReceiver( 2088): Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
,D/BootCompletedReceiver( 2088): Got an BootCompleted event.
,I/SELinux ( 4190): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4190): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WindowOrientationListener( 1016):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,D/SensorService( 1016): [SO] activate (ident=0xb7b2a9e8, enabled=0)
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/BootCompletedReceiver( 2088): Will NOT schedule AdAttestation signal task because it's disabled.
,D/SensorManager( 1016): unregisterListener ::   
,I/Sensors ( 1016): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/SensorService( 1016): [SO] changed settle time [1]
D/SensorService( 1016): [SO] setDelay [66000000]
D/SensorService( 1016): [SO] activate (ident=0xb7b103f8, enabled=1)
D/SensorService( 1016): [SO] AR_init
I/Sensors ( 1016): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1016): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,D/TimaKeyStoreProvider( 4190): TimaSignature is unavailable
,D/ActivityThread( 4190): Added TimaKeyStore provider
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 4031): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/SSRM:n  ( 1016): SIOP:: AP = 390
,D/GCM     ( 2088): COMPAT: Multi user not supported
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
E/KnoxSetupWizardClient( 4190): isShipMode : 1
I/KnoxSetupWizardClient( 4190): onReceive : android.intent.action.BOOT_COMPLETED
,I/GFX raster( 3878): took 0.754010ms for 96*96 texture 0
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb7498478 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76c36e0 counterpartCT=4 counterpartW=96 counterparth=96
,D/GCM     ( 1842): COMPAT: Multi user not supported
,D/SensorService( 1016): [SO] Reset Rotation Old [100], Init [1]
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/WebViewFactory( 4169): Loading com.google.android.webview version 43.0.2357.121 (code 2357121),
,E/Zygote  ( 4211): MountEmulatedStorage(),
E/Zygote  ( 4211): v2
I/libpersona( 4211): KNOX_SDCARD checking this for 10107,
I/libpersona( 4211): KNOX_SDCARD not a persona,
,I/SELinux ( 4211): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4211): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4211): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 4031): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4031): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4031): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/ActivityManager( 1016): Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=4211 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 3344:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
D/SensorService( 1016): [SO] 0.134 0.383 10.132
D/SensorService( 1016): [SO] [100 -> 255]
D/TimaKeyStoreProvider( 4211): TimaSignature is unavailable
D/ActivityThread( 4211): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3878): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1016): Process com.sec.android.app.sns3 (pid 4055)(adj 0) has died(56,1155)
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/LibraryLoader( 4169): Time to load native libraries: 2 ms (timestamps 4179-4181)
I/LibraryLoader( 4169): Expected native library version number "",actual native library version number ""
,E/Zygote  ( 4229): MountEmulatedStorage()
E/Zygote  ( 4229): v2
I/libpersona( 4229): KNOX_SDCARD checking this for 10034
I/libpersona( 4229): KNOX_SDCARD not a persona
,I/SELinux ( 4229): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4229 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a,
I/SELinux ( 4229): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
,E/SELinux ( 4229): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/WebViewChromiumFactoryProvider( 4169): Binding Chromium to main looper Looper (main, tid 1) {3a4e2968}
,I/LibraryLoader( 4169): Expected native library version number "",actual native library version number ""
,I/chromium( 4169): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,W/System.err( 4190): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,W/System.err( 4190): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 4190): 	at android.os.Parcel.readException(Parcel.java:1493)
,W/System.err( 4190): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4212)
,D/TimaKeyStoreProvider( 4229): TimaSignature is unavailable
,W/System.err( 4190): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1948)
,D/ActivityThread( 4229): Added TimaKeyStore provider
W/System.err( 4190): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
,W/System.err( 4190): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GFX raster( 3878): took 0.603803ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb77031c0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76f9248 counterpartCT=4 counterpartW=96 counterparth=96
,I/GCoreUlr( 2088): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/BrowserStartupController( 4169): Initializing chromium process, singleProcess=true
,W/art     ( 4169): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 4169): ApplicationContext is null in ApplicationStatus
,I/AMMetaDataParserService( 3878): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3878): took 0.847136ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb76ff2b0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76f9248 counterpartCT=4 counterpartW=96 counterparth=96
,W/chromium( 4169): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 4169): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
,I/chromium( 4169): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,I/Adreno-EGL( 4169): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 4169): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 4169): Build Date: 04/06/15 Mon
I/Adreno-EGL( 4169): Local Branch: 
I/Adreno-EGL( 4169): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 4169): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 4169):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/AMMetaDataParserService( 3878): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,I/SurfaceFlinger(  259): id=8 Removed Mauncher (5/8)
,I/SurfaceFlinger(  259): id=8 Removed Mauncher (-2/8)
,I/DBG_DM  ( 3196): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3878): took 0.624740ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb76f9698 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76f9248 counterpartCT=4 counterpartW=96 counterparth=96
,E/SQLiteLog( 3947): (284) automatic index on conversation_participants_view(conversation_id)
,I/AMMetaDataParserService( 3878): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3878): took 0.783177ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb76f9248 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76ed700 counterpartCT=4 counterpartW=96 counterparth=96
,I/CheckinService( 2088): Disabling old GoogleServicesFramework version
,I/AMMetaDataParserService( 3878): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SystemUpdateService( 2088): onCreate
,E/SQLiteLog( 3947): (284) automatic index on conversation_participants_view(conversation_id)
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.policydm, hostingType: broadcast
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4270): MountEmulatedStorage()
I/ActivityManager( 1016): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4270 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/Zygote  ( 4270): v2
I/libpersona( 4270): KNOX_SDCARD checking this for 1000
,I/SELinux ( 4270): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 4270): KNOX_SDCARD not a persona
I/SELinux ( 4270): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Killing 3455:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31,
E/SELinux ( 4270): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/SQLiteLog( 3947): (284) automatic index on conversation_participants_view(conversation_id)
,W/chromium( 4169): [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,D/TimaKeyStoreProvider( 4270): TimaSignature is unavailable
,D/ActivityThread( 4270): Added TimaKeyStore provider
,W/libprocessgroup( 1016): failed to open /acct/uid_10057/pid_3344/cgroup.procs: No such file or directory
,I/CheckinService( 2088): Checking schedule, now: 1457972211575 next: 1458246240395
I/CheckinService( 2088): active receiver: disabled
,D/SystemUpdateService( 2088): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,V/AuthZen ( 2088): Handling intent: android.intent.action.BOOT_COMPLETED
,D/AuthZenEventHandler( 2088): Handling event: android.intent.action.BOOT_COMPLETED
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3878): took 0.544844ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb76fd960 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb731b408 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3878): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,W/art     ( 4169): Attempt to remove local handle scope entry from IRT, ignoring
,W/libprocessgroup( 1016): failed to open /acct/uid_10003/pid_3455/cgroup.procs: No such file or directory
,E/SQLiteLog( 3947): (284) automatic index on conversation_participants_view(conversation_id)
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
W/ContextImpl( 3878): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/AwContents( 4169): onDetachedFromWindow called when already detached. Ignoring
,E/SQLiteLog( 3947): (284) automatic index on conversation_participants_view(conversation_id)
,I/ActivityManager( 1016): Killing 3471:com.fmm.dm/1000 (adj 15): empty #31
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:assistant
I/AMMetaDataParserService( 3878,): Resource data:2131165203
,D/PhoneWindow( 4169): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 4169): *FMB* installDecor flags : -2139027200
,W/ResourcesManager( 3878): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 3878): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3878): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3878): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3878): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/SystemWebViewEngine( 4169): CordovaWebView is running on device made by: samsung
,I/AMMetaDataParserService( 3878): getResourceName:com.android.email:xml/email_assistant_menu
I/AMMetaDataParserService( 3878): getResourceTypeNamexml
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3878): took 2.662396ms for 0*0 texture 0
,W/art     ( 4169): Attempt to remove local handle scope entry from IRT, ignoring
,W/art     ( 4169): Attempt to remove local handle scope entry from IRT, ignoring
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3471/cgroup.procs: No such file or directory
,I/SystemUpdateService( 2088): cancelUpdate (empty URL)
I/SystemUpdateService( 2088): active receiver: disabled
,I/GFX generate_partition_tables( 3878): took 10.359012ms for 0*0 texture 0
,I/GFX raster( 3878): took 13.902864ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb78b0f50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb78b1110 counterpartCT=4 counterpartW=96 counterparth=96
,W/BaseAppContext( 2088): Using Auth Proxy for data requests.
,I/AMMetaDataParserService( 3878): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3878): took 0.786146ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb76d63f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb76d6498 counterpartCT=4 counterpartW=96 counterparth=96
,D/OpenGLRenderer( 4169): Render dirty regions requested: true
,I/AMMetaDataParserService( 3878): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,D/ActivityManager( 1016): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1016): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1016): postActiveUserChange, showWhenLocked: false
,D/KnoxTimeoutHandler( 1016): handleActiveUserChange for user 0
,D/PersonaManagerService( 1016): getPersonasForUser(): returning null!
,D/PhoneWindow( 4169): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,I/DBG_POLICYDM( 4270): [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
D/PhoneWindow( 4169): *FMB* isFloatingMenuEnabled return false
,I/DBG_POLICYDM( 4270): [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,I/SurfaceFlinger(  259): id=11 createSurf (1x1),1 flag=404, NainActivit
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/InputDispatcher( 1016): Focus entered window: 4169
,I/DBG_POLICYDM( 4270): [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/DBG_POLICYDM( 4270): [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,I/DBG_POLICYDM( 4270): [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,D/PointerIcon( 1016): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1016): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 4169): log_dcs ThreadedRenderer::initialize entered! 
,I/OpenGLRenderer( 4169): Initialized EGL, version 1.4
,D/OpenGLRenderer( 4169): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 4169): Enabling debug mode 0
,E/BaseAppContext( 2088): Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.,
,D/InputMethodManagerService( 1016): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,I/DBG_POLICYDM( 4270): [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3878): took 0.760469ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb76d63f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7384528 counterpartCT=4 counterpartW=96 counterparth=96
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PanelView( 1184): There is/are notification(s) 
,I/ActivityManager( 1016): Displayed Component not be shown by security: +1s350ms
,I/AMMetaDataParserService( 3878): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
D/CustomFrequencyManagerService( 1016): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  tag : ACTIVITY_RESUME_BOOSTER@7
D/CustomFrequencyManagerService( 1016): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  pkgName : ACTIVITY_RESUME_BOOSTER@11
D/CustomFrequencyManagerService( 1016): FrequencyrequestList.getNextMaxCPUCoreRequest, index: 1
W/ActivityManager( 1016): mDVFSHelper.release()
I/Timeline( 1016): Timeline: Activity_windows_visible id: ActivityRecord{22ffa0e3 u0 com.test.thalitest/.MainActivity t12} time:45116
,I/DBG_POLICYDM( 4270): [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,I/SamsungIME( 1816): getCurrentCandidateView
,I/Timeline( 4169): Timeline: Activity_idle id: android.os.BinderProxy@3dc4472d time:45136
,I/DBG_POLICYDM( 4270): [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/DBG_POLICYDM( 4270): [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,D/Launcher.HomeView( 1486): onStop
I/DBG_POLICYDM( 4270): [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 4270): [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,V/ActivityThread( 1486): updateVisibility : ActivityRecord{1852cd0e token=android.os.BinderProxy@46f35bb {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
D/Launcher( 1486): onTrimMemory. Level: 20
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/DBG_POLICYDM( 4270): [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,I/AuthZen ( 2088): Fetching signing key...
,I/AuthZen ( 2088): Signing key fetched successfully!
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3878): took 0.915938ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb76d63f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7384528 counterpartCT=4 counterpartW=96 counterparth=96
,D/SystemUpdateService( 2088): onDestroy
,I/AMMetaDataParserService( 3878): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3878): took 0.611927ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb7384528 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76ccaa8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3878): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3878): took 0.636875ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb7384528 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76cdc30 counterpartCT=4 counterpartW=96 counterparth=96
,W/BindingManager( 4169): Cannot call determinedVisibility() - never saw a connection for the pid: 4169
,I/AMMetaDataParserService( 3878): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4324): MountEmulatedStorage()
E/Zygote  ( 4324): v2
I/libpersona( 4324): KNOX_SDCARD checking this for 10035
I/libpersona( 4324): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4324 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 3491:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31
,I/SELinux ( 4324): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4324): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4324): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,W/BaseAppContext( 2088): Using Auth Proxy for data requests.
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,I/SurfaceFlinger(  259): id=10 Removed uhalitest (7/8)
,I/SurfaceFlinger(  259): id=10 Removed uhalitest (-2/8)
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4324): TimaSignature is unavailable
,D/ActivityThread( 4324): Added TimaKeyStore provider
,I/DBG_DM  ( 3196): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,D/CustomFrequencyManagerService( 1016): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1016  tag : ACTIVITY_RESUME_BOOSTER@11
,D/GCM     ( 1842): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,D/EnterpriseController(  279): uids 10012
D/EnterpriseController(  279): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10012
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 45195(2MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 27MB/41MB, paused 3.209ms total 244.437ms
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
W/ContextImpl( 3878): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3878): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,D/a       ( 2088): Opening database auth.proximity.permit_store...
,D/SecurityLogAgent:SEDenialService( 1016): Got CLOSE_WRITE Event sk.log
,D/JsMessageQueue( 4169): Set native->JS mode to OnlineEventsBridgeMode
,D/AuthZenTransactionCache( 2088): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 2088): Clearing transaction cache
,W/libprocessgroup( 1016): failed to open /acct/uid_10060/pid_3491/cgroup.procs: No such file or directory
,I/GCoreUlr( 1842): DispatchingService.onCreate()
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3878): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3878): getResourcePackageName:assistant
I/AMMetaDataParserService( 3878): Resource data:2131099648
,W/ResourcesManager( 3878): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 3878): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3878): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3878): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3878): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 3878): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3878): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3878): getResourceTypeNamexml
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3878): took 8.649636ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb7c06038 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7c06310 counterpartCT=4 counterpartW=96 counterparth=96
,E/SPPClientService( 4324): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 4324): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService( 4324): [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,I/AMMetaDataParserService( 3878): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/SPPClientService( 4324): PushLog.txt file is not deleted.,
,D/BatteryService( 1016): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 1016): level:100, scale:100, status:2, health:2, present:true, voltage: 4316, temperature: 267, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
D/BatteryService( 1016): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
,D/BatteryService( 1016): Sending ACTION_BATTERY_CHANGED.
,W/art     ( 2638): Suspending all threads took: 46.705ms
,D/SPPClientService( 4324): PushLog.txt file is not deleted.
,D/SPPClientService( 4324): ============PushLog. stop!
,I/MotionRecognitionService( 1016): Plugged
I/MotionRecognitionService( 1016): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1184): handleBatteryUpdate
,V/EmergencyMode( 1425): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
V/EmergencyMode( 1425): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2694): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 2694): Disconnected process message: 10
,D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/StrictMode( 4211): StrictMode policy violation; ~duration=1371 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4211): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4211): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4211): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4211): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4211): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4211): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4211): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 4211): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
D/StrictMode( 4211): 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4211): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4211): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4211): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4211): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4211): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4211): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4211): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4211): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4211): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4211): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4211): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4211): StrictMode policy violation; ~duration=1363 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4211): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4211): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4211): 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
D/StrictMode( 4211): 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
D/StrictMode( 4211): 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
D/StrictMode( 4211): 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
D/StrictMode( 4211): 	at java.lang.System.loadLibrary(System.java:989)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4211): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4211): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4211): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4211): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4211): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4211): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4211): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4211),: 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4211): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4211): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4211): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4211): StrictMode policy violation; ~duration=1235 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4211): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4211): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4211): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4211): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4211): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 4211): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 4211): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
D/StrictMode( 4211): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4211): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4211): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4211): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4211): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4211): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4211): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4211): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4211): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4211): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4211): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4211): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4211): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4211): StrictMode policy violation; ~duration=1234 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4211): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4211): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
D/StrictMode( 4211): 	at libcore.io.IoBridge.open(IoBridge.java:442)
D/StrictMode( 4211): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4211): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 4211): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4211): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4211): 	at android.app.Instrumentation.callApplicationOnCreate(Inst,rumentation.java:1020)
D/StrictMode( 4211): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4211): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4211): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4211): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4211): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4211): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4211): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4211): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4211): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4211): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4211): StrictMode policy violation; ~duration=1233 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4211): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4211): 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
D/StrictMode( 4211): 	at libcore.io.IoBridge.open(IoBridge.java:445)
D/StrictMode( 4211): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
D/StrictMode( 4211): 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
D/StrictMode( 4211): 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4211): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4211): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4211): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4211): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4211): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4211): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4211): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4211): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4211): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4211): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4211): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4211): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4211): StrictMode policy violation; ~duration=1230 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4211): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4211): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4211): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4211): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4211): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4211): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4211): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 4211): 	at com.google.r.k.a(PG:2107)
D/StrictMode( 4211): 	at com.google.v.a.a.eq.<init>(PG:23)
D/StrictMode( 4211): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 4211): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 4211): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 4211): 	at com.google.r.e.b(PG:170)
D/StrictMode( 4211): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4211): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4211): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4211): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4211): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4211): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4211): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4211): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4211): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4211): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4211): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4211): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4211): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4211): StrictMode policy violation; ~duration=1193 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4211): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4211): 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
D/StrictMode( 4211): 	at libcore.io.IoBridge.read(IoBridge.java:472)
D/StrictMode( 4211): 	at java.io.FileInputStream.read(FileInputStream.java:177)
D/StrictMode( 4211): 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
D/StrictMode( 4211): 	at java.io.DataInputStream.read(DataInputStream.java:63)
D/StrictMode( 4211): 	at com.google.r.k.c(PG:1187)
D/StrictMode( 4211): 	at com.google.r.k.b(PG:14147)
D/StrictMode( 4211): 	at com.google.r.k.c(PG:583)
D/StrictMode( 4211): 	at com.google.v.a.a.eq.<init>(PG:40)
D/StrictMode( 4211): 	at com.google.v.a.a.eq.a(PG:12397)
D/StrictMode( 4211): 	at com.google.r.v.a(PG:1206)
D/StrictMode( 4211): 	at com.google.r.y.a(PG:2233)
D/StrictMode( 4211): 	at com.google.r.e.b(PG:170)
D/StrictMode( 4211): 	at com.google.r.e.b(PG:13188)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
D/StrictMode( 4211): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4211): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4211): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4211): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4211): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4211): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4211): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4211): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4211): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4211): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4211): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4211): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4211): StrictMode policy violation; ~duration=1147 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4211): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4211): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4211): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4211): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4211): 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
D/StrictMode( 4211): 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
D/StrictMode( 4211): 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
D/StrictMode( 4211): 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
D/StrictMode( 4211): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4211): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4211): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4211): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4211): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4211): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4211): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4211): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4211): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4211): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4211): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4211): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/StrictMode( 4211): StrictMode policy violation; ~duration=1146 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
D/StrictMode( 4211): 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
D/StrictMode( 4211): 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
D/StrictMode( 4211): 	at java.io.File.doAccess(File.java:283)
D/StrictMode( 4211): 	at java.io.File.exists(File.java:363)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.map.l.s.a(PG:7692)
D/StrictMode( 4211): 	at com.google.b.a.ca.a(PG:125)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
D/StrictMode( 4211): 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
D/StrictMode( 4211): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
D/StrictMode( 4211): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
D/StrictMode( 4211): 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
D/StrictMode( 4211): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
D/StrictMode( 4211): 	at android.os.Handler.dispatchMessage(Handler.java:102)
D/StrictMode( 4211): 	at android.os.Looper.loop(Looper.java:145)
D/StrictMode( 4211): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
D/StrictMode( 4211): 	at java.lang.reflect.Method.invoke(Native Method)
D/StrictMode( 4211): 	at java.lang.reflect.Method.invoke(Method.java:372)
D/StrictMode( 4211): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
D/StrictMode( 4211): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.mt, hostingType: broadcast
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 1184): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 4353): MountEmulatedStorage()
E/Zygote  ( 4353): v2
I/libpersona( 4353): KNOX_SDCARD checking this for 1000
I/libpersona( 4353): KNOX_SDCARD not a persona
I/SELinux ( 4353): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/ActivityManager( 1016): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4353 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
I/SELinux ( 4353): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4353): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Killing 3533:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
I/GAV2    ( 3727): Thread[GAThread,5,main]: No campaign data found.
,D/TimaKeyStoreProvider( 4353): TimaSignature is unavailable
,D/ActivityThread( 4353): Added TimaKeyStore provider
,D/jxcore_app_log( 4169): JniHelper::setJavaVM(0xb7325450), pthread_self() = -1215830368
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4370): MountEmulatedStorage()
E/Zygote  ( 4370): v2
I/libpersona( 4370): KNOX_SDCARD checking this for 10041
I/libpersona( 4370): KNOX_SDCARD not a persona
,I/SELinux ( 4370): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4370): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4370): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/DBG_POLICYDM( 4270): [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT,
I/DBG_POLICYDM( 4270): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
D/SamsungIME( 1816): Dismiss ExpandCandiate
W/dex2oat ( 4100): Verification of void com.google.android.gms.ads.internal.overlay.m.a() took 155.602ms
,I/ActivityManager( 1016): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4370 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/ActivityManager( 1016): Killing 3548:com.fmm.ds/1000 (adj 15): empty #31
,D/TimaKeyStoreProvider( 4370): TimaSignature is unavailable
,D/ActivityThread( 4370): Added TimaKeyStore provider
,I/DBG_POLICYDM( 4270): [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
,I/DBG_POLICYDM( 4270): [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4169): load: 
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4169):     - Connection timeout in milliseconds: 15000
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4169):     - Insecure RFCOMM socket port number: -1
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4169):     - Maximum number of connection attempt retries: 0
V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4169):     - Handshake required: true
,V/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4169): addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b62fbe0 added. We now have 1 listener(s)
,I/DBG_POLICYDM( 4270): [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
,I/GCM     ( 1842): GCM config loaded
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4169): setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,I/org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent( 4169): verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"7C:F9:0E:37:96:AB"}
,D/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4169): setIdentityString: {"name":"<no peer name>","address":"7C:F9:0E:37:96:AB"}
,D/org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings( 4169): setHandshakeRequired: true -> false
V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector( 4169): setHandshakeRequired: true -> false
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4169): load: 
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4169):     - Automate Bluetooth MAC address resolution: true
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4169):     - Provide Bluetooth MAC address timeout in milliseconds: 40000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4169):     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4169):     - Discovery mode: BLE
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4169):     - Peer expiration time in milliseconds: 60000
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4169):     - Advertise mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4169):     - Advertise TX power level: 2
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4169):     - Scan mode: 1
V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4169):     - Scan report delay in milliseconds: 500
,V/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4169): addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2158bd3f added. We now have 1 listener(s)
,D/org.thaliproject.p2p.btconnectorlib.utils.PeerModel( 4169): addListener: New listener added - the number of listeners is now 1
,V/org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager( 4169): isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
,I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4169): setDiscoveryMode: Discovery mode BLE is supported
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4169): setAdvertiseMode: 1 -> 2
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4169): setAdvertiseTxPowerLevel: 2 -> 3
I/org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings( 4169): setScanMode: 1 -> 2
,W/libprocessgroup( 1016): failed to open /acct/uid_10062/pid_3533/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3548/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms,
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0,
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/chromium( 4169): [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/dex2oat ( 4100): Verification of void com.google.android.gms.common.api.c.<init>() took 116.341ms
,I/GFX construct_block_size_descriptor_2d second part( 3878): took 3.303751ms for 0*0 texture 0
,W/GCoreFlp( 1842): No location to return for getLastLocation(),
,W/FusedLocationProvider( 1842): location=null,
,I/ActivityManager( 1016): Waited long enough for: ServiceRecord{1d1322bd u0 com.samsung.hs20settings/.WifiHs20UtilityService},
,W/GCoreFlp( 1842): No location to return for getLastLocation()
,W/FusedLocationProvider( 1842): location=null
,I/DBG_POLICYDM( 4270): [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
,W/Auth    ( 1842): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/StatusChecker( 4353): onReceive : android.intent.action.BOOT_COMPLETED
,I/StatusChecker( 4353): onReceive : net.mt.init : DONE
,I/GFX generate_partition_tables( 3878): took 10.368126ms for 0*0 texture 0
,I/GFX raster( 3878): took 14.779272ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb731b3d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb76f9698 counterpartCT=4 counterpartW=96 counterparth=96
,W/dex2oat ( 4100): Verification of void com.google.android.gms.common.internal.o$a$a.a(com.google.android.gms.common.internal.n, com.google.android.gms.common.internal.ValidateAccountRequest) took 172.595ms
,I/AMMetaDataParserService( 3878): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3878): took 0.677968ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb76e0d28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb76f9350 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_POLICYDM( 4270): [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,I/AMMetaDataParserService( 3878): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3878): took 0.688334ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb76fd1e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7c06268 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3878): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.pagebuddynotisvc, hostingType: broadcast
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3878): took 0.645730ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb7701078 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76f9350 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3878): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/DBG_POLICYDM( 4270): [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
,V/GLSActivity( 1842): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/SecDataIO(  258): Write to block,
,I/DBG_POLICYDM( 4270): [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true,
,I/DBG_POLICYDM( 4270): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,E/Zygote  ( 4404): MountEmulatedStorage(),
E/Zygote  ( 4404): v2
,I/ActivityManager( 1016): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4404 uid=10116 gids={50116, 9997} abi=armeabi-v7a
I/libpersona( 4404): KNOX_SDCARD checking this for 10116,
I/ActivityManager( 1016): Killing 3570:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
I/libpersona( 4404): KNOX_SDCARD not a persona
,I/SELinux ( 4404): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4404): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4404): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_POLICYDM( 4270): [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
,I/DBG_POLICYDM( 4270): [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
,I/DBG_DM  ( 3196): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,D/TimaKeyStoreProvider( 4404): TimaSignature is unavailable
,D/ActivityThread( 4404): Added TimaKeyStore provider
,W/ContextImpl( 2638): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,I/DBG_DM  ( 3196): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/DBG_DM  ( 3196): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
,E/DBG_DM  ( 3196): [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
,I/DBG_DM  ( 3196): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
I/DBG_POLICYDM( 4270): [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/03/18/16:12:11
,I/DBG_POLICYDM( 4270): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 4270): [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,I/DBG_POLICYDM( 4270): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/03/14/17:16:53
,I/Process ( 2638): Sending signal. PID: 2638 SIG: 9
,I/PageBuddyNotiSvc( 4404): Intent received : action=android.intent.action.BOOT_COMPLETED
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3878): took 0.725989ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb76d8bf0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7c06268 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3878): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/ContextImpl( 4404): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,I/SA      ( 4370): [SSP] onCreated
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:assistant
I/AMMetaDataParserService( 3878): Resource data:2131099648
,I/DBG_POLICYDM( 4270): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,I/DBG_POLICYDM( 4270): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,I/DBG_POLICYDM( 4270): [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,I/DBG_POLICYDM( 4270): [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
,I/DBG_POLICYDM( 4270): [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,I/DBG_POLICYDM( 4270): [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
,I/DBG_POLICYDM( 4270): [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,I/DBG_POLICYDM( 4270): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
,I/DBG_POLICYDM( 4270): [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
,D/PersistentNotificationBroadcastReceiver( 1842): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3570/cgroup.procs: No such file or directory
,I/ActivityManager( 1016): Process com.sec.android.app.sysscope (pid 2638)(adj 0) has died(31,1138)
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
I/AMMetaDataParserService( 3878): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3878): getResourceTypeNamexml
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,I/GFX raster( 3878): took 0.890312ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb7c06038 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76a3138 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,I/DBG_POLICYDM( 4270): [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.sync.focus.ContactsSyncIntentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,I/PageBuddyNotiSvc( 4404): onCreate mCpBitFlag=0
,I/AMMetaDataParserService( 3878): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4423): MountEmulatedStorage()
,E/Zygote  ( 4423): v2
I/libpersona( 4423): KNOX_SDCARD checking this for 10125
I/SELinux ( 4423): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/libpersona( 4423): KNOX_SDCARD not a persona
,I/SELinux ( 4423): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4423): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,I/ActivityManager( 1016): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4423 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,E/SMD     (  289): DCD OFF
,I/art     (  308): Explicit concurrent mark sweep GC freed 8733(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 632us total 24.089ms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncReceiverService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4423): TimaSignature is unavailable
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 626us total 18.768ms
,D/ActivityThread( 4423): Added TimaKeyStore provider
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3878): took 0.801042ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb731b3d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb7c06268 counterpartCT=4 counterpartW=96 counterparth=96
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 617us total 17.475ms
,I/DBG_POLICYDM( 4270): [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
,W/ResourcesManager( 4423): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4423): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4423): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/SA      ( 4370): [TPM] There is no property file
,I/SA      ( 4370): [SCU] isHaveSA() - false
,I/AMMetaDataParserService( 3878): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,I/SA      ( 4370): [TPM] getModelProperty : null
I/SA      ( 4370): [TPM] getCSCProperty : null
,I/SA      ( 4370): [DM] FLOATING AMOLED FEATURE: true
,I/SA      ( 4370): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 4370): [DM] TFT FEATURE: false
,I/SA      ( 4370): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
I/SA      ( 4370): [DM] init START
,I/SA      ( 4370): [DM] This device is not a Vodafone
,W/ResourceType( 4370): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 4370): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75),
W/ResourceType( 4370): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,W/ResourceType( 4370): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
W/ResourceType( 4370): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
,W/ResourceType( 4370): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
W/ResourceType( 4370): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 4370): No package identifier when getting value for resource number 0x00000000
,W/ResourceType( 4370): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,W/ResourceType( 4370): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,W/ResourceType( 4370): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 4370): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,W/ResourceType( 4370): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,W/ResourceType( 4370): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,W/ResourceType( 4370): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,W/ResourceType( 4370): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
,W/ResourceType( 4370): Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,W/ResourceType( 4370): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
,W/ResourceType( 4370): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 4370): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,W/ResourceType( 4370): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
,W/ResourceType( 4370): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
W/ResourceType( 4370): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
,W/ResourceType( 4370): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,W/ResourceType( 4370): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,I/SA      ( 4370): [SCU] isHaveSA() - false
I/SA      ( 4370): support phone number id : false
I/SA      ( 4370): [DM] Supports Ref Jpn : true
,I/SA      ( 4370): [DM] init END
,I/SA      ( 4370): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
I/SA      ( 4370): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,D/ActivityManager( 1016): startService callerProcessName:com.osp.app.signin, calleePkgName: com.osp.app.signin
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,I/SA      ( 4370): [OR] onReceive END
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4442): MountEmulatedStorage()
E/Zygote  ( 4442): v2
I/libpersona( 4442): KNOX_SDCARD checking this for 10042
I/libpersona( 4442): KNOX_SDCARD not a persona
,I/SELinux ( 4442): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4442): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4442): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,W/dex2oat ( 4100): Verification of boolean maps.ai.y.a(java.lang.String) took 133.616ms
,I/ActivityManager( 1016): Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=4442 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SA      ( 4370): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 4370): [ODM] queryOpenData(key= GEO_IP )
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/QuickConnect( 4423): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,D/QuickConnect( 4423): Util.setSCRunningSetting - [value]0
,I/SA      ( 4370): getMccForGalaxyJpn step2 GEO_IP MCC : 260
I/SA      ( 4370): [LBE] REF_JPN : true
,I/SA      ( 4370): [BDC] create
,D/TimaKeyStoreProvider( 4442): TimaSignature is unavailable
,D/ActivityThread( 4442): Added TimaKeyStore provider
,I/GFX raster( 3878): took 0.682552ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb76e0d28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb7384300 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3878): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521,
D/SettingsProvider( 1016): name = scon_is_running
,D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
,D/SettingsProvider( 1016): selectionArgs: 10125
W/ResourcesManager( 4442): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncService; callingUser = 0; userId(target) = 0
,W/BackupManagerService( 1016): dataChanged but no participant pkg='com.android.providers.settings' uid=10125
,I/SecKeyguardClockSingleView( 1184): Ignore. Because it is same clock text
,I/QuickConnect( 4423): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,W/ActivityThread( 4211): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,I/QuickConnect( 4423): PeriphStartReceiver.onReceive - no need to start
,I/art     ( 1651): Explicit concurrent mark sweep GC freed 6839(276KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 7MB/10MB, paused 844us total 1.685s
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/System.out( 4211): (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
I/System.out( 4211): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 4211): (HTTPLog)-Static: isShipBuild true
I/System.out( 4211): (HTTPLog)-Thread-641-459470228: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 4211): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController(  279): uids 10107
D/EnterpriseController(  279): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10107
,I/GFX raster( 3878): took 0.697135ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb76fd1e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb732c5d0 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.sbrowser, hostingType: broadcast
,W/SQLiteConnectionPool( 1651): A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/SA      ( 4370): [DBMV2] getEmailID
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/SA      ( 4370): [DBMV2] getDataV02ForItems
I/SA      ( 4370): [SSP] query invoked
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3878): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,W/art     ( 3856): Suspending all threads took: 1.280s
,I/SA      ( 4370): [SCU] get signed id from samsung account2.0 DB.
,E/Zygote  ( 4460): MountEmulatedStorage()
,I/libpersona( 4460): KNOX_SDCARD checking this for 10131
E/Zygote  ( 4460): v2
I/libpersona( 4460): KNOX_SDCARD not a persona
,I/SELinux ( 4460): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4460 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a,
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3878): took 0.629948ms for 96*96 texture 0
I/ActivityManager( 1016): Killing 3587:com.sec.esdk.elm/u0a94 (adj 15): empty #31
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb7701078 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76c48c8 counterpartCT=4 counterpartW=96 counterparth=96
,I/SELinux ( 4460): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/SA      ( 4370): [SCU] get signed id from samsung account1.0 DB.
,I/SA      ( 4370): [BDC] destroy
,E/SELinux ( 4460): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Killing 3362:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
,I/AMMetaDataParserService( 3878): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3878): took 0.991351ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb76d8bf0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7c06268 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4460): TimaSignature is unavailable
,D/ActivityThread( 4460): Added TimaKeyStore provider,
,I/CalendarProvider2( 4442): CalendarProvider2.onCreate() called
,I/AMMetaDataParserService( 3878): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524,
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:assistant
I/AMMetaDataParserService( 3878): Resource data:2131099648
,I/AMMetaDataParserService( 3878): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3878): getResourceTypeNamexml
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3878): took 0.826459ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb7c06038 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb78b0d38 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1016): Killing 3638:com.sec.factory.camera/1000 (adj 15): empty #31
,I/AMMetaDataParserService( 3878): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/com.google.a.a.b.d.a( 4211): Application name is not set. Call Builder#setApplicationName.
,W/dex2oat ( 4100): Verification of void maps.ak.b$a.<init>() took 214.436ms
,W/dex2oat ( 4100): Verification of void maps.aj.f$a.<init>(maps.aj.f, maps.aj.a) took 251.412ms
W/dex2oat ( 4100): Verification of java.lang.String maps.aj.h.a() took 241.765ms
,I/SamsungIME( 1816): getDebugLevel  : 0x4f4c
,W/dex2oat ( 4100): Verification of void maps.ak.d$e.b() took 217.869ms
,W/ResourcesManager( 4460): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4460): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4460): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 4460): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/System.out( 4211): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,I/DBG_POLICYDM( 4270): [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1016): failed to open /acct/uid_10009/pid_3362/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10094/pid_3587/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3638/cgroup.procs: No such file or directory
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3878): took 0.637031ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb731b3d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb76c48c8 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3878): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/DBG_POLICYDM( 4270): [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
I/GFX raster( 3878): took 0.646667ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb76e0d28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb76f9350 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3878): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/DBG_POLICYDM( 4270): [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,I/DBG_POLICYDM( 4270): [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3878): took 0.652656ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb76fd1e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb76f9698 counterpartCT=4 counterpartW=96 counterparth=96
,D/SBrowserFeatureFlag( 4460): initialized in static block : loadCscFeatureValue() succeed! 
,I/AMMetaDataParserService( 3878): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3878): took 0.648906ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb7701078 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb78b0f50 counterpartCT=4 counterpartW=96 counterparth=96
,D/ManifestProvider( 4460): onCreate()
,I/AMMetaDataParserService( 3878): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/SamsungIME( 1816): getDebugLevel  : 0x4f4c
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3878): took 0.782500ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb76d8bf0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76d72c0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3878): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524,
,I/SamsungIME( 1816): KeybaordView init() : load resources
,I/DBG_DM  ( 3196): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 8 sec
,I/DBG_DM  ( 3196): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,I/DBG_DM  ( 3196): [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.test.thalitest.MainActivity
,I/DBG_DM  ( 3196): [IIlIIIlllllIIlIIIlII(91/llllIIIllIlIIIIllllI)] 
,I/DBG_DM  ( 3196): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/SamsungIME( 1816): getCurrentKeyboard
I/SamsungIME( 1816): getTextKeyboard
,I/DBG_DM  ( 3196): [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 3
,I/DBG_DM  ( 3196): [com.wssyncmldm.db.file.XDB(6236/IlIIlIIlIllllIlllIII)] Initiated Type: 2
,I/DBG_DM  ( 3196): [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:assistant
I/AMMetaDataParserService( 3878): Resource data:2131099648
,I/DBG_DM  ( 3196): [IlIlllIlllllIlIllllI(177/lllIlIlIIIllIIlIllIl)] nDownloadPostpone is [3]
,I/DBG_DM  ( 3196): [IlIIlIIlIllllIlllIII(274/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
,I/DBG_DM  ( 3196): [com.wssyncmldm.llIIllllIIlllIIIIlll(1140/handleMessage)] 
,I/DBG_DM  ( 3196): [com.wssyncmldm.XDMService(685/llIIlIlIIIllIIIIIllI)] 
,I/DBG_DM  ( 3196): [IlIIlIIlIllllIlllIII(1901/llllIIIllIlIIIIllllI)] 
,I/AMMetaDataParserService( 3878): getResourceName:com.android.mms:xml/assistant_messaging
,I/DBG_DM  ( 3196): [com.wssyncmldm.DMSecBroadcastReceiver(572/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,I/DBG_DM  ( 3196): [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(503/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,I/AMMetaDataParserService( 3878): getResourceTypeNamexml
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3878): took 0.682448ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb7c06038 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76a3138 counterpartCT=4 counterpartW=96 counterparth=96
I/DBG_DM  ( 3196): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 3196): [com.wssyncmldm.ui.XUIFotaPostponeActivity(501/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 3196): [com.wssyncmldm.ui.XUIFotaPostponeActivity(474/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 3196): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 3 / Notification IndicatorState : 3
,D/SamsungIME( 1816): [SwiftkeyWrapper] currentLangauge : 1701729619
,E/NetworkSettingsReceiver( 4460): onReceive: android.intent.action.BOOT_COMPLETED
I/ActivityManager( 1016): Killing 3612:com.wssnps/1000 (adj 15): empty #31
,I/AMMetaDataParserService( 3878): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/jxcore-log( 4169): Initializing JXcore engine
W/jxcore-log( 4169): JXcore engine is ready
,D/ApplicationPolicy( 1016): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 1016): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3878): took 0.655730ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb731b3d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb7384300 counterpartCT=4 counterpartW=96 counterparth=96
,D/WindowManager( 1016): showStatusBarByNotification() mOpenByNotification=false
,W/NotificationService( 1016): Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,I/AMMetaDataParserService( 3878): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/SBrowserFeatureFlag( 4460): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@24907414
,D/SBrowserFeatureFlag( 4460): initialize : initSupportedPkg() succeed! 
I/VerificationLog( 4460): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,W/ResourcesManager( 1184): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3878): took 0.631719ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb76e0d28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb732c5d0 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/audit   ( 1929): type=1400 msg=audit(1457972214.749:205): avc:  denied  { ioctl } for  pid=4392 comm="Thread-644" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1929):  SEPF_SM-A500FU_5.0.2-1_0038
E/audit   ( 1929): type=1300 msg=audit(1457972214.749:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=9cc608f8 items=0 ppid=308 ppcomm=main pid=4392 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-644" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1929): type=1320 msg=audit(1457972214.749:205): 
,I/AMMetaDataParserService( 3878): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,E/Zygote  ( 4486): MountEmulatedStorage()
I/libpersona( 4486): KNOX_SDCARD checking this for 10135
E/Zygote  ( 4486): v2
I/libpersona( 4486): KNOX_SDCARD not a persona
I/SELinux ( 4486): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
W/jxcore-log( 4169): Starting JXcore engine
,D/PowerManagerService( 1016): [s] UserActivityState : 1 -> 2
D/DisplayPowerController( 1016): getFinalBrightness : Summary is 19 -> 19,
D/DisplayPowerController( 1016): animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 1016): [s] DisplayPowerCallbacks : onStateChanged()
I/ActivityManager( 1016): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4486 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 3655:com.google.android.onetimeinitializer/u0a14 (adj 15): empty #31
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3612/cgroup.procs: No such file or directory
,I/SELinux ( 4486): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4486): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/lights  ( 1016): lcd : 28 +
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 19 -> 19
,D/DisplayPowerController( 1016): animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 1016): lcd : 28 -
,D/lights  ( 1016): lcd : 19 +
,D/KnoxNotification( 1184): ----- inflateViews : modified publicViewLocal -----
,D/TimaKeyStoreProvider( 4486): TimaSignature is unavailable
,D/ActivityThread( 4486): Added TimaKeyStore provider
,D/lights  ( 1016): lcd : 19 -
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 19 -> 19
,D/DisplayPowerController( 1016): animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/KnoxNotification( 1184): ----- inflateViews : modified KnoxViewLocal -----
I/GFX raster( 3878): took 0.660416ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb76fd1e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb7c06268 counterpartCT=4 counterpartW=96 counterparth=96
,D/PersonaManager( 1184): PersonaID is invalid or persona doesn't exists. : 0
,D/PersonaManager( 1184): isKioskContainerExistOnDevice
D/PersonaManager( 1184): isKioskContainerExistOnDevice
,I/AMMetaDataParserService( 3878): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/PanelView( 1184): There is/are notification(s) 
D/PanelView( 1184): kidsfalse mQsExpansionEnabled:true
,D/PersonaManager( 1184): isKioskContainerExistOnDevice
D/PanelView( 1184): There is/are notification(s) 
D/PanelView( 1184): kidsfalse mQsExpansionEnabled:true
,D/ActivityManager( 1016): startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3878): took 0.649219ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb7701078 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb78b0d38 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/AMMetaDataParserService( 3878): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3878): took 0.722500ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb76d8bf0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76c48c8 counterpartCT=4 counterpartW=96 counterparth=96
,W/ResourcesManager( 4486): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4486): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4486): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3878): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/libprocessgroup( 1016): failed to open /acct/uid_10014/pid_3655/cgroup.procs: No such file or directory
,D/PanelView( 1184): mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,W/jxcore-log( 4169): Platform android
W/jxcore-log( 4169): 
,W/jxcore-log( 4169): Process ARCH arm
W/jxcore-log( 4169): 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:assistant
I/AMMetaDataParserService( 3878): Resource data:2131099648
,I/AMMetaDataParserService( 3878): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3878): getResourceTypeNamexml
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3878): took 0.682031ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb7c06038 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb78b0f50 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3878): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/daemonapp( 1333): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/ActivityManager( 1016): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3878): took 0.624167ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb731b3d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb76f9350 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3878): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3878): took 0.640677ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb76e0d28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb76f9698 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3878): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/ActivityManager( 1016): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4507): MountEmulatedStorage()
E/Zygote  ( 4507): v2
I/libpersona( 4507): KNOX_SDCARD checking this for 10139
,I/libpersona( 4507): KNOX_SDCARD not a persona
,I/SELinux ( 4507): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4507): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,I/ActivityManager( 1016): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4507 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a,
,E/SELinux ( 4507): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3878): took 0.632188ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb76fd1e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb76d72c0 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3878): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3878): took 0.620208ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb7701078 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb76a3138 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3878): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/TimaKeyStoreProvider( 4507): TimaSignature is unavailable
,D/ActivityThread( 4507): Added TimaKeyStore provider
,V/Herrevad( 2088): NQAS connected
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 4507): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 4507): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 4507): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 4507): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,W/ResourcesManager( 4507): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3878): took 0.712604ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb76d8bf0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7384300 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3878): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:assistant
I/AMMetaDataParserService( 3878): Resource data:2131099648
,I/AMMetaDataParserService( 3878): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3878): getResourceTypeNamexml
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3878): took 0.679010ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb7c06038 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb78b0d38 counterpartCT=4 counterpartW=96 counterparth=96
,I/art     ( 1842): Explicit concurrent mark sweep GC freed 28098(2MB) AllocSpace objects, 39(624KB) LOS objects, 40% free, 12MB/20MB, paused 46.529ms total 2.467s
,I/AMMetaDataParserService( 3878): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3878): took 0.626927ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb731b3d8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb732c5d0 counterpartCT=4 counterpartW=96 counterparth=96
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,I/AMMetaDataParserService( 3878): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/GCoreUlr( 1842): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,I/GFX raster( 3878): took 0.626094ms for 96*96 texture 0
I/ActivityManager( 1016): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4529 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb76e0d28 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb7c06268 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3878): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521,
,I/jxcore-log( 4169): JXcore Cordova bridge is ready!,
I/jxcore-log( 4169): 
W/jxcore-log( 4169): JXcore engine is started
,E/Zygote  ( 4529): MountEmulatedStorage()
E/Zygote  ( 4529): v2,
I/libpersona( 4529): KNOX_SDCARD checking this for 10145
,I/libpersona( 4529): KNOX_SDCARD not a persona
,I/SELinux ( 4529): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4529): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4529): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/org.thaliproject.p2p.ThaliPermissions( 4169): execute: REQUEST_ACCESS_COARSE_LOCATION
,I/chromium( 4169): [INFO:CONSOLE(47)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (47)
,D/TimaKeyStoreProvider( 4529): TimaSignature is unavailable,
D/ActivityThread( 4529): Added TimaKeyStore provider
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3878): took 0.646510ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb76fd1e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb732c5d0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3878): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3878): took 0.666823ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb7701078 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7c06268 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3878): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,W/ResourcesManager( 4529): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4529): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4529): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 4529): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4529): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ConfigService( 1842): onCreate
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3878): took 0.787292ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb76d8bf0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb732c5d0 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1016): Killing 3694:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,I/AMMetaDataParserService( 3878): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/GCoreUlr( 1842): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.saverestore.RestorePreviewActivity
W/ContextImpl( 3878): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 3878),: Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3878): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm,
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:assistant
I/AMMetaDataParserService( 3878): Resource data:2131165197
,W/ResourcesManager( 3878): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3878): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3878): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 3878): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3878): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3878): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 3878): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3878): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3878): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 3878): getResourceTypeNamexml
,W/libprocessgroup( 1016): failed to open /acct/uid_10100/pid_3694/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3878): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,W/dex2oat ( 4100): Verification of void maps.k.b$g.a(byte[], byte[]) took 147.302ms
,I/AMMetaDataParserService( 3878): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/GCoreUlr( 1842): Unbound from all location providers
I/GCoreUlr( 1842): Place inference reporting - stopped
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3878): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,W/dex2oat ( 4100): Verification of void maps.k.b$l.a(byte[], byte[]) took 107.009ms
,I/GCoreUlr( 1842): DispatchingService.onDestroy()
I/GCoreUlr( 1842): Stopping handler for UlrDispSvcFast
,I/CalendarProvider2( 4442): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,I/GCoreUlr( 1842): Unbound from all location providers
,I/GCoreUlr( 1842): Place inference reporting - stopped
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1016): Killing 3417:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3878): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3878): getResourcePackageName:assistant
I/AMMetaDataParserService( 3878): Resource data:2131165197
,I/AMMetaDataParserService( 3878): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3878): getResourceTypeNamexml
,I/AMMetaDataParserService( 3878): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/AMMetaDataParserService( 3878): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/AMMetaDataParserService( 3878): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/AMMetaDataParserService( 3878): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,W/libprocessgroup( 1016): failed to open /acct/uid_10015/pid_3417/cgroup.procs: No such file or directory
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.cooliris.media.Gallery
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:assistant
I/AMMetaDataParserService( 3878): Resource data:2131165197
,I/AMMetaDataParserService( 3878): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3878): getResourceTypeNamexml
,I/AMMetaDataParserService( 3878): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/AMMetaDataParserService( 3878): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/AMMetaDataParserService( 3878): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,I/ActivityManager( 1016): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4556 uid=10072 gids={50072, 9997} abi=armeabi-v7a,
E/Zygote  ( 4556): MountEmulatedStorage()
E/Zygote  ( 4556): v2,
I/libpersona( 4556): KNOX_SDCARD checking this for 10072
I/libpersona( 4556): KNOX_SDCARD not a persona
,I/SELinux ( 4556): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,D/ActivityManager( 1016): startService callerProcessName:com.android.email, calleePkgName: com.android.email,
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
I/SELinux ( 4556): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
E/SELinux ( 4556): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4556): TimaSignature is unavailable
,D/ActivityThread( 4556): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3878): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.exchange, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4576): MountEmulatedStorage(),
I/libpersona( 4576): KNOX_SDCARD checking this for 10146
E/Zygote  ( 4576): v2
I/libpersona( 4576): KNOX_SDCARD not a persona
I/SELinux ( 4576): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4576): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 4576): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4576 uid=10146 gids={50146, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/ActivityManager( 1016): Killing 3786:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
I/ActivityManager( 1016): Killing 3767:com.android.managedprovisioning/u0a22 (adj 15): empty #32
,W/dex2oat ( 4100): Compilation of void maps.k.b$g.a(byte[], byte[]) took 113.408ms
,D/SamsungIME( 1816): [SwiftkeyWrapper] currentLangauge : 1701729619
,W/dex2oat ( 4100): Compilation of void maps.k.b$h.a(byte[], byte[]) took 110.119ms
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
W/ContextImpl( 3878): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.Pho,toNote
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,D/BadgeProvider( 4556): onCreate
,D/BadgeProvider( 4556): DatabaseHelper
,D/TimaKeyStoreProvider( 4576): TimaSignature is unavailable
,D/ActivityThread( 4576): Added TimaKeyStore provider
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3786/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10022/pid_3767/cgroup.procs: No such file or directory
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1184): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1184): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1184): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1184): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1184): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/Watchdog( 1016): !@Sync 1
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SettingsProvider( 1016): name = audio_safe_volume_state
,I/dex2oat ( 4100): dex2oat took 6.236s (threads: 4)
,D/DexOptUtils( 2088): Odex created at:/data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.dex
D/DexOptUtils( 2088): Set odex to world readable.
,D/DexOptUtils( 2088): Renamed odex to /data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.odex
,I/ActivityManager( 1016): Killing 3811:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #31
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 31662(1689KB) AllocSpace objects, 7(112KB) LOS objects, 33% free, 27MB/40MB, paused 2.793ms total 193.493ms
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
I/AMMetaDataParserService( 3878): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.keyguard.layout
I/AMMetaDataParserService( 3878): getResourcePackageName:assistant
I/AMMetaDataParserService( 3878): Resource data:2131099648
,W/ResourcesManager( 3878): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 3878): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 3878): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,D/BadgeProvider( 4556): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
W/ResourcesManager( 3878): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,W/ResourcesManager( 3878): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3878): getResourceName:com.sec.android.app.camera:xml/assistant
I/AMMetaDataParserService( 3878): getResourceTypeNamexml
,I/AMMetaDataParserService( 3878): Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,D/BadgeProvider( 4556): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,W/ResourcesManager( 4576): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,D/BadgeProvider( 4556): sendNotify, [notify] : null
,D/BadgeProvider( 4556): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4556): update, [BadgeCount] : badgecount=0
,D/BadgeProvider( 4556): update, [UpdateCount] : 1
,D/Launcher.Model( 1486): reloadBadges entered.
,I/AMMetaDataParserService( 3878): Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3811/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
W/ContextImpl( 3878): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/ActivityManager( 1016): startService callerProcessName:com.android.exchange, calleePkgName: com.android.exchange
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.exchange/com.android.exchange.service.ExchangeBroadcastProcessorService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,W/ActivityManager( 1016): getTasks: caller 10145 does not hold GET_TASKS; limiting output
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.SecSetupWizard, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/SMD     (  289): DCD OFF,
,E/Zygote  ( 4593): MountEmulatedStorage(),
E/Zygote  ( 4593): v2
I/libpersona( 4593): KNOX_SDCARD checking this for 1000
,I/libpersona( 4593): KNOX_SDCARD not a persona
,I/SELinux ( 4593): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1016): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4593 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 3831:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,I/SELinux ( 4593): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4593): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/Process ( 4529): Sending signal. PID: 4529 SIG: 9
,D/TimaKeyStoreProvider( 4593): TimaSignature is unavailable
,D/ActivityThread( 4593): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.GridSettings
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:assistant
I/AMMetaDataParserService( 3878): Resource data:2131165220
,W/ResourcesManager( 3878): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 3878): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3878): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3878): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3878): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3878): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3878): getResourceName:com.android.settings:xml/assistant
I/AMMetaDataParserService( 3878): getResourceTypeNamexml
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
I/GFX raster( 3878): took 0.701614ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb7dfd5a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7dfd2d0 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3878): Icon data: ResourceSearch2131363521com.android.settings.Search2130837580
,E/Zygote  ( 4609): MountEmulatedStorage(),
E/Zygote  ( 4609): v2,
I/libpersona( 4609): KNOX_SDCARD checking this for 1000
I/SELinux ( 4609): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 4609): KNOX_SDCARD not a persona
,E/        ( 3878): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3878): took 0.665834ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3878): Bitmap=0xb7dfd3f0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb7e0fe10 counterpartCT=4 counterpartW=96 counterparth=96
,I/SELinux ( 4609): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4609): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1016): Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4609 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
E/lowmemorykiller(  256): Error writing /proc/4529/oom_score_adj; errno=22
I/ActivityManager( 1016): Killing 3506:com.sec.pcw.device/1000 (adj 15): empty #31
,I/AMMetaDataParserService( 3878): Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.SubSettings
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings,.Settings$AdvancedWifiSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity,
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
,I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3878): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.TetherSettings
,I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3878): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  ch,eck
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID,
,I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/ActivityThread( 4576): Removing dead content provider:android.content.ContentProviderProxy@1978748b
I/AMMetaDataParserService( 3878): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/ActivityThread( 4576): Removing dead content provider:android.content.ContentProviderProxy@1978748b
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED,
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/ActivityManager( 1016): Process com.android.email (pid 4529)(adj 9) has died(44,1105)
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
W/ContextImpl( 3878): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.LanguageSettings
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3878): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.android.exchange, calleePkgName: com.android.email
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3878): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
,I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.DockSettings
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3878): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3878): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.ManageApplications
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
,I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
,I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.SecuritySettings
,I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3878): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
,I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.SetProfileOwner
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
,I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/libpersona( 4624): KNOX_SDCARD checking this for 10145
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
,I/libpersona( 4624): KNOX_SDCARD not a persona
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
,I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
,I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/ActivityManager( 1016): Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=4624 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
,I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.ActivityPicker,
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
,I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
D/TimaKeyStoreProvider( 4609): TimaSignature is unavailable
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
,I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3878): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
D/ActivityThread( 4609): Added TimaKeyStore provider
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
,I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/ActivityManager( 1016): Killing 2877:com.google.android.apps.plus/u0a120 (adj 15): empty #31
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 3878): Resource data:Loop for, running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.SViewColor2014
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.SViewStyleClock
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
,I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/splitIntent( 1016): Queue : backgroundsplit_1 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/ActivityManager( 1016): Killing 3878:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
,I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
,I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
W/ResourcesManager( 4624): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity,
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
W/ResourcesManager( 4624): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
W/ResourcesManager( 4624): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
W/ResourcesManager( 4624): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
W/ResourcesManager( 4624): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
W/libprocessgroup( 1016): failed to open /acct/uid_10069/pid_3831/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3506/cgroup.procs: No such file or directory
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:c,om.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 3878): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3878): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 3878): Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
E/Zygote  ( 4624): MountEmulatedStorage()
E/Zygote  ( 4624): v2
I/SELinux ( 4624): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/SELinux ( 4624): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4624): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 4624): TimaSignature is unavailable
D/ActivityThread( 4624): Added TimaKeyStore provider
D/SecurityLogAgent( 4609): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 4609): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4609): StateMachine : Current State = 1
D/SecurityLogAgent( 4609): BootReceiver : completed task. Failed to return wakelock . 
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023,
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1016): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1016): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1016): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/WearableService( 1842): callingUid 10012, callindPid: 1842
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 2088): Restart initialization of location
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,E/MDM     ( 1842): [233] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/BadgeProvider( 4556): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,D/BadgeProvider( 4556): sendNotify entered. [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 4556): sendNotify, [notify] : null
D/Launcher.Model( 1486): reloadBadges entered.
D/BadgeProvider( 4556): update, [uri] : content://com.sec.badge/apps/1
,D/BadgeProvider( 4556): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4556): update, [UpdateCount] : 1
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): getTasks: caller 10146 does not hold GET_TASKS; limiting output
,I/Process ( 4576): Sending signal. PID: 4576 SIG: 9
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,D/TP/SmsProvider( 1464): query,matched:0, calling pid = 2088
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TP/SmsProvider( 1464): match 0:Elapsed time : 3.385 ms
,I/ActivityManager( 1016): Process com.android.exchange (pid 4576)(adj 11) has died(58,1107)
,D/TP/MmsProvider( 1464): Query uri=content://mms, match=0, calling pid = 2088
,D/TP/SmsProvider( 1464): query,matched:0, calling pid = 2088
,D/TP/SmsProvider( 1464): match 0:Elapsed time : 1.780 ms
,D/TP/MmsProvider( 1464): Query uri=content://mms, match=0, calling pid = 2088
,I/DBG_POLICYDM( 4270): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 4270): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 4270): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 4270): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
W/IcingInternalCorpora( 2088): getNumBytesRead when not calculated.
,I/DBG_POLICYDM( 4270): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 4270): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 4270): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1184): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1184): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1184): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/libprocessgroup( 1016): failed to open /acct/uid_10120/pid_2877/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3878/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.location.nearby.direct.service.NearbyDirectService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
,D/AuthorizationBluetoothService( 1842): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/a       ( 1842): Opening database auth.proximity.permit_store...
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.location.nearby.direct.service.NearbyDirectService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1842): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GCoreFlp( 1842): No location to return for getLastLocation()
,W/FusedLocationProvider( 1842): location=null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 2546): Starting #4
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
I/Hs20UtilService( 2546): Message received 5007
,D/NearbySettings( 1317): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1317): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1317): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1317): DMSUtil.isNetworkConnected - P2P: IDLE
I/NearbySettings( 1317): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1317): MountReceiver.onReceive - Keep current state
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/splitIntent( 1016): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1016): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1016): other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
I/splitIntent( 1016): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1842): [248] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 2088): Restart initialization of location
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1842): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1016): Waited long enough for: ServiceRecord{fc19496 u0 com.samsung.android.providers.context/.ContextService}
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1842): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 2546): Starting #5
,I/Hs20UtilService( 2546): Message received 5007
,D/NearbySettings( 1317): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,W/GCoreFlp( 1842): No location to return for getLastLocation()
,W/FusedLocationProvider( 1842): location=null
,I/NearbySettings( 1317): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 2546): Starting #6
,I/Hs20UtilService( 2546): Message received 5007
D/NearbySettings( 1317): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,V/NearbySettings( 1317): DMSUtil.isNetworkConnected - flag-null, state-null
,I/NearbySettings( 1317): DMSUtil.isNetworkConnected - WIFI: CONNECTED
,I/NearbySettings( 1317): DMSUtil.isNetworkConnected - P2P: IDLE,
I/NearbySettings( 1317): DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1317): MountReceiver.onReceive - Keep current state
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2,
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 2546): Starting #7
,I/Hs20UtilService( 2546): Message received 5007
,D/NearbySettings( 1317): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1317): MountReceiver.onReceive - Keep current state
,D/WifiStateMachine( 1016): SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityEnabledState,
D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravity
D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityXOffset,
D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastGravityYOffset
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastEnabledState
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 15 selection = getToastShowPackageNameState
,D/SecContentProvider2( 1016): mCursor = null
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/ActivityManager( 1016): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=4677 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,E/Zygote  ( 4677): MountEmulatedStorage(),
E/Zygote  ( 4677): v2
I/libpersona( 4677): KNOX_SDCARD checking this for 1000
I/libpersona( 4677): KNOX_SDCARD not a persona,
,I/SELinux ( 4677): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4677): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,I/SurfaceFlinger(  259): id=12 createSurf (1x1),1 flag=4, Uoast
,E/SELinux ( 4677): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/PowerManagerService( 1016): [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1016
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 60 -> 60
D/DisplayPowerController( 1016): animation target = 60, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 1016): [s] DisplayPowerCallbacks : onStateChanged()
,I/art     (  308): Explicit concurrent mark sweep GC freed 8753(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 634us total 30.671ms
,D/SRIB_DCS( 1184): log_dcs ThreadedRenderer::initialize entered! 
,D/TimaKeyStoreProvider( 4677): TimaSignature is unavailable
,D/lights  ( 1016): lcd : 42 +
,D/ActivityThread( 4677): Added TimaKeyStore provider
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 610us total 16.944ms
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 60 -> 60
D/DisplayPowerController( 1016): animation target = 60, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 1016): lcd : 42 -
D/lights  ( 1016): lcd : 60 +
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 620us total 16.996ms
,I/PCWCLIENTTRACE_LOG( 4677): DEFAULT_LOGON : true
,I/PCWCLIENTTRACE_LOG( 4677): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 4677): new DMDBOpenHelper instance
,D/lights  ( 1016): lcd : 60 -
,D/DisplayPowerController( 1016): getFinalBrightness : Summary is 60 -> 60
D/DisplayPowerController( 1016): animation target = 60, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/PCWCLIENTTRACE_PushUtil( 4677): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 4677): sales region : global
I/PCWCLIENTTRACE_PushUtil( 4677): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 4677): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1016): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=10, mSplitNum[1]=17, mSplitNum[2]=26, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=34
I/splitIntent( 1016): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4694): MountEmulatedStorage()
,E/Zygote  ( 4694): v2
I/libpersona( 4694): KNOX_SDCARD checking this for 10111
,I/libpersona( 4694): KNOX_SDCARD not a persona
,I/ActivityManager( 1016): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=4694 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 4694): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4694): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4694): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/accuweather( 1727): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,I/KLMS-2.5.183: ( 3744): KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Mar 14 17:16:57 GMT+01:00 2016
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,D/SecurityLogAgent( 4609): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 4609): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4609): StateMachine : Current State = 1
,I/ActivityManager( 1016): Waited long enough for: ServiceRecord{30904404 u0 com.android.settings/.wifi.WifiCredService}
,D/SecurityLogAgent( 4609): StateMachine : Changed Current State = 1
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,I/KLMS-2.5.183: ( 3744): KLMSAbstractReciever(): onReceive().END.
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/daemonapp( 1333): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,D/TimaKeyStoreProvider( 4694): TimaSignature is unavailable
,D/ActivityThread( 4694): Added TimaKeyStore provider
,I/KLMS-2.5.183: ( 3744): KLMSIntentService(): onCreate()
,I/KLMS-2.5.183: ( 3744): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,I/KLMS-2.5.183: ( 3744): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,I/KLMS-2.5.183: ( 3744): KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,E/Zygote  ( 4710): MountEmulatedStorage()
,E/Zygote  ( 4710): v2
I/libpersona( 4710): KNOX_SDCARD checking this for 10159
I/SELinux ( 4710): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
I/libpersona( 4710): KNOX_SDCARD not a persona
I/ActivityManager( 1016): Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=4710 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/KLMS-2.5.183: ( 3744): KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
I/SELinux ( 4710): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4710): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.183: ( 3744): KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,I/KLMS-2.5.183: ( 3744): StateImplV2(): networkChangeListener().START
,D/accuweather( 1727): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 1727): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1727): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1727): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,I/KLMS-2.5.183: ( 3744): NetworkChangeOperations(): uploadRequestLog().START 
,D/accuweather( 1727): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1727): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,I/KLMS-2.5.183: ( 3744): NetworkChangeOperations(): uploadRequestLog().END 
,I/KLMS-2.5.183: ( 3744): StateImplV2(): networkChangeListener().END
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4710): TimaSignature is unavailable
,E/Zygote  ( 4725): MountEmulatedStorage(),
E/Zygote  ( 4725): v2
D/ActivityThread( 4710): Added TimaKeyStore provider
I/libpersona( 4725): KNOX_SDCARD checking this for 10081,
I/libpersona( 4725): KNOX_SDCARD not a persona
,I/SELinux ( 4725): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/ActivityManager( 1016): Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=4725 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 4725): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
E/SELinux ( 4725): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,I/KLMS-2.5.183: ( 3744): KLMSIntentService(): onDestroy()
,I/DBG_POLICYDM( 4270): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 4270): [com.policydm.XDMApplication(469/isNetworkChanged)] a previous network is 0, current network is 2
,E/DBG_POLICYDM( 4270): [com.policydm.XDMApplication(471/isNetworkChanged)] network changed.... 
,D/TimaKeyStoreProvider( 4725): TimaSignature is unavailable
,D/ActivityThread( 4725): Added TimaKeyStore provider
,E/SPPClientService( 4324): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 4370): [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,I/SA      ( 4370): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 4370): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/DBG_POLICYDM( 4270): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 4270): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 4270): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 4270): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 4270): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 4270): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 4270): [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,I/DBG_POLICYDM( 4270): [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,I/SA      ( 4370): [SLFUCHKMGR] constructor called
,E/DBG_POLICYDM( 4270): [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,I/SA      ( 4370): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 4370): [OR] == isSIMCardReady false ==
,I/DBG_POLICYDM( 4270): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/SA      ( 4370): [SCU] == networkStateCheck == true
,I/SA      ( 4370): [DM] getCountryCodeFromCSC : PL
I/SA      ( 4370): isChinaCountryCode : false
I/SA      ( 4370): [SCU] is ChinestModel Data Restricted   : false
I/SA      ( 4370): [OR] == networkStateCheck true ==
,D/SensorService( 1016): [SO] 0.134 0.402 10.151
,I/iu.SyncManager( 2088): SYNC; picasa accounts
,D/NetworkLogImpl( 2088): Loaded NetworkSpeedPredictor
I/SA      ( 4370): [OR] GetMyCountryZoneTask
,I/SA      ( 4370): [OR] onReceive END
,I/iu.Environment( 2088): update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,V/DownloadManager( 1239): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,D/ActivityManager( 1016): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,D/SecContentProvider2( 1016): uri = 15 selection = getAppBlockDownloadState
D/SecContentProvider2( 1016): mCursor = null
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4750): MountEmulatedStorage(),
,E/Zygote  ( 4750): v2,
I/libpersona( 4750): KNOX_SDCARD checking this for 10010
I/libpersona( 4750): KNOX_SDCARD not a persona
,I/SELinux ( 4750): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4750): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1184): onWifiSignalChanged enabled=true enabledDesc:"NG700"
I/ActivityManager( 1016): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=4750 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a,
D/StatusBar.NetworkController( 1184): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
E/SELinux ( 4750): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/SA      ( 4370): [SRS] prepareGetMyCountryZone,
,D/StatusBar.NetworkController( 1184): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1184): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/SA      ( 4370): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 4370): [SSP] query invoked
,I/SA      ( 4370): [TPMU] GetMccFromDB : null
I/SA      ( 4370): [SCU] getMccFromPreferece mcc = 260
,I/SA      ( 4370): [TPM] isNoProxy(default) : true
,D/TimaKeyStoreProvider( 4750): TimaSignature is unavailable
,D/ActivityThread( 4750): Added TimaKeyStore provider
,I/ActivityManager( 1016): Killing 3727:com.google.android.gm/u0a101 (adj 15): empty #31
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/File    ( 4370): fail readDirectory() errno=2
,E/Zygote  ( 4768): MountEmulatedStorage(),
E/Zygote  ( 4768): v2
I/libpersona( 4768): KNOX_SDCARD checking this for 10113
I/libpersona( 4768): KNOX_SDCARD not a persona
,I/SELinux ( 4768): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/iu.UploadsManager( 2088): num queued entries: 0,
I/SELinux ( 4768): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4768 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 4768): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Killing 3670:com.samsung.android.sm/1000 (adj 15): empty #31,
I/iu.UploadsManager( 2088): num updated entries: 0
,I/iu.SyncManager( 2088): NEXT; no task
,D/TimaKeyStoreProvider( 4768): TimaSignature is unavailable
,D/ActivityThread( 4768): Added TimaKeyStore provider
,I/MusicStore( 4694): Database version: 108
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3670/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10101/pid_3727/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/WaitQueueForNetworkActivate( 4750): notifyNetworkActivated
,W/ContextImpl( 4750): Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,W/ResourcesManager( 4694): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4694): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp ( 4694): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread( 4694): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  ( 4694): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@e9efa3c: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 4694): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic( 4694): GMSCore installation verified
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/ConfigStore( 4694): Config Database version: 1
,D/ActivityManager( 1016): startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.example.hello, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4796): MountEmulatedStorage()
E/Zygote  ( 4796): v2
I/libpersona( 4796): KNOX_SDCARD checking this for 10174
,I/libpersona( 4796): KNOX_SDCARD not a persona
,I/SELinux ( 4796): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.example.hello for broadcast com.example.hello/io.jxcore.node.ConnectivityChangeListener: pid=4796 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
,I/SELinux ( 4796): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4796): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/hcjo    ( 4750): AutoUpdateManager:IDLE:execute
,D/InitializeManagerStateMachine( 4750): execute::IDLE:EXECUTE
,D/InitializeManagerStateMachine( 4750): exit::IDLE
D/InitializeManagerStateMachine( 4750): entry::NETWORK_CHECK
,D/InitializeManagerStateMachine( 4750): execute::NETWORK_CHECK:NETWORK_STATE_OK
D/InitializeManagerStateMachine( 4750): exit::NETWORK_CHECK
D/InitializeManagerStateMachine( 4750): entry::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4750): execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
D/InitializeManagerStateMachine( 4750): exit::CHECK_COUNTRY_INFO
D/InitializeManagerStateMachine( 4750): entry::SUCCESS
D/hcjo    ( 4750): AutoUpdateManager:INITCHECK:onInitializeSuccess
,D/TimaKeyStoreProvider( 4796): TimaSignature is unavailable
,D/hcjo    ( 4750): AutoUpdateTriggerManager:IDLE:setInterval:345600000
,D/ActivityThread( 4796): Added TimaKeyStore provider
,D/hcjo    ( 4750): AutoUpdateTriggerManager:IDLE:notifyNextTime
D/hcjo    ( 4750): AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,D/InitializeManagerStateMachine( 4750): exit::SUCCESS
D/InitializeManagerStateMachine( 4750): entry::IDLE
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4694): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4694): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4694): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/jxcore_app_log( 4796): JniHelper::setJavaVM(0xb7325450), pthread_self() = -1224909112
,E/JX-Cordova( 4796): JXcore wasn't initialized yet
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/,
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4768): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
,W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4768): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1016): getStreamVolume 3 index 0
,I/MediaRouter( 4694): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,V/MusicLeanback( 4694): onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,I/NetworkMonitor( 4694): type=WIFI subType= reason=null isConnected=true
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4768): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  258): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  258): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4768): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1184): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 1184): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1184): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1184): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1184): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/WifiDisplayAdapter( 1016): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/NetworkMonitor( 4694): type=WIFI subType= reason=null isConnected=true
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4833): MountEmulatedStorage()
E/Zygote  ( 4833): v2
I/libpersona( 4833): KNOX_SDCARD checking this for 10002
I/libpersona( 4833): KNOX_SDCARD not a persona
,I/SELinux ( 4833): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4833): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4833): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=4833 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 4833): TimaSignature is unavailable
,D/ActivityThread( 4833): Added TimaKeyStore provider
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,W/GoogleHttpClient( 4694): Failed to load SSLCertificateSocketFactory from package
I/GoogleHttpClient( 4694): Falling back to old SSLCertificateSocketFactory
,I/GHttpClientFactory( 4694): Using the GMSCore's GoogleHttpClient
,D/ActivityManager( 1016): bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,I/WebViewFactory( 4768): Loading com.google.android.webview version 43.0.2357.121 (code 2357121),
,I/LibraryLoader( 4768): Time to load native libraries: 1 ms (timestamps 2510-2511)
,I/LibraryLoader( 4768): Expected native library version number "",actual native library version number ""
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1016): Killing 3399:com.google.android.youtube/u0a166 (adj 15): empty #31
,V/AlarmManager( 1016): waitForAlarm result :4
,V/WebViewChromiumFactoryProvider( 4768): Binding Chromium to main looper Looper (main, tid 1) {759d1c3}
,I/LibraryLoader( 4768): Expected native library version number "",actual native library version number ""
,I/chromium( 4768): [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,I/ActivityManager( 1016): Killing 3901:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/BrowserStartupController( 4768): Initializing chromium process, singleProcess=true
,W/art     ( 4768): Attempt to remove local handle scope entry from IRT, ignoring
,E/SysUtils( 4768): ApplicationContext is null in ApplicationStatus,
,E/Zygote  ( 4854): MountEmulatedStorage()
E/Zygote  ( 4854): v2
I/libpersona( 4854): KNOX_SDCARD checking this for 1000
I/libpersona( 4854): KNOX_SDCARD not a persona
,I/SELinux ( 4854): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4854): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,I/ActivityManager( 1016): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=4854 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
E/SELinux ( 4854): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4854): TimaSignature is unavailable
,D/ActivityThread( 4854): Added TimaKeyStore provider
,W/chromium( 4768): [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,I/chromium( 4768): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
I/chromium( 4768): [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,E/SMD     (  289): DCD OFF
I/Adreno-EGL( 4768): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 4768): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 4768): Build Date: 04/06/15 Mon
I/Adreno-EGL( 4768): Local Branch: 
I/Adreno-EGL( 4768): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 4768): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 4768):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,I/DIAGMON_AGENT( 4854): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,W/AudioManagerAndroid( 4768): Requires BLUETOOTH permission
,I/NSApplication( 4768): Starting up...
,W/libprocessgroup( 1016): failed to open /acct/uid_10166/pid_3399/cgroup.procs: No such file or directory
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4885): MountEmulatedStorage(),
E/Zygote  ( 4885): v2
,I/libpersona( 4885): KNOX_SDCARD checking this for 10120
I/libpersona( 4885): KNOX_SDCARD not a persona,
,I/SELinux ( 4885): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4885): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,I/ActivityManager( 1016): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=4885 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1016): Killing 4109:com.samsung.helphub/1000 (adj 15): empty #31
I/ActivityManager( 1016): Killing 3856:com.vlingo.midas/u0a31 (adj 15): empty #32
,I/ActivityManager( 1016): Killing 1934:com.android.defcontainer/u0a4 (adj 15): empty #33
,E/SELinux ( 4885): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 4885): TimaSignature is unavailable
,D/ActivityThread( 4885): Added TimaKeyStore provider
,I/DIAGMON_AGENT( 4854): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_3901/cgroup.procs: No such file or directory
,I/DIAGMON_AGENT( 4854): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 4854): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,I/DIAGMON_AGENT( 4854): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 4854): ./extraInfo: "NG700"
,I/DIAGMON_AGENT( 4854): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,W/ResourcesManager( 4885): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,V/AlarmManager( 1016): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 1184): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 1184): handleTimeUpdate
,D/SecKeyguardClockView( 1184): onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
,D/SecKeyguardClockView( 1184): HomeTimezone(): 1
,D/SecKeyguardStatusUtils( 1184): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/KeyguardEffectViewController( 1184): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 1184): *** don't update sliding image ***
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4109/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10004/pid_1934/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10031/pid_3856/cgroup.procs: No such file or directory
,D/accuweather( 1727): [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK
,D/accuweather( 1727): [KK AccuPhone]>>> UIM:119 [0:0] getInstance
,D/accuweather( 1727): [KK AccuPhone]>>> UIM:289 [0:0] direct update clock
,D/accuweather( 1727): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
D/accuweather( 1727): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,D/accuweather( 1727): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
,D/accuweather( 1727): [KK AccuPhone]>>> UIM:1448 [0:0] mc sy = 2
,D/accuweather( 1727): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 141span x = 4, span y = 2
D/accuweather( 1727): [KK AccuPhone]>>> UIM:185 [0:0] get widget 4x2 view!!! wid = 2
,D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,E/accuweather( 1727): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 17 17
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4905): MountEmulatedStorage()
E/Zygote  ( 4905): v2
I/libpersona( 4905): KNOX_SDCARD checking this for 10009
I/SA      ( 4370): [RC New] Execute method=[GET] start
I/libpersona( 4905): KNOX_SDCARD not a persona
,I/SELinux ( 4905): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4905): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4905): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=4905 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 4905): TimaSignature is unavailable
,D/ActivityThread( 4905): Added TimaKeyStore provider
,D/DateView( 1184): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1184): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 1184): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SecKeyguardStatusUtils( 1184): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/SA      ( 4370): [RC New] Security=[true]
,I/System.out( 4370): Thread-660(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 4370): Thread-660(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 4370): Thread-660(ApacheHTTPLog):isShipBuild true
I/System.out( 4370): Thread-660(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 4370): Thread-660(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController(  279): uids 10041
D/EnterpriseController(  279): mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10041
,I/FOTA_Client( 4905): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,I/FOTA_Client( 4905): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,I/FOTA_Client( 4905): [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,W/FOTA_Client( 4905): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,I/ActivityManager( 1016): Killing 4002:com.android.vending/u0a28 (adj 15): empty #31
,W/libprocessgroup( 1016): failed to open /acct/uid_10028/pid_4002/cgroup.procs: No such file or directory
,D/QuickConnect( 4423): PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,I/QuickConnect( 4423): PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
I/QuickConnect( 4423): PeriphStartReceiver.onReceive - no need to start
,D/StatusBar.NetworkController( 1184): refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1184): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1184): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1184): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1184): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,D/RCPManagerService( 1016): exchangeData() failure , invalid userId
,I/splitIntent( 1016): Queue : backgroundsplit_1 intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 1016): Killing 4150:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
,I/splitIntent( 1016): Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=13, mSplitNum[2]=18, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=24
I/splitIntent( 1016): finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,I/FOTA_Client( 4905): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/FOTA_Client( 4905): [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,E/Zygote  ( 4928): MountEmulatedStorage()
E/Zygote  ( 4928): v2
I/ActivityManager( 1016): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=4928 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/libpersona( 4928): KNOX_SDCARD checking this for 10062
I/libpersona( 4928): KNOX_SDCARD not a persona
,I/SELinux ( 4928): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,I/SELinux ( 4928): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 4928): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.183: ( 3744): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Mon Mar 14 17:17:00 GMT+01:00 2016
D/ActivityManager( 1016): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,I/art     (  308): Explicit concurrent mark sweep GC freed 8706(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 675us total 22.451ms
,D/TimaKeyStoreProvider( 4928): TimaSignature is unavailable
,D/ActivityThread( 4928): Added TimaKeyStore provider
,D/daemonapp( 1333): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1333): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
W/ActivityManager( 1016): userId = 0, bbcId = -10000
D/daemonapp( 1333): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 616us total 17.133ms
D/daemonapp( 1333): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/KLMS-2.5.183: ( 3744): KLMSAbstractReciever(): onReceive().END.
,D/daemonapp( 1333): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,I/KLMS-2.5.183: ( 3744): KLMSIntentService(): onCreate()
,D/daemonapp( 1333): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4150/cgroup.procs: No such file or directory
,I/art     (  308): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 631us total 16.831ms
,D/comsamsunglog( 1333): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1333): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1333): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1333): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1333): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1333): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/KLMS-2.5.183: ( 3744): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,D/daemonapp( 1333): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/ActivityManager( 1016): startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,I/SA      ( 4370): [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
D/daemonapp( 1333): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1333): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1333): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
I/KLMS-2.5.183: ( 3744): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,D/daemonapp( 1333): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/KLMS-2.5.183: ( 3744): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,I/KLMS-2.5.183: ( 3744): KLMSIntentService(): TIME_CHANGED
,D/SecurityLogAgent( 4609): KnoxConfiguration : Current State = 1
D/SecurityLogAgent( 4609): KnoxConfiguration : Current State Mapping Found 
D/SecurityLogAgent( 4609): StateMachine : Current State = 1
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,E/daemonapp( 1333): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
I/KLMS-2.5.183: ( 3744): StateImplV2(): dateTimeChanged().START : Mon Mar 14 17:17:00 GMT+01:00 2016
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,I/KLMS-2.5.183: ( 3744): StateImplV2(): dateTimeChanged().END
,E/Zygote  ( 4946): MountEmulatedStorage()
E/Zygote  ( 4946): v2
I/libpersona( 4946): KNOX_SDCARD checking this for 10157
I/libpersona( 4946): KNOX_SDCARD not a persona
,I/SELinux ( 4946): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4946): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=4946 uid=10157 gids={50157, 9997} abi=armeabi-v7a
E/SELinux ( 4946): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/KLMS-2.5.183: ( 3744): KLMSIntentService(): onDestroy()
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/comdaemonstockapp( 1333): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,D/comdaemonstockapp( 1333): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,I/ExternalOEMControlProvider( 4928): onCreate
,E/Zygote  ( 4957): MountEmulatedStorage()
,E/Zygote  ( 4957): v2
I/libpersona( 4957): KNOX_SDCARD checking this for 10046
I/libpersona( 4957): KNOX_SDCARD not a persona
,I/SELinux ( 4957): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=4957 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/SELinux ( 4957): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4957): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4946): TimaSignature is unavailable
,D/ActivityThread( 4946): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 4957): TimaSignature is unavailable,
D/ActivityThread( 4957): Added TimaKeyStore provider
,D/PowerManagerService( 1016): [s] UserActivityState : 2 -> 4
,I/PowerManagerService( 1016): [PWL] On : 0 (53630 ms ago)
,I/PowerManagerService( 1016): [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x4
,I/PowerManagerService( 1016): [PWL]  SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1016, ws=WorkSource{10054}) (elapsedTime=2862)
,I/ServiceManager(  319): Waiting for service AtCmdFwd...,
,I/art     ( 1016): Explicit concurrent mark sweep GC freed 36947(2MB) AllocSpace objects, 0(0B) LOS objects, 33% free, 27MB/40MB, paused 2.635ms total 159.991ms
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ConfigService( 1842): onDestroy
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 4957): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 4957): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4957): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 4946): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/Zygote  ( 4977): MountEmulatedStorage()
E/Zygote  ( 4977): v2
,I/libpersona( 4977): KNOX_SDCARD checking this for 1000
I/libpersona( 4977): KNOX_SDCARD not a persona
,I/SELinux ( 4977): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
W/ResourcesManager( 4957): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4957): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 4957): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.,
,I/SELinux ( 4977): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 4977): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.contextagent.ContextAgentReceiver: pid=4977 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.qualcomm.timeservice, hostingType: broadcast
,I/ Time Manager ( 4928): Time Difference not stored. TIME_DIFFERENCE
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4992): MountEmulatedStorage(),
E/Zygote  ( 4992): v2
,I/libpersona( 4992): KNOX_SDCARD checking this for 1000
I/libpersona( 4992): KNOX_SDCARD not a persona,
I/ActivityManager( 1016): Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4992 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,I/SELinux ( 4992): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 4992): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 4992): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/TimaKeyStoreProvider( 4977): TimaSignature is unavailable
D/ActivityThread( 4977): Added TimaKeyStore provider
,D/PackageManager( 1016): [MSG] WRITE_PACKAGE_RESTRICTIONS
,D/TimaKeyStoreProvider( 4992): TimaSignature is unavailable
,D/ActivityThread( 4992): Added TimaKeyStore provider
,D/Mms/MmsApp( 4957): [start]    onCreate() consume time = 0.0
,I/ActivityManager( 1016): Killing 4190:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,D/ActivityManager( 1016): startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 4977): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/ActivityManager( 1016): Killing 4211:com.google.android.apps.maps/u0a107 (adj 15): empty #31
,D/TimeService( 4992): Receivedandroid.intent.action.TIME_SET intent. Current Time is 1457972220972
D/        ( 4992): TimeServiceNative: User Time to be set is 1457972220972
D/QC-time-services( 4992): Lib:time_genoff_operation: pargs->base = 2
D/QC-time-services( 4992): Lib:time_genoff_operation: pargs->operation = 0
D/QC-time-services( 4992): Lib:time_genoff_operation: pargs->ts_val = 1457972220972
,D/QC-time-services( 4992): Lib:time_genoff_operation: Send to server  passed!!
D/QC-time-services(  321): Daemon: Connection accepted:time_genoff
,D/QC-time-services(  321): Daemon:Received base = 2, unit = 1, operation = 0,value = 1457972220972
D/QC-time-services(  321): Daemon:genoff_opr: Base = 2, val = 1457972220972, operation = 0
,D/QC-time-services(  321): Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS8/13/70 14:22:17
D/QC-time-services(  321): Daemon:Value read from RTC seconds = 22083737000
D/QC-time-services(  321): Daemon:new time 1457972220972 
D/QC-time-services(  321): Daemon: delta 1435888483972 genoff 1435888483972 
D/QC-time-services(  321): Daemon:genoff_persistent_update: Writing genoff = 1435888483972 to memory
D/QC-time-services(  321): Daemon:Opening File: /data/time/ats_2
D/QC-time-services(  321): Daemon:time_persistent_memory_opr:Genoff write operation 
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4190/cgroup.procs: No such file or directory
,D/accuweather( 1727): [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,D/accuweather( 1727): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/QC-time-services(  321): Updating the TOD offset
D/QC-time-services(  321): Daemon:genoff_persistent_update: Writing genoff = 1435888483972 to memory
D/QC-time-services(  321): Daemon:Opening File: /data/time/ats_1
D/QC-time-services(  321): Daemon:time_persistent_memory_opr:Genoff write operation 
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/QC-time-services(  321): Daemon:Update to modem bit set
D/QC-time-services(  321): Daemon:genoff_send_modem: Sending data to MODEM !
D/QC-time-services(  321): Daemon: Base = 2, Value being sent to MODEM = 1119923683972
,E/QC-time-services( 4992): Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,E/QC-time-services(  321): Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
E/QC-time-services(  321): Daemon: Time-services: Waiting to acceptconnection
,E/Zygote  ( 5009): MountEmulatedStorage()
,E/Zygote  ( 5009): v2
I/libpersona( 5009): KNOX_SDCARD checking this for 10085
I/libpersona( 5009): KNOX_SDCARD not a persona
,I/SELinux ( 5009): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=5009 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 5009): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
E/SELinux ( 5009): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Killing 4353:com.sec.android.app.mt/1000 (adj 15): empty #31,
,I/ActivityManager( 1016): Killing 4460:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
,D/ActivityManager( 1016): startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
D/TimaKeyStoreProvider( 5009): TimaSignature is unavailable
,D/ActivityThread( 5009): Added TimaKeyStore provider
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,W/ResourcesManager( 5009): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager( 5009): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 5009): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 5009): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 5009): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 5009): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,I/ActivityManager( 1016): Killing 4507:com.sec.android.app.camera/u0a139 (adj 15): empty #31
,W/art     ( 4957): Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 139.065ms
,D/SSRM:n  ( 1016): SIOP:: AP = 400
,D/SettingsProvider( 1016): name = next_alarm_formatted
,D/SettingsProvider( 1016): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1016): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1016): selectionArgs: false
D/SettingsProvider( 1016): selectionArgs: 10085
D/SecContentProvider( 1016): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1016): ret = -1
,W/libprocessgroup( 1016): failed to open /acct/uid_10107/pid_4211/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10131/pid_4460/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4353/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10139/pid_4507/cgroup.procs: No such file or directory
,D/Mms/ArtClassLoader( 4957): init before art
,D/Mms/TelephonyPermission( 4957): start operation mode monitor
,W/ResourcesManager( 4957): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/Mms/TelephonyPermission( 4957): DefaultSmsApp is com.android.mms
,D/Mms/TelephonyPermission( 4957): isDefault true
,D/Mms/MmsApp( 4957): onCreate() com.android.mms
,D/PowerManagerService( 1016): [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 1016) eventTime = 54239
,D/PowerManagerService( 1016): [s] UserActivityState : 4 -> 1
,D/PowerManagerService( 1016): [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1016 (0x0)
,D/PowerManagerService( 1016): [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1016, ws=WorkSource{10054}) (elapsedTime=3473)
,D/Mms/MmsApp( 4957): [start]    initCountryIso consume time = 387.112813
,D/CountryDetector( 1016): The first listener is added
,D/Mms/MmsApp( 4957): [end]    initCountryIso consume time = 7.972604
D/Mms/MmsConfig( 4957): [start]    MmsConfig.init() consume time = 0.119896
,W/art     ( 5009): Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 127.379ms
,D/Mms/MmsConfig( 4957): before partial update
,D/Mms/MmsConfig( 4957): Load Resize quality : 80
,D/EasySignUpManager_1.0.1( 4957): serviceId : 1, features : -1
,D/EasySignUpManager_1.0.1( 4957): isAuth is false
,D/Mms/MmsConfig( 4957): setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,D/TP/MmsSmsProvider( 1464): query,matched:2117, calling pid = 4957
,D/TP/MmsSmsProvider( 1464): match 2117:Elapsed time : 1.782 ms
,I/SA      ( 4370): [RC New] [v2liruge] api execute + 1190
,I/SA      ( 4370): [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,D/EasySignUpManager_1.0.1( 4957): isAuth is false
,D/EasySignUpManager_1.0.1( 4957): getServiceStatus : serviceId (1) is OFF
,E/CscParser( 4957): mps_code.dat does not exist
,E/CscParser( 4957): customer_path =/system/csc/customer.xml
,E/CscParser( 4957): fileName + /system/csc/customer.xml
I/System.out( 4370): AsyncTask #1 calls detatch()
,E/CscParser( 4957): mps_code.dat does not exist
,E/CscParser( 4957): customer_path =/system/csc/customer.xml
E/CscParser( 4957): fileName + /system/csc/customer.xml
,I/SA      ( 4370): [ODM] saveOpenData( GEO_IP, PL )
,D/CscParser( 4957): getInstance fileName =/system/csc/customer.xml
,D/Mms/MmsConfig( 4957):  enable multiwindow = true
,E/Mms/MessageUtils( 4957): setCountryDetector : update country detector info 
,E/Mms/MessageUtils( 4957): updateCountryIso : update country iso info 
,I/SA      ( 4370): [OCP] update openData : PL
,I/SA      ( 4370): [TPMU] getNetworkMcc : 
,I/SA      ( 4370): [SCU] saveMccToPreferece Start
,I/SA      ( 4370): [SCU] RegionMCC : 260
I/SA      ( 4370): [SSP] query invoked
,D/Mms/MmsConfig( 4957): [end]    init() consume time = 126.667135
D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/ContextImpl( 1016): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
D/Mms/Contact( 4957): [start]    init() consume time = 2.840052
,I/SA      ( 4370): [TPMU] GetMccFromDB : null,
I/SA      ( 4370): [SCU] getMccFromPreferece mcc = 260
I/SA      ( 4370): [SCU] saveMccToPreferece End
,I/SA      ( 4370): [RC New] executeRequest [v2liruge] end. 1345
I/SA      ( 4370): [RC New] Execute end
I/SA      ( 4370): [OR] GetMyCountryZoneTask mcc = 260
I/SA      ( 4370): [OR] GetMyCountryZoneTask Success
,E/Zygote  ( 5031): MountEmulatedStorage()
E/Zygote  ( 5031): v2
,I/libpersona( 5031): KNOX_SDCARD checking this for 10094
I/libpersona( 5031): KNOX_SDCARD not a persona
,I/SELinux ( 5031): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5031): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
I/ActivityManager( 1016): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5031 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
E/SELinux ( 5031): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1016): Killing 4556:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,D/TP/MmsSmsProvider( 1464): query,matched:13, calling pid = 4957
,D/TP/MmsSmsProvider( 1464): match 13:Elapsed time : 2.902 ms
,D/TimaKeyStoreProvider( 5031): TimaSignature is unavailable
,D/ActivityThread( 5031): Added TimaKeyStore provider
,D/Mms/Contact( 4957): [end]    init consume time = 54.532135
,D/Mms/DraftCache( 4957): [start]    rebuildCache consume time = 7.742084
,D/TP/MmsSmsProvider( 1464): query,matched:12, calling pid = 4957
,D/TP/MmsSmsProvider( 1464): match 12:Elapsed time : 2.360 ms
,D/Mms/MethodReflector( 4957): getSubId is called
D/Mms/TelephonyUtils( 4957): getLongSubId from simSlot 0, return Value = -1
,D/Mms/MethodReflector( 4957): getTelephonyProperty is called
D/Mms/DownloadManager( 4957): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 4957): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 4957): auto download without roaming -> true
D/Mms/DownloadManager( 4957): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,D/Mms/MethodReflector( 4957): getSubId is called
,D/Mms/MethodReflector( 4957): getDefaultSmsSubId is called
E/Mms/TelephonyUtils( 4957): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils( 4957): getLongSubId from simSlot 1, return Value = -1000
,D/Mms/MethodReflector( 4957): getTelephonyProperty is called
D/Mms/DownloadManager( 4957): roaming -> false (slotId = 1)
D/Mms/DownloadManager( 4957): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager( 4957): auto download without roaming -> true
D/Mms/DownloadManager( 4957): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager( 4957): auto download during roaming secondary -> false
D/Mms/DownloadManager( 4957): mAutoDownload ------> true
,D/Mms/DraftCache( 4957): [end]    rebuildCache consume time = 36.511146
,D/elm:15183( 5031): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,D/elm:15183( 5031): ELMEngine.ELMEngine( context ).
,D/elm:15183( 5031): MDMBridge.setEnterpriseBridge()
,D/ActivityManager( 1016): startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm,
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,D/elm:15183( 5031): ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,W/libprocessgroup( 1016): failed to open /acct/uid_10072/pid_4556/cgroup.procs: No such file or directory
,D/elm:15183( 5031): ElmAgentService : onCreate()
D/elm:15183( 5031): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,E/Zygote  ( 5051): MountEmulatedStorage()
,E/Zygote  ( 5051): v2
,D/ComposerPerformance( 4957): 1457972221561 ms / [DONE] Composer constructor
I/libpersona( 5051): KNOX_SDCARD checking this for 10134
I/libpersona( 5051): KNOX_SDCARD not a persona
,I/SELinux ( 5051): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=5051 uid=10134 gids={50134, 9997} abi=armeabi-v7a,
,I/SELinux ( 5051): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5051): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
D/elm:15183( 5031): ELMAgentService.listeningToTimeDateChanges( context, intent ).
,D/elm:15183( 5031): ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,E/CII     ( 4957): CommonIMSInterface: VoLTE CSC feature disabled.
,I/Mms/ReservationManager( 4957): ReservationManager()
I/Mms/ReservationManager( 4957): resetAfterConnected()
,D/elm:15183( 5031): ModuleBase.ModifySetAlarm()
D/elm:15183( 5031): MDMBridge.getInstance()
D/elm:15183( 5031): MDMBridge.getAllLicenseInfoFromSDK()
,D/TP/MmsSmsProvider( 1464): query,matched:7, calling pid = 4957
,D/elm:15183( 5031): ElmAgentService : onDestroy().
,I/ActivityManager( 1016): Killing 4593:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
,D/TP/MmsSmsProvider( 1464): match 7:Elapsed time : 4.200 ms
,D/Mms/Conversation( 4957): [start]    init() consume time = 67.651979
,D/TP/MmsSmsProvider( 1464): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 1464): delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,V/TP/MmsSmsDatabaseHelper( 1464): updateThread(), thread_id = 9223372036854775807
,V/TP/MmsSmsDatabaseHelper( 1464): sUpgradeVersion = 0, db.getVersion() = 81
,E/SQLiteLog( 1464): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1464): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1464): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1464): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1464): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 1464): (284) automatic index on im_threads(normal_thread_id)
,I/Mms/ReservationManager( 4957): getReservedSendMessageCount(): retMessageCount=0
,D/TimaKeyStoreProvider( 5051): TimaSignature is unavailable
,D/TP/MmsSmsProvider( 1464): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 1464): need read changed broadcast:false
,D/ActivityThread( 5051): Added TimaKeyStore provider
,D/Mms/Conversation( 4957): [end]    init consume time = 27.01401
,D/Mms/MessagingNotification( 4957): [start]    init() consume time = 3.547917
,D/Mms/MmsApp( 4957): [end]    onCreate() consume time = 2.263958
,D/Mms/DownloadManager( 4957): Service state changed: Bundle[mParcelledData.dataSize=744]
,D/Mms/DownloadManager( 4957): roaming ------> false, mSimSlot = 0
,I/ActivityManager( 1016): Killing 4677:com.sec.pcw.device/1000 (adj 15): empty #31
,D/Mms/MessagingNotification( 4957): [end]    init consume time = 7.875625
,D/PackageManager( 1016): [MSG] SEND_PENDING_BROADCAST
,D/Mms/MethodReflector( 4957): getSubId is called
,D/Mms/TelephonyUtils( 4957): getLongSubId from simSlot 0, return Value = -1
,D/TP/MmsSmsProvider( 1464): query,matched:0, calling pid = 4957
,V/TP/MmsSmsProvider( 1464): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 1464): match 0:Elapsed time : 4.078 ms
,D/Mms/MethodReflector( 4957): getTelephonyProperty is called
D/Mms/DownloadManager( 4957): roaming -> false (slotId = 0)
D/Mms/DownloadManager( 4957): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager( 4957): auto download without roaming -> true
D/Mms/DownloadManager( 4957): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager( 4957): mAutoDownload ------> true
D/Mms/Synchronizer( 4957): [start]    doSync consume time = 20.580156
,D/Mms/SpamFilter( 4957): [start]    SpamFilter fill() begin consume time = 0.951927
,W/ResourcesManager( 5051): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 5051): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/Mms/ArtClassLoader( 4957): init [DONE] art
,I/PageBuddyNotiSvc( 4404): mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
,I/InputReader( 1016): Reconfiguring input devices.  changes=0x00000010
,D/TP/MmsSmsProvider( 1464): query,matched:400, calling pid = 4957
,D/TP/MmsSmsProvider( 1464): update, matched:300, calling pid = 4957
V/TP/MmsSmsProvider( 1464): syncDBData start
,I/ServiceManager(  319): Waiting for service AtCmdFwd...
,V/TP/MmsSmsProvider( 1464): syncDBData sms end
,V/TP/MmsSmsProvider( 1464): syncDBData mms end
,V/TP/MmsSmsProvider( 1464): syncDBData end
,D/RegisteredComponentCache( 1450): Collect Tech packages for Knox
,D/PersonaManager( 1450): isKioskContainerExistOnDevice
,D/Mms/Synchronizer( 4957): [end]    doSync consume time = 92.695625
,D/Mms/SpamFilter( 4957): [end]    SpamFilter fill() finished consume time = 0.644844
,D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,D/PersonaManager( 1450): isKioskContainerExistOnDevice
,E/Zygote  ( 5070): MountEmulatedStorage()
I/libpersona( 5070): KNOX_SDCARD checking this for 10072
E/Zygote  ( 5070): v2
I/libpersona( 5070): KNOX_SDCARD not a persona
I/SELinux ( 5070): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/SELinux ( 5070): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5070): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1016): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5070 uid=10072 gids={50072, 9997} abi=armeabi-v7a
I/splitIntent( 1016): Queue : backgroundsplit_0 intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
I/ActivityManager( 1016): Killing 4031:com.samsung.android.app.galaxyfinder:tagService/u0a32 (adj 15): empty #31
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,D/RegisteredServicesCache( 1450): empty dynamic service
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/SurfaceFlinger(  259): id=12 Removed Uoast (8/8)
,I/SurfaceFlinger(  259): id=12 Removed Uoast (-2/8)
,D/ActivityManager( 1016): startService callerProcessName:com.android.contacts, calleePkgName: com.android.contacts
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.contacts/com.samsung.contacts.sim.MakeSimDBService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,D/TimaKeyStoreProvider( 5070): TimaSignature is unavailable
,D/ActivityThread( 5070): Added TimaKeyStore provider
,D/SecContentProvider2( 1016): uri = 11 selection = getMyKnoxAdmin
,I/ActivityManager( 1016): Killing 4229:com.sec.android.soagent/u0a34 (adj 15): empty #31
,D/SecContentProvider2( 1016): mCursor = null
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BadgeProvider( 5070): onCreate
,D/BadgeProvider( 5070): DatabaseHelper
,W/IntentResolver( 1016): resolveIntent: multiple matches, only some with CATEGORY_DEFAULT
,D/BackupManagerService( 1016): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService( 1016): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService( 1016): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 5086): MountEmulatedStorage(),
E/Zygote  ( 5086): v2
I/libpersona( 5086): KNOX_SDCARD checking this for 1000
I/SELinux ( 5086): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
I/libpersona( 5086): KNOX_SDCARD not a persona
,I/SELinux ( 5086): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,E/SELinux ( 5086): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1016): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=5086 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
D/ActivityManager( 1016): bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.backup.TRANSPORT_HOST
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.backup.BackupTransportService; callingUser = 0; userId(target) = 0,
,D/TimaKeyStoreProvider( 5086): TimaSignature is unavailable
,D/ActivityThread( 5086): Added TimaKeyStore provider
,D/Mms/MessagingNotification( 4957): checkBadgeCount unreadCount=0 badgeCount=0
,D/TP/SmsProvider( 1464): query,matched:26, calling pid = 4957
,D/TP/SmsProvider( 1464): match 26:Elapsed time : 1.233 ms
,D/TP/MmsSmsProvider( 1464): query,matched:6, calling pid = 4957
,D/TP/MmsSmsProvider( 1464): match 6:Elapsed time : 2.627 ms
,V/BackupManagerService( 1016): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService( 1016): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@219d52a2
,E/MTPRx   ( 5086): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/SecContentProvider2( 1016): uri = 14 selection = getSealedState
,D/SecContentProvider2( 1016): mCursor = null
,D/SecContentProvider2( 1016): uri = 14 selection = getSealedUsbMassStorageState
,D/SecContentProvider2( 1016): mCursor = null
,D/ActivityManager( 1016): getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,V/MTPRx   ( 5086): sealedState: false
,V/MTPRx   ( 5086): sealedUsbMassStorageState: false
,W/ResourceType( 1016): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
E/MTPRx   ( 5086): check value of boot_completed is1
E/MTPRx   ( 5086): check booting is completed_sys.boot_completed
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1},
E/MTPRx   ( 5086): Sd-Card path/storage/extSdCard
E/MTPRx   ( 5086): Status for mount/Unmount :removed
E/MTPRx   ( 5086): SDcard is not available,
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/Zygote  ( 5102): MountEmulatedStorage()
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/Zygote  ( 5102): v2
I/libpersona( 5102): KNOX_SDCARD checking this for 10025
I/libpersona( 5102): KNOX_SDCARD not a persona
,I/SELinux ( 5102): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,I/ActivityManager( 1016): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5102 uid=10025 gids={50025, 9997} abi=armeabi-v7a
I/SELinux ( 5102): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
W/MTPRx   ( 5086): value of connected istrue
W/ResourcesManager( 1016): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/MTPRx   ( 5086): value of configured istrue
W/ResourcesManager( 1016): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/MTPRx   ( 5086): value of mtpEnabled istrue
W/ResourcesManager( 1016): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/MTPRx   ( 5086): value of ptpEnabled isfalse
E/MTPRx   ( 5086): Received USB_STATE with sdCardLaunch = 0
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/MTPRx   ( 5086): mFirstTime: false
E/SELinux ( 5102): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/TimaKeyStoreProvider( 5102): TimaSignature is unavailable
,D/ActivityThread( 5102): Added TimaKeyStore provider
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/        ( 5086): MTP: reading debug level property
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,E/MTPJNIInterface( 5086): Getting CryptionKey from JAVA
E/MTPRx   ( 5086): currentUserId is 0
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/ActivityManager( 1016): Killing 4710:com.samsung.android.service.travel/u0a159 (adj 15): empty #31
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,E/MTPRx   ( 5086): Start observing USB_STATE_MATCH 
,W/Resources( 1016): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
E/MTPRx   ( 5086): cannot open file : /sys/class/android_usb/android0/bcdUSB
E/MTPRx   ( 5086): is_Privatemode is NOT 1
,W/ResourcesManager( 5102): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/SettingsProvider( 1016): name = boot_time_connected
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,E/MTPRx   ( 5086): Sending NORMAL_BOOT to stack
E/MTPJNIInterface( 5086): noti = 17
,D/SettingsProvider( 1016): name = mtp_usb_conditions_met
D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = -2
,W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4677/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_1000/pid_4593/cgroup.procs: No such file or directory
,W/libprocessgroup( 1016): failed to open /acct/uid_10032/pid_4031/cgroup.procs: No such file or directory
W/libprocessgroup( 1016): failed to open /acct/uid_10034/pid_4229/cgroup.procs: No such file or directory
,D/SecContentProvider( 1016): uri = 18 selection = isUsbMediaPlayerAvailable
,E/MTPRx   ( 5086): sending MTP_ICON_ENABLED to stack
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1016): name = mtp_running_status
,I/ValidateNoPeople( 1016): mEvictionCount: 0
,D/Mms/Contact( 4957): sContactsObserver.onChange(),selfUpdate=false
,D/Mms/Contact( 4957): performUpdate:widgetCount=0
,D/SettingsProvider( 1016): name = mtp_usb_conditions_met
,E/MTPRx   ( 5086): else part ... so first time!!!
,E/MTPPlaObsrvr( 5086): inside setContext()
E/MTPPlaObsrvr( 5086):  inside createplafiles
,I/OMACP   ( 5102): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,I/SecKeyguardClockSingleView( 1184): Ignore. Because it is same clock text
,D/Mms/ContactsCache( 4957): [start]    invalidate() consume time = 395.414635
D/Mms/ContactsCache( 4957): [end]    invalidate() consume time = 0.134844
,E/MTPPlaObsrvr( 5086): playlist count is0
E/MTPPlaObsrvr( 5086):  inside try branch createplafiles
,D/Mms/Omacp( 4957): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,E/MTPPlaObsrvr( 5086):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 5086): Inside registerContentObserver
,E/MtpAdbObserver( 5086): inside setContext()
E/MtpAdbObserver( 5086): Inside registerContentObserver
W/Settings( 5086): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,V/MtpMediaDBManager( 5086): inside deleteAllDB
,D/ActivityManager( 1016): startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,D/LocationProviderProxy( 1016): applying state to connected service
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,D/SettingsProvider( 1016): name = mtp_running_status
,D/SettingsProvider( 1016): name = mtp_usb_conditions_met
,I/OMACP   ( 5102): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   ( 5102): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,E/MtpService( 5086): onCreate.
,W/libprocessgroup( 1016): failed to open /acct/uid_10159/pid_4710/cgroup.procs: No such file or directory
I/OMACP   ( 5102): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   ( 5102): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   ( 5102): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   ( 5102): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,E/MtpService( 5086): < MTP > Registering BroadCast receiver :::::
,D/ActivityManager( 1016): startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
,D/ActivityManager( 1016): retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,I/OMACP   ( 5102): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,E/MtpService( 5086): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,I/OMACP   ( 5102): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   ( 5102): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   ( 5102): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,E/MtpService( 5086): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,D/MtpService( 1239): updating state; isCurrentUser=true, mMtpLocked=false
I/OMACP   ( 5102): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   ( 5102): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,V/MtpMediaDBManager( 5086): inside Thread updateDB
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,I/OMACP   ( 5102): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
W/ActivityManager( 1016): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,E/MtpService( 5086): onStartCommand.
,W/MTPRx   ( 5086): calling native method
,E/MTPJNIInterface( 5086): < MTP > Registering BroadCast receiver :::::
E/MtpService( 5086): handleMessage. msg= { when=0 what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,E/MtpMediaDBManager( 5086): count : 27
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,E/MTPJNIInterface( 5086): < MTP > Registering BroadCast receiver :::::::
,E/MTPJNIInterface( 5086): noti = 10
E/MtpService( 5086): onStartCommand.
W/MTPRx   ( 5086): calling native method
E/MtpService( 5086): handleMessage. msg= { when=0 what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
E/MTPRx   ( 5086): Checking the driver time out
E/MTPJNIInterface( 5086): noti = 2
D/        ( 5086): deleting sockets before message queue initialization
,D/        ( 5086): event handler thread is created, so set the flag
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,E/MTPRx   ( 5086): called native method
E/MTPJNIInterface( 5086): setting Media scanner status0
E/MTPJNIInterface( 5086): After setting Media scanner status0
,W/MTPRx   ( 5086): notification from stack 1
,V/UserPresentBroadcastReceiver( 1842): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,E/        ( 5086): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
E/MTPJNIInterface( 5086): Getting media scanner status0
,E/MTPJNIInterface( 5086): DeviceName is A5-1
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
,W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,W/MtpMediaDBManager( 5086): sending db update complete noti to stack
E/MTPJNIInterface( 5086): noti = 29
,D/ActivityManager( 1016): retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,W/ActivityManager( 1016): userId = 0, bbcId = -10000
,W/ActivityManager( 1016): NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
W/ActivityManager( 1016): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MTPJNIInterface( 5086): Status for mount/Unmount :removed
,D/BluetoothNotiBroadcastReceiver( 1317): onReceive
,E/MTPJNIInterface( 5086): SDcard is not available
,V/BluetoothStatusReceiver( 1184): Received android.bluetooth.adapter.action.STATE_CHANGED
,D/BluetoothStatusReceiver( 1184): AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
,D/ActivityManager( 1016): startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
,E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1016): checkUser: useridlist=null, currentuser=0
,E/        ( 5086): lstat failed! errno [13] [Permission denied] [mtp_ifind_next 452],
,I/ActivityManager( 1016): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.predictor.PlacePredictor$BtConnectionReceiver: pid=5125 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 1007, 3001} abi=armeabi-v7a
E/Zygote  ( 5125): MountEmulatedStorage()
E/Zygote  ( 5125): v2
I/libpersona( 5125): KNOX_SDCARD checking this for 10003
I/libpersona( 5125): KNOX_SDCARD not a persona
I/SELinux ( 5125): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,E/        ( 5086): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,I/SELinux ( 5125): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,E/SELinux ( 5125): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/MTPJNIInterface( 5086): Status for mount/Unmount :removed
,E/MTPJNIInterface( 5086): SDcard is not available
I/art     (  308): Explicit concurrent mark sweep GC freed 8724(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 775us total 20.368ms
,E/SQLiteLog( 5086): (21) API call with NULL database connection pointer
E/SQLiteLog( 5086): (21) misuse at line 106108 of [9491ba7d73]
E/SQLiteLog( 5086): (21) API call with NULL database connection pointer
E/SQLiteLog( 5086): (21) misuse at line 100726 of [9491ba7d73],
E/SQLiteLog( 5086): (21) API call with NULL database connection pointer
E/SQLiteLog( 5086): (21) misuse at line 100726 of [9491ba7d73]
E/SQLiteLog( 5086): (21) API call with NULL database connection pointer
E/SQLiteLog( 5086): (21) misuse at line 106108 of [9491ba7d73]
W/MTPRx   ( 5086): notification from stack 2
D/        ( 5086): [mtp_init_device] Library open with 32 bits.
D/        ( 5086): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
,E/        ( 5086): [mtp_init_device 702]  After open the MTP fd = 32 and line = 702...
D/        ( 5086): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
,E/        ( 5086):  [sua_support_present:1287] returning false 
,D/        ( 5086): [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
,D/TimaKeyStoreProvider( 5125): TimaSignature is unavailable
,D/ActivityThread( 5125): Added TimaKeyStore provider

```
