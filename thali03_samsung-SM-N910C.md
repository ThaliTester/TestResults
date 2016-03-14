#### Test 62509094cfda267_thali03_samsung-SM-N910C Logs


```
--------- beginning of system
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
--------- beginning of main
E/Zygote  ( 8937): MountEmulatedStorage()
E/Zygote  ( 8937): v2
I/SELinux ( 8937): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/libpersona( 8937): KNOX_SDCARD checking this for 10122
I/libpersona( 8937): KNOX_SDCARD not a persona
I/SELinux ( 8937): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux ( 8937): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=8937 uid=10122 gids={50122, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/TimaKeyStoreProvider( 8937): TimaSignature is unavailable
D/ActivityThread( 8937): Added TimaKeyStore provider
D/ResourcesManager( 8937): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,W/ActivityManager( 3521): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/ActivityThread( 8937): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
W/ActivityManager( 3521): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/ActivityManager( 3521): Waited long enough for: ServiceRecord{33ba3d88 u0 com.sec.android.app.SmartClipService/com.samsung.android.service.hermes.HermesServiceStarter}
I/ActivityManager( 3521): Waited long enough for: ServiceRecord{ce1805d u0 com.sec.android.app.SmartClipService/com.samsung.android.service.hermes.HermesCollectorService}
I/Gmail   ( 8937): getAccountsCursor
V/GLSActivity( 4659): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 3521): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager( 3521): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager( 3521): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
V/GLSActivity( 4659): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 4659): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 8937): Observing account changes for notifications
W/GAV2    ( 8937): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ActivityManager( 3521): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager( 3521): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/Gmail   ( 8937): Error finding the version of the Email provider.....
E/Gmail   ( 8937): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 8937): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:137)
E/Gmail   ( 8937): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
E/Gmail   ( 8937): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 8937): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 8937): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 8937): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 8937): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 8937): We do not support migrating this version of the Email provider.
I/Gmail   ( 8937): getAccountsCursor
D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
V/GLSActivity( 4659): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager( 3521): Killing 8383:com.wsomacp/u0a28 (adj 13): bgCount ##31
V/AlarmManager( 3521): waitForAlarm result :4
E/SQLiteLog( 8937): (283) recovered 51 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
V/GLSActivity( 4659): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 4659): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 8937): notifyAccountChanged
I/Gmail   ( 8937): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 8937): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
V/AlarmManager( 3521): waitForAlarm result :4
I/Gmail   ( 8937): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 8937): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 8937): getAccountsCursor
V/GLSActivity( 4659): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 3521): Background partial concurrent mark sweep GC freed 360886(21MB) AllocSpace objects, 2(3MB) LOS objects, 19% free, 64MB/80MB, paused 3.039ms total 145.363ms
D/GCM     ( 4659): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
D/AndroidRuntime( 8957): 
D/AndroidRuntime( 8957): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
W/GCoreFlp( 4659): No location to return for getLastLocation()
W/FusedLocationProvider( 4659): location=null
V/AlarmManager( 3521): waitForAlarm result :4
D/AndroidRuntime( 8957): CheckJNI is OFF
D/AndroidRuntime( 8957): readGMSProperty: start
D/AndroidRuntime( 8957): readGMSProperty: already setted!!
D/AndroidRuntime( 8957): readGMSProperty: end
D/AndroidRuntime( 8957): addProductProperty: start
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 8989): MountEmulatedStorage()
I/libpersona( 8989): KNOX_SDCARD checking this for 10125
E/Zygote  ( 8989): v2
I/libpersona( 8989): KNOX_SDCARD not a persona
I/SELinux ( 8989): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux ( 8989): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux ( 8989): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=8989 uid=10125 gids={50125, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
D/TimaKeyStoreProvider( 8989): TimaSignature is unavailable
D/ActivityThread( 8989): Added TimaKeyStore provider
D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/ResourcesManager( 8989): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
W/ResourcesManager( 8989): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/Gmail   ( 8937): getAccountsCursor
V/GLSActivity( 4659): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/art     ( 6671): Explicit concurrent mark sweep GC freed 17189(1231KB) AllocSpace objects, 30(480KB) LOS objects, 35% free, 29MB/45MB, paused 1.083ms total 53.544ms
I/Babel   ( 8989): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 8989): MmsConfig.loadMmsSettings
I/Babel   ( 8989): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N910C, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N910C.xml
I/Babel   ( 8989): MmsConfig.loadFromDatabase
E/Babel   ( 8989): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 8989): MmsConfig.loadFromResources
W/AudioCapabilities( 8989): Unsupported mime audio/mpeg-L1
W/AudioCapabilities( 8989): Unsupported mime audio/mpeg-L2
E/Babel   ( 8989): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 8989): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N910C, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N910C.xml
W/AudioCapabilities( 8989): Unsupported mime audio/x-ms-wma
D/ResourcesManager( 8989): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/AudioCapabilities( 8989): Unsupported mime audio/x-ima
W/PackageManager( 3521): verifying app can be installed or not
D/ApplicationPolicy( 3521): isApplicationInstallationEnabled
D/ApplicationPolicy( 3521): isApplicationInstallationEnabled :  Checking PKG WL - false
D/ApplicationPolicy( 3521): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy( 3521): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy( 3521): isApplicationInstallationEnabled :  Checking SIG BL - true
D/ApplicationPolicy( 3521): isApplicationInstallationEnabled :  Checking PKG WL - false
D/ApplicationPolicy( 3521): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy( 3521): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy( 3521): isApplicationInstallationEnabled :  Checking SIG BL - true
W/VideoCapabilities( 8989): Unrecognized profile/level 32768/2 for video/mp4v-es
E/AffinityControl( 8957): AffinityControl: registerfunction enter
W/VideoCapabilities( 8989): Unsupported mime video/wvc1
W/VideoCapabilities( 8989): Unsupported mime video/x-ms-wmv
D/ApplicationPolicy( 3521): isApplicationInstallationEnabled :  enabled true
I/AASAInstall( 3521): product true
W/Settings( 8989): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/VideoCapabilities( 8989): Unrecognized profile/level 32768/2 for video/mp4v-es
D/AndroidRuntime( 8957): Calling main entry com.android.commands.am.Am
W/VideoCapabilities( 8989): Unsupported mime video/wvc1
W/VideoCapabilities( 8989): Unsupported mime video/x-ms-wmv
W/VideoCapabilities( 8989): Unsupported mime video/x-ms-wmv7
W/VideoCapabilities( 8989): Unsupported mime video/x-ms-wmv8
E/PersonaManagerService( 3521): inState():  stateMachine is null !!
I/PersonaManagerService( 3521): PersonaId don't exist
I/ActivityManager( 3521): do not start freezing screen for locked container getKeyguardshowstate = false
W/VideoCapabilities( 8989): Unsupported mime video/sorenson
I/ActivityManager( 3521): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/AndroidRuntime( 8957): Shutting down VM
W/VideoCapabilities( 8989): Unsupported mime video/mp43
W/AudioCapabilities( 8989): Unsupported mime audio/mpeg-L1
W/AudioCapabilities( 8989): Unsupported mime audio/mpeg-L2
W/VideoCapabilities( 8989): Unrecognized profile/level 32768/2 for video/mp4v-es
D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
I/VideoCapabilities( 8989): Unsupported profile 4 for video/mp4v-es
V/AlarmManager( 3521): waitForAlarm result :4
E/SQLiteLog( 8989): (284) automatic index on conversation_participants_view(conversation_id)
E/SQLiteLog( 8989): (284) automatic index on conversation_participants_view(conversation_id)
E/SQLiteLog( 8989): (284) automatic index on conversation_participants_view(conversation_id)
I/ActivityManager( 3521): Waited long enough for: ServiceRecord{12749acf u0 com.trustonic.tuiservice/.TuiService}
E/SQLiteLog( 8989): (284) automatic index on conversation_participants_view(conversation_id)
E/SQLiteLog( 8989): (284) automatic index on conversation_participants_view(conversation_id)
I/ActivityManager( 3521): Killing 8402:com.sec.esdk.elm/u0a106 (adj 13): bgCount ##31
V/AlarmManager( 3521): waitForAlarm result :4
V/AlarmManager( 3521): waitForAlarm result :4
V/AlarmManager( 3521): waitForAlarm result :4
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/AlarmManager( 3521): waitForAlarm result :4
,I/art     ( 3521): Background partial concurrent mark sweep GC freed 254510(15MB) AllocSpace objects, 6(9MB) LOS objects, 20% free, 60MB/76MB, paused 3.119ms total 131.267ms
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/Widget  ( 8573): onReceive com.sec.android.snote.widget.ACTION_NOTE_UPDATE
,D/Widget  ( 8573): onReceive android.appwidget.action.APPWIDGET_UPDATE
,D/Widget  ( 8573): widgetUpdate 5
,D/RCPManagerService( 3521): exchangeData() failure , invalid userId
,D/SHealthUpgrade(SHealthUpgradeUtil)( 6929): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 6929): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 6929): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,I/AASAUninstall( 3521):  com.test.thalitest not target!
,D/PackageManager( 3521): Renaming /data/app/vmdl1207840611.tmp to /data/app/com.test.thalitest-1
,D/PackageManager( 3521): installNewPackageLI: Package{2da195ae com.test.thalitest}
,I/SELinux ( 2861): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 2861): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/SELinux ( 2861): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux ( 2861): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 2861): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
E/SELinux ( 2861): [DEBUG] get_category: variable seinfo: app_data_file sensitivity: NULL, cateogry: NULL
,I/SELinux ( 2861): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 2861): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux ( 2861): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
E/SELinux ( 2861): [DEBUG] get_category: variable seinfo: app_data_file sensitivity: NULL, cateogry: NULL
,D/LocationWidgetUtils( 8440): getUpcommingInstances() start: 1457945489703, end: 1458514799999
,D/LocationWidgetUtils( 8440): getUpcommingInstances() DB begin time >= start:1457945489703, DB begin time <= end:1458514799999
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9041): MountEmulatedStorage()
I/libpersona( 9041): KNOX_SDCARD checking this for 10037
E/Zygote  ( 9041): v2
I/libpersona( 9041): KNOX_SDCARD not a persona
,I/SELinux ( 9041): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9041): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3521): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.app.profile.SnsStatusStreamBroadcastReceiver: pid=9041 uid=10037 gids={50037, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,E/SELinux ( 9041): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/SELinux ( 2861): selinux_android_setcategory: no category for userid: 0, path: /data/data/com.test.thalitest/lib 
,I/art     ( 3521): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@app@com.test.thalitest-1@base.apk@classes.dex' for file location '/data/app/com.test.thalitest-1/base.apk': Failed to open oat filename for reading: No such file or directory
I/art     ( 3521): DexFile_isDexOptNeeded failed to open oat file '/data/app/com.test.thalitest-1/arm/base.odex' for file location '/data/app/com.test.thalitest-1/base.apk': Failed to open oat filename for reading: No such file or directory
D/PackageManager( 3521): Running dexopt on: /data/app/com.test.thalitest-1/base.apk pkg=com.test.thalitest isa=arm vmSafeMode=false interpret_only=false
,D/TimaKeyStoreProvider( 9041): TimaSignature is unavailable
,D/ActivityThread( 9041): Added TimaKeyStore provider
,D/ResourcesManager( 9041): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager( 9041): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/ResourcesManager( 9041): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 9041): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9041): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/dex2oat ( 9056): ----------------------------------------------------
I/dex2oat ( 9056): <SS>: S T A R T I N G . . .
I/dex2oat ( 9056): <SS>: going to process manifest for 32-bit...
,D/ResourcesManager( 9041): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 9041): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9041): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9041): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9041): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,I/        ( 9056): SS_ART_lib [I]: Memory allocation: ctx
I/        ( 9056): SS_ART_lib [I]: Memory allocation: manifest_buf
,I/        ( 9056): SS_ART_lib [I]: Parsing Manifest for SS stuff
I/        ( 9056): SS_ART_lib [I]: Memory allocation: ctx->libs
I/        ( 9056): SS_ART_lib [I]: Memory allocation: ctx->package_name
I/        ( 9056): SS_ART_lib [I]: Parsing completed
I/        ( 9056): SS_ART_lib [I]: permission is absent: /data/app/com.test.thalitest-1/base.apk
I/        ( 9056): SS_ART_lib [I]: Closing zip file: /data/app/com.test.thalitest-1/base.apk
I/        ( 9056): SS_ART_lib [I]: access to SS denied
I/        ( 9056): SS_ART_lib [I]: ctx will be cleaned
I/        ( 9056): SS_ART_lib [I]: ctx component will be cleaned: ctx->libs
I/        ( 9056): SS_ART_lib [I]: ctx component is cleaned: ctx->libs
I/        ( 9056): SS_ART_lib [I]: ctx component will be cleaned: ctx->package_name
I/        ( 9056): SS_ART_lib [I]: ctx component is cleaned: ctx->package_name
I/        ( 9056): SS_ART_lib [I]: ctx is cleaned
I/dex2oat ( 9056): /system/bin/dex2oat --zip-fd=11 --zip-location=/data/app/com.test.thalitest-1/base.apk --oat-fd=12 --art-fd=13 --oat-location=/data/dalvik-cache/arm/data@app@com.test.thalitest-1@base.apk@classes.dex --instruction-set=arm --instruction-set-features=div --runtime-arg -Xms64m --runtime-arg -Xmx512m
,D/ResourcesManager( 9041): creating new AssetManager and set to /system/app/LegacyInCallUI/LegacyInCallUI.apk
,W/ResourcesManager( 9041): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 9041): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
,D/ResourcesManager( 9041): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
,W/ResourcesManager( 9041): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9041): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9041): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/ActivityManager( 3521): Killing 8459:com.sec.android.app.mt/1000 (adj 13): bgCount ##31
,E/CscReceiver( 3979): onReceive android.intent.action.SIM_STATE_CHANGED
D/CscReceiver( 3979): Recieve Sim State Changed : ABSENT
,I/splitIntent( 3521): Split this intent : android.intent.action.SIM_STATE_CHANGED !!   mSplitNum[0]=4, mSplitNum[1]=7, mSplitNum[2]=10 divideNum= 2 r.nextReceiver= 1 receivers.size=12
,I/splitIntent( 3521): finish to split intent : android.intent.action.SIM_STATE_CHANGED !! Enqueue -> schedule it!!
,W/BroadcastQueue( 3521): Permission Denial: broadcasting Intent { act=android.intent.action.SIM_STATE_CHANGED flg=0x20000010 (has extras) } from null (pid=3979, uid=1001) requires com.sec.android.permission.DSMLAWMO due to receiver com.fmm.dm/.XDMBroadcastReceiver
,I/WifiApBroadcastReceiver( 8499): onReceive: action android.intent.action.SIM_STATE_CHANGED
,E/JavaBinder( 3521): !!! FAILED BINDER TRANSACTION !!!
,W/BroadcastQueue( 3521): Exception when sending broadcast to ComponentInfo{com.sec.android.app.mt/com.sec.android.app.mt.StatusChecker}
W/BroadcastQueue( 3521): android.os.TransactionTooLargeException
W/BroadcastQueue( 3521): 	at android.os.BinderProxy.transactNative(Native Method)
W/BroadcastQueue( 3521): 	at android.os.BinderProxy.transact(Binder.java:496)
W/BroadcastQueue( 3521): 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:947)
W/BroadcastQueue( 3521): 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:292)
W/BroadcastQueue( 3521): 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1173)
W/BroadcastQueue( 3521): 	at com.android.server.am.BroadcastQueue$BroadcastHandler.handleMessage(BroadcastQueue.java:192)
W/BroadcastQueue( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/BroadcastQueue( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/BroadcastQueue( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/BroadcastQueue( 3521): 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9079): MountEmulatedStorage()
E/Zygote  ( 9079): v2
I/libpersona( 9079): KNOX_SDCARD checking this for 1000
I/libpersona( 9079): KNOX_SDCARD not a persona
,I/SELinux ( 9079): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9079): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux ( 9079): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=9079 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
D/SettingsProvider( 3521): name = internet_call_settings_visibility
D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
D/SettingsProvider( 3521): selectionArgs: 1001
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
D/BootupListener( 3979): intent.getAction() = android.intent.action.SIM_STATE_CHANGED
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 8729(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 474us total 21.276ms
,D/TimaKeyStoreProvider( 9079): TimaSignature is unavailable
,D/ActivityThread( 9079): Added TimaKeyStore provider
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 528us total 13.363ms
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 465us total 8.976ms
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/Zygote  ( 9094): MountEmulatedStorage()
E/Zygote  ( 9094): v2
I/libpersona( 9094): KNOX_SDCARD checking this for 1000
I/libpersona( 9094): KNOX_SDCARD not a persona
I/SELinux ( 9094): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3521): Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=9094 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 9094): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9094): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9109): MountEmulatedStorage()
E/Zygote  ( 9109): v2
I/libpersona( 9109): KNOX_SDCARD checking this for 10017
D/TimaKeyStoreProvider( 9094): TimaSignature is unavailable
I/libpersona( 9109): KNOX_SDCARD not a persona
,D/ActivityThread( 9094): Added TimaKeyStore provider
I/SELinux ( 9109): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9109): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=9109 uid=10017 gids={50017, 9997, 3003} abi=armeabi-v7a
E/SELinux ( 9109): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 9079): creating new AssetManager and set to /system/app/MobileTrackerEngineTwo/MobileTrackerEngineTwo.apk
,D/ResourcesManager( 9094): creating new AssetManager and set to /system/app/SilentLog/SilentLog.apk
,D/TimaKeyStoreProvider( 9109): TimaSignature is unavailable
,D/ActivityThread( 9109): Added TimaKeyStore provider
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 9109): creating new AssetManager and set to /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk
,E/Zygote  ( 9125): MountEmulatedStorage()
I/libpersona( 9125): KNOX_SDCARD checking this for 1000
E/Zygote  ( 9125): v2
I/libpersona( 9125): KNOX_SDCARD not a persona
,I/SELinux ( 9125): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9125): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.sec.tcpdumpservice for broadcast com.sec.tcpdumpservice/.TcpDumpReceiver: pid=9125 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 9125): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Killing 7744:com.sec.spp.push/u0a39 (adj 13): bgCount ##31
,D/StatusChecker( 9079): onReceive : android.intent.action.SIM_STATE_CHANGED
,D/TimaKeyStoreProvider( 9125): TimaSignature is unavailable
D/ActivityThread( 9125): Added TimaKeyStore provider
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9141): MountEmulatedStorage()
I/libpersona( 9141): KNOX_SDCARD checking this for 10156
E/Zygote  ( 9141): v2
I/libpersona( 9141): KNOX_SDCARD not a persona
,I/SELinux ( 9141): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9141): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9141): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.bookmarksDb.Controller.OperatorBookmarksSIMReceiver: pid=9141 uid=10156 gids={50156, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager( 3521): Killing 8536:com.samsung.android.app.mirrorlink/1000 (adj 13): bgCount ##31
,D/Mms/SmsReceiver( 8268): filterMsgServiceIntent : intent.getAction() : android.intent.action.SIM_STATE_CHANGED
,D/TimaKeyStoreProvider( 9141): TimaSignature is unavailable
,D/ActivityThread( 9141): Added TimaKeyStore provider
,D/ResourcesManager( 9125): creating new AssetManager and set to /system/app/TcpdumpService/TcpdumpService.apk
,D/Mms/SmsReceiverService( 8268): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.SIM_STATE_CHANGED
,D/Mms/TelephonyPermission( 8268): isDefault true
D/Mms/SmsReceiverService( 8268): [SMS]Receiver handleMessage : Action =android.intent.action.SIM_STATE_CHANGED
,D/Mms/SmsReceiverService( 8268): handleSIMStatus()
D/Mms/SmsReceiverService( 8268): handleSIMStatus(): SIM_STATUS = ABSENT
,D/ResourcesManager( 9141): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,I/ActivityManager( 3521): Killing 8556:com.sec.factory/1000 (adj 13): bgCount ##31
W/ResourcesManager( 9141): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 9141): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9141): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/ActivityManager( 3521): Killing 7938:com.samsung.klmsagent/u0a21 (adj 13): bgCount ##31
,I/VerificationLog( 9141): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,E/OperatorBookmarksSIMReceiver( 9141): onReceive runs..android.intent.action.SIM_STATE_CHANGED
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/Zygote  ( 9161): MountEmulatedStorage()
I/libpersona( 9161): KNOX_SDCARD checking this for 1000
E/Zygote  ( 9161): v2
I/libpersona( 9161): KNOX_SDCARD not a persona
,I/SELinux ( 9161): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9161): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9161): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=9161 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/dex2oat ( 9056): Explicit concurrent mark sweep GC freed 785(205KB) AllocSpace objects, 0(0B) LOS objects, 69% free, 443KB/1467KB, paused 276us total 5.617ms
I/ActivityManager( 3521): Killing 8591:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider( 9161): TimaSignature is unavailable
,D/ActivityThread( 9161): Added TimaKeyStore provider
,D/ResourcesManager( 9161): creating new AssetManager and set to /system/app/SecSetupWizard2013/SecSetupWizard2013.apk
,I/splitIntent( 3521): Queue : backgroundsplit_1 intent android.intent.action.SIM_STATE_CHANGED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 3521): Killing 8614:com.sec.android.app.SPenKeeper/u0a161 (adj 13): bgCount ##31
,I/dex2oat ( 9056): dex2oat took 536.425ms (threads: 8)
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,I/PackageManager( 3521): do mInstaller.dexopt : 0
D/PackageManager( 3521): Time to dexopt: 0.617 seconds
,W/System.err( 3521): java.io.FileNotFoundException: /data/app/com.test.thalitest-1: open failed: EISDIR (Is a directory)
,W/System.err( 3521): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 3521): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/System.err( 3521): 	at android.content.pm.PackageParser.getHashValueOfPackage(PackageParser.java:5071)
W/System.err( 3521): 	at com.android.server.pm.PackageManagerService.saveHash(PackageManagerService.java:18002)
W/System.err( 3521): 	at com.android.server.pm.PackageManagerService.access$5100(PackageManagerService.java:322)
W/System.err( 3521): 	at com.android.server.pm.PackageManagerService$20.run(PackageManagerService.java:17987)
W/System.err( 3521): Caused by: android.system.ErrnoException: open failed: EISDIR (Is a directory)
W/System.err( 3521): 	at libcore.io.IoBridge.open(IoBridge.java:446)
W/System.err( 3521): 	... 5 more
,E/Zygote  ( 9179): MountEmulatedStorage()
I/libpersona( 9179): KNOX_SDCARD checking this for 10039
E/Zygote  ( 9179): v2
I/libpersona( 9179): KNOX_SDCARD not a persona
,I/SELinux ( 9179): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9179): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.ForceUpdateAlarmReceiver: pid=9179 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 9179): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 9179): TimaSignature is unavailable
,D/ActivityThread( 9179): Added TimaKeyStore provider
,W/PackageSettings( 3521): Skipping PackageSetting{147a5b2 com.example.hello/10691} due to missing metadata
,D/PackageManager( 3521): New package installed
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/PackageSettings( 3521): Skipping PackageSetting{147a5b2 com.example.hello/10691} due to missing metadata
,I/HarmonyEASService( 3521): Updating for all 1
,D/PackageManager( 3521): doPostInstall for uid{10208}
,D/PackageManager( 3521): token 1 to BM for possible restore
V/BackupManagerService( 3521): restoreAtInstall pkg=com.test.thalitest token=1 restoreSet=0
V/BackupManagerService( 3521): Finishing install immediately
D/PackageManager( 3521): BM finishing package install for 1
,D/ResourcesManager( 9179): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,D/PackageManager( 3521): [MSG] SEND_PENDING_BROADCAST
,D/PackageManager( 3521): [MSG] POST_INSTALL: observer{476625236}
D/PackageManager( 3521):           Handling post-install for 1
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/ResourcesManager( 3521): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,W/Settings( 3521): Setting install_non_market_apps has moved from android.provider.Settings.Global to android.provider.Settings.Secure, returning read-only value.
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,I/InputReader( 3521): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager( 4003): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager( 3979): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,I/PageBuddyNotiSvc( 4872): mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
,D/ResourcesManager( 3979): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager( 3979): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Books/Books.apk
,I/LocationWidgetApplication( 8440): Intent.ACTION_PACKAGE_CHANGED has been called for com.google.android.gms
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 5235): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,I/InputReader( 3521): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager( 3521): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourceType( 5235): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5235): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,E/SamsungIME( 4471): mOCRHelper is null
,D/RegisteredServicesCache( 3966): empty dynamic service
,E/SPPClientService( 9179): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 9179): [PushClientApplication] Push log off : This is Ship build version
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
D/SPPClientService( 9179): PushLog.txt file is not deleted.
D/SPPClientService( 9179): PushLog.txt file is not deleted.
D/SPPClientService( 9179): ============PushLog. stop!
,E/SPPClientService( 9179): [ForceUpdateAlarmReceiver] Alarm Setting. After one day, it will alram.
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9200): MountEmulatedStorage()
I/libpersona( 9200): KNOX_SDCARD checking this for 10039
E/Zygote  ( 9200): v2
I/libpersona( 9200): KNOX_SDCARD not a persona
,I/SELinux ( 9200): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3521): Start proc com.sec.spp.push:RemoteDlcProcess for broadcast com.sec.spp.push/.dlc.sender.DlcRequestReceiver: pid=9200 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 9200): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9200): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Killing 8633:com.sec.android.app.videoplayer/u0a56 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider( 9200): TimaSignature is unavailable
,D/ActivityThread( 9200): Added TimaKeyStore provider
,D/ResourcesManager( 5235): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager( 9200): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,D/SecContentProvider2( 3521): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3521): mCursor = null
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/RegisteredServicesCache( 3966): empty dynamic service
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/WifiStateMachine( 3521): CMD_RSSI_POLL : calculateWifiScore in!
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/WifiStateMachine( 3521): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3521): CMD_RSSI_POLL : out!
,W/ResourceType( 5235): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5235): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,E/SPPClientService( 9200): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 9200): [PushClientApplication] Push log off : This is Ship build version
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,D/SPPClientService( 9200): PushLog.txt file is not deleted.
D/SPPClientService( 9200): PushLog.txt file is not deleted.
D/SPPClientService( 9200): ============PushLog. stop!
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/art     ( 3521): Explicit concurrent mark sweep GC freed 101298(6MB) AllocSpace objects, 11(176KB) LOS objects, 19% free, 64MB/80MB, paused 3.674ms total 192.025ms
D/PackageManager( 3521): result of install: 1{476625236}
,I/PackageManager( 3521): Observer no longer exists.
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,D/SecContentProvider2( 3521): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3521): mCursor = null
,E/Zygote  ( 9223): MountEmulatedStorage()
E/Zygote  ( 9223): v2
I/libpersona( 9223): KNOX_SDCARD checking this for 10039
I/libpersona( 9223): KNOX_SDCARD not a persona
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager( 4003): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,I/SELinux ( 9223): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3521): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PhoneStatusChangeReceiver: pid=9223 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 9223): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Drive/Drive.apk
E/SELinux ( 9223): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/ActivityManager( 3521): Killing 8727:com.android.vending/u0a31 (adj 13): bgCount ##31
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,D/TimaKeyStoreProvider( 9223): TimaSignature is unavailable
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ActivityThread( 9223): Added TimaKeyStore provider
,W/ResourcesManager( 8440): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 9223): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,E/SPPClientService( 9223): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 9223): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 9223): PushLog.txt file is not deleted.
D/SPPClientService( 9223): PushLog.txt file is not deleted.
D/SPPClientService( 9223): ============PushLog. stop!
,E/LNoti   ( 9223): [PhoneStatusChangeReceiver] This device doesn't register yet.
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 8440): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8440): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8440): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8440): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,W/ResourceType( 3521): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/Videos/Videos.apk
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3521): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 3521): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3521): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3521): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3521): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/BackupManagerService( 3521): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService( 3521): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/ResourcesManager( 3521): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,I/BackupManagerService( 3521): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/RCPManagerService( 3521): PackageReceiver onReceive()
D/RCPManagerService( 3521): App Installed with packageNAme = com.test.thalitest
,E/RCPManagerService( 3521):  PackageReceiver onReceive() Failed to load meta-data, NullPointer: Attempt to invoke virtual method 'java.lang.String android.os.Bundle.getString(java.lang.String)' on a null object reference
D/RCPManagerService( 3521):  PackageReceiver onReceive() bundle null
,D/ResourcesManager( 8440): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/KnoxMUMContainerPolicy( 3521): mPackageReceiver : action - android.intent.action.PACKAGE_ADDED
D/BackupManagerService( 3521): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,W/BackupManagerService( 3521): Removing schedule queue dupe of com.test.thalitest
,V/EnterpriseBillingPolicy( 3521): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_ADDED
V/EnterpriseBillingPolicy( 3521): uID is 10208
V/EnterpriseBillingPolicy( 3521): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3521): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 3521): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3521): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3521): packageModificationReceiver - onreceive - might be a vpn vendor package 
,V/EnterpriseBillingPolicyStorage( 3521): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 3521): getBillingProfileForVpnEngine - end - null
,D/PersonaPolicyManagerService( 3521): PersonaPolicyReceiver Receiver : android.intent.action.PACKAGE_ADDED
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,V/BackupManagerService( 3521): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
V/BackupManagerService( 3521): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@2a69f5ee
,D/KnoxMUMContainerPolicy( 3521): packageInstalledForExternalStorage com.test.thalitest
,I/GCoreNlp( 4659): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/SettingsProvider( 3521): name = assisted_gps_enabled
,D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
D/SettingsProvider( 3521): selectionArgs: 10014
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,I/System.out( 3521): Thread-151(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 3521): Thread-151(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 3521): Thread-151(ApacheHTTPLog):isShipBuild true
I/System.out( 3521): Thread-151(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2849): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2849): getNetworkForDns: using netid 502 for uid 1000
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/EnterpriseDeviceManagerService( 3521): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3521): Admin package name: com.google.android.gms
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourceType( 3521): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/Drive/Drive.apk
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/CrashAnrDetector( 3521): onPackageAdded : com.test.thalitest
,D/LocationProviderProxy( 3521): applying state to connected service
,D/LocationProviderProxy( 3521): applying state to connected service
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/Maps/Maps.apk
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager( 8440): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 8440): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8440): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8440): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8440): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/Videos/Videos.apk
,I/System.out( 3521): AsyncTask #1 calls detatch()
,W/System.err( 3521): java.io.IOException: Not Found
W/System.err( 3521): 	at a.d.b(Unknown Source)
W/System.err( 3521): 	at a.d.doInBackground(Unknown Source)
W/System.err( 3521): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 3521): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 3521): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 3521): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 3521): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 3521): 	at java.lang.Thread.run(Thread.java:818)
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/Maps/Maps.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,D/ResourcesManager( 8519): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,D/ResourcesManager( 8519): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ResourcesManager( 8440): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,D/ResourcesManager( 8440): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,D/LocationManagerService( 3521): getProviders()=[]
D/LocationManagerService( 3521): getProviders()=[passive]
D/LocationManagerService( 3521): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
,D/LWLocationManager( 8440): mPrivacy is null
,W/ContextImpl( 8440): Implicit intents with startService are not safe: Intent { act=com.samsung.android.providers.context.privacy.IPrivacyManager } android.content.ContextWrapper.bindService:559 com.samsung.android.providers.context.privacy.PrivacyManager.bindService:394 com.sec.android.widgetapp.locationwidget.data.LWLocationManager.bindPrivacyService:150 
,D/ContextFramework:PrivacyManager( 8440): Service for PrivacyManager is connected
,D/BluetoothManager( 6929): getConnectedDevices
,D/BluetoothManager( 6929): getConnectedDevices
D/BluetoothManager( 6929): getConnectedDevices
,D/LWLocationManager( 8440): Privacy service : STATUS_PLACE
D/LWLocationManager( 8440): updateLocationStatus()
,I/LocationWidgetFuctionData( 8440): readDB
,D/BluetoothManager( 6929): getConnectedDevices
,D/BluetoothManager( 6929): getConnectedDevices
,I/LocationWidgetFuctionData( 8440): selectedAppSize: 3
I/LocationWidgetFuctionData( 8440): configPlaceList aroundMeItems
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/BluetoothManager( 6929): getConnectedDevices
,E/Zygote  ( 9252): MountEmulatedStorage()
,E/Zygote  ( 9252): v2
I/libpersona( 9252): KNOX_SDCARD checking this for 10003
I/libpersona( 9252): KNOX_SDCARD not a persona
,I/SELinux ( 9252): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9252): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3521): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=9252 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 3006, 1007, 3001} abi=armeabi-v7a
,E/SELinux ( 9252): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 9252): TimaSignature is unavailable
,D/ActivityThread( 9252): Added TimaKeyStore provider
,I/ActivityManager( 3521): Killing 8695:com.samsung.dcm:DCMService/u0a4 (adj 13): bgCount ##31
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 9252): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,E/Zygote  ( 9268): MountEmulatedStorage()
E/Zygote  ( 9268): v2
I/libpersona( 9268): KNOX_SDCARD checking this for 1000
I/libpersona( 9268): KNOX_SDCARD not a persona
,I/SELinux ( 9268): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9268): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9268): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/com.diagmondm.XDMBroadcastReceiver: pid=9268 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,V/AlarmManager( 3521): waitForAlarm result :4
,D/UserAnalysis.PlaceProvider( 9252): PlaceProvider onCreate()
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/CalendarAlarmManager( 7337): sys current time:1457945491869
,D/CalendarAlarmManager( 7337): reminder amount:0
,I/ActivityManager( 3521): Killing 8519:com.samsung.android.app.galaxyfinder:tagService/u0a35 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider( 9268): TimaSignature is unavailable
,D/ActivityThread( 9268): Added TimaKeyStore provider
,D/UserAnalysis.SecureDbManager( 9252): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 9252): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider( 9252): Create SecureDbHelper
,D/IntelligenceServiceApplication( 9252): onCreate()
,D/ResourcesManager( 9268): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,I/DIAGMON_AGENT( 9268): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/LocationWidgetFuctionData( 8440): selectedAppSize: 3
,I/LocationWidgetFuctionData( 8440): selectedAppSize: 3
,I/LocationWidgetFuctionData( 8440): selectedAppSize: 3
,I/LocationWidgetFuctionData( 8440): selectedAppSize: 3
,E/LWLocationManager( 8440): findLocationType() : cursor_location.moveToFirst() return false!!
,D/LWLocationManager( 8440): Intent broadcast sent with action: com.sec.android.widgetapp.locationwidget.LOCATION_SOURCES_UPDATED
D/LWLocationManager( 8440): setShouldUpdateLocationId
D/LWLocationManager( 8440): setShouldUpdateLocationId return false
D/LWLocationManager( 8440): setShouldUpdateLocationId
D/LWLocationManager( 8440): setShouldUpdateLocationId return false
D/LWLocationManager( 8440): setShouldUpdateLocationId
D/LWLocationManager( 8440): setShouldUpdateLocationId return false
D/LWLocationManager( 8440): updateDeviceLocation() : lastDeviceLocationId = -100 mDeviceLocationId: -100 cocktailId: -1
I/DIAGMON_AGENT( 9268): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 9268): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 9268): [com.diagmondm.XDMBroadcastReceiver(33/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/ActivityManager( 3521): Killing 8746:com.sec.android.app.music:service/u0a44 (adj 13): bgCount ##31
,I/DBG_DM  ( 6204): [com.wssyncmldm.XDMBroadcastReceiver(153/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9283): MountEmulatedStorage()
E/Zygote  ( 9283): v2
I/libpersona( 9283): KNOX_SDCARD checking this for 10173
I/libpersona( 9283): KNOX_SDCARD not a persona
,I/SELinux ( 9283): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9283): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3521): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=9283 uid=10173 gids={50173, 9997, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 9283): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 9283): TimaSignature is unavailable
,D/ActivityThread( 9283): Added TimaKeyStore provider
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 8765(373KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 839us total 21.164ms
,D/ResourcesManager( 9283): creating new AssetManager and set to /system/app/SamsungWidget_ActiveApplication/SamsungWidget_ActiveApplication.apk
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 790us total 18.956ms
,V/TaskCloserActivity( 9283): TaskCloserActivity enter()
,V/TaskCloserActivity( 9283): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,D/Widget  ( 8573): onReceive com.sec.android.snote.widget.ACTION_NOTE_UPDATE
,D/Widget  ( 8573): onReceive android.appwidget.action.APPWIDGET_UPDATE
,D/Widget  ( 8573): widgetUpdate 5
I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 306us total 11.178ms
,D/RCPManagerService( 3521): exchangeData() failure , invalid userId
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9298): MountEmulatedStorage()
I/libpersona( 9298): KNOX_SDCARD checking this for 1000
E/Zygote  ( 9298): v2
I/libpersona( 9298): KNOX_SDCARD not a persona
,I/SELinux ( 9298): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9298): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9298): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=9298 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3521): Killing 8788:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider( 9298): TimaSignature is unavailable
,D/ActivityThread( 9298): Added TimaKeyStore provider
,D/ResourcesManager( 9298): creating new AssetManager and set to /system/priv-app/MtpApplication/MtpApplication.apk
,E/MTPRx   ( 9298): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/SecContentProvider2( 3521): uri = 14 selection = getSealedState
D/SecContentProvider2( 3521): mCursor = null
,D/SecContentProvider2( 3521): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 3521): mCursor = null
,V/MTPRx   ( 9298): sealedState: false
V/MTPRx   ( 9298): sealedUsbMassStorageState: false
E/MTPRx   ( 9298): check value of boot_completed is1
E/MTPRx   ( 9298): check booting is completed_sys.boot_completed
,E/MTPRx   ( 9298): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 9298): Status for mount/Unmount :removed
E/MTPRx   ( 9298): SDcard is not available
,W/MTPRx   ( 9298): value of connected istrue
W/MTPRx   ( 9298): value of configured istrue
W/MTPRx   ( 9298): value of mtpEnabled isfalse
W/MTPRx   ( 9298): value of ptpEnabled istrue
E/MTPRx   ( 9298): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 9298): mFirstTime: false
,D/        ( 9298): MTP: reading debug level property
,E/MTPJNIInterface( 9298): Getting CryptionKey from JAVA
E/MTPRx   ( 9298): currentUserId is 0
,E/MTPRx   ( 9298): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 9298): usbMode is 0200
E/MTPRx   ( 9298): is_Privatemode is NOT 1
,D/SettingsProvider( 3521): name = mtp_usb_conditions_met
,D/SecContentProvider( 3521): uri = 18 selection = isUsbMediaPlayerAvailable
,E/MTPRx   ( 9298): sending PTP_ICON_ENABLED to stack 
,D/SettingsProvider( 3521): name = mtp_running_status
,D/SettingsProvider( 3521): name = mtp_usb_conditions_met
,E/MTPRx   ( 9298): else part ... so first time!!!
E/MTPPlaObsrvr( 9298): inside setContext()
E/MTPPlaObsrvr( 9298):  inside createplafiles
,E/MTPPlaObsrvr( 9298): playlist count is0
E/MTPPlaObsrvr( 9298):  inside try branch createplafiles
,E/MTPPlaObsrvr( 9298):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 9298): Inside registerContentObserver
,E/MtpAdbObserver( 9298): inside setContext()
E/MtpAdbObserver( 9298): Inside registerContentObserver
W/Settings( 9298): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,D/SettingsProvider( 3521): name = mtp_running_status
,D/SettingsProvider( 3521): name = mtp_usb_conditions_met
,E/MtpService( 9298): onCreate.
,E/MtpService( 9298): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 9298): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/MtpService( 9298): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,E/MtpService( 9298): onStartCommand.
W/MTPRx   ( 9298): calling native method
E/MTPJNIInterface( 9298): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 9298): handleMessage. msg= { when=0 what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
E/MTPJNIInterface( 9298): < MTP > Registering BroadCast receiver :::::::
,D/MtpService( 5431): updating state; isCurrentUser=true, mMtpLocked=false
,E/MTPJNIInterface( 9298): noti = 11
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9315): MountEmulatedStorage()
I/libpersona( 9315): KNOX_SDCARD checking this for 1000
E/Zygote  ( 9315): v2
I/libpersona( 9315): KNOX_SDCARD not a persona
,I/SELinux ( 9315): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9315): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=9315 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux ( 9315): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/MtpService( 9298): onStartCommand.
,E/MtpService( 9298): handleMessage. msg= { when=-1ms what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,W/MTPRx   ( 9298): calling native method
E/MTPRx   ( 9298): Checking the driver time out
E/MTPJNIInterface( 9298): noti = 2
D/        ( 9298): deleting sockets before message queue initialization
,D/        ( 9298): event handler thread is created, so set the flag
,E/MTPRx   ( 9298): called native method
E/MTPJNIInterface( 9298): setting Media scanner status0
E/MTPJNIInterface( 9298): After setting Media scanner status0
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/MTPRx   ( 9298): notification from stack 1
,E/        ( 9298): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
E/MTPJNIInterface( 9298): Getting media scanner status0
,E/MTPJNIInterface( 9298): DeviceName is Note4-1
,D/TimaKeyStoreProvider( 9315): TimaSignature is unavailable
,D/ActivityThread( 9315): Added TimaKeyStore provider
,D/ResourcesManager( 9315): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,D/TMNetworkReceiver( 9315): TMNetworkReceiver.TMNetworkReceiver() Enter 1 main
D/TMNetworkReceiver( 9315): TMNetworkReceiver.onReceive() Enter
D/TMNetworkReceiver( 9315): TMNetworkReceiver.onReceive() Action android.hardware.usb.action.USB_STATE
D/TMNetworkReceiver( 9315): TMNetworkReceiver.onReceive(): intent.getExtras() is not null
,D/TMNetworkReceiver( 9315): TMNetworkReceiver.onReceive() on USB - connected:true, configured :true, mtp = false, mIsFileUpdated= false
D/TMNetworkReceiver( 9315): TMNetworkReceiver.onReceive() USB CONNECTED
D/TMNetworkReceiver( 9315): TMNetworkReceiver.onReceive() Exit 
,D/TMNetworkReceiver( 9315): TMNetworkReceiver.onReceive() UsbCheck Thread Enter
,D/TMSLogRemovalReceiver( 9315): TMLogRemovalReceiver.onReceive() Enter isCalled =false
D/TMSLogRemovalReceiver( 9315): TMLogRemovalReceiver.onReceive() action android.hardware.usb.action.USB_STATE
D/TMSLogRemovalReceiver( 9315): TMLogRemovalReceiver.onReceive() Exit
,I/ActivityManager( 3521): Killing 8656:com.google.android.music:main/u0a135 (adj 13): bgCount ##31
,D/MediaScannerReceiver( 5431): action: android.intent.action.MTP_FILE_SCAN
,I/SettingSearch/SearchIntentReceiver( 8499): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
I/SettingSearch/SearchIntentReceiver( 8499): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,I/SettingSearch/SearchIntentReceiver( 8499): InitTitleDBThread start --> mDoingInitTitleDB : true
,I/SettingSearch/SearchIntentReceiver( 8499): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
I/SettingSearch/SearchIntentReceiver( 8499): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,I/SettingSearch/SettingsSearchManager( 8499): Infomation -> numtitleinfo : 0 numSearchinfo : 367
,V/AlarmManager( 3521): waitForAlarm result :4
,D/MediaScannerService( 5431): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private, /storage/UsbDriveA, /storage/UsbDriveB, /storage/UsbDriveC, /storage/UsbDriveD, /storage/UsbDriveE, /storage/UsbDriveF]
,I/Avrcp   ( 5587): Received the onChange database event
I/Avrcp   ( 5587): onChange on thread: 1 Uri: content://media/ selfchange: false
I/Avrcp   ( 5587): send MSG_CHECK_NOW_PLAYING_CONTENT_CHANGED after 500ms
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/MediaProvider( 5431): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 5431): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
,D/MediaProvider( 5431): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,V/AlarmManager( 3521): waitForAlarm result :4
,D/MediaProvider( 5431): savePlaylistTableInBulkDeleter finished
D/MediaProvider( 5431): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 5431): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,D/MediaProvider( 5431): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,D/MediaProvider( 5431): savePlaylistTableInBulkDeleter finished
,D/MediaScanner( 5431): Prescan. DB items number : 62 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,I/SettingSearch/SettingsSearchManager( 8499):  Infomation -> getItem size : 367
,I/iu.UploadsManager( 6671): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
,V/MediaScanner( 5431): processDirectory :  /storage/emulated/0
,D/MediaScanner( 5431): Skipping:
D/MediaScanner( 5431): 7klwibgf7fvntblfd7(75ebcf7
,D/MediaScanner( 5431): Skipping:
D/MediaScanner( 5431): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,D/ResourcesManager( 8499): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager( 8499): creating new AssetManager and set to /system/priv-app/TeleService/TeleService.apk
,V/AlarmManager( 3521): waitForAlarm result :4
D/BluetoothManager( 6929): getConnectedDevices
,W/ResourcesManager( 8499): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 8499): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 8499): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8499): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,V/MediaScanner( 5431): processDirectory :  /storage/extSdCard
W/MediaScanner( 5431): Error opening directory, reason : Permission denied.
W/MediaScanner( 5431): 7klwibgf7fxlKdCbid7
,D/ResourcesManager( 8499): creating new AssetManager and set to /system/app/AssistantMenu2/AssistantMenu2.apk
,V/MediaScanner( 5431):  prescan time: 40ms (DB items: 62)
V/MediaScanner( 5431):     scan time: 21ms (Caching mode: true), (makeEntry time: 15ms ~71%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 5431): postscan time: 2ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 5431):    total time: 63ms
V/MediaScanner( 5431): checked files: 19  directories : 36  (I: 0, U: 0)
,D/BluetoothManager( 6929): getConnectedDevices
,D/MediaScannerService( 5431): !@done scanning volume external
,E/MTPJNIInterface( 9298): In MTPJNIINterface onReceive:android.intent.action.MEDIA_SCANNER_FINISHED
,D/BluetoothManager( 6929): getConnectedDevices
,D/BluetoothManager( 6929): getConnectedDevices
,D/BluetoothManager( 6929): getConnectedDevices
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/BluetoothManager( 6929): getConnectedDevices
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/LWLocationManager( 8440): getDeviceLocationId :  id = -100
D/LocationWidgetApplication( 8440): getLastUiLocationId() : mLastUiLocationId = -100
,I/art     ( 5431): Explicit concurrent mark sweep GC freed 9403(613KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 27MB/43MB, paused 1.100ms total 33.693ms
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,I/iu.UploadsManager( 6671): End new media; added: 0, uploading: 0, time: 158 ms
,E/Zygote  ( 9348): MountEmulatedStorage()
E/Zygote  ( 9348): v2
I/libpersona( 9348): KNOX_SDCARD checking this for 10035
I/libpersona( 9348): KNOX_SDCARD not a persona
,I/SELinux ( 9348): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9348): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3521): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=9348 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,E/SELinux ( 9348): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 9348): TimaSignature is unavailable
,D/ActivityThread( 9348): Added TimaKeyStore provider
,D/ResourcesManager( 9348): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,I/FeatureConfig( 9348): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ResourcesManager( 9348): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 9348): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 9348): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 9348): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,W/ResourcesManager( 9348): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 9348): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 9348): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 9348): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 9348): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 9348): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager( 9348): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/ResourcesManager( 9348): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 9348): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/ResourcesManager( 9348): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 9348): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 9348): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 9348): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 9348): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,I/SettingSearch/SearchIntentReceiver( 8499): InitTitleDBThread end --> mDoingInitTitleDB : false
I/SettingSearch/SearchIntentReceiver( 8499): LOCALE_CHANGED call search setting db finish!!
,I/ActivityManager( 3521): Killing 8840:com.sec.smartcard.manager/u0a187 (adj 13): bgCount ##31
,D/ResourcesManager( 9348): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 9348): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ResourcesManager( 9348): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,W/ResourcesManager( 9348): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/Zygote  ( 9365): MountEmulatedStorage()
E/Zygote  ( 9365): v2
I/libpersona( 9365): KNOX_SDCARD checking this for 10050
I/libpersona( 9365): KNOX_SDCARD not a persona
,I/SELinux ( 9365): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9365): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=9365 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
E/SELinux ( 9365): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 9348): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 9348): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/SettingSearch/SearchIntentReceiver( 8499): InitTitleDBThread start --> mDoingInitTitleDB : true
,D/TimaKeyStoreProvider( 9365): TimaSignature is unavailable
,D/ActivityThread( 9365): Added TimaKeyStore provider
,D/ResourcesManager( 9348): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 9348): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/ResourcesManager( 9348): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager( 9365): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/ResourcesManager( 9365): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 9365): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 9365): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 9365): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9365): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
D/ResourcesManager( 9348): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 9365): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 9365): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 9365): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 9348): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 9348): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,W/ResourcesManager( 9348): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 9348): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/SettingSearch/SearchIntentReceiver( 8499): InitTitleDBThread end --> mDoingInitTitleDB : false
I/SettingSearch/SearchIntentReceiver( 8499): LOCALE_CHANGED call search setting db finish!!
,W/GalaxyFinderApplication( 9348): system/finder_cp/cpdata.xml file not found
,V/Avrcp   ( 5587): handleMessage, msg=207
D/BluetoothMediaBrowser( 5587):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,I/art     ( 3521): Explicit concurrent mark sweep GC freed 246655(16MB) AllocSpace objects, 23(9MB) LOS objects, 24% free, 48MB/64MB, paused 2.137ms total 174.454ms
,D/BluetoothMediaBrowser( 5587): no now playing list
D/BluetoothMediaBrowser( 5587):  getNowPlayingId now playing id : -1
D/Avrcp   ( 5587):  checkNowPlayingList start
,D/PackageManager( 3521): findPreferredActivity: No PreferredActivities set
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/NearbySource( 9365): Nearby Source Create!
D/NearbyContext( 9365): Nearby Context Create!
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
,W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9365): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource( 9365): Samsung link source created
,D/WifiDisplayAdapter( 3521): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ContactProvider( 9365): getAllContactInfoList Start
E/MTPJNIInterface( 9298): Status for mount/Unmount :removed
E/MTPJNIInterface( 9298): SDcard is not available
,D/WifiDisplayAdapter( 3521): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/        ( 9298): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,E/MTPJNIInterface( 9298): Status for mount/Unmount :removed
E/MTPJNIInterface( 9298): SDcard is not available
,E/SQLiteLog( 9298): (21) API call with NULL database connection pointer
E/SQLiteLog( 9298): (21) misuse at line 105958 of [9491ba7d73]
E/SQLiteLog( 9298): (21) API call with NULL database connection pointer
E/SQLiteLog( 9298): (21) misuse at line 100622 of [9491ba7d73]
E/SQLiteLog( 9298): (21) API call with NULL database connection pointer
E/SQLiteLog( 9298): (21) misuse at line 100622 of [9491ba7d73]
E/SQLiteLog( 9298): (21) API call with NULL database connection pointer
E/SQLiteLog( 9298): (21) misuse at line 105958 of [9491ba7d73]
,W/MTPRx   ( 9298): notification from stack 2
,D/        ( 9298): [mtp_init_device] Library open with 32 bits.
D/        ( 9298): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
,E/        ( 9298): [mtp_init_device 694]  After open the MTP fd = 32 and line = 694...
D/        ( 9298): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
E/        ( 9298):  [sua_support_present:1277] returning false 
D/        ( 9298): *****Starting mtp_io()
,I/UpdateIcingCorporaServi( 4054): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,W/MTPRx   ( 9298): notification from stack 3
D/        ( 9298): [mtp_start_io] source_thread Creation 
D/        ( 9298): [mtp_start_io] sink_thread Creation 
D/        ( 9298): [mtp_start_io:368] sink thread created so set th_sink
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9395): MountEmulatedStorage()
E/Zygote  ( 9395): v2
I/libpersona( 9395): KNOX_SDCARD checking this for 10079
I/libpersona( 9395): KNOX_SDCARD not a persona
,I/SELinux ( 9395): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9395): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=9395 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 9395): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Killing 8860:com.sec.android.app.popupuireceiver/1000 (adj 13): bgCount ##31
,D/ContactProvider( 9365): getAllContactInfoList End
I/syncContacts( 9365): thread: 1183, sync time = 104
,D/TimaKeyStoreProvider( 9395): TimaSignature is unavailable
,D/ActivityThread( 9395): Added TimaKeyStore provider
,D/ResourcesManager( 6671): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ResourcesManager( 9395): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,D/FileShare-Server( 9395): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9412): MountEmulatedStorage()
I/libpersona( 9412): KNOX_SDCARD checking this for 1000
E/Zygote  ( 9412): v2
I/libpersona( 9412): KNOX_SDCARD not a persona
,I/SELinux ( 9412): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3521): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=9412 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 9412): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Killing 8876:com.samsung.android.app.powersharing/u0a149 (adj 13): bgCount ##31
,E/SELinux ( 9412): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 9412): TimaSignature is unavailable
,D/ActivityThread( 9412): Added TimaKeyStore provider
,D/ResourcesManager( 9412): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 9412): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9427): MountEmulatedStorage()
E/Zygote  ( 9427): v2
I/libpersona( 9427): KNOX_SDCARD checking this for 1000
I/libpersona( 9427): KNOX_SDCARD not a persona
,I/SELinux ( 9427): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/SELinux ( 9427): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=9427 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux ( 9427): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Killing 8419:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider( 9427): TimaSignature is unavailable
,D/ActivityThread( 9427): Added TimaKeyStore provider
,D/ResourcesManager( 9427): creating new AssetManager and set to /system/app/KnoxSetupWizardClient/KnoxSetupWizardClient.apk
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ShortcutReceiver( 9427):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/SSRM:n  ( 3521): SIOP:: AP = 360, PST = 340, CUR = -816
,E/Zygote  ( 9442): MountEmulatedStorage()
D/PackageManager( 3521): [MSG] MCS_UNBIND
,E/Zygote  ( 9442): v2
I/libpersona( 9442): KNOX_SDCARD checking this for 10147
I/libpersona( 9442): KNOX_SDCARD not a persona
,I/SELinux ( 9442): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3521): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=9442 uid=10147 gids={50147, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 9442): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9442): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Killing 8283:com.android.calendar/u0a164 (adj 13): bgCount ##31
,I/ActivityManager( 3521): Killing 9041:com.sec.android.app.sns3/u0a37 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider( 9442): TimaSignature is unavailable
,D/ActivityThread( 9442): Added TimaKeyStore provider
,V/AlarmManager( 3521): waitForAlarm result :4
,D/ResourcesManager( 9442): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/ResourcesManager( 9442): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 4054): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,I/UpdateIcingCorporaServi( 4054): UpdateCorporaTask done [took 431 ms] updated apps [took 431 ms] 
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/WifiStateMachine( 3521): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3521): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3521): CMD_RSSI_POLL : out!
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/PkgBroadcastIntentOp( 6671): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
I/PkgBroadcastIntentOp( 6671): Null package name or gms related package.  Ignoreing.
,E/Zygote  ( 9474): MountEmulatedStorage()
I/libpersona( 9474): KNOX_SDCARD checking this for 10031
E/Zygote  ( 9474): v2
I/libpersona( 9474): KNOX_SDCARD not a persona
,I/SELinux ( 9474): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9474): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=9474 uid=10031 gids={50031, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 9474): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,V/AlarmManager( 3521): waitForAlarm result :4
,I/Icing   ( 6671): updateResources: need to parse f{com.google.android.gms}
,D/WearableController( 6671): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/GAV2    ( 8937): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager( 3521): waitForAlarm result :4
,D/TimaKeyStoreProvider( 9474): TimaSignature is unavailable
,D/ActivityThread( 9474): Added TimaKeyStore provider
,D/ResourcesManager( 9474): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,V/GLSActivity( 4659): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4659): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/Finsky  ( 9474): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 9474): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings( 9474): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 9474): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 9474): Skipping gmscore version check
,D/Finsky  ( 9474): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 9474): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 9474): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/Finsky  ( 9474): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,E/Zygote  ( 9524): MountEmulatedStorage()
I/libpersona( 9524): KNOX_SDCARD checking this for 10063
E/Zygote  ( 9524): v2
I/libpersona( 9524): KNOX_SDCARD not a persona
,I/SELinux ( 9524): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9524): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=9524 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 9524): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Killing 9079:com.sec.android.app.mt/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider( 9524): TimaSignature is unavailable
,D/ActivityThread( 9524): Added TimaKeyStore provider
,D/ResourcesManager( 9524): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,D/VRSetupWizardStub/PackageIntentReceiver( 9524): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver( 9524): ACTION_PACKAGE_ADDED
,I/ActivityManager( 3521): Killing 9094:com.sec.modem.settings/1000 (adj 13): bgCount ##31
,I/HomeSyncInstallReceiver( 3966): This pkg do not need BT addr. Do nothing
,I/splitIntent( 3521): Split this intent : android.intent.action.PACKAGE_ADDED !!   mSplitNum[0]=15, mSplitNum[1]=27, mSplitNum[2]=39 divideNum= 12 r.nextReceiver= 3 receivers.size=51
I/splitIntent( 3521): finish to split intent : android.intent.action.PACKAGE_ADDED !! Enqueue -> schedule it!!
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9540): MountEmulatedStorage()
I/libpersona( 9540): KNOX_SDCARD checking this for 10101
E/Zygote  ( 9540): v2
I/libpersona( 9540): KNOX_SDCARD not a persona
,I/SELinux ( 9540): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9540): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3521): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=9540 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 9540): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 8766(373KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 873us total 25.849ms
,D/TimaKeyStoreProvider( 9540): TimaSignature is unavailable
,D/ActivityThread( 9540): Added TimaKeyStore provider
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 623us total 22.413ms
,D/ResourcesManager( 9540): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 437us total 17.258ms
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 6671): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,E/Watchdog( 3521): !@Sync 1
,E/Zygote  ( 9559): MountEmulatedStorage()
E/Zygote  ( 9559): v2
I/libpersona( 9559): KNOX_SDCARD checking this for 10019
I/libpersona( 9559): KNOX_SDCARD not a persona
,I/SELinux ( 9559): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9559): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=9559 uid=10019 gids={50019, 9997} abi=armeabi-v7a
E/SELinux ( 9559): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/PkgBroadcastIntentOp( 6671): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/Mms/FreeMessageStatusReceiver( 8268): onReceive, action : android.intent.action.PACKAGE_ADDED
,D/SettingsProvider( 3521): name = audio_safe_volume_state
,D/TimaKeyStoreProvider( 9559): TimaSignature is unavailable
,D/ActivityThread( 9559): Added TimaKeyStore provider
,D/Mms/FreeMessageReceiverService( 8268): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 8268): onHandleIntent: ACTION_PACKAGE_ADDED
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 9559): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,E/Zygote  ( 9575): MountEmulatedStorage()
E/Zygote  ( 9575): v2
I/libpersona( 9575): KNOX_SDCARD checking this for 10053
I/libpersona( 9575): KNOX_SDCARD not a persona
,I/SELinux ( 9575): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9575): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3521): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=9575 uid=10053 gids={50053, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
,E/SELinux ( 9575): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 9559): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 9559): onReceive called  PACKAGE_ADDED package:com.test.thalitest
I/art     ( 6671): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.permission.PermissionUtils$1>
D/com.sec.android.service.health.upgrade.UninstallReceiver( 9559): onReceive() : package name is not s health. Return !!!
,D/WearableController( 6671): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9590): MountEmulatedStorage()
E/Zygote  ( 9590): v2
I/libpersona( 9590): KNOX_SDCARD checking this for 1000
I/libpersona( 9590): KNOX_SDCARD not a persona
,I/SELinux ( 9590): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/TimaKeyStoreProvider( 9575): TimaSignature is unavailable
,D/ActivityThread( 9575): Added TimaKeyStore provider
,I/SELinux ( 9590): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9590): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=9590 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 9590): TimaSignature is unavailable
,D/ActivityThread( 9590): Added TimaKeyStore provider
,D/ResourcesManager( 9575): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 9575): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 9575): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 9575): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 9590): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/DocsApplication( 9540): Installing DEX configuration.
,I/PCWCLIENTTRACE_LOG( 9590): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 9590): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 9590): new DMDBOpenHelper instance
,D/DexInstaller( 9540): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,I/PCWCLIENTTRACE_PushUtil( 9590): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 9590): sales region : global
I/PCWCLIENTTRACE_PushUtil( 9590): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 9590): [onReceive] - android.intent.action.PACKAGE_ADDED
I/PackageInfoHelper( 9540): Provided clientMode=RELEASE, packageInfo=PackageInfo{3f882b02 com.google.android.apps.docs}
,D/TAG     ( 9540): onCreate()
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9606): MountEmulatedStorage()
E/Zygote  ( 9606): v2
I/libpersona( 9606): KNOX_SDCARD checking this for 1000
I/libpersona( 9606): KNOX_SDCARD not a persona
,I/SELinux ( 9606): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9606): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9606): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.policydm for broadcast com.policydm/.XSPPReceiver: pid=9606 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3521): Killing 9125:com.sec.tcpdumpservice/1000 (adj 13): bgCount ##31
,D/CrossAppStateProvider( 9540): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
D/MyFiles ( 9575): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
,D/TimaKeyStoreProvider( 9606): TimaSignature is unavailable
,D/ActivityThread( 9606): Added TimaKeyStore provider
,I/TactileAssist( 3521): enable value -1
I/TactileAssist( 3521): internal enable value -1
I/TactileAssist( 3521): intensity value -1
I/TactileAssist( 3521): saveAppList value true
,I/TactileAssist( 3521): List of disabled apps :
,E/installd( 2861): system dir 0 : /system/app/
E/installd( 2861): system dir 1 : /system/priv-app/
E/installd( 2861): system dir 2 : /vendor/app/
E/installd( 2861): system dir 3 : /oem/app/
,D/ResourcesManager( 9606): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/PackageManager( 3521): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,E/Zygote  ( 9623): MountEmulatedStorage()
E/Zygote  ( 9623): v2
I/libpersona( 9623): KNOX_SDCARD checking this for 10059
I/libpersona( 9623): KNOX_SDCARD not a persona
,I/ActivityManager( 3521): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=9623 uid=10059 gids={50059, 9997, 3003, 3002} abi=armeabi-v7a
,I/SELinux ( 9623): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9623): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9623): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Killing 9141:com.sec.android.app.sbrowser/u0a156 (adj 13): bgCount ##31
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/TimaKeyStoreProvider( 9623): TimaSignature is unavailable
,D/ActivityThread( 9623): Added TimaKeyStore provider
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:2, health:2, present:true, voltage: 4350, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:-692, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-119
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/ActivityManager( 3521): Waited long enough for: ServiceRecord{1b75d9f8 u0 com.sec.android.service.sm/.service.SecurityManagerService}
,I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/AsyncTaskServiceImpl( 6671): Submit a task: k
,D/ResourcesManager( 9623): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
,W/ResourcesManager( 9623): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5587): Disconnected process message: 10
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/k       ( 6671): Processing package: com.test.thalitest
,E/Zygote  ( 9649): MountEmulatedStorage()
E/Zygote  ( 9649): v2
I/libpersona( 9649): KNOX_SDCARD checking this for 10035
I/libpersona( 9649): KNOX_SDCARD not a persona
,I/SELinux ( 9649): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3521): Start proc com.samsung.android.app.galaxyfinder:tagService for service com.samsung.android.app.galaxyfinder/.tag.TagReadyService: pid=9649 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/SELinux ( 9649): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9649): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/Compatibility( 9623): onReceive() it will make start service
,D/TimaKeyStoreProvider( 9649): TimaSignature is unavailable
,D/ActivityThread( 9649): Added TimaKeyStore provider
,D/GassUtils( 6671): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
D/k       ( 6671): Found info for package com.test.thalitest in db.
,E/Zygote  ( 9666): MountEmulatedStorage()
E/Zygote  ( 9666): v2
I/libpersona( 9666): KNOX_SDCARD checking this for 10042
I/libpersona( 9666): KNOX_SDCARD not a persona
,I/ActivityManager( 3521): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=9666 uid=10042 gids={50042, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
I/SELinux ( 9666): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9666): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9666): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/Compatibility( 9623): onHandleIntent()
,D/Compatibility( 9623): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10208, android.intent.extra.user_handle=0}]
,D/Compatibility( 9623): found: 2
,D/Compatibility( 9623): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 9623): skipping ResolveInfo{fa11c13 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 9623): considering ResolveInfo{7d8ee50 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 9623): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 9623): enabling receiver ResolveInfo{11da0849 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/Compatibility( 9623): enabling receiver ResolveInfo{39d1f54e com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/TimaKeyStoreProvider( 9666): TimaSignature is unavailable
,D/ActivityThread( 9666): Added TimaKeyStore provider
,I/UpdateIcingCorporaServi( 4054): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/Compatibility( 9623): enabling receiver ResolveInfo{1f77666f com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/ResourcesManager( 9649): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/Compatibility( 9623): enabling receiver ResolveInfo{2fe69f7c com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,D/Compatibility( 9623): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,W/ContextImpl( 8911): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:2994 
,D/ResourcesManager( 9666): creating new AssetManager and set to /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk
,W/ResourcesManager( 9666): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9666): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,E/Zygote  ( 9688): MountEmulatedStorage()
E/Zygote  ( 9688): v2
I/libpersona( 9688): KNOX_SDCARD checking this for 10010
I/libpersona( 9688): KNOX_SDCARD not a persona
,I/SELinux ( 9688): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9688): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.facebook.system for broadcast com.facebook.system/com.facebook.oxygen.installer.service.PackageReceiver: pid=9688 uid=10010 gids={50010, 9997} abi=armeabi-v7a
E/SELinux ( 9688): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 9688): TimaSignature is unavailable
,D/ActivityThread( 9688): Added TimaKeyStore provider
,I/FeatureConfig( 9649): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,D/ResourcesManager( 4054): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
I/Icing   ( 6671): Indexing 24C12EC0A8A9103D64E8433CB9B0F00F2CE53D26 from com.google.android.gms
,I/ActivityManager( 3521): Killing 9161:com.sec.android.app.SecSetupWizard/1000 (adj 13): bgCount ##31
,I/art     ( 3521): Explicit concurrent mark sweep GC freed 31882(2013KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 48MB/64MB, paused 10.925ms total 152.490ms
,V/AlarmManager( 3521): waitForAlarm result :4
,W/BaseAppContext( 6671): Using Auth Proxy for data requests.
,W/BaseAppContext( 6671): Using Auth Proxy for data requests.
,I/ActivityManager( 3521): Killing 9200:com.sec.spp.push:RemoteDlcProcess/u0a39 (adj 13): bgCount ##31
,D/ResourcesManager( 9649): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 9649): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 9649): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 9649): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 9649): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9649): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 9649): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,W/BaseAppContext( 6671): Using Auth Proxy for data requests.
,D/ResourcesManager( 9649): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager( 9688): creating new AssetManager and set to /data/app/com.facebook.system-1/base.apk
,W/ResourcesManager( 9649): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 9649): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/ResourcesManager( 9649): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 9649): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,I/PeopleDatabaseHelper( 6671): cleanUpNonGplusAccounts done.
,W/ResourcesManager( 9649): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 9649): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 9649): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 9649): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9649): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9649): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9649): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 9649): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/BaseAppContext( 6671): Using Auth Proxy for data requests.
,D/ResourcesManager( 9649): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 9649): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9649): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9649): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9649): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/Finsky  ( 9474): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/SL_DEBUG( 9666): isLoggable:: isProductShip = 1
D/ResourcesManager( 9649): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,I/SL_DEBUG( 9666): isLoggable:: SL_DEBUG_EXIST = false
,W/ResourcesManager( 9649): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 9649): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9649): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/Zygote  ( 9710): MountEmulatedStorage()
E/Zygote  ( 9710): v2
I/libpersona( 9710): KNOX_SDCARD checking this for 10114
I/libpersona( 9710): KNOX_SDCARD not a persona
,I/SELinux ( 9710): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 9649): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,I/SELinux ( 9710): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9710): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 9649): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9649): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9649): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 9649): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 9649): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 9649): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 9649): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 9649): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/ActivityManager( 3521): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.feed.platformads.AppInstallReceiver: pid=9710 uid=10114 gids={50114, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,D/ResourcesManager( 9649): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 9649): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9649): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 9649): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,V/AlarmManager( 3521): waitForAlarm result :4
D/ResourcesManager( 9649): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 9649): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 9649): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9649): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 9649): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9649): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/BaseAppContext( 6671): Using Auth Proxy for data requests.
,D/TimaKeyStoreProvider( 9710): TimaSignature is unavailable
,D/ResourcesManager( 9649): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ActivityThread( 9710): Added TimaKeyStore provider
,W/ResourcesManager( 9649): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 9649): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9649): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/ActivityManager( 3521): Killing 9223:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 13): bgCount ##31
D/ResourcesManager( 9649): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,W/ResourcesManager( 9649): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ActivityThread( 9666): Loading provider com.samsung.android.sdk.samsunglink.provider.SLinkMedia: com.mfluent.asp.datamodel.ASPMediaStoreProvider
,D/ResourcesManager( 9649): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 9649): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 9649): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9649): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 9649): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9649): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager( 9649): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 9710): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,D/ResourcesManager( 9649): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 9649): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/ResourcesManager( 9649): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 9649): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9649): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager( 9649): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 9649): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 9649): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
D/ResourcesManager( 6671): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
W/ResourcesManager( 9649): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9649): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 9649): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9649): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 9649): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,W/ResourcesManager( 9649): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 9649): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/Icing   ( 6671): Loaded CLD2 Version V2.0 - 20141016
,W/GalaxyFinderApplication( 9649): system/finder_cp/cpdata.xml file not found
,I/UpdateIcingCorporaServi( 4054): UpdateCorporaTask done [took 309 ms] updated apps [took 309 ms] 
,I/Icing   ( 6671): Indexing done 24C12EC0A8A9103D64E8433CB9B0F00F2CE53D26
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9666): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
,W/ResourcesManager( 9710): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9666): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
,V/Transcoder( 9666): Transcoder(0xaf076560)::constructor
V/Transcoder( 9666): addObitRecipient
V/TMI-JNI ( 9666): Mobile Transcoder JNI version 1.6.0/20131120/4.4
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/AppStateLoggerExceptionHandler( 9710): Installed uncaught exception handler for app state logging
,D/AppStateLogger( 9710): Attempting to open app state logging file
,W/GAV2    ( 9540): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/AppStateLogger( 9710): Successfully opened app state logging file: /data/data/com.facebook.katana/app_state_logs/9ffa5d99-74ec-1bdb-ef6e-84b2eb34760f.txt
,D/ACRA    ( 9710): ACRA is enabled for com.facebook.katana, intializing...
,E/Zygote  ( 9752): MountEmulatedStorage()
,E/Zygote  ( 9752): v2
I/libpersona( 9752): KNOX_SDCARD checking this for 10102
,I/libpersona( 9752): KNOX_SDCARD not a persona
,I/SELinux ( 9752): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9752): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9752): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.sec.android.automotive.drivelink for broadcast com.sec.android.automotive.drivelink/com.sec.android.app.automotive.carmode.framework.manager.update.UpdateManagerReceiver: pid=9752 uid=10102 gids={50102, 9997, 3002, 1028, 1015, 3001, 3003} abi=armeabi-v7a
,V/fb-UnpackingSoSource( 9710): locked dso store /data/data/com.facebook.katana/lib-main
,I/fb-UnpackingSoSource( 9710): dso store is up-to-date: /data/data/com.facebook.katana/lib-main
V/fb-UnpackingSoSource( 9710): releasing dso store lock for /data/data/com.facebook.katana/lib-main
,V/fb-UnpackingSoSource( 9710): locked dso store /data/data/com.facebook.katana/lib-assets
I/fb-UnpackingSoSource( 9710): dso store is up-to-date: /data/data/com.facebook.katana/lib-assets
V/fb-UnpackingSoSource( 9710): releasing dso store lock for /data/data/com.facebook.katana/lib-assets
,V/fb-UnpackingSoSource( 9710): locked dso store /data/data/com.facebook.katana/lib-xzs
I/fb-UnpackingSoSource( 9710): dso store is up-to-date: /data/data/com.facebook.katana/lib-xzs
V/fb-UnpackingSoSource( 9710): releasing dso store lock for /data/data/com.facebook.katana/lib-xzs
,I/art     ( 9710): Thread[1,tid=9710,WaitingForJniOnLoad,Thread*=0xb4e08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.katana-2/lib/arm/libfbjni.so"
,V/appstatelogger( 9710): Registered App State Logger stream with Breakpad
,V/MemoryEnlargementHack( 9710): largeHeap already enabled in manifest
V/DexLibLoader( 9710): DLL.loadAll betaBuild:false flags:0x00000004
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 9752): TimaSignature is unavailable
,D/ActivityThread( 9752): Added TimaKeyStore provider
,V/dalvik-internals( 9710): hooked _ZN3art12FaultManager35EnsureArtActionInFrontOfSignalChainEv using jump ()
V/dalvik-internals( 9710): hooked signal using trap ()
V/dalvik-internals( 9710): hooked sysv_signal using trap ()
V/dalvik-internals( 9710): hooked bsd_signal using trap ()
V/dalvik-internals( 9710): hooked sigaction using jump ()
V/dalvik-internals( 9710): hooked _ZN3art6mirror5Class19FindInterfaceMethodEPKNS0_8DexCacheEj using jump ()
V/dalvik-internals( 9710): hooked _ZN3art6mirror5Class25FindDeclaredVirtualMethodEPKNS0_8DexCacheEj using jump ()
V/dalvik-internals( 9710): hooked _ZN3art6mirror5Class17FindVirtualMethodEPKNS0_8DexCacheEj using jump ()
D/DexLibLoader( 9710): patched ART 5.0.x miranda bug
V/DexLibLoader( 9710): opening dex store /data/data/com.facebook.katana/dex
V/DexLibLoader( 9710): Secondary program dex metadata: [.root_relative]
V/DexLibLoader( 9710): Secondary program dex metadata: [.locators]
V/DexLibLoader( 9710): Secondary program dex metadata: [classes2.dex 102b05d6536f178eac593d7d65578de2ddd6825a secondary.dex01.Canary]
V/DexLibLoader( 9710): Secondary program dex metadata: [classes3.dex 857a97620767f7e63fa9c0527067cd6c7a002041 secondary.dex02.Canary]
V/DexLibLoader( 9710): Secondary program dex metadata: [classes4.dex 9935231bfc9137654b613e0c3ad23e5d3c069eb5 secondary.dex03.Canary]
V/DexLibLoader( 9710): Secondary program dex metadata: [classes5.dex 08fa37bfdbdd915e303997b9b9eee7d09b51c215 secondary.dex04.Canary]
V/DexLibLoader( 9710): Secondary program dex metadata: [classes6.dex 82b91dbe59da3b655a867a417fbb83d9fc617838 secondary.dex05.Canary]
V/DexLibLoader( 9710): Secondary program dex metadata: [classes7.dex a8a078ec908ddaee0545b2315081ac33b68f213a secondary.dex06.Canary]
V/DexLibLoader( 9710): Secondary program dex metadata: [classes8.dex 294c9ad6031509e29eb40eb619940d45eeb3c245 secondary.dex07.Canary]
V/DexLibLoader( 9710): Secondary program dex metadata: [classes9.dex 43850a0126da4bbcbaf22e20c7357a75cf3a71aa secondary.dex08.Canary]
V/DexLibLoader( 9710): Secondary program dex metadata: [classes10.dex 3c65d9974656bb0f434d5d9e03c6534a2f64b58a secondary.dex09.Canary]
V/DexLibLoader( 9710): Secondary program dex metadata: [classes11.dex 5501f6915e13d4353ae2cf4cb583284b418d46c4 secondary.dex10.Canary]
,E/Zygote  ( 9771): MountEmulatedStorage()
E/Zygote  ( 9771): v2
I/libpersona( 9771): KNOX_SDCARD checking this for 10045
I/libpersona( 9771): KNOX_SDCARD not a persona
I/SELinux ( 9771): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3521): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=9771 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 9771): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux ( 9771): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/art     ( 2877): Explicit concurrent mark sweep GC freed 8743(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 874us total 23.158ms
,D/ResourcesManager( 9752): creating new AssetManager and set to /system/app/DriveLink/DriveLink.apk
,V/DexLibLoader( 9710): read status:9 check:faceb007faceb00e
,V/DexLibLoader( 9710): read saved dep file /data/data/com.facebook.katana/dex/deps (176 bytes)
V/DexLibLoader( 9710): verified deps file
I/DexLibLoader( 9710): current scheme: com.facebook.common.dextricks.OdexSchemeNoop next step: LA_LOAD_EXISTING
,V/MultiDexClassLoader( 9710): installing MultiDexClassLoader before application classloader
,D/MultiDexClassLoader( 9710): primary dex name: /data/app/com.facebook.katana-2/base.apk
D/MultiDexClassLoader( 9710): Found system/other dex /system/framework/com.google.android.maps.jar
D/MultiDexClassLoader( 9710): Found primary dex /data/app/com.facebook.katana-2/base.apk
D/MultiDexClassLoader( 9710): Setup multi dex took 0 ms.
V/DexLibLoader( 9710): optimization needed: no
,D/MemoryReductionHack( 9710): Marked as initialized entry corresponding to path /data/app/com.facebook.katana-2/base.apk
,D/TimaKeyStoreProvider( 9771): TimaSignature is unavailable
,D/ActivityThread( 9771): Added TimaKeyStore provider
I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 424us total 14.566ms
,W/ResourcesManager( 9752): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 273us total 8.741ms
,D/ResourcesManager( 9771): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,I/GMPM    ( 9710): App measurement is starting up
,E/GMPM    ( 9710): getGoogleAppId failed with status: 10
,E/GMPM    ( 9710): Uploading is not possible. App measurement disabled
,I/ActivityManager( 3521): Killing 7337:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,E/[CarMode]( 9752): [DLApplication]-onCreate: Applicatino Started!
,I/SA      ( 9771): [SSP] onCreated
,D/SampleAppCoreManager( 9752): SampleAppCoreManager VACVersion '2.2.0.11867'
D/SampleAppCoreManager( 9752): mContext is not null
,I/VlingoAndroidCore( 9752): AppName: SamsungCCTproject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
,I/SA      ( 9771): [TPM] There is no property file
,I/SA      ( 9771): [SCU] isHaveSA() - false
,I/SA      ( 9771): [TPM] getModelProperty : null
I/SA      ( 9771): [TPM] getCSCProperty : null
,I/SA      ( 9771): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,I/SA      ( 9771): [DM] init START
,I/SA      ( 9771): [DM] This device is not a Vodafone
,I/SA      ( 9771): checkReactivationActive for LOLLIPOP
I/SA      ( 9771): checkReactivationActive for reactiveActive
I/SA      ( 9771): setSupportRL : true
,I/SA      ( 9771): [SCU] isHaveSA() - false
I/SA      ( 9771): support phone number id : false
I/SA      ( 9771): [DM] init END
,I/SA      ( 9771): [SUR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      ( 9771): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10208 extra.user_handle.:0 ]
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,W/StaticBindingVerifier( 9710): Verify
,E/Zygote  ( 9808): MountEmulatedStorage()
I/libpersona( 9808): KNOX_SDCARD checking this for 10046
E/Zygote  ( 9808): v2
I/libpersona( 9808): KNOX_SDCARD not a persona
,I/SELinux ( 9808): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9808): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.samsung.android.app.pinboard:sync for broadcast com.samsung.android.app.pinboard/com.sec.android.sCloudRelayData.RelayReceiver: pid=9808 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,E/SELinux ( 9808): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,W/LightSharedPreferencesImpl( 9710): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl( 9710): java.io.FileNotFoundException: /data/data/com.facebook.katana/app_light_prefs/com.facebook.katana/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl( 9710): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl( 9710): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl( 9710): 	at com.facebook.crudolib.prefs.LightSharedPreferencesStorage.a(update_current:56)
W/LightSharedPreferencesImpl( 9710): 	at com.facebook.crudolib.prefs.LightSharedPreferencesImpl$1.run(update_favorite_contacts:61)
W/LightSharedPreferencesImpl( 9710): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl( 9710): 	at com.facebook.common.executors.WrappingExecutorService$1.run(video_home:77)
W/LightSharedPreferencesImpl( 9710): 	at com.facebook.common.executors.DefaultConstrainedListeningExecutorService$Worker.run(video_sleep_timeout_ms:327)
W/LightSharedPreferencesImpl( 9710): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl( 9710): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl( 9710): 	at com.facebook.common.executors.NamedThreadFactory$1.run(video_story:42)
W/LightSharedPreferencesImpl( 9710): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl( 9710): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl( 9710): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl( 9710): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl( 9710): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl( 9710): 	... 10 more
,E/Zygote  ( 9824): MountEmulatedStorage()
,E/Zygote  ( 9824): v2
I/libpersona( 9824): KNOX_SDCARD checking this for 10034
I/libpersona( 9824): KNOX_SDCARD not a persona
,I/SELinux ( 9824): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3521): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=9824 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 9824): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Killing 9252:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,E/SELinux ( 9824): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 9808): TimaSignature is unavailable
,D/ActivityThread( 9808): Added TimaKeyStore provider
,D/WifiService( 3521): New client listening to asynchronous messages
,D/ResourcesManager( 9808): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/TimaKeyStoreProvider( 9824): TimaSignature is unavailable
,D/ActivityThread( 9824): Added TimaKeyStore provider
,W/ResourcesManager( 9808): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 9808): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager( 9808): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 9824): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,E/Minikin ( 9808): addFont failed to create font /system/fonts/SamsungSans-light.ttf
,W/fb4a(:<default>):UserScope( 9710): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,I/System.out( 9824): Inside WakeupProvider
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,E/DatabaseUtils( 9824): Writing exception to parcel
E/DatabaseUtils( 9824): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 9824): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 9824): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 9824): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1535)
E/DatabaseUtils( 9824): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 9824): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 9824): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 9824): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/DatabaseUtils( 9824): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/DatabaseUtils( 9824): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 9824): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System.err( 9752): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
,W/System.err( 9752): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 9752): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 9752): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 9752): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 9752): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 9752): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 9752): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 9752): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 9752): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 9752): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 9752): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 9752): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 9752): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err( 9752): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err( 9752): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err( 9752): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err( 9752): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
W/System.err( 9752): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:131)
W/System.err( 9752): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:197)
W/System.err( 9752): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:126)
W/System.err( 9752): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 9752): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
W/System.err( 9752): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
W/System.err( 9752): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
W/System.err( 9752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 9752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 9752): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err( 9752): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 9752): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 9752): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 9752): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/RelayReceiver_PinBoard( 9808): onReceive... android.intent.action.PACKAGE_ADDED
W/fb4a(:<default>):UserScope( 9710): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
E/DatabaseUtils( 9824): Writing exception to parcel
E/DatabaseUtils( 9824): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 9824): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 9824): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 9824): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1535)
E/DatabaseUtils( 9824): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 9824): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 9824): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 9824): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/DatabaseUtils( 9824): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/DatabaseUtils( 9824): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 9824): 	at android.os.Binder.execTransact(Binder.java:446)
I/RelayService_PinBoard( 9808): RelayService Started!! : android.intent.action.PACKAGE_ADDED
W/System.err( 9752): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
W/System.err( 9752): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 9752): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 9752): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 9752): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 9752): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 9752): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 9752): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 9752): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 9752): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 9752): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 9752): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 9752): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 9752): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.otherMasterExists(InternalMdsoUtils.java:98)
W/System.err( 9752): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.isSlave(InternalMdsoUtils.java:32)
W/System.err( 9752): 	at com.vlingo.core.facade.lmtt.MdsoUtils.isSlave(MdsoUtils.java:13)
W/System.err( 9752): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:242)
W/System.err( 9752): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:126)
W/System.err( 9752): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 9752): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
W/System.err( 9752): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
W/System.err( 9752): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
W/System.err( 9752): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 9752): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 9752): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err( 9752): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 9752): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 9752): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 9752): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
E/[CarMode]( 9752): [DLApplication]-Init Called!:false
W/[CarMode]( 9752): [CommonUtil]-=========================================
W/[CarMode]( 9752): [CommonUtil]-CarMode Version:1.10.38.19768
W/[CarMode]( 9752): [CommonUtil]-=========================================
E/[CarMode]( 9752): [DLApplication]-Init Started!:true
I/VlingoApplication( 9824): VlingoApplication appVersion ='11.7.0.1.39589', coreVersion = '2.5.2.15201', ro.csc.sales_code=XEO
I/[CarModeFW]( 9752): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW]( 9752): ### com.sec.android.app.automotive.carmode.framework.DriveLinkServiceInterfaceImp::initialize(132)
I/[CarModeFW]( 9752): ### com.sec.android.automotive.drivelink.DLApplication::init(211)
I/[CarModeFW]( 9752): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(135)
I/[CarModeFW]( 9752): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW]( 9752): ### android.app.ActivityThread::handleBindApplication(5115)
I/[CarModeFW]( 9752): ### android.app.ActivityThread::access$1600(178)
I/[CarModeFW]( 9752): ### android.app.ActivityThread$H::handleMessage(1510)
I/[CarModeFW]( 9752): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW]( 9752): ### android.os.Looper::loop(145)
I/[CarModeFW]( 9752): ### android.app.ActivityThread::main(5944)
I/[CarModeFW]( 9752): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW]( 9752): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW]( 9752): ### com.android.internal.os.ZygoteInit::main(1194)
D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/GAV2    ( 9540): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/ActivityManager( 3521): Killing 9268:com.sec.android.diagmonagent/1000 (adj 13): bgCount ##31
I/VlingoAndroidCore( 9824): AppName: SamsungTproject, Core: 2.5.2.15201, SDK: 2.0.1657, EDM:15201
I/MessageDataHandler( 9752): initialize
D/[CarModeFW]( 9752): CDH-initiazlieCaches : before sync
D/[CarModeFW]( 9752): CDH-initiazlieCaches : after sync
W/fb4a(:<default>):UserScope( 9710): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/[CarModeFW]( 9752): CDH-buildContactCacheWireFrame : cur len =0
,D/[CarModeFW]( 9752): CDH-ContactDataHandler initiazlieCaches time : 26
D/[CarModeFW]( 9752): CDH-initiazlieCaches : end sync
,D/[CarModeFW]( 9752): DrivingManager-initialize...
,I/SensorService( 3521): Skipped sensor HRMLED IR because it requires permission com.samsung.permission.SSENSOR_HRM_RAW_PPG
I/SensorService( 3521): Skipped sensor HRMLED RED because it requires permission com.samsung.permission.SSENSOR_HRM_RAW_PPG
I/SensorService( 3521): Skipped sensor MAX86902 because it requires permission 
I/SensorService( 3521): Skipped sensor HRM Sensor because it requires permission 
I/SensorService( 3521): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
,V/xAnalytics( 9710): java/com/facebook/xanalytics/jni/XAnalyticsNative.cpp - jint JNI_OnLoad(JavaVM*, void*)
V/xAnalytics( 9710): JNI_OnLoad XAnalyticsNative entered
V/xAnalytics( 9710): JNI_OnLoad XAnalyticsNative complete
,V/xAnalytics( 9710): tigon: 0x0 - xanalytics: 0xffffffff93514220
,V/xAnalytics( 9710): xplat/fbacore/fbacore/FbaBeaconLogger.cpp - void facebook::xanalytics::FbaBeaconLogger::init(const string&, const string&, uint32_t) 0 0
,V/xAnalytics( 9710): xplat/fbacore/fbacore/FbaBeaconLogger.cpp - void facebook::xanalytics::FbaBeaconLogger::init(const string&, const string&, uint32_t) 0 0
W/art     ( 9710): Attempt to remove local handle scope entry from IRT, ignoring
,D/VlingoApplication( 9824): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,D/VlingoApplication( 9824): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,D/DialogFlow( 9824): initQueue()
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9875): MountEmulatedStorage()
E/Zygote  ( 9875): v2
I/libpersona( 9875): KNOX_SDCARD checking this for 10110
I/libpersona( 9875): KNOX_SDCARD not a persona
,I/SELinux ( 9875): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9875): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9875): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.oxygen.appmanager.common.packages.PackageReceiver: pid=9875 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/TimaKeyStoreProvider( 9875): TimaSignature is unavailable
,D/ActivityThread( 9875): Added TimaKeyStore provider
,I/ActivityManager( 3521): Killing 9283:com.sec.android.widgetapp.activeapplicationwidget/u0a173 (adj 13): bgCount ##31
,D/ResourcesManager( 9875): creating new AssetManager and set to /data/app/com.facebook.appmanager-1/base.apk
,I/MediaPlayer( 9752): Need to enable context aware info
V/MediaPlayer-JNI( 9752): native_setup
V/MediaPlayer( 9752): constructor
,V/MediaPlayer( 9752): setListener
,D/[CarModeFW]( 9752): MY_TAG-[YANG] MusicButtonReceiver construct MusicButtonReceiver() 
,I/[CarModeFW]( 9752): DriveLinkServiceInterfaceImp-drivelink framework initialize end
,D/[CarMode]( 9752): [DLServiceManager]-getOnDLLocationSuggestionListener..........
,D/[CarModeFW]( 9752): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestCallLogList => start time : 1457945495928
,D/[CarMode]( 9752): [DLServiceManager]-updateLocationList
D/[CarMode]( 9752): [DLServiceManager]-requestRecommendedLocationList
D/[CarModeFW]( 9752): insertNavigationAvailable-sql: select distinct nav_package from tb_location_navigation_available
,D/[CarModeFW]( 9752): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestInboxList => start time : 1457945495928
D/[CarModeFW]( 9752): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestUnreadMessageCount => start time : 1457945495928
D/[CarModeFW]( 9752): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedLocationList => start time : 1457945495928
,D/[CarModeFW]( 9752): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForCall => start time : 1457945495928
,D/[CarModeFW]( 9752): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => start time : 1457945495928
,D/[CarModeFW]( 9752): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => start time : 1457945495928
,F/DLApplication( 9752): DLApplication mListNavitationAvailable: [com.skt.skaf.l001mtm091, com.google.android.apps.maps, kt.navi, com.mnsoft.lgunavi, com.autonavi.xmgd.navigator.samsung, com.here.app.maps]
I/[CarMode]( 9752): [LogNotNull]-Package name is: com.here.app.maps
,D/[CarModeFW]( 9752): ContactDataHandler-getFavoriteContactList : cur len = 0
,D/[CarModeFW]( 9752): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => execute time : 15
,D/TP/SmsProvider( 3979): query,matched:2, calling pid = 9752
,D/TP/SmsProvider( 3979): match 2:Elapsed time : 1.574 ms
,D/[CarModeFW]( 9752): ContactDataHandler-getFavoriteContactList : cur len = 0
,D/TP/SmsProvider( 3979): query,matched:2, calling pid = 9752
,D/TP/SmsProvider( 3979): match 2:Elapsed time : 1.389 ms
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/[CarMode]( 9752): [DLApplication]-Init End!:true
,D/[CarModeFW]( 9752): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => execute time : 31
,D/[CarMode]( 9752): [TAG]-phone sound mode is: 0
V/[CarMode]( 9752): [DLApplication]-savePreviousGpsState
D/[CarModeFW]( 9752): ContactDataHandler-getFavoriteContactList : cur len = 0
,D/[CarModeFW]( 9752): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForCall => execute time : 35
,E/Zygote  ( 9892): MountEmulatedStorage()
,E/Zygote  ( 9892): v2
I/libpersona( 9892): KNOX_SDCARD checking this for 10047
I/libpersona( 9892): KNOX_SDCARD not a persona
,I/SELinux ( 9892): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9892): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3521): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=9892 uid=10047 gids={50047, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 9892): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/MessageDataHandler( 9752):  getInboxList smsCursor : 47
,D/[CarModeFW]( 9752): CalllogDataHandler-getCalllogList : cur len = 0
,D/TP/MmsProvider( 3979): Query uri=content://mms, match=0, calling pid = 9752
,D/TP/MmsProvider( 3979): Query uri=content://mms/inbox, match=2, calling pid = 9752
,D/[CarModeFW]( 9752): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestCallLogList => execute time : 58
,I/MessageDataHandler( 9752): getUnreadMessageCount :0
,D/[CarModeFW]( 9752): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestUnreadMessageCount => execute time : 59
,V/[CarMode]( 9752): [DLApplication]-savePreviousGpsState: Previous state = 0
,D/MessageDataHandler( 9752):  getInboxList mmsCursor : 14
,D/MessageDataHandler( 9752):  getInboxList mms,sms cursor join : 4
,D/TP/MmsSmsProvider( 3979): query,matched:0, calling pid = 9752
,V/TP/MmsSmsProvider( 3979): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 3979): match 0:Elapsed time : 2.395 ms
,I/Icing   ( 6671): Indexing 24C12EC0A8A9103D64E8433CB9B0F00F2CE53D26 from com.google.android.gms
,D/[CarMode]( 9752): [DLApplication]-GooglePlayServices SUCCESS.
,D/TimaKeyStoreProvider( 9892): TimaSignature is unavailable
I/Icing   ( 6671): Indexing done 24C12EC0A8A9103D64E8433CB9B0F00F2CE53D26
E/[CarMode]( 9752): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,D/ActivityThread( 9892): Added TimaKeyStore provider
,D/TP/MmsSmsProvider( 3979): query,matched:13, calling pid = 9752
,I/[CarMode]( 9752): [[DLUncaughtExceptionHandler]]-setDLUncaughtExceptionHandler
D/TP/MmsSmsProvider( 3979): match 13:Elapsed time : 1.726 ms
E/[CarMode]( 9752): [[DLUncaughtExceptionHandler]]-DLUncaughtExceptionHandler is created!
,I/UpdateManagerReceiver( 9752): Intent : android.intent.action.PACKAGE_ADDEDMon Mar 14 09:51:36 GMT+01:00 2016
,D/ResourcesManager( 9649): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,D/DialogFlow( 9752): initQueue()
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 9892): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,D/ResourcesManager( 9649): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,W/ResourcesManager( 9892): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/ResourcesManager( 9649): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,E/Zygote  ( 9907): MountEmulatedStorage()
I/libpersona( 9907): KNOX_SDCARD checking this for 1000
E/Zygote  ( 9907): v2
I/libpersona( 9907): KNOX_SDCARD not a persona
,I/SELinux ( 9907): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9907): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3521): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=9907 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux ( 9907): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Killing 8894:com.sec.providers.settingsearch/u0a181 (adj 13): bgCount ##31
,I/ActivityManager( 3521): Killing 9315:com.samsung.android.app.mirrorlink/1000 (adj 13): bgCount ##32
,I/ActivityManager( 3521): Killing 8573:com.samsung.android.snote/u0a160 (adj 15): bgCount ##33
,W/ResourcesManager( 9649): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ResourcesManager( 9649): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/MessageDataHandler( 9752):  getInboxList address cursor : 46
D/ResourcesManager( 9649): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager( 9649): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/TP/MmsSmsProvider( 3979): query,matched:0, calling pid = 9752
V/TP/MmsSmsProvider( 3979): getSimpleConversations entered.
,D/ResourcesManager( 9649): creating new AssetManager and set to /system/app/Videos/Videos.apk
,V/fb-UnpackingSoSource( 9875): locked dso store /data/data/com.facebook.appmanager/lib-main
I/fb-UnpackingSoSource( 9875): dso store is up-to-date: /data/data/com.facebook.appmanager/lib-main
V/fb-UnpackingSoSource( 9875): releasing dso store lock for /data/data/com.facebook.appmanager/lib-main
,D/TP/MmsSmsProvider( 3979): match 0:Elapsed time : 1.892 ms
V/fb-UnpackingSoSource( 9875): locked dso store /data/data/com.facebook.appmanager/lib-assets
I/fb-UnpackingSoSource( 9875): dso store is up-to-date: /data/data/com.facebook.appmanager/lib-assets
V/fb-UnpackingSoSource( 9875): releasing dso store lock for /data/data/com.facebook.appmanager/lib-assets
V/fb-UnpackingSoSource( 9875): locked dso store /data/data/com.facebook.appmanager/lib-xzs
I/fb-UnpackingSoSource( 9875): dso store is up-to-date: /data/data/com.facebook.appmanager/lib-xzs
V/fb-UnpackingSoSource( 9875): releasing dso store lock for /data/data/com.facebook.appmanager/lib-xzs
,D/ACRA    ( 9875): ACRA is enabled for com.facebook.appmanager, intializing...
D/MessageDataHandler( 9752):  getInboxList thread cursor : 11
,D/MessageDataHandler( 9752):  thread, addr result: 6
I/[CarModeFW]( 9752): ContentManager-com.sec.android.app.automotive.carmode.framework.manager.content.ContentManager end getInboxList() : 148
I/[CarModeFW]( 9752): ContentManager-com.sec.android.app.automotive.carmode.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
D/[CarModeFW]( 9752): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestInboxList => execute time : 149
,V/DexLibLoader( 9875): DLL.loadAll betaBuild:true flags:0x00000001
,V/dalvik-internals( 9875): hooked _ZN3art12FaultManager35EnsureArtActionInFrontOfSignalChainEv using jump ()
,V/dalvik-internals( 9875): hooked signal using trap ()
V/dalvik-internals( 9875): hooked sysv_signal using trap ()
V/dalvik-internals( 9875): hooked bsd_signal using trap ()
V/dalvik-internals( 9875): hooked sigaction using jump ()
,V/DexLibLoader( 9875): opening dex store /data/data/com.facebook.appmanager/dex
,V/DexLibLoader( 9875): Secondary program dex metadata: [classes2.dex 810147d6f366c39a471d8dcf6e02fd5ad5c640fa secondary.dex01.Canary]
V/DexLibLoader( 9875): read status:9 check:faceb007faceb00e
V/DexLibLoader( 9875): read saved dep file /data/data/com.facebook.appmanager/dex/deps (176 bytes)
V/DexLibLoader( 9875): verified deps file
I/DexLibLoader( 9875): current scheme: com.facebook.common.dextricks.OdexSchemeNoop next step: LA_LOAD_EXISTING
V/MultiDexClassLoader( 9875): installing MultiDexClassLoader before application classloader
,D/MultiDexClassLoader( 9875): Found primary dex /data/app/com.facebook.appmanager-1/base.apk
D/MultiDexClassLoader( 9875): Setup multi dex took 0 ms.
V/DexLibLoader( 9875): optimization needed: no
,D/TimaKeyStoreProvider( 9907): TimaSignature is unavailable
,D/ActivityThread( 9907): Added TimaKeyStore provider
,D/ResourcesManager( 9649): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager( 9649): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,D/ResourcesManager( 9649): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
I/CalendarProvider2( 9892): CalendarProvider2.onCreate() called
,D/ResourcesManager( 9649): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,D/ResourcesManager( 9649): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager( 9907): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
,I/GMPM    ( 9875): App measurement is starting up
,I/System.out( 9824): INFO:Resource not found:/Common.properties Using default values
,E/GMPM    ( 9875): getGoogleAppId failed with status: 10
,E/GMPM    ( 9875): Uploading is not possible. App measurement disabled
,W/cn      ( 9875): Verify
D/ResourcesManager( 9649): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
,D/ResourcesManager( 9649): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,W/ContextImpl( 9907): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2994 
,D/ResourcesManager( 9649): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager( 9649): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 9907): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
D/ResourcesManager( 9649): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 9649): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,W/appmanager(:<default>):LightSharedPreferencesImpl( 9875): Failed to load preference file from Disk!
W/appmanager(:<default>):LightSharedPreferencesImpl( 9875): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9875): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9875): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9875): 	at com.facebook.crudolib.d.k.a(LightSharedPreferencesStorage.java:56)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9875): 	at com.facebook.crudolib.d.g.run(LightSharedPreferencesImpl.java:61)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9875): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9875): 	at com.facebook.common.executors.dt.run(WrappingExecutorService.java:77)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9875): 	at com.facebook.common.executors.aa.run(DefaultConstrainedListeningExecutorService.java:327)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9875): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9875): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9875): 	at com.facebook.common.executors.cs.run(NamedThreadFactory.java:42)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9875): 	at java.lang.Thread.run(Thread.java:818)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9875): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9875): 	at libcore.io.Posix.open(Native Method)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9875): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9875): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9875): 	... 10 more
,D/ResourcesManager( 9649): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
,D/ResourcesManager( 9649): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
,D/ResourcesManager( 9649): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,E/Zygote  ( 9942): MountEmulatedStorage()
E/Zygote  ( 9942): v2
I/libpersona( 9942): KNOX_SDCARD checking this for 10121
D/ResourcesManager( 9649): creating new AssetManager and set to /system/app/Maps/Maps.apk
I/libpersona( 9942): KNOX_SDCARD not a persona
,I/SELinux ( 9942): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager( 9649): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,I/ActivityManager( 3521): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=9942 uid=10121 gids={50121, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
D/ResourcesManager( 9649): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
I/SELinux ( 9942): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9942): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/appmanager(:<default>):b( 9875): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 9649): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
,E/FilterInstaller( 9907): installFilters
,W/appmanager(:<default>):b( 9875): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,E/FilterInstaller( 9907): There is no requred permission
D/ResourcesManager( 9649): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ResourcesManager( 9649): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 9649): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,D/ResourcesManager( 9649): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,E/Zygote  ( 9957): MountEmulatedStorage()
,E/Zygote  ( 9957): v2
I/libpersona( 9957): KNOX_SDCARD checking this for 10013
I/libpersona( 9957): KNOX_SDCARD not a persona
,I/SELinux ( 9957): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/TimaKeyStoreProvider( 9942): TimaSignature is unavailable
,D/ActivityThread( 9942): Added TimaKeyStore provider
I/ActivityManager( 3521): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=9957 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 9957): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9957): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 9942): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
,D/TimaKeyStoreProvider( 9957): TimaSignature is unavailable
I/ActivityManager( 3521): Killing 8937:com.google.android.gm/u0a122 (adj 15): bgCount ##31
,D/ActivityThread( 9957): Added TimaKeyStore provider
V/AlarmManager( 3521): waitForAlarm result :4
,D/[CarModeFW]( 9752): LocationDataHandler-No schedules found.
,V/AlarmManager( 3521): waitForAlarm result :4
,D/ResourcesManager( 9649): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,I/Icing   ( 6671): Indexing 5F814D61A0DCF2E8041D271E5054F7C0773240D3 from com.google.android.googlequicksearchbox
,D/ResourcesManager( 9649): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,D/ResourcesManager( 9957): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,D/PackageIntentReceiver( 9942): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 9942): Not GearManger package! 
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/AlarmManager( 3521): waitForAlarm result :12
,W/appmanager(:<default>):QuickExperimentControllerImpl( 9875): Exposure of experiment com.facebook.http.g.c@397d259 occurred when no user was logged in
,I/art     ( 9875): Rejecting re-init on previously-failed class java.lang.Class<com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper>
,I/art     ( 9875): Rejecting re-init on previously-failed class java.lang.Class<com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper>
,D/AppStateLogger( 9710): Successfully dumped app state to log file
,I/art     ( 3521): Explicit concurrent mark sweep GC freed 16256(1039KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 48MB/64MB, paused 1.262ms total 108.997ms
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9987): MountEmulatedStorage()
E/Zygote  ( 9987): v2
I/libpersona( 9987): KNOX_SDCARD checking this for 1000
I/libpersona( 9987): KNOX_SDCARD not a persona
,I/SELinux ( 9987): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9987): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=9987 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux ( 9987): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/[CarModeFW]( 9752): MyPlaceProvider-Provider uri: content://com.samsung.android.internal.intelligence.useranalysis/place
,V/GLSActivity( 4659): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out( 9875): Thread-1305(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 9875): Thread-1305(ApacheHTTPLog):isSBSettingEnabled false
,V/GLSActivity( 4659): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,I/System.out( 9875): Thread-1305(ApacheHTTPLog):isShipBuild true
I/System.out( 9875): Thread-1305(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2849): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2849): getNetworkForDns: using netid 502 for uid 10110
,E/Zygote  (10003): MountEmulatedStorage()
E/Zygote  (10003): v2
I/libpersona(10003): KNOX_SDCARD checking this for 10003
I/libpersona(10003): KNOX_SDCARD not a persona
,I/SELinux (10003): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/TimaKeyStoreProvider( 9987): TimaSignature is unavailable
,D/ActivityThread( 9987): Added TimaKeyStore provider
,I/SELinux (10003): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=10003 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 3006, 1007, 3001} abi=armeabi-v7a
,E/SELinux (10003): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Killing 8989:com.google.android.talk/u0a125 (adj 15): bgCount ##31
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/EnterpriseController( 2849): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2849): getNetworkForDns: using netid 502 for uid 10064
,D/ResourcesManager( 9987): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/TimaKeyStoreProvider(10003): TimaSignature is unavailable
,D/ActivityThread(10003): Added TimaKeyStore provider
,I/ActivityManager( 3521): Killing 8440:com.sec.android.widgetapp.locationwidget/u0a22 (adj 15): bgCount ##31
,D/ResourcesManager(10003): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,D/UserAnalysis.PlaceProvider(10003): PlaceProvider onCreate()
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10021): MountEmulatedStorage()
E/Zygote  (10021): v2
I/libpersona(10021): KNOX_SDCARD checking this for 1000
I/libpersona(10021): KNOX_SDCARD not a persona
,I/SELinux (10021): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10021): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10021): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=10021 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3521): Killing 9395:com.samsung.android.app.FileShareServer/u0a79 (adj 15): bgCount ##31
,D/UserAnalysis.SecureDbManager(10003): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper(10003): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider(10003): Create SecureDbHelper
,D/IntelligenceServiceApplication(10003): onCreate()
,I/Icing   ( 6671): Indexing done 5F814D61A0DCF2E8041D271E5054F7C0773240D3
,D/TimaKeyStoreProvider(10021): TimaSignature is unavailable
,D/ActivityThread(10021): Added TimaKeyStore provider
,D/ResourcesManager(10021): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,D/AcmsPackageEventListener(10021): Received: android.intent.action.PACKAGE_ADDED
,W/ContextImpl(10021): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,I/ActivityManager( 3521): Killing 9412:com.sec.knox.bridge/1000 (adj 15): bgCount ##31
,D/AcmsService(10021): Enter Oncreate
D/AcmsServiceMonitor(10021): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService(10021): creating AcmsCore
D/AcmsCore(10021): AcmsCore.getAcmsCore() - Enter
D/AcmsCore(10021): AcmsCore
,D/[CarModeFW]( 9752): MyPlaceProvider-+++Begin print all data in content provider+++
D/[CarModeFW]( 9752): MyPlaceProvider-=============
D/[CarModeFW]( 9752): MyPlaceProvider-=============
D/[CarModeFW]( 9752): MyPlaceProvider-=============
D/[CarModeFW]( 9752): MyPlaceProvider-=============
D/[CarModeFW]( 9752): MyPlaceProvider-=============
D/[CarModeFW]( 9752): MyPlaceProvider-=============
D/[CarModeFW]( 9752): MyPlaceProvider----End print all data in content provider---
D/[CarModeFW]( 9752): MyPlaceProvider-==============
D/[CarModeFW]( 9752): MyPlaceProvider-==============
D/[CarModeFW]( 9752): MyPlaceProvider-==============
D/[CarModeFW]( 9752): MyPlaceProvider-==============
D/[CarModeFW]( 9752): MyPlaceProvider-==============
,D/AcmsCore(10021): init
,D/AcmsCore(10021): Looper handler is not null
D/AcmsCore(10021): Post to AcmsCoreHandler
,D/[CarModeFW]( 9752): DestinationAvailableTableHandler-sql: select dest_name from tb_destination_list_available where ((1457945496622 - dest_date ) / 360000 ) <= 24 ORDER BY dest_date DESC LIMIT 100
D/AcmsServiceMonitor(10021): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(10021): Incrementing - Counter value: 1
D/AcmsCore(10021): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService(10021): onStartCommand
D/AcmsService(10021): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor(10021): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor(10021): Incrementing - Counter value: 2
D/AcmsService(10021): Incremented Counter Value : onStartCommand
,D/AcmsCertificateMngr(10021): AcmsCertificateMngr
,E/[CarModeFW]( 9752): DestinationAvailableTableHandler-insert FAIL!
D/AcmsRevocationMngr(10021): AcmsRevocationMngr
E/DestinationList( 9752): loadLocationDestinationList is null
D/[CarModeFW]( 9752): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedLocationList => execute time : 696
,D/ActivityThread(10021): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/AcmsService(10021): Inside handle Intent
D/AcmsService(10021): App added - package name: com.test.thalitest
D/AcmsCore(10021): Post to AcmsCoreHandler
D/AcmsServiceMonitor(10021): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(10021): Incrementing - Counter value: 3
D/AcmsCore(10021): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService(10021): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor(10021): Decrementing - Counter value: 2
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10039): MountEmulatedStorage()
E/Zygote  (10039): v2
I/libpersona(10039): KNOX_SDCARD checking this for 10160
I/libpersona(10039): KNOX_SDCARD not a persona
,I/SELinux (10039): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3521): Start proc com.samsung.android.snote for broadcast com.samsung.android.snote/.library.plugin.PluginBroadcastReceiver: pid=10039 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
,I/SELinux (10039): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10039): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 8759(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 864us total 22.938ms
,D/TimaKeyStoreProvider(10039): TimaSignature is unavailable
,D/ActivityThread(10039): Added TimaKeyStore provider
,D/ResourcesManager(10039): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 844us total 18.930ms
,W/ResourcesManager(10039): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(10039): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(10039): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 435us total 12.955ms
,I/WifiStateMachine( 3521): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3521): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3521): CMD_RSSI_POLL : out!
,V/Common  (10039): getScreenSize 1440 2560
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/JAM     (10039): Load The ApaService JNI
,I/JAM     (10039): version: ProfessionalAudio_v1.0.b5
I/JAM     (10039): Try v1.0.b3 ...
D/Spen    (10039): SpenSdk version level = 55
D/Spen    (10039): SpenSdk jar version = 3.0.243
,D/Spen    (10039): SpenSdk apk version = 3.0.235
D/Spen    (10039): Server UPDATE Check
,W/linker  (10039): libSPenBase.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
E/Zygote  (10057): MountEmulatedStorage()
E/Zygote  (10057): v2
I/libpersona(10057): KNOX_SDCARD checking this for 10160
I/libpersona(10057): KNOX_SDCARD not a persona
,D/SPenError(10039): JNI_OnLoad
I/SELinux (10057): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/JNI_Bitmap(10039): Init .. Done
D/SPenSpiDecoder(10039): JNI_OnLoad .. Done
D/SPenError(10039): JNI_OnLoad Success
,D/PluginManager(10039): Registering com/samsung/android/sdk/pen/plugin/framework/JniPluginManager natives
D/PluginManager(10039): Registering com/samsung/android/sdk/pen/plugin/framework/SpenPluginManager$PluginListener natives
,D/Init_SPenSdk_Jni(10039): JNI_OnLoad
D/Init_SPenSdk_Jni(10039): AndroidSDK: 21
I/ActivityManager( 3521): Start proc com.samsung.android.snote:provider for content provider com.samsung.android.snote/.model.provider.SNoteProvider: pid=10057 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
D/Init_SPenSdk_Jni(10039): JNI_OnLoad .. Done
I/SELinux (10057): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10057): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/Model_ObjectBase_Jni(10039): JNI_OnLoad .. Done
,D/Model_ObjectStroke_Jni(10039): JNI_OnLoad .. Done
D/Model_ObjectImage_Jni(10039): JNI_OnLoad .. Done
,D/Model_ObjectText_Jni(10039): JNI_OnLoad .. Done
D/Model_ObjectContainer_Jni(10039): JNI_OnLoad .. Done
,D/Model_PageDoc_Jni(10039): JNI_OnLoad .. Done
,D/Model_NoteDoc_Jni(10039): check build type eng[0]
D/Model_NoteDoc_Jni(10039): JNI_OnLoad .. Done
D/Model_NoteFile_Jni(10039): JNI_OnLoad .. Done
,D/Model_ObjectUtil_Jni(10039): JNI_OnLoad .. Done
D/Model   (10039): OnLoad class Done
,D/spe_log (10039): SPen::GLRenderThreadImpl::GLRenderThreadImpl() Initialize: 0
W/ActivityThread( 9875): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
D/SPen_Library(10039): Draw Engine JNI_OnLoad enter!!
D/SPen_Library(10039): Canvas JNI_OnLoad enter!!
,D/SPen_Library(10039): Canvas JNI_OnLoad Success
D/SPen_Library(10039): TextView JNI_OnLoad enter!!
,D/SPen_Library(10039): TextView JNI_OnLoad Success
D/SPen_Library(10039): Text JNI_OnLoad enter!!
D/SPen_Library(10039): Text JNI_OnLoad Success
D/SPen_Library(10039): FontManager JNI_OnLoad enter!!
D/SPen_Library(10039): FontManager JNI_OnLoad Success
D/SPen_Library(10039): CapturePage JNI_OnLoad enter!!
D/SPen_Library(10039): CapturePage JNI_OnLoad Success
D/SPen_Library(10039): Multi JNI_OnLoad enter!!
,D/SPen_Library(10039): Multi JNI_OnLoad Success
D/SPen_Library(10039): Draw Engine JNI_OnLoad Success
,D/SPen_Library(10039): Brush JNI_OnLoad enter!!
,D/SPen_Library(10039): Brush JNI_OnLoad Success
D/TimaKeyStoreProvider(10057): TimaSignature is unavailable
,D/ActivityThread(10057): Added TimaKeyStore provider
D/SPen_Library(10039): ChineseBrush JNI_OnLoad enter!!
,D/SPen_Library(10039): ChineseBrush JNI_OnLoad Success
,D/SPen_Library(10039): InkPen JNI_OnLoad enter!!
,D/SPen_Library(10039): InkPen JNI_OnLoad Success
,D/SPen_Library(10039): Marker JNI_OnLoad enter!!
,D/SPen_Library(10039): Marker JNI_OnLoad Success
,D/SPen_Library(10039): Pencil JNI_OnLoad enter!!
,D/SPen_Library(10039): Pencil JNI_OnLoad Success
,D/SPen_Library(10039): NativePen JNI_OnLoad enter!!
D/SPen_Library(10039): NativePen JNI_OnLoad Success
,D/SPen_Library(10039): MontblancFountainPen JNI_OnLoad enter!!
,D/SPen_Library(10039): MontblancFountainPen JNI_OnLoad Success
,D/SPen_Library(10039): MontblancCalligraphyPen JNI_OnLoad enter!!
,D/SPen_Library(10039): MontblancCalligraphyPen JNI_OnLoad Success
,D/SPen_Library(10039): MagicPen JNI_OnLoad enter!!
D/SPen_Library(10039): MagicPen JNI_OnLoad Success
,D/SPen_Library(10039): ObliquePen JNI_OnLoad enter!!
,D/SPen_Library(10039): ObliquePen JNI_OnLoad Success
,D/SPen_Library(10039): FountainPen JNI_OnLoad enter!!
D/ResourcesManager(10057): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/SPen_Library(10039): FountainPen JNI_OnLoad Success
D/Spen    (10039): SpenSdk Libraries are loaded.
D/Init_SPenSdk_Jni(10039): SPenSdk_init2
D/Init_SPenSdk(10039): Init - screen_width = 1440, screen_height = 2560, maxCacheSize = 100 M
,D/Init_SPenSdk(10039): Total S Pen SDK Directory Size = 0
D/Spen    (10039): initialize complete
W/linker  (10039): libSPenImageFilterLibs.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,W/ResourcesManager(10057): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(10057): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager(10057): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
D/ResourcesManager(10039): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10074): MountEmulatedStorage()
E/Zygote  (10074): v2
I/libpersona(10074): KNOX_SDCARD checking this for 10183
I/libpersona(10074): KNOX_SDCARD not a persona
,I/SELinux (10074): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10074): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3521): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=10074 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
,E/SELinux (10074): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Killing 9427:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(10074): TimaSignature is unavailable
,D/ActivityThread(10074): Added TimaKeyStore provider
,D/SNoteProvider(10057): onCreate enableSnoteSync = true
,D/ResourcesManager(10074): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,D/SNoteProvider(10057): ===query=== 
,V/Common  (10057): getScreenSize 1440 2560
,E/SQLiteLog(10074): (284) automatic index on shooting_modes(title_id)
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10092): MountEmulatedStorage()
I/libpersona(10092): KNOX_SDCARD checking this for 10190
E/Zygote  (10092): v2
I/libpersona(10092): KNOX_SDCARD not a persona
,I/SELinux (10092): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10092): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3521): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=10092 uid=10190 gids={50190, 9997} abi=armeabi-v7a
,E/SELinux (10092): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Killing 9524:com.samsung.android.app.vrsetupwizardstub/u0a63 (adj 15): bgCount ##31
,I/System.out( 9875): P[5]_NetworkDispatch1 calls detatch()
,D/SNoteProvider(10057): ===query=== 
,I/ActivityManager( 3521): Killing 9365:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(10092): TimaSignature is unavailable
,D/ActivityThread(10092): Added TimaKeyStore provider
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/BroadcastQueue( 3521): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{1f2388f0 u0 ReceiverList{39a0fd33 9875 com.facebook.appmanager/10110/u0 remote:25445ca2}}
,W/BroadcastQueue( 3521): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{1f2388f0 u0 ReceiverList{39a0fd33 9875 com.facebook.appmanager/10110/u0 remote:25445ca2}}
,D/ResourcesManager(10092): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
,I/TapandpayWidget:TanpandpayAppWidgetProvider(10092): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(10092): onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
,I/TapandpayWidget:Utils(10092): Clear T&P info.
,D/TapandpayWidget:TanpandpayAppWidgetProvider(10092): Widget is not attached.
W/BroadcastQueue( 3521): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{1d78ddfa u0 ReceiverList{2695b825 9875 com.facebook.appmanager/10110/u0 remote:1e50441c}}
,I/splitIntent( 3521): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 3521): Killing 9109:com.google.android.partnersetup/u0a17 (adj 13): bgCount ##31
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10116): MountEmulatedStorage()
E/Zygote  (10116): v2
I/libpersona(10116): KNOX_SDCARD checking this for 10135
I/libpersona(10116): KNOX_SDCARD not a persona
,I/SELinux (10116): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10116): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3521): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver: pid=10116 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (10116): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(10116): TimaSignature is unavailable
,D/ActivityThread(10116): Added TimaKeyStore provider
,D/ResourcesManager(10116): creating new AssetManager and set to /system/app/Music2/Music2.apk
,I/MusicStore(10116): Database version: 104
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ResourcesManager(10116): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,W/ResourcesManager(10116): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(10116): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/CalendarProvider2( 9892): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,V/JNIHelp (10116): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(10116): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (10116): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3e75a609: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(10116): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(10116): GMSCore installation verified
,I/ConfigStore(10116): Config Database version: 1
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10116): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10116): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9875): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
W/ContextImpl(10116): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9875): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,D/WifiDisplayAdapter( 3521): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3521): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3521): getStreamVolume 3 index 0
,I/MediaRouter(10116): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/NetworkMonitor(10116): type=WIFI subType= reason=null isConnected=true
,D/WifiDisplayAdapter( 3521): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/ActivityManager( 3521): Killing 8268:com.android.mms/u0a52 (adj 13): bgCount ##31
,D/WearableService( 4659): callingUid 10014, callindPid: 4659
,I/NetworkMonitor(10116): type=WIFI subType= reason=null isConnected=true
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/CountryDetector( 3521): No listener is left
E/Zygote  (10149): MountEmulatedStorage()
I/libpersona(10149): KNOX_SDCARD checking this for 10122
E/Zygote  (10149): v2
I/libpersona(10149): KNOX_SDCARD not a persona
,I/SELinux (10149): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10149): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10149): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=10149 uid=10122 gids={50122, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider(10149): TimaSignature is unavailable
,D/ActivityThread(10149): Added TimaKeyStore provider
,I/MusicLeanback(10116): Stop autocaching.
,I/MusicLeanback(10116): Stop autocaching.
,I/MusicLeanback(10116): Conditions not met for autocaching.
I/MusicLeanback(10116): Stop autocaching.
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/MusicLeanback(10116): Stop autocaching.
,I/MusicLeanback(10116): Stop autocaching.
,D/ResourcesManager(10149): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,W/GoogleHttpClient(10116): Failed to load SSLCertificateSocketFactory from package
I/GoogleHttpClient(10116): Falling back to old SSLCertificateSocketFactory
I/GHttpClientFactory(10116): Using the GMSCore's GoogleHttpClient
,D/WearableClient(10116): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(10116): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(10116): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(10116): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(10116): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(10116): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(10116): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@2fc51a0b that was originally bound here
E/ActivityThread(10116): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@2fc51a0b that was originally bound here
E/ActivityThread(10116): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(10116): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(10116): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(10116): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(10116): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(10116): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(10116): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(10116): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(10116): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(10116): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(10116): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(10116): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(10116): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(10116): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(10116): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(10116): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(10116): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(10116): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(10116): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(10116): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(10116): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(10116): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(10116): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(10116): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(10116): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/ActivityManager( 3521): Killing 9559:com.sec.android.service.health/u0a19 (adj 13): bgCount ##31
,W/ActivityManager( 3521): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/ActivityThread(10149): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
,W/ActivityManager( 3521): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/Gmail   (10149): getAccountsCursor
,V/GLSActivity( 4659): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4659): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4659): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GAV2    (10149): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager( 3521): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 3521): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,W/ActivityManager( 3521): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,I/Gmail   (10149): Observing account changes for notifications
,W/ActivityManager( 3521): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 3521): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/Gmail   (10149): Error finding the version of the Email provider.....
E/Gmail   (10149): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   (10149): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:137)
E/Gmail   (10149): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
E/Gmail   (10149): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   (10149): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   (10149): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   (10149): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   (10149): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration(10149): We do not support migrating this version of the Email provider.
,I/Gmail   (10149): getAccountsCursor
,E/CscFactoryReceiver( 3979): onReceive android.intent.action.MEDIA_SCANNER_FINISHED
D/CscFactoryReceiver( 3979): Media DB Scanner finished.
D/CscFactoryReceiver( 3979): start service to Set Ringtone
,V/GLSActivity( 4659): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/CscFactoryReceiver( 3979): start service to Set Notification
,V/GLSActivity( 4659): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/CscFactoryReceiver( 3979): start service to Set Alarmtone
,V/GLSActivity( 4659): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ActivityManager( 3521): Killing 9575:com.sec.android.app.myfiles/u0a53 (adj 13): bgCount ##31
,D/CscUpdateService( 3979): onStart
E/CscUpdateService( 3979): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 3979): only ringtone update
,D/CscUpdateService( 3979): onStart
E/CscUpdateService( 3979): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 3979): only notification update
,E/CscParser( 3979): update(): xml file exist
D/CscUpdateService( 3979): onStart
E/CscUpdateService( 3979): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 3979): only alarmtone update
,E/CscParser( 3979): update(): xml file exist
,E/CscParser( 3979): update(): xml file exist
,W/CSCSettings( 3979): Setting Ringtones (type) : 2
E/SQLiteLog(10149): (283) recovered 52 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
D/CscParser( 3979): MessageTone: null
W/CSCSettings( 3979): 1. Tag_Str: null
,W/CSCSettings( 3979): Setting Ringtones (type) : 4
D/CscParser( 3979): AlarmTone: null
W/CSCSettings( 3979): 1. Tag_Str: null
,W/CSCSettings( 3979): Setting Ringtones (type) : 1
,D/CscParser( 3979): RingTone: null
W/CSCSettings( 3979): 1. Tag_Str: null
,I/Gmail   (10149): notifyAccountChanged
,I/Gmail   (10149): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   (10149): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/Gmail   (10149): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   (10149): calculateUnknownSyncRationalesAndPurgeInBackground: running
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/art     ( 3521): Explicit concurrent mark sweep GC freed 17571(1141KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 48MB/64MB, paused 1.212ms total 72.258ms
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,I/Gmail   (10149): getAccountsCursor
,E/Zygote  (10200): MountEmulatedStorage()
I/libpersona(10200): KNOX_SDCARD checking this for 10004
E/Zygote  (10200): v2
I/libpersona(10200): KNOX_SDCARD not a persona
,I/SELinux (10200): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10200): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.samsung.dcm:DCMService for broadcast com.samsung.dcm/.framework.broadcastreceivers.SystemBroadcastReceiver$DCMBroadcastReceiver: pid=10200 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux (10200): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/GLSActivity( 4659): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/TimaKeyStoreProvider(10200): TimaSignature is unavailable
,D/ActivityThread(10200): Added TimaKeyStore provider
,D/ResourcesManager(10200): creating new AssetManager and set to /system/priv-app/DCMProvider/DCMProvider.apk
,D/ResourcesManager( 6671): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/Gmail   (10149): getAccountsCursor
,V/GLSActivity( 4659): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DCMProvider(10200): [#DCM#] onCreate this Instance = com.sec.dcm.provider.DCMProvider@3f882b02 Provider Ref Count:1
,I/DCMConfig(10200): [#DCM#] initializeTransport.SystemBroadcastReceiver  1 ms
,I/StorageController(10200): [#DCM#]  state through storage volume =  mounted
,I/StorageController(10200): [#DCM#]  storageId =  65537 removable = false path = /storage/emulated/0 state = mounted subsystem = fuse
I/StorageController(10200): [#DCM#]  state through storage volume =  removed
,I/StorageController(10200): [#DCM#]  storageId =  131073 removable = true path = /storage/extSdCard state = removed subsystem = sd
I/StorageController(10200): [#DCM#]  state through storage volume =  unmounted
I/StorageController(10200): [#DCM#]  storageId =  196609 removable = false path = /storage/Private state = unmounted subsystem = private
I/StorageController(10200): [#DCM#]  state through storage volume =  removed
,I/StorageController(10200): [#DCM#]  storageId =  262145 removable = true path = /storage/UsbDriveA state = removed subsystem = usb
I/StorageController(10200): [#DCM#]  state through storage volume =  removed
I/StorageController(10200): [#DCM#]  storageId =  327681 removable = true path = /storage/UsbDriveB state = removed subsystem = usb
I/StorageController(10200): [#DCM#]  state through storage volume =  removed
,I/StorageController(10200): [#DCM#]  storageId =  393217 removable = true path = /storage/UsbDriveC state = removed subsystem = usb
I/StorageController(10200): [#DCM#]  state through storage volume =  removed
I/StorageController(10200): [#DCM#]  storageId =  458753 removable = true path = /storage/UsbDriveD state = removed subsystem = usb
I/StorageController(10200): [#DCM#]  state through storage volume =  removed
,I/StorageController(10200): [#DCM#]  storageId =  524289 removable = true path = /storage/UsbDriveE state = removed subsystem = usb
I/StorageController(10200): [#DCM#]  state through storage volume =  removed
I/StorageController(10200): [#DCM#]  storageId =  589825 removable = true path = /storage/UsbDriveF state = removed subsystem = usb
,I/DCMPolicyManager(10200): [#DCM#] setCriticalStateFromSystem screenOn =  true high siop = false camera running = false
,I/DCMPolicyManager(10200): [#DCM#] opening file DCMRules.txt 
,I/DCMConfig(10200): [#DCM#] initializeTransport.DCMPolicyManager  12 ms
,I/DCMConfig(10200): [#DCM#] initializeTransport.MediaManager  13 ms
,I/CheckinService( 6671): Done disabling old GoogleServicesFramework version
,I/DCMConfig(10200): [#DCM#] initializeTransport.DCMNRTManager  17 ms
,I/DCMConfig(10200): [#DCM#] No of CPU Core 8
I/DCMConfig(10200): [#DCM#] initializeTransport took  17 ms
I/DCMProvider(10200): [#DCM#] onCreate end 
,I/DCMNRTManager(10200): [#DCM#] intialize 
,I/SystemBroadcastReceiver(10200): [#DCM#] [DCM_Performance] onReceive completed in time  12 microsec. 
I/SystemBroadcastReceiver(10200): [#DCM#] [DCM_Performance] onReceive completed in time  8 microsec. 
,I/SystemBroadcastReceiver(10200): [#DCM#] Calling notifyListeners. 
,I/StorageController(10200): [#DCM#]  state through storage volume =  mounted
I/StorageController(10200): [#DCM#]  storageId =  65537 removable = false path = /storage/emulated/0 state = mounted subsystem = fuse
I/StorageController(10200): [#DCM#]  state through storage volume =  removed
,I/StorageController(10200): [#DCM#]  storageId =  131073 removable = true path = /storage/extSdCard state = removed subsystem = sd
I/StorageController(10200): [#DCM#]  state through storage volume =  unmounted
,I/StorageController(10200): [#DCM#]  storageId =  196609 removable = false path = /storage/Private state = unmounted subsystem = private
I/StorageController(10200): [#DCM#]  state through storage volume =  removed
,I/StorageController(10200): [#DCM#]  storageId =  262145 removable = true path = /storage/UsbDriveA state = removed subsystem = usb
I/StorageController(10200): [#DCM#]  state through storage volume =  removed
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
I/StorageController(10200): [#DCM#]  storageId =  327681 removable = true path = /storage/UsbDriveB state = removed subsystem = usb
I/StorageController(10200): [#DCM#]  state through storage volume =  removed
,I/StorageController(10200): [#DCM#]  storageId =  393217 removable = true path = /storage/UsbDriveC state = removed subsystem = usb
I/StorageController(10200): [#DCM#]  state through storage volume =  removed
,I/StorageController(10200): [#DCM#]  storageId =  458753 removable = true path = /storage/UsbDriveD state = removed subsystem = usb
I/StorageController(10200): [#DCM#]  state through storage volume =  removed
,I/StorageController(10200): [#DCM#]  storageId =  524289 removable = true path = /storage/UsbDriveE state = removed subsystem = usb
I/StorageController(10200): [#DCM#]  state through storage volume =  removed
I/StorageController(10200): [#DCM#]  storageId =  589825 removable = true path = /storage/UsbDriveF state = removed subsystem = usb
I/StorageController(10200): [#DCM#] Bundle =  Bundle[{path=file:///storage/emulated/0, CleanBuffer=false}]
I/StorageController(10200): [#DCM#] Sending intent for OS Upgrade for Phone contents 
I/DCMUtilities(10200): [#DCM#] Scan Completed:Check if lucene upgrade is required for OS upgrade 
,I/WriterFactory(10200): [#DCM#] verifyLuceneDB ++ 
,I/SystemUtils(10200): [#DCM#] pref_value getOSUpgradeSharedPrefForMedia is = true
I/SystemUtils(10200): [#DCM#] setOSUpgradeSharedPrefForMedia set as  true
I/DCMUtilities(10200): [#DCM#] OSUpgrade not required 
I/SystemBroadcastReceiver(10200): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager(10200): [#DCM#] onReceive action = EVENT_SIOP
I/SystemBroadcastReceiver(10200): [#DCM#] Calling notifyListeners. 
I/SystemBroadcastReceiver(10200): [#DCM#] No one is registered with Event Id EVENT_NETWORK_CHANGED
,I/WriterFactory(10200): [#DCM#] verifyLuceneDB OK breaking 
I/WriterFactory(10200): [#DCM#] verifyLuceneDB OK -- 
I/libpersona(10219): KNOX_SDCARD checking this for 10007
,I/WriterFactory(10200): [#DCM#] TAXO in mode CREATE_OR_APPEND
I/libpersona(10219): KNOX_SDCARD not a persona
E/Zygote  (10219): MountEmulatedStorage()
E/Zygote  (10219): v2
I/SELinux (10219): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10219): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10219): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.samsung.indexservice for broadcast com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentBroadcastReceiver: pid=10219 uid=10007 gids={50007, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3521): Killing 9590:com.sec.pcw.device/1000 (adj 13): bgCount ##31,
,I/WriterFactory(10200): [#DCM#] Before facet 
I/WriterFactory(10200): [#DCM#] After facet=!null ? true
,I/DCMUtilities(10200): [#DCM#] isCommitOk; kKeyOnCommit = true
I/DCMController(10200): [#DCM#] isCommitOk:  true, isIntentFinished: trueisRebuildDone = true
,I/DCMConfig(10200): [#DCM#] setSuccessState =  true
,D/TimaKeyStoreProvider(10219): TimaSignature is unavailable
,D/ActivityThread(10219): Added TimaKeyStore provider
,D/ResourcesManager(10219): creating new AssetManager and set to /system/priv-app/DocumentService/DocumentService.apk
,I/ThumbnailProvider(10219): ThumbnailProvider onCreate()
,I/DocumentBroadcastReceiver(10219): DocumentService onReceive android.intent.action.MEDIA_SCANNER_FINISHED
,I/BroadcastProcessorService(10219): [START] processBroadcastIntent ...
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,I/BroadcastProcessorService(10219): DocumentService onHandleIntent ACTION_MEDIA_SCANNER_FINISHED
,E/Zygote  (10238): MountEmulatedStorage()
I/libpersona(10238): KNOX_SDCARD checking this for 10044
E/Zygote  (10238): v2
I/libpersona(10238): KNOX_SDCARD not a persona
,I/SELinux (10238): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10238): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10238): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.sec.android.app.music:service for broadcast com.sec.android.app.music/.appwidget.MusicAppWidgetProvider: pid=10238 uid=10044 gids={50044, 9997, 3003, 3002, 1028, 1015, 1023, 1007} abi=armeabi-v7a
,I/SystemInfo(10219): [SYSTEM STATUS] Battery and Storage levels are OK:
I/BroadcastProcessorService(10219): [CURRENT_STATE] DocumentService state: SERVICE_NOT_STARTED
,I/BroadcastProcessorService(10219): [START] DocumentService startDocumentService
,I/DocumentService(10219): DocumentService onCreate ... service
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10219): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10219): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
D/TimaKeyStoreProvider(10238): TimaSignature is unavailable
,D/ActivityThread(10238): Added TimaKeyStore provider
,D/ResourcesManager(10238): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager(10238): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(10238): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(10238): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
E/SystemInfo(10219): [SIOP LEVEL] : -2
W/ResourcesManager(10238): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(10238): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10238): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,I/DocumentService(10219): [BEGIN SYNC] DocumentService beginIndexing :17
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10219): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,I/DocumentServiceUtils(10219):  Total PDF: 0 PDF size: 0 OtherFiles Size: 0
E/SystemInfo(10219): DocumentService [SIOP LEVEL] changed to -2
E/SystemInfo(10219): DocumentService Resume indexing as [SIOP LEVEL] changed to < 2
,I/SystemInfo(10219): [SYSTEM STATUS] Battery and Storage levels are OK:
I/DocumentService(10219): [BEGIN SYNC] DocumentService beginIndexing :16
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
W/ContextImpl(10219): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10257): MountEmulatedStorage()
I/libpersona(10257): KNOX_SDCARD checking this for 10050
E/Zygote  (10257): v2
I/libpersona(10257): KNOX_SDCARD not a persona
,I/SELinux (10257): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10257): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10257): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=10257 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/ActivityManager( 3521): Killing 9348:com.samsung.android.app.galaxyfinder/u0a35 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(10257): TimaSignature is unavailable
,D/ActivityThread(10257): Added TimaKeyStore provider
,I/SystemInfo(10219): [SYSTEM STATUS] Battery and Storage levels are OK:
I/DocumentService(10219): [VERIFY] verifyThumbnailImages
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/ContextImpl(10219): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,I/DocumentService(10219): [STOP DOCUMENTSERVICE] Attempting to stop the Service
E/DocumentService(10219): [THUMBNAIL AND INDEX] Thumbnail and indexing is Completed Total Time taken for both :53
E/DocumentService(10219): [THUMBNAIL] Total Time taken for each file :0
E/        (10219): [INDEX] Total time taken for each file :0
,I/DocumentService(10219): DocumentService onDestroy start
,I/DocumentService(10219): DocumentService onDestroy end
,I/ActivityManager( 3521): Killing 6929:com.sec.android.app.shealth/u0a36 (adj 13): bgCount ##31
,D/ResourcesManager(10257): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,I/DocumentService(10219): DocumentService cleanupEverything start
,W/ResourcesManager(10257): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(10257): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/IndexParserThreadsManager(10219): InterruptedException: null
W/ResourcesManager(10257): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(10257): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10257): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(10257): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/SystemInfo(10219): [SYSTEM STATUS] Battery and Storage levels are OK:
W/ResourcesManager(10257): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
I/DocumentService(10219): DocumentService cleanupEverything end
W/ResourcesManager(10257): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/Process (10219): Sending signal. PID: 10219 SIG: 9
,I/ActivityManager( 3521): Process com.samsung.indexservice (pid 10219)(adj 9) has died(97,1256)
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PackageManager( 3521): findPreferredActivity: No PreferredActivities set
,D/NearbySource(10257): Nearby Source Create!
,D/NearbyContext(10257): Nearby Context Create!
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10257): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource(10257): Samsung link source created
,D/ContactProvider(10257): getAllContactInfoList Start
,D/WifiDisplayAdapter( 3521): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3521): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/GalleryCacheReady(10257): Receive action.ACTION_MEDIA_SCANNER_FINISHED
,D/GalleryCacheReady(10257): handleMeidaScanFinish()
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10257): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/ContextImpl(10257): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
W/ContextImpl(10257): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/ContextImpl(10257): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,D/FaceInterface(10257): requestFaceScan() is called.
,I/FaceInterface(10257): startFaceScan() : waiting 5 sec
,W/LocalSuggestAlbumData(10257): query fail: 
W/LocalSuggestAlbumData(10257): query fail: 
,D/BootupListener( 3979): ACTION_DRIVELINK
,D/SettingsProvider( 3521): name = drivelink_navigation
D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
D/SettingsProvider( 3521): selectionArgs: 1001
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
D/BootupListener( 3979): NAVI : com.here.app.maps
D/SettingsProvider( 3521): name = internet_call_settings_visibility
D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
D/SettingsProvider( 3521): selectionArgs: 1001
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
D/BootupListener( 3979): intent.getAction() = com.sec.android.automotive.drivelink.NAVIGATION_PACKAGE_NAME
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10280): MountEmulatedStorage()
E/Zygote  (10280): v2
I/libpersona(10280): KNOX_SDCARD checking this for 10125
,I/libpersona(10280): KNOX_SDCARD not a persona
I/SELinux (10280): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10280): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10280): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=10280 uid=10125 gids={50125, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,D/ContactProvider(10257): getAllContactInfoList End
I/syncContacts(10257): thread: 1373, sync time = 59
,D/TimaKeyStoreProvider(10280): TimaSignature is unavailable
,D/ActivityThread(10280): Added TimaKeyStore provider
,D/ResourcesManager(10280): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(10280): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,I/MediaStoreImporter(10116): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/Babel   (10280): MmsConfig: mnc/mcc: 0/0
I/Babel   (10280): MmsConfig.loadMmsSettings
,I/Babel   (10280): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N910C, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N910C.xml
I/Babel   (10280): MmsConfig.loadFromDatabase
,D/ResourcesManager(10280): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,E/Babel   (10280): canonicalizeMccMnc: invalid mccmnc 
I/Babel   (10280): MmsConfig.loadFromResources
,E/Babel   (10280): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   (10280): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N910C, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N910C.xml
W/AudioCapabilities(10280): Unsupported mime audio/mpeg-L1
W/AudioCapabilities(10280): Unsupported mime audio/mpeg-L2
W/AudioCapabilities(10280): Unsupported mime audio/x-ms-wma
W/AudioCapabilities(10280): Unsupported mime audio/x-ima
,W/VideoCapabilities(10280): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities(10280): Unsupported mime video/wvc1
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/VideoCapabilities(10280): Unsupported mime video/x-ms-wmv
,W/Settings(10280): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,W/VideoCapabilities(10280): Unrecognized profile/level 32768/2 for video/mp4v-es
,W/VideoCapabilities(10280): Unsupported mime video/wvc1
,W/VideoCapabilities(10280): Unsupported mime video/x-ms-wmv
,W/VideoCapabilities(10280): Unsupported mime video/x-ms-wmv7
,W/VideoCapabilities(10280): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities(10280): Unsupported mime video/sorenson
,W/VideoCapabilities(10280): Unsupported mime video/mp43
,W/AudioCapabilities(10280): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities(10280): Unsupported mime audio/mpeg-L2
,W/VideoCapabilities(10280): Unrecognized profile/level 32768/2 for video/mp4v-es
,D/Widget  (10039): onReceive com.sec.android.snote.widget.ACTION_NOTE_UPDATE
,D/Widget  (10039): onReceive android.appwidget.action.APPWIDGET_UPDATE
,D/Widget  (10039): widgetUpdate 5
,D/RCPManagerService( 3521): exchangeData() failure , invalid userId
,I/VideoCapabilities(10280): Unsupported profile 4 for video/mp4v-es
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10313): MountEmulatedStorage()
I/libpersona(10313): KNOX_SDCARD checking this for 10022
E/Zygote  (10313): v2
I/libpersona(10313): KNOX_SDCARD not a persona
I/SELinux (10313): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10313): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10313): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=10313 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3521): Killing 9606:com.policydm/1000 (adj 13): bgCount ##31
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 8736(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 555us total 11.995ms
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 570us total 8.985ms
,D/TimaKeyStoreProvider(10313): TimaSignature is unavailable
,D/ActivityThread(10313): Added TimaKeyStore provider
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 427us total 9.668ms
,D/ResourcesManager(10313): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
,W/ResourcesManager(10313): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10313): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10313): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/LocationWidgetApplication(10313): onCreate() : start
,D/LocationWidgetApplication(10313): countryCode = POLAND
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/LocationWidgetUtils(10313): getUpcommingInstances() start: 1457945498296, end: 1458514799999
D/LocationWidgetUtils(10313): getUpcommingInstances() DB begin time >= start:1457945498296, DB begin time <= end:1458514799999
,E/Zygote  (10333): MountEmulatedStorage()
I/libpersona(10333): KNOX_SDCARD checking this for 10163
E/Zygote  (10333): v2
I/libpersona(10333): KNOX_SDCARD not a persona
,I/SELinux (10333): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10333): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=10333 uid=10163 gids={50163, 9997} abi=armeabi-v7a
E/SELinux (10333): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Killing 8499:com.android.settings/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(10333): TimaSignature is unavailable
,D/ActivityThread(10333): Added TimaKeyStore provider
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ResourcesManager(10333): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG_Transparent/SPlannerWidget_OS_UPG_Transparent.apk
,W/ResourcesManager(10333): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10333): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Zygote  (10348): MountEmulatedStorage()
I/libpersona(10348): KNOX_SDCARD checking this for 10164
E/Zygote  (10348): v2
I/libpersona(10348): KNOX_SDCARD not a persona
,I/SELinux (10348): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10348): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10348): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=10348 uid=10164 gids={50164, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/ActivityManager( 3521): Killing 9179:com.sec.spp.push/u0a39 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(10348): TimaSignature is unavailable
,D/ActivityThread(10348): Added TimaKeyStore provider
,D/ResourcesManager(10348): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(10348): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(10348): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10348): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10348): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/LocationManagerService( 3521): getProviders()=[]
D/LocationManagerService( 3521): getProviders()=[passive]
D/LocationManagerService( 3521): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
,D/LWLocationManager(10313): mPrivacy is null
,W/ContextImpl(10313): Implicit intents with startService are not safe: Intent { act=com.samsung.android.providers.context.privacy.IPrivacyManager } android.content.ContextWrapper.bindService:559 com.samsung.android.providers.context.privacy.PrivacyManager.bindService:394 com.sec.android.widgetapp.locationwidget.data.LWLocationManager.bindPrivacyService:150 
,D/ContextFramework:PrivacyManager(10313): Service for PrivacyManager is connected
,I/ActivityManager( 3521): Killing 9623:com.sec.android.app.soundalive/u0a59 (adj 13): bgCount ##31
,D/LWLocationManager(10313): Privacy service : STATUS_PLACE
D/LWLocationManager(10313): updateLocationStatus()
,I/LocationWidgetFuctionData(10313): readDB
,I/LocationWidgetFuctionData(10313): selectedAppSize: 3
I/LocationWidgetFuctionData(10313): configPlaceList aroundMeItems
,I/LocationWidgetFuctionData(10313): selectedAppSize: 3
,I/LocationWidgetFuctionData(10313): selectedAppSize: 3
,I/LocationWidgetFuctionData(10313): selectedAppSize: 3
,I/LocationWidgetFuctionData(10313): selectedAppSize: 3
,E/LWLocationManager(10313): findLocationType() : cursor_location.moveToFirst() return false!!
,D/LWLocationManager(10313): Intent broadcast sent with action: com.sec.android.widgetapp.locationwidget.LOCATION_SOURCES_UPDATED
D/LWLocationManager(10313): setShouldUpdateLocationId
D/LWLocationManager(10313): setShouldUpdateLocationId return false
D/LWLocationManager(10313): setShouldUpdateLocationId
D/LWLocationManager(10313): setShouldUpdateLocationId return false
D/LWLocationManager(10313): setShouldUpdateLocationId
D/LWLocationManager(10313): setShouldUpdateLocationId return false
D/LWLocationManager(10313): updateDeviceLocation() : lastDeviceLocationId = -100 mDeviceLocationId: -100 cocktailId: -1
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/GAV2    ( 9442): Thread[GAThread,5,main]: No campaign data found.
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/ActivityManager( 3521): Killing 8911:com.samsung.android.app.assistantmenu/1000 (adj 13): bgCount ##31
,W/SQLiteConnectionPool( 6671): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,I/ActivityManager( 3521): Waited long enough for: ServiceRecord{22af215f u0 tv.peel.smartremote/tv.peel.samsung.widget.service.WidgetTimerService}
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AcmsKeyStoreHelper(10021):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper(10021): Key Store exist
I/AcmsKeyStoreHelper(10021): Hence loading the keystore file
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AcmsKeyStoreHelper(10021):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr(10021): getKeyStoreForApplication success 
D/AcmsCore(10021): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor(10021): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(10021): Decrementing - Counter value: 1
D/AcmsCore(10021): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore(10021): This is NOT a valid MirrorLink app
D/AcmsCore(10021): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor(10021): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(10021): Decrementing - Counter value: 0
D/AcmsServiceMonitor(10021): Counter value is 0: Stopping ACMS service
D/AcmsServiceMonitor(10021): getSvcCounter - Counter value: 0
D/AcmsService(10021): Enter onDestroy
I/AcmsService(10021): cleanUp(): inside service clean up
D/AcmsCore(10021): AcmsCore: inside DeInit
D/AcmsCore(10021): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr(10021): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr(10021): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper(10021): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface(10021): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor(10021): getSvcCounter - Counter value: 0
D/AcmsService(10021): killing acms process
I/Process (10021): Sending signal. PID: 10021 SIG: 9
,I/ActivityManager( 3521): Process ACMS.Process (pid 10021)(adj 0) has died(97,1256)
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/WifiStateMachine( 3521): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3521): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine( 3521): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/fb4a(:<default>):UserScope( 9710): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,I/art     ( 9710): Thread[1,tid=9710,WaitingForJniOnLoad,Thread*=0xb4e08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/data/com.facebook.katana/lib-xzs/libomnistore.so"
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/GAV2    ( 9540): Thread[GAThread,5,main]: No campaign data found.
,W/art     ( 9710): JNI RegisterNativeMethods: attempt to register 0 native methods for com.facebook.compactdisk.DiskCache
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching, sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
D/StatusBar.NetworkController( 3690): applyOpen
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching, sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/BroadcastQueue( 3521): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{3a84af0b u0 ReceiverList{1872ceda 9710 com.facebook.katana/10114/u0 remote:2d2f6085}}
,W/BroadcastQueue( 3521): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{3a84af0b u0 ReceiverList{1872ceda 9710 com.facebook.katana/10114/u0 remote:2d2f6085}}
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/GcOptimizer( 9710): Configure for next cold start: disable
,W/BroadcastQueue( 3521): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{31e1b3d u0 ReceiverList{3f6e6494 9710 com.facebook.katana/10114/u0 remote:204d30e7}}
,W/fb4a(:<default>):UserScope( 9710): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QuickExperimentControllerImpl( 9710): Exposure of experiment com.facebook.placetips.gpscore.abtest.GeneratedPlaceTipsGpsMainExperiment@2e691a9 occurred when no user was logged in
W/fb4a(:<default>):QuickExperimentControllerImpl( 9710): Exposure of experiment com.facebook.placetips.gpscore.abtest.GeneratedPlaceTipsGpsPassiveListenerExperiment@e43b32e occurred when no user was logged in
,W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/art     ( 4659): Explicit concurrent mark sweep GC freed 32204(1924KB) AllocSpace objects, 12(192KB) LOS objects, 35% free, 29MB/45MB, paused 1.670ms total 52.228ms
,W/fb4a(:<default>):QuickExperimentControllerImpl( 9710): Exposure of experiment com.facebook.inject.init.GeneratedFbInjectorWeakrefExperiment@d1a1889 occurred when no user was logged in
,W/fb4a(:<default>):UserScope( 9710): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10410): MountEmulatedStorage()
E/Zygote  (10410): v2
I/libpersona(10410): KNOX_SDCARD checking this for 10082
I/libpersona(10410): KNOX_SDCARD not a persona
,I/SELinux (10410): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10410): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=10410 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,E/SELinux (10410): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(10410): TimaSignature is unavailable
,D/ActivityThread(10410): Added TimaKeyStore provider
,D/ResourcesManager(10410): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/BadgeProvider(10410): onCreate
D/BadgeProvider(10410): DatabaseHelper
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/EnterpriseController( 2849): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2849): getNetworkForDns: using netid 502 for uid 10110
,D/BadgeProvider(10410): sendNotify entered. [uri] : content://com.sec.badge/apps
D/BadgeProvider(10410): sendNotify, [notify] : null
D/BadgeProvider(10410): update, [uri] : content://com.sec.badge/apps
D/BadgeProvider(10410): update, [BadgeCount] : badgecount=0
D/BadgeProvider(10410): update, [UpdateCount] : 1
,D/Launcher.Model( 4003): reloadBadges entered.
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.katana/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9710): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.katana/files
,E/Vold    ( 2830): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.katana/files/
W/Vold    ( 2830): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9710): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.katana/files
,W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QuickExperimentControllerImpl( 9710): Exposure of experiment com.facebook.imagepipeline.abtest.GeneratedDecodeFileDescriptorExperiment@1229d450 occurred when no user was logged in
,W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,I/System.out( 9875): P[5]_NetworkDispatch2 calls detatch()
,I/ActivityManager( 3521): Killing 9688:com.facebook.system/u0a10 (adj 13): bgCount ##31
,V/analytics4a( 9710): JNI_OnLoad called
V/analytics4a( 9710): JNI_OnLoad complete
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/fb4a(:<default>):UserScope( 9710): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,I/System.out( 9875): P[5]_NetworkDispatch3 calls detatch()
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9710): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/art     ( 3521): Explicit concurrent mark sweep GC freed 19850(1245KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 48MB/64MB, paused 1.842ms total 124.572ms
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/AlarmManager( 3521): waitForAlarm result :4
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/WearableClient(10116): WearableClientImpl.onPostInitHandler: done
,I/MusicLeanback(10116): Conditions not met for autocaching.
I/MusicLeanback(10116): Stop autocaching.
D/WearableClient(10116): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(10116): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(10116): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/WearableClient(10116): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(10116): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,I/GAV2    (10149): Thread[GAThread,5,main]: No campaign data found.
,V/AlarmManager( 3521): waitForAlarm result :4
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/iu.UploadsManager( 6671): End new media; added: 0, uploading: 0, time: 40 ms
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/WifiStateMachine( 3521): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3521): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3521): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/FaceInterface(10257): startFaceScan() : going on
D/FaceInterface(10257): startFaceScan() is called.
,D/ContentApp( 5431): startScan() is called.
,D/FaceValue( 5431): mSleepTime: 800
D/FaceValue( 5431): mMaxThreadNum: 2
,D/ContentApp( 5431): startScan() is end.
,D/ContentApp( 5431): face_restore FINISHED_TYPE: 3
D/FaceScanner( 5431): isNeedToRestore : start
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/SSRM:n  ( 3521): SIOP:: AP = 340, PST = 340, CUR = -692
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/PackageManager( 3521): [MSG] MCS_UNBIND
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/ActivityManager( 3521): Killing 9474:com.android.vending/u0a31 (adj 13): bgCount ##31
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:2, health:2, present:true, voltage: 4386, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:-456, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:112
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QuickExperimentControllerImpl( 9710): Exposure of experiment com.facebook.http.qe.LigerProxyQuickExperiment@12af9cd2 occurred when no user was logged in
W/fb4a(:<default>):QuickExperimentControllerImpl( 9710): Exposure of experiment com.facebook.http.qe.LigerHttpQuickExperiment@12f9f1a3 occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl( 9710): Exposure of experiment com.facebook.http.qe.LigerRequestSchedulingQuickExperiment@31dbca0 occurred when no user was logged in
,W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QuickExperimentControllerImpl( 9710): Exposure of experiment com.facebook.http.qe.NetworkInfoCollectorQuickExperiment@26e24059 occurred when no user was logged in
,W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QuickExperimentControllerImpl( 9710): Exposure of experiment com.facebook.http.qe.LigerConnectionManagementQuickExperiment@1bc6b41e occurred when no user was logged in
,W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9710): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
I/WifiStateMachine( 3521): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine( 3521): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3521): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/fb4a(:<default>):QuickExperimentControllerImpl( 9710): Exposure of experiment com.facebook.http.qe.Liger2gEmpathyDogfoodQuickExperiment@1f89f21b occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl( 9710): Exposure of experiment com.facebook.http.qe.TracerouteQuickExperiment@11627fb8 occurred when no user was logged in
,D/EnterpriseController( 2849): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
,D/Netd    ( 2849): getNetworkForDns: using netid 502 for uid 10114
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/ActivityManager( 3521): Waited long enough for: ServiceRecord{6f35e4 u0 com.samsung.android.MtpApplication/.MtpService}
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/AlarmManager( 3521): waitForAlarm result :4
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/PowerManagerService( 3521): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 3521): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  ( 3521): lcd : 1 +
,D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 3521): lcd : 1 -
,D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/Zygote  (10465): MountEmulatedStorage()
E/Zygote  (10465): v2
I/libpersona(10465): KNOX_SDCARD checking this for 10031
I/libpersona(10465): KNOX_SDCARD not a persona
,I/SELinux (10465): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10465): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3521): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.DailyHygiene: pid=10465 uid=10031 gids={50031, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (10465): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(10465): TimaSignature is unavailable
,D/ActivityThread(10465): Added TimaKeyStore provider
,D/ResourcesManager(10465): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/WifiStateMachine( 3521): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3521): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3521): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/Finsky  (10465): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  (10465): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings(10465): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings(10465): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  (10465): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/Ads     (10465): Skipping gmscore version check
,D/Finsky  (10465): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  (10465): [1] Libraries$2.run: Finished loading 1 libraries.
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/GLSActivity( 4659): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  (10465): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/GLSActivity( 4659): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4659): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  (10465): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/System.out(10465): Thread-1407(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(10465): Thread-1407(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(10465): Thread-1407(ApacheHTTPLog):isShipBuild true
I/System.out(10465): Thread-1407(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2849): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2849): getNetworkForDns: using netid 502 for uid 10031
,I/qtaguid (10465): Tagging socket 44 with tag e8d195d100000000{3906049489,0} uid -1, pid: 10465, getuid(): 10031
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/qtaguid (10465): Tagging socket 48 with tag e8d195d100000000{3906049489,0} uid -1, pid: 10465, getuid(): 10031
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/qtaguid (10465): Untagging socket 44
,I/System.out(10465): Thread-1407 calls detatch()
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/GLSActivity( 4659): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,I/qtaguid (10465): Untagging socket 44
,I/qtaguid (10465): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid (10465): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger(10465): untagSocket(44) failed with errno -22
I/System.out(10465): Thread-1408 calls detatch()
,D/Finsky  (10465): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,I/ActivityManager( 3521): Waited long enough for: ServiceRecord{36a15627 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,V/GLSActivity( 4659): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/Zygote  (10507): MountEmulatedStorage()
,E/Zygote  (10507): v2
I/libpersona(10507): KNOX_SDCARD checking this for 10014
I/libpersona(10507): KNOX_SDCARD not a persona
,I/SELinux (10507): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10507): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3521): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=10507 uid=10014 gids={50014, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
,E/SELinux (10507): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(10507): TimaSignature is unavailable
,D/ActivityThread(10507): Added TimaKeyStore provider
,D/ResourcesManager(10507): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,W/ResourcesManager(10507): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(10507): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/AlarmManager( 3521): waitForAlarm result :4
,I/MultiDex(10507): VM with version 2.1.0 has multidex support
I/MultiDex(10507): install
I/MultiDex(10507): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp (10507): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(10507): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  (10507): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@3041c036: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(10507): Installed default security provider GmsCore_OpenSSL
,I/splitIntent( 3521): Split this intent : com.google.android.gms.INITIALIZE !!   mSplitNum[0]=4, mSplitNum[1]=7, mSplitNum[2]=9 divideNum= 2 r.nextReceiver= 1 receivers.size=11
I/splitIntent( 3521): finish to split intent : com.google.android.gms.INITIALIZE !! Enqueue -> schedule it!!
,D/ChimeraCfgMgr(10507): Reading stored module config
,D/AuthorizationBluetoothService( 4659): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/qtaguid (10465): Untagging socket 44
,I/qtaguid (10465): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid (10465): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger(10465): untagSocket(44) failed with errno -22
,I/System.out(10465): Thread-1407 calls detatch()
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/LocationInitializer( 6671): Restart initialization of location
,D/WearableService( 4659): callingUid 10014, callindPid: 4659
,E/MDM     ( 4659): [309] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,V/GLSActivity( 4659): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/GCoreFlp( 4659): No location to return for getLastLocation()
,D/NativeLibraryUtils(10507): Install completed successfully. count=14 extracted=0
,W/FusedLocationProvider( 4659): location=null
,I/splitIntent( 3521): Queue : backgroundsplit_1 intent com.google.android.gms.INITIALIZE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,D/CAR.SERVICE(10507): Connecting to CarCallService...
,I/art     (10507): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     (10507): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE(10507): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service(10507): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter(10507): Creating a new PhoneAdapter instance
,W/ActivityManager( 3521): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter(10507): setListener: com.google.android.gms.car.dn@91e3c7d
,W/ActivityManager( 3521): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter(10507): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service(10507): Starting CarCallService with initial phone null
,D/CAR.SERVICE(10507): Package validated; name: com.android.vending
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/Finsky  (10465): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,D/Finsky  (10465): [1420] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  (10465): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/ActivityManager( 3521): Waited long enough for: ServiceRecord{1e340300 u0 com.samsung.android.app.pinboard/com.sec.android.sCloudRelayData.RelayService}
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/GLSActivity( 4659): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/qtaguid (10465): Untagging socket 44
I/qtaguid (10465): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid (10465): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger(10465): untagSocket(44) failed with errno -22
I/System.out(10465): Thread-1408 calls detatch()
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ResourcesManager(10465): creating new AssetManager and set to /system/framework/framework-res.apk
,D/ResourcesManager(10465): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(10465): creating new AssetManager and set to /system/app/ANTRadioService/ANTRadioService.apk
,D/ResourcesManager(10465): creating new AssetManager and set to /system/app/AntHalService/AntHalService.apk
,W/ResourcesManager(10465): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager(10465): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,W/ResourcesManager(10465): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(10465): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,I/WifiStateMachine( 3521): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3521): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3521): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ResourcesManager(10465): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager(10465): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/ResourcesManager(10465): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  (10465): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager( 3521): waitForAlarm result :4
,D/Finsky  (10465): [1429] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/DeviceConnectionService( 4659): client connected with version: 8296000
,V/GLSActivity( 4659): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  (10465): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  (10465): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,I/System.out(10465): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out(10465): (HTTPLog)-Static: isShipBuild true
I/System.out(10465): (HTTPLog)-Thread-1418-419020330: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out(10465): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2849): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2849): getNetworkForDns: using netid 502 for uid 10031
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/System.out(10465): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/ActivityManager( 3521): Killing 9666:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/SSRM:n  ( 3521): SIOP:: AP = 300, PST = 332, CUR = -456
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 3521): [s] UserActivityState : 2 -> 4
,I/PowerManagerService( 3521): !@[ps] Screen__Off - 0 : timeout (0x4) (2)
I/PowerManagerService( 3521): Going to sleep due to screen timeout (uid 1000)...
,D/InputManager-JNI( 3521): setDeviceInteractive: 0
D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
,D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 3521): [s] DisplayPowerCallbacks : onStateChanged()
D/InputManager-JNI( 3521): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/InputManager-JNI( 3521): sysfs_write +: /sys/class/input/event2/device/enabled: 0
,D/InputManager-JNI( 3521): sysfs_write +: /sys/class/input/event3/device/enabled: 0
,D/PowerManagerService( 3521): [PWL] sb acquire: PowerManagerService.Broadcasts
D/InputManager-JNI( 3521): sysfs_write -: /sys/class/input/event3/device/enabled: 0
,D/PowerManagerService( 3521): SecHardwareInterface.setBatteryADC : false
,D/InputManager-JNI( 3521): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/InputManager-JNI( 3521): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/PowerManagerService( 3521): handleSandman : startDream()
,D/SContextService( 3521): 	.unregisterCallback : 1, client=
D/SContextService( 3521): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@f0a09e3, Service = Auto Rotation, used = 1
E/PowerManagerService( 3521): handleSandman : startDreaming, but isDreaming false
,I/PowerManagerService( 3521): Sleeping (uid 1000)...
W/CAE     ( 3521): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
D/PowerManagerService( 3521): [s] UserActivityState : 4 -> 0
D/PowerManagerService( 3521): [input device light] setInputDeviceLightOn is called : 0
D/PowerManagerService( 3521): [input device light] handleInputDeviceLightOff
,V/CAE     ( 3521): stop(ContextProvider.java:149)
,V/CAE     ( 3521): clear(AutoRotationRunner.java:182)
V/CAE     ( 3521): disable(AutoRotationRunner.java:171)
,I/SurfaceFlinger( 2853): id=12 createSurf (1440x2560),2 flag=404, DolorFade
,I/CAE     ( 3521): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
,D/SensorHubManager( 3521): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs( 2866): sendContextData: -78, 7, 0, 0
,D/CAE     ( 3521): getFaultDetectionResult(AutoRotationRunner.java:195) - true
I/CAE     ( 3521): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/PowerManagerService( 3521): Excessive delay in ColorFade : createSurface: 22ms
,D/PowerManagerService( 3521): Excessive delay in ColorFade : createEglContext: 24ms
,D/mali_winsys( 3521): new_window_surface returns 0x3000,  [1440x2560]-format:1
,D/PermissionCache( 2853): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (311 us)
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/CAE     ( 3521): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     ( 3521): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
,D/CAE     ( 3521): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     ( 3521): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService( 3521): removeSContextService() : service = Auto Rotation
D/SContextService( 3521): ===== SContext Service List =====
D/SContextManager( 3521):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@1708f86b, service=Auto Rotation
,D/KeyguardViewMediator( 3690): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 3690): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 3690): changeWallpaperByScreenOff()
,D/KeyguardViewMediator( 3690): notifyScreenOffLocked
,I/DBG_DM  ( 6204): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
,D/KeyguardViewMediator( 3690): timeout : 5000
,V/ActivityThread( 6204): updateVisibility : ActivityRecord{d9ae04a token=android.os.BinderProxy@29826d1f {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/KeyguardViewMediator( 3690): setting alarm to turn off keyguard, seq = 1
D/KeyguardViewMediator( 3690): handleNotifyScreenOff
,D/PowerManagerService( 3521): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 49ms
,I/CAE     ( 3521): handleMessage(CaPowerManager.java:188) - AP_WAKEUP
,I/CAE     ( 3521): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_WAKEUP
I/CAE     ( 3521): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -47, 0,
,D/SensorHubManager( 3521): SendSensorHubData: send data = -76, 13, -47, 0
D/Sensorhubs( 2866): sendContextData: -76, 13, -47, 0
,D/InputMethodManagerService( 3521): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,D/MotionRecognitionService( 3521):   mReceiver.onReceive : ACTION_SCREEN_ON
,I/WifiTrafficPoller( 3521): evaluateTrafficStatsPolling
,E/MotionRecognitionService( 3521):  handler : SCREEN_ON end
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/WifiStateMachine( 3521): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine( 3521): handleScreenStateChanged Exit: true
D/NotificationService( 3521): ACTION_SCREEN_ON
D/LightsService( 3521): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 3521) 
D/LightsService( 3521): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
,D/LightsService( 3521): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService( 3521): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/PowerManagerService( 3521): Excessive delay in ColorFade : initGLShaders: 45ms
,I/AudioHardwareTinyALSA( 2858): setParameters(screen_state=on)
,I/SecExternalDisplayIntents_Java( 3521): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,E/WifiStateMachine( 3521): setSuspendOptimizationsNative: 4 false -want true stack:setSuspendOptimizationsNative - access$16900 - processMessage - processMsg
E/native  ( 3521): do suspend false
,D/PowerManagerService( 3521): Excessive delay in ColorFade : draw: 19ms
,I/wpa_supplicant( 3834): reset timer : RESET_TIMER 1
I/wpa_supplicant( 3834): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3834): P2P: Current p2p state = IDLE
,D/PowerManagerService( 3521): Excessive delay in ColorFade : draw: 18ms
,I/wpa_supplicant( 3834): Scan requested (ret=0) - scan timeout 30 seconds
,D/IpRemoteDisplayController( 3521): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController( 3521): Bridge Server is not available
,D/PowerManagerService( 3521): Excessive delay in ColorFade : draw: 14ms
D/PowerManagerService( 3521): Excessive delay in ColorFade prepare: 205ms
,D/DisplayPowerController( 3521): ColorFade: onAnimationStart
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 0
D/DisplayPowerController( 3521): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 0
D/DisplayPowerController( 3521): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/GpsLocationProvider( 3521): receive broadcast intent, action: android.intent.action.SCREEN_ON
,E/GpsLocationProvider( 3521): ++ Invoked android_location_GpsLocationProvider_set_lcd_mode --> mode:1 ++
E/GpsLocationProvider( 3521): sExerciseIterface is not available
,D/PersonaManagerService( 3521): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 3521): MSG_ACTION_SCREEN_ON called
,D/lights  ( 3521): lcd : 0 +
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 0
D/DisplayPowerController( 3521): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 3521): lcd : 0 -
,I/NfcService( 3966): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 3966): call the applyRouting
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:2, health:2, present:true, voltage: 4377, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:-165, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/SamsungIME( 4471): getNextShiftState() cursorCapsMode : 0
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/accuweather( 5188): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 5188): [KK AccuPhone]>>> UIM:118 [0:0] getInstance
D/accuweather( 5188): [KK AccuPhone]>>> UIM:118 [0:0] getInstance
,D/accuweather( 5188): [KK AccuPhone]>>> UIM:281 [0:0] update clock event, is not screen on!!
,D/SSRM:n  ( 3521): SIOP:: AP = 300, PST = 326, CUR = -165
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 0
D/DisplayPowerController( 3521): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/SystemBroadcastReceiver(10200): [#DCM#] [DCM_Performance] onReceive completed in time  3274 microsec. 
,D/daemonapp( 3777): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 3777): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/SystemBroadcastReceiver(10200): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager(10200): [#DCM#] onReceive action = EVENT_SCREEN_ON
,I/DCMController(10200): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_ON
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 3777): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 3777): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 3777): [MSC_Daemon]>>> daemonapp [Version : 15022501 ] [ 3 ] 
D/comsamsunglog( 3777): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
,D/comsamsunglog( 3777): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 3777): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 3777): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 3777): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 3777): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1457967060000
D/daemonapp( 3777): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1457945515035
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 3777): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
D/LightsService( 3521): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 10, onMS = 0, offMS = 0,  (uid: 1000 pid: 3521) 
D/LightsService( 3521): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x10 | SvcLED(id=3) set On
,D/LightsService( 3521): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 3521): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/BatteryService( 3521): turn on LED for charging
D/SensorManager( 3521): unregisterListener ::   
D/lights  ( 3521): led_pattern : 1 +
,D/daemonapp( 3777): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 3777): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/lights  ( 3521): led_pattern : 1 -
D/LightsService( 3521): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
D/daemonapp( 3777): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/CAE     ( 3521): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     ( 3521): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     ( 3521): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager( 3521): SendSensorHubData: send data = -76, 13, -46, 0
,E/daemonapp( 3777): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/Sensorhubs( 2866): sendContextData: -76, 13, -46, 0
,I/CAE     ( 3521): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 8, 51, 55,
D/SensorHubManager( 3521): SendSensorHubData: send data = -63, 14, 8, 51, 55
D/Sensorhubs( 2866): sendContextData: -63, 14, 8, 51, 55
,D/MotionRecognitionService( 3521):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService( 3521):  handler : SCREEN_OFF end 
,I/WifiTrafficPoller( 3521): evaluateTrafficStatsPolling
,D/NotificationService( 3521): ACTION_SCREEN_OFF
D/WifiStateMachine( 3521): backgroundScan enabled=false startBackgroundScanIfNeeded:false
D/LightsService( 3521): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 3521) 
E/WifiStateMachine( 3521): handleScreenStateChanged Exit: false
D/LightsService( 3521): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x10 | SvcLED(id=4) set Off
,D/LightsService( 3521): [SvcLED]  onSensorChanged::light value = 0
,E/WifiStateMachine( 3521): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16900 - processMessage - processMsg
,E/WifiStateMachine( 3521): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16900 - processMessage - processMsg
E/native  ( 3521): do suspend true
,D/SensorManager( 3521): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager( 3521): unregisterListener ::   
D/LightsService( 3521): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/AudioHardwareTinyALSA( 2858): setParameters(screen_state=off)
,D/DisplayPowerState( 3521): !@ ColorFade entry
D/DisplayPowerController( 3521): ColorFade: onAnimationEnd
,I/SecExternalDisplayIntents_Java( 3521): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController( 3521): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController( 3521): Bridge Server is not available
,D/VolumePanel( 3690): registerReceiver: onReceive start 
D/VolumePanel( 3690): registerReceiver ACTION_SCREEN_OFF start
D/VolumePanel( 3690): registerReceiver ACTION_SCREEN_OFF end
D/VolumePanel( 3690): registerReceiver: onReceive end 
,D/AutomaticBrightnessController( 3521): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/AutomaticBrightnessController( 3521): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
,I/AutomaticBrightnessController( 3521): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
D/AutomaticBrightnessController( 3521): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
I/Sensors ( 3521): Light old sensor_state 513, new sensor_state : 1 en : 0
I/AutomaticBrightnessController( 3521): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
,D/VolumePanel( 3690): mCoverBroadcastReceiver: onReceive() start : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/VolumePanel( 3690): mCoverBroadcastReceiver: Screen OFF start
D/DisplayPowerController( 3521): getFinalBrightness : 0 -> 0
D/SensorManager( 3521): unregisterListener ::   
D/DisplayPowerController( 3521): animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
I/Sensors ( 3521): Acc old sensor_state 1, new sensor_state : 0 en : 0
,D/VolumePanel( 3690): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
D/DisplayPowerController( 3521): getFinalBrightness : 0 -> 0
D/DisplayPowerController( 3521): animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/DisplayPowerController( 3521): getFinalBrightness : 0 -> 0
D/DisplayPowerController( 3521): animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 3521): [s] DisplayPowerCallbacks : onStateChanged()
D/SurfaceFlinger( 2853): Set power mode=0, type=0 flinger=0xb6962000
D/PowerManagerService( 3521): [PWL] sb release: PowerManagerService.Display
I/hwcomposer( 2853): int exynos5_blank(hwc_composer_device_1*, int, int):: disp(0), blank(1)
I/DisplayManagerService( 3521): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1440 x 2560, 59.0 fps, supportedRefreshRates [59.0], density 640, 515.154 x 520.192 dpi, appVsyncOff 0, presDeadline 17949152, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager( 3521): Display changed displayId=0
,D/SensorManager( 3521): unregisterListener ::   
,D/VolumePanel( 3690): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 3690): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/GpsLocationProvider( 3521): receive broadcast intent, action: android.intent.action.SCREEN_OFF
E/GpsLocationProvider( 3521): ++ Invoked android_location_GpsLocationProvider_set_lcd_mode --> mode:0 ++
E/GpsLocationProvider( 3521): sExerciseIterface is not available
,D/PersonaManagerService( 3521): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 3521): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 3966): call the applyRouting
,D/STATUSBAR-PhoneStatusBar( 3690):      ACTION_SCREEN_OFF is finished!!!! 
,E/StatusBar( 3690): onReceive : Intent.ACTION_SCREEN_OFF
,D/accuweather( 5188): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 5188): [KK AccuPhone]>>> UIM:118 [0:0] getInstance
,D/accuweather( 5188): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/SSRM:n  ( 3521): SIOP:: AP = 300, PST = 322, CUR = -165
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 5188): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5188): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5188): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
D/accuweather( 5188): [KK AccuPhone]>>> UIM:311 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,I/SystemBroadcastReceiver(10200): [#DCM#] [DCM_Performance] onReceive completed in time  98 microsec. 
I/SystemBroadcastReceiver(10200): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager(10200): [#DCM#] onReceive action = EVENT_SCREEN_OFF
I/DCMController(10200): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_OFF
,D/PowerManagerService( 3521): [PWL] sb release: PowerManagerService.Broadcasts
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 5188): [KK AccuPhone]>>> UIM:157 [0:0] make widget 4x1 view!!! 
,D/accuweather( 5188): [KK AccuPhone]>>> UIM:159 [0:0] make widget 4x2 view!!! 
,D/accuweather( 5188): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 160span x = 4, span y = 2
D/accuweather( 5188): [KK AccuPhone]>>> UIM:184 [0:0] get widget 4x2 view!!! wid = 2
,D/accuweather( 5188): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,D/accuweather( 5188): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 5188): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/SurfaceControl( 3521): Excessive delay in setPowerMode(): 201ms
D/PowerManagerService( 3521): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
,D/MISC PowerHAL( 3521): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 3521): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,D/PowerManagerService( 3521): Excessive delay in mPhotonicModulator.requestDisplayState(mRequestingState): 204ms
,I/PowerManagerService( 3521): [PWL] Off : 0s ago
,D/CAR.SERVICE(10507): mConnectedToCar = false, abort
,E/ActivityThread(10507): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1bc999c5 that was originally bound here
E/ActivityThread(10507): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@1bc999c5 that was originally bound here
E/ActivityThread(10507): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(10507): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(10507): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(10507): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(10507): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(10507): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(10507): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(10507): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
E/ActivityThread(10507): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
E/ActivityThread(10507): 	at com.google.android.gms.car.hc.<init>(:com.google.android.gms:319)
E/ActivityThread(10507): 	at com.google.android.gms.car.CarChimeraService.onCreate(:com.google.android.gms:74)
E/ActivityThread(10507): 	at com.google.android.chimera.container.ServiceProxy.setImpl(:com.google.android.gms:119)
E/ActivityThread(10507): 	at com.google.android.chimera.container.ServiceProxy.onCreate(:com.google.android.gms:109)
E/ActivityThread(10507): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(10507): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(10507): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(10507): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(10507): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(10507): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(10507): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(10507): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(10507): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(10507): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/ActivityThread(10507): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@34142d4 that was originally bound here
E/ActivityThread(10507): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@34142d4 that was originally bound here
E/ActivityThread(10507): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(10507): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(10507): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(10507): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(10507): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(10507): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
E/ActivityThread(10507): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
E/ActivityThread(10507): 	at com.google.android.gms.car.dp.a(:com.google.android.gms:586)
E/ActivityThread(10507): 	at com.google.android.gms.car.dp.<init>(:com.google.android.gms:511)
E/ActivityThread(10507): 	at com.google.android.gms.car.dp.a(:com.google.android.gms:488)
E/ActivityThread(10507): 	at com.google.android.gms.car.dm.<init>(:com.google.android.gms:112)
E/ActivityThread(10507): 	at com.google.android.gms.car.CarCallService.onBind(:com.google.android.gms:79)
E/ActivityThread(10507): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3181)
E/ActivityThread(10507): 	at android.app.ActivityThread.access$2000(ActivityThread.java:178)
E/ActivityThread(10507): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1537)
E/ActivityThread(10507): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(10507): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(10507): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(10507): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(10507): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(10507): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(10507): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/ActivityManager( 3521): Unbind failed: could not find connection for android.os.BinderProxy@1c70df9d
,D/SSRM:a  ( 3521): DeviceInfo:: 000000100000
D/SSRM:a  ( 3521): SettingsAirViewInfo:: 000000000
,I/art     ( 3521): Explicit concurrent mark sweep GC freed 44922(2MB) AllocSpace objects, 10(160KB) LOS objects, 24% free, 48MB/64MB, paused 1.962ms total 164.180ms
,W/IcingInternalCorpora( 6671): getNumBytesRead when not calculated.
,W/IdleConnectionHandler( 9875): Removing a connection that never existed!
,W/IdleConnectionHandler( 9875): Removing a connection that never existed!
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/wpa_supplicant( 3834): nl80211: Received scan results (15 BSSes)
,E/WifiStateMachine( 3521): [1,457,945,518,669 ms] noteScanEnd no scan source
,D/WifiP2pService( 3521): InactiveState{ what=147461 }
,D/WifiP2pService( 3521): P2pEnabledState{ what=147461 }
,D/WifiP2pService( 3521): DefaultState{ what=147461 }
,E/WifiStateMachine( 3521): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@3e1d98d3 sup_state=COMPLETED debouncing=false
,V/AlarmManager( 3521): waitForAlarm result :4
,D/KeyguardViewMediator( 3690): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/KeyguardViewMediator( 3690): doKeyguard: not showing because lockscreen is off
,V/AlarmManager( 3521): waitForAlarm result :8
,I/PowerManagerService( 3521): [PWL] Off : 5s ago
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3521): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3690): handleTimeUpdate
,D/KeyguardEffectViewController( 3690): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3690): *** don't update sliding image ***
,D/DateView( 3690): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,E/Watchdog( 3521): !@Sync 2
,D/DateView( 3690): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,V/AlarmManager( 3521): waitForAlarm result :4
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:2, health:2, present:true, voltage: 4395, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:93
,D/BatteryService( 3521): stay LED for charging
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 290, PST = 318
,V/AlarmManager( 3521): waitForAlarm result :4
,V/xAnalytics( 9710): xplat/fbacore/fbacore/XAnalytics.cpp - virtual void facebook::xanalytics::XAnalytics::resumeUploadFromStorage(const string&)
,D/Finsky  (10465): [1420] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  (10465): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:4/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3521): [PWL] Off : 15s ago
,V/AlarmManager( 3521): waitForAlarm result :4
,E/ActivityThread( 6671): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager( 3521): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 52390, reason: UserStart, SyncResult: databaseError: true stats []
D/SyncManager( 3521): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 144748, reason: UserStart
,W/ResourceType( 5235): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5235): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/SecContentProvider2( 3521): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 3521): mCursor = null
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:2, health:2, present:true, voltage: 4395, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:63, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:111
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for charging
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 280, PST = 314, CUR = 63
,I/ActivityManager( 3521): Killing 9540:com.google.android.apps.docs/u0a101 (adj 13): bgCount ##31
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3521): waitForAlarm result :4
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:86, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:92
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/LightsService( 3521): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 3521) 
,D/LightsService( 3521): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=3) set On
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,I/Sensors ( 3521): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/SensorManager( 3521): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/BatteryService( 3521): turn on LED for fully charged
,D/SSRM:n  ( 3521): SIOP:: AP = 270, PST = 310, CUR = 86
,D/SecContentProvider2( 3521): uri = 14 selection = getSealedState
,D/SecContentProvider2( 3521): mCursor = null
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/ApplicationPolicy( 3521): isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -2
V/ApplicationPolicy( 3521): isApplicationStateBlocked userId -2 pkgname com.android.systemui
,D/WindowManager( 3521): showStatusBarByNotification() mOpenByNotification=false
,D/PowerManagerService( 3521): [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10060 pid=3690
I/PowerManagerService( 3521): !@[ps] Screen__On  - 1 :  wl: PowerUI.Notification
I/PowerManagerService( 3521): Waking up from sleep (uid 10060)...
,D/PowerManagerService( 3521): [PWL] sb acquire: PowerManagerService.Broadcasts
,V/KeyguardServiceDelegate( 3521): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@e5ee1ba)
D/PowerManagerService( 3521): [s] UserActivityState : 0 -> 1
D/PowerManagerService( 3521): [PWL] sb acquire: PowerManagerService.Display
,D/KeyguardViewMediator( 3690): onScreenTurnedOn, seq = 2
,D/KeyguardViewMediator( 3690): notifyScreenOnLocked
D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
I/DisplayPowerController( 3521): Blocking screen on until initial contents have been drawn.
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AutomaticBrightnessController( 3521): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
D/SContextService( 3521): 	.registerCallback : 1, client=
D/DisplayPowerController( 3521): getFinalBrightness : 0 -> 0
D/DisplayPowerController( 3521): animation target = 0, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)), PendingAutoBrightness)
,D/AutomaticBrightnessController( 3521): [DAB] setLightSensorEnabled : registerListener mLightSensor
,D/PowerManagerService( 3521): !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
D/MISC PowerHAL( 3521): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
D/MISC PowerHAL( 3521): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
W/CAE     ( 3521): setCAProperty(ContextAwareService.java:464) - [setProperty 01] Mutex is locked for AUTO_ROTATION
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/AutomaticBrightnessController( 3521): [api] [DAB] onSensorChanged : 1st lux : 0.0
D/AutomaticBrightnessController( 3521): [DAB] updateAutoBrightnessSEC : 11(11.0)    0.0 < 0.0 < 15.0 (0.6)
D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
I/AutomaticBrightnessController( 3521): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 1
I/AutomaticBrightnessController( 3521): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1
,I/AutomaticBrightnessController( 3521): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 1
I/CAE     ( 3521): setPropertyValue(AutoRotationRunner.java:119) - Device Type = 0.0
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/SurfaceFlinger( 2853): Set power mode=2, type=0 flinger=0xb6962000
I/hwcomposer( 2853): int exynos5_blank(hwc_composer_device_1*, int, int):: disp(0), blank(0)
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SensorManager( 3521): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/PowerManagerService( 3521): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 4ms
,I/Sensors ( 3521): Acc old sensor_state 512, new sensor_state : 513 en : 1
,I/CAE     ( 3521): setCAProperty(ContextAwareService.java:469) - result : true
,W/CAE     ( 3521): setCAProperty(ContextAwareService.java:470) - [setProperty 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService( 3521): sendAttribute() : service = Auto Rotation
,W/CAE     ( 3521): registerCallback(ContextAwareService.java:137) - [regi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     ( 3521): start(ContextProvider.java:126)
,V/CAE     ( 3521): clear(AutoRotationRunner.java:182)
V/CAE     ( 3521): enable(AutoRotationRunner.java:158)
,I/DisplayManagerService( 3521): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1440 x 2560, 59.0 fps, supportedRefreshRates [59.0], density 640, 515.154 x 520.192 dpi, appVsyncOff 0, presDeadline 17949152, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager( 3521): Display changed displayId=0
,D/SensorManager( 3521): registerListener :: 0, ICM20610 Acceleration Sensor, 200000, 0,  
D/PowerManagerService( 3521): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 11ms
,I/CAE     ( 3521): sendCmdToSensorHub(SensorHubCommManager.java:144) - -79, 7, 0, 0,
D/SensorHubManager( 3521): SendSensorHubData: send data = -79, 7, 0, 0
,D/Sensorhubs( 2866): sendContextData: -79, 7, 0, 0
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/CAE     ( 3521): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     ( 3521): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/CAE     ( 3521): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     ( 3521): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0
,D/CAE     ( 3521): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,I/CAE     ( 3521): showListenerList(ContextAwareService.java:256) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@21097e4b, Service : AUTO_ROTATION(1)
,W/CAE     ( 3521): registerCallback(ContextAwareService.java:173) - [regi 02] Mutex is unlocked for AUTO_ROTATION
,D/SContextService( 3521): addSContextService() : service = Auto Rotation
D/SContextService( 3521): ===== SContext Service List =====
D/SContextService( 3521): Listener : android.hardware.scontext.SContextService$Listener@2e87d028, Service : Auto Rotation
,D/SContextManager( 3521):   .registerListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@1708f86b, service=Auto Rotation
,V/ActivityManager( 3521): Display changed displayId=0
,D/InputManager-JNI( 3521): setDeviceInteractive: 1
,D/KeyguardViewMediator( 3690): handleNotifyScreenOn
,D/StatusBarKeyguardViewManager( 3690): onScreenTurnedOn()
,I/Sensors ( 3521): #>LightSensor r=1 g=1 b=2 c=5 atime=238 again=64 lux=0.000000
D/LightsService( 3521): [SvcLED]  onSensorChanged::light value = 0
D/InputManager-JNI( 3521): sysfs_write +: /sys/class/input/event3/device/enabled: 1
D/InputManager-JNI( 3521): sysfs_write -: /sys/class/input/event3/device/enabled: 1
D/SensorManager( 3521): unregisterListener ::   
D/lights  ( 3521): led_pattern : 5 +
,D/InputManager-JNI( 3521): sysfs_write +: /sys/class/input/event1/device/enabled: 1
D/InputManager-JNI( 3521): sysfs_write +: /sys/class/input/event2/device/enabled: 1
,D/lights  ( 3521): led_pattern : 5 -
D/LightsService( 3521): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/NfcService( 3966): call the applyRouting
,D/SurfaceControl( 3521): Excessive delay in setPowerMode(): 211ms
D/PowerManagerService( 3521): Excessive delay in mPhotonicModulator.requestDisplayState(mRequestingState): 212ms
,D/KnoxNotification( 3690): ----- inflateViews : modified publicViewLocal -----
,D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/KnoxNotification( 3690): ----- inflateViews : modified KnoxViewLocal -----
,V/UserPresentBroadcastReceiver( 4659): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,D/PersonaManager( 3690): PersonaID is invalid or persona doesn't exists. : 0
,D/PhoneStatusBar( 3690): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@e144376
,D/InputManager-JNI( 3521): sysfs_write -: /sys/class/input/event1/device/enabled: 1
,D/PersonaManager( 3690): isKioskContainerExistOnDevice
,D/PersonaManager( 3690): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 3690): Icon Only
,I/StatusBar( 3690): Icon Only
,D/PanelView( 3690): There is/are notification(s) 
,D/PanelView( 3690): There is/are notification(s) 
,D/PersonaManager( 3690): isKioskContainerExistOnDevice
,I/PhoneStatusBar( 3690): Icon Only
I/StatusBar( 3690): Icon Only
,D/PanelView( 3690): There is/are notification(s) 
,V/KeyguardServiceDelegate( 3521): **** SHOWN CALLED ****
,D/DisplayPowerController( 3521): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
D/StatusBarKeyguardViewManager( 3690): callback.onShown()
,I/DisplayPowerController( 3521): Unblocked screen on after 328 ms
D/DisplayPowerState( 3521): !@ ColorFade exit
,D/PalmMotion( 3521): 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
D/PalmMotion( 3521): SURFACE_PALM_SWIPE: 1
E/MotionRecognitionService( 3521):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
,I/SurfaceFlinger( 2853): id=12 Removed DolorFade (8/8)
,I/SurfaceFlinger( 2853): id=12 Removed DolorFade (-2/8)
,D/LightsService( 3521): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 3521) 
D/LightsService( 3521): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/LightsService( 3521): [SvcLED]  onSensorChanged::light value = 0
E/libEGL  ( 3521): call to OpenGL ES API with no current context (logged once per thread)
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/lights  ( 3521): lcd : 11 +
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/Sensors ( 3521): #>LightSensor r=1 g=1 b=2 c=5 atime=238 again=64 lux=0.000000
,D/BatteryMeterView( 3690): onDraw batteryColor : -1
,D/SensorManager( 3521): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager( 3521): unregisterListener ::   
D/LightsService( 3521): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/SSRM:a  ( 3521): DeviceInfo:: 000000100000
D/SSRM:a  ( 3521): SettingsAirViewInfo:: 000000000
,D/lights  ( 3521): lcd : 11 -
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 3521): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 3521): SecHardwareInterface.setBatteryADC : true
,D/PowerManagerService( 3521): [input device light] setInputDeviceLightOn is called : 1
D/PowerManagerService( 3521): [input device light] handleInputDeviceLightOn
D/lights  ( 3521): button : 1 +
,D/InputManager-JNI( 3521): sysfs_write -: /sys/class/input/event2/device/enabled: 1
,D/SamsungIME( 4471): showDlgMsgBox : false true true
,I/DBG_DM  ( 6204): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
,D/LightsService( 3521): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 3521) 
,D/LightsService( 3521): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
D/BatteryService( 3521): turn off LED
,D/LightsService( 3521): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
,D/lights  ( 3521): button : 1 -
,D/lights  ( 3521): led_pattern : 0 +
,D/lights  ( 3521): led_pattern : 0 -
,D/LightsService( 3521): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/DBG_DM  ( 6204): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 28
,I/CAE     ( 3521): handleMessage(CaPowerManager.java:188) - AP_WAKEUP
,I/CAE     ( 3521): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_WAKEUP
I/CAE     ( 3521): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -47, 0,
D/SensorHubManager( 3521): SendSensorHubData: send data = -76, 13, -47, 0
,D/Sensorhubs( 2866): sendContextData: -76, 13, -47, 0
,D/InputMethodManagerService( 3521): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,D/PanelView( 3690): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,I/DBG_DM  ( 6204): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/MotionRecognitionService( 3521):   mReceiver.onReceive : ACTION_SCREEN_ON
,E/MotionRecognitionService( 3521):  handler : SCREEN_ON end
,I/WifiTrafficPoller( 3521): evaluateTrafficStatsPolling
,I/DBG_DM  ( 6204): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6204): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 28
,D/NotificationService( 3521): ACTION_SCREEN_ON
D/LightsService( 3521): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 3521) 
D/LightsService( 3521): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 3521): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService( 3521): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/WifiStateMachine( 3521): backgroundScan enabled=false startBackgroundScanIfNeeded:false
,E/WifiStateMachine( 3521): handleScreenStateChanged Exit: true
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
I/DBG_DM  ( 6204): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,D/StatusBar.NetworkController( 3690): applyOpen
,I/AudioHardwareTinyALSA( 2858): setParameters(screen_state=on)
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,I/SecExternalDisplayIntents_Java( 3521): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,E/WifiStateMachine( 3521): setSuspendOptimizationsNative: 4 false -want true stack:setSuspendOptimizationsNative - access$16900 - processMessage - processMsg
E/native  ( 3521): do suspend false
,I/wpa_supplicant( 3834): reset timer : RESET_TIMER 1
I/wpa_supplicant( 3834): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3834): P2P: Current p2p state = IDLE
,I/wpa_supplicant( 3834): Scan requested (ret=0) - scan timeout 30 seconds
,I/DBG_DM  ( 6204): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,D/IpRemoteDisplayController( 3521): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController( 3521): Bridge Server is not available
,D/GpsLocationProvider( 3521): receive broadcast intent, action: android.intent.action.SCREEN_ON
,E/GpsLocationProvider( 3521): ++ Invoked android_location_GpsLocationProvider_set_lcd_mode --> mode:1 ++
E/GpsLocationProvider( 3521): sExerciseIterface is not available
,I/DBG_DM  ( 6204): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/SecContentProvider2( 3521): uri = 14 selection = getSealedState
D/SecContentProvider2( 3521): mCursor = null
,D/PersonaManagerService( 3521): ACTION_SCREEN_ON onReceive
D/PersonaManagerServiceHandler( 3521): MSG_ACTION_SCREEN_ON called
D/ApplicationPolicy( 3521): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,V/ApplicationPolicy( 3521): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,I/DBG_DM  ( 6204): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 28
,I/NfcService( 3966): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 3966): call the applyRouting
,I/DBG_DM  ( 6204): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,D/StatusBar( 3690): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 3690): isKioskContainerExistOnDevice
D/PersonaManager( 3690): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3690): Icon Only
I/StatusBar( 3690): Icon Only
D/PanelView( 3690): There is/are notification(s) 
D/PanelView( 3690): There is/are notification(s) 
,D/PersonaManager( 3690): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3690): Icon Only
I/StatusBar( 3690): Icon Only
D/PanelView( 3690): There is/are notification(s) 
,I/DBG_DM  ( 6204): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6204): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 6204): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
,I/DBG_DM  ( 6204): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
,I/DBG_DM  ( 6204): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,D/ActivityManager( 3521): post active user change for 0
D/KnoxTimeoutHandler( 3521): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3521): handleActiveUserChange for user 0
,I/Timeline( 6204): Timeline: Activity_idle id: android.os.BinderProxy@29826d1f time:94468
,I/Sensors ( 3521): #>LightSensor r=1 g=2 b=2 c=5 atime=238 again=64 lux=0.000000
,I/SamsungIME( 4471): getNextShiftState() cursorCapsMode : 0
,D/accuweather( 5188): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 5188): [KK AccuPhone]>>> UIM:118 [0:0] getInstance
D/accuweather( 5188): [KK AccuPhone]>>> UIM:118 [0:0] getInstance
,D/accuweather( 5188): [KK AccuPhone]>>> UIM:288 [0:0] direct update clock
,D/accuweather( 5188): [KK AccuPhone]>>> UIM:157 [0:0] make widget 4x1 view!!! 
,D/accuweather( 5188): [KK AccuPhone]>>> UIM:159 [0:0] make widget 4x2 view!!! 
,D/accuweather( 5188): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 160span x = 4, span y = 2
D/accuweather( 5188): [KK AccuPhone]>>> UIM:1426 [0:0] mc sy = 2
,D/accuweather( 5188): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 160span x = 4, span y = 2
,D/accuweather( 5188): [KK AccuPhone]>>> UIM:184 [0:0] get widget 4x2 view!!! wid = 2
,E/accuweather( 5188): [KK AccuPhone]>>> UIM:1464 [0:0] bTM 09 52
,D/PanelView( 3690): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,I/SystemBroadcastReceiver(10200): [#DCM#] [DCM_Performance] onReceive completed in time  316 microsec. 
,I/SystemBroadcastReceiver(10200): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager(10200): [#DCM#] onReceive action = EVENT_SCREEN_ON
I/DCMController(10200): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_ON
,D/PowerManagerService( 3521): [PWL] sb release: PowerManagerService.Broadcasts
,D/SSRM:n  ( 3521): SIOP:: AP = 270, PST = 306, CUR = 86
,D/daemonapp( 3777): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 3777): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 3777): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 3777): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 3777): [MSC_Daemon]>>> daemonapp [Version : 15022501 ] [ 3 ] 
D/comsamsunglog( 3777): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 3777): [MSC_Daemon]>>> ====================================================================================================================
,D/daemonapp( 3777): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 3777): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 3777): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
D/daemonapp( 3777): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1457967060000
D/daemonapp( 3777): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1457945545977
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 3777): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 3777): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 3777): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 3777): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 3777): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/SSRM:a  ( 3521): DeviceInfo:: 000000100000
D/SSRM:a  ( 3521): SettingsAirViewInfo:: 000000000
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/PowerManagerService( 3521): [input device light] handleInputDeviceLightOff
D/lights  ( 3521): button : 0 +
,D/lights  ( 3521): button : 0 -
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,I/WifiStateMachine( 3521): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3521): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3521): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/AlarmManager( 3521): waitForAlarm result :4
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/wpa_supplicant( 3834): nl80211: Received scan results (17 BSSes)
,D/WifiP2pService( 3521): InactiveState{ what=147461 }
,D/WifiP2pService( 3521): P2pEnabledState{ what=147461 }
,D/WifiP2pService( 3521): DefaultState{ what=147461 }
,E/WifiStateMachine( 3521): [1,457,945,549,588 ms] noteScanEnd no scan source
,E/WifiStateMachine( 3521): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@3e1d98d3 sup_state=COMPLETED debouncing=false
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/GLSActivity( 4659): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/VacuumService( 4659): Vacuum at: now=1457945549832 tag=VacuumService
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/PhenotypeConfigurator( 4659): Scheduling Phenotype for one-off execution 3750 seconds from now (1457945550564)
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/PhenotypeFlagCommitter( 4659): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 4659): Using platform SSLCertificateSocketFactory
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/LocationManagerService( 3521): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/System.out( 4659): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 4659): (HTTPLog)-Static: isShipBuild true
I/System.out( 4659): (HTTPLog)-Thread-317-288359686: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 4659): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2849): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2849): getNetworkForDns: using netid 502 for uid 10014
,I/System.out( 4659): KnoxVpnUidStorageknoxVpnSupported API value returned is false,
I/qtaguid ( 4659): Tagging socket 77 with tag 3000120100000000{805310977,0} uid -1, pid: 4659, getuid(): 10014
D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/qtaguid ( 4659): Tagging socket 81 with tag 3000120100000000{805310977,0} uid -1, pid: 4659, getuid(): 10014
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/LocationManagerService( 3521): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/System.out( 4659): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4659): Tagging socket 77 with tag 3000120100000000{805310977,0} uid -1, pid: 4659, getuid(): 10014
,D/LocationManagerService( 3521): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/System.out( 4659): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4659): Tagging socket 77 with tag 3000120100000000{805310977,0} uid -1, pid: 4659, getuid(): 10014
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,I/WifiStateMachine( 3521): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3521): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3521): CMD_RSSI_POLL : out!
,D/LocationManagerService( 3521): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/System.out( 4659): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4659): Tagging socket 77 with tag 3000120100000000{805310977,0} uid -1, pid: 4659, getuid(): 10014
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/FactoryTest( 9298): Not factory mode
D/FactoryTest( 9298): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 9298): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 9298): still no open session command from host, so toast
,W/ContextImpl( 9298): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:717 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 9298): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1608 android.app.ContextImpl.startActivity:1597 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:717 
I/Timeline( 9298): Timeline: Activity_launch_request id:com.android.settings time:100981
,E/PersonaManagerService( 3521): inState():  stateMachine is null !!
I/PersonaManagerService( 3521): PersonaId don't exist
I/ActivityManager( 3521): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 3521): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager( 3521): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,D/CustomFrequencyManagerService( 3521): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3521  pkgName : ACTIVITY_RESUME_BOOSTER@2,
,W/ActivityManager( 3521): mDVFSHelper.acquire()
,I/DBG_DM  ( 6204): [com.wssyncmldm.ui.XUIInstallConfirmActivity(394/onUserLeaveHint)] 
,I/DBG_DM  ( 6204): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 28
,E/MTPRx   ( 9298): started activity for popup
,D/PointerIcon( 3521): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3521): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3521): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3521): setHoveringSpenCustomIcon IconType is same.1
,I/DBG_DM  ( 6204): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,I/DBG_DM  ( 6204): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6204): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 6204): [com.wssyncmldm.ui.XUIInstallConfirmActivity(399/onUserLeaveHint)] Home Key!!
,I/DBG_DM  ( 6204): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
,I/DBG_DM  ( 6204): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 6204): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 3
,I/DBG_DM  ( 6204): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 3 / Notification IndicatorState : 3
,D/SecContentProvider2( 3521): uri = 14 selection = getSealedState
D/LightsService( 3521): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 3521) 
D/SecContentProvider2( 3521): mCursor = null
D/LightsService( 3521): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 3521): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService( 3521): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/PersonaManager( 3690): isKioskContainerExistOnDevice
D/PersonaManager( 3690): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3690): Icon Only
,D/ApplicationPolicy( 3521): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3521): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/WindowManager( 3521): showStatusBarByNotification() mOpenByNotification=false
,I/DBG_DM  ( 6204): [com.wssyncmldm.db.file.XDB(3657/llIIIIlllllIIllllllI)] FUMO_Status : 220
,I/StatusBar( 3690): Icon Only
D/PanelView( 3690): There is/are notification(s) 
,D/PanelView( 3690): There is/are notification(s) 
,D/PersonaManager( 3690): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3690): Icon Only
I/StatusBar( 3690): Icon Only
D/PanelView( 3690): There is/are notification(s) 
,I/DBG_DM  ( 6204): [com.wssyncmldm.ui.XUIFotaPostponeActivity(373/lllIlIlIIIllIIlIllIl)] xdbSetFUMOStatus  to XDL_STATE_POSTPONE_TO_UPDATE
,I/DBG_DM  ( 6204): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 6204): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
,V/ActivityManager( 3521): Display changed displayId=0
,D/KnoxNotification( 3690): ----- inflateViews : modified publicViewLocal -----
,V/WindowOrientationListener( 3521): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowManager( 3521): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 3521): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowOrientationListener( 3521): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3521): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/Launcher( 4003): onRestart, Launcher: 896890753
,D/KnoxNotification( 3690): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 3690): PersonaID is invalid or persona doesn't exists. : 0
,D/PhoneStatusBar( 3690): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@e144376
D/PersonaManager( 3690): isKioskContainerExistOnDevice
D/PersonaManager( 3690): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3690): Icon Only
,D/Launcher( 4003): onStart, Launcher: 896890753
D/Launcher.HomeView( 4003): onStart
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/ActivityThread( 4003): updateVisibility : ActivityRecord{22389c64 token=android.os.BinderProxy@39f1c456 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,I/StatusBar( 3690): Icon Only
,D/PanelView( 3690): There is/are notification(s) 
D/ResourcesManager( 9298): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
D/PanelView( 3690): There is/are notification(s) 
,D/PersonaManager( 3690): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3690): Icon Only
I/StatusBar( 3690): Icon Only
D/PanelView( 3690): There is/are notification(s) 
,W/ResourcesManager( 9298): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 9298): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 9298): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 9298): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9298): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 9298): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9298): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/SurfaceFlinger( 2853): id=13 createSurf (1440x2560),1 flag=4, Mauncher
,D/mali_winsys( 4003): new_window_surface returns 0x3000,  [1440x2560]-format:1
,E/SettingsReceiverActivity( 9298): PREF_DONT_ASK_AGAIN : true
,D/FocusedStackFrame( 3521): Set to : 0
,D/StatusBarManagerService( 3521): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,E/ActivityManager( 3521): Invalid thumbnail dimensions: 768x768
,D/PointerIcon( 3521): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3521): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3521): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3521): setHoveringSpenCustomIcon IconType is same.1
,D/PanelView( 3690): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,W/OpenGLRenderer( 4003): SFEffectCache::get: create texture(0x988436f4): name, size, mSize = 41, 574656, 1388584
,D/InputMethodManagerService( 3521): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SettingsReceiverActivity( 9298): dev.kiessupport is : TRUE
,D/PanelView( 3690): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,D/Activity( 9298): performCreate Call secproduct feature valuefalse
D/Activity( 9298): performCreate Call debug elastic valuetrue
,D/Launcher( 4003): onResume, Launcher: 896890753
,D/SettingsProvider( 3521): name = kids_home_mode
D/SettingsProvider( 3521): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3521): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3521): selectionArgs: false
D/SettingsProvider( 3521): selectionArgs: 10008
D/SecContentProvider( 3521): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3521): ret = -1
D/Launcher.HomeView( 4003): onResume
,D/StatusBarManagerService( 3521): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/Launcher( 4003): setSystemUiTransparency.SettingNotFoundException : set as TRUE
,D/Launcher( 4003): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/MenuAppsGridFragment( 4003): onResume
,I/MicrophoneInputStream( 4054): mic_starting gfk@23e84e30
I/splitIntent( 3521): Split this intent : com.sec.android.intent.action.HOME_RESUME !!   mSplitNum[0]=3, mSplitNum[1]=7, mSplitNum[2]=9 divideNum= 2 r.nextReceiver= 1 receivers.size=11
I/splitIntent( 3521): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,D/WallpaperManager( 4003): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,I/HotwordRecognitionRnr( 4054): Starting hotword detection.
D/WallpaperManager( 4003): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,V/AudioPolicyManager( 2858): getInput() inputSource 1999, samplingRate 16000, format 8, channelMask 1, session 0, flags 0x10
V/AudioPolicyManager( 2858): getDeviceForInputSource()input source 1999, device 80000004
E/AudioHardwareTinyALSA( 2858): AudioStreamInALSA userDefined 0, pSize 960, pCount 2, buffer 1920, latency 120000
,E/AudioHardwareTinyALSA( 2858): can not make /data/snd/input_after_ns2.pcm
E/AudioHardwareTinyALSA( 2858): can not make /data/snd/input_before_ns2.pcm
E/AudioHardwareTinyALSA( 2858): can not make /data/snd/input2.pcm
E/AudioHardwareTinyALSA( 2858): can not make /data/snd/seamless_compress_16k_mono.bin
E/AudioHardwareTinyALSA( 2858): can not make /data/snd/seamless_decode_16k_stereo.pcm
D/AudioHardwareTinyALSA( 2858): Input	: format = 1, channels = 16, rate = 16000
D/AudioHardwareTinyALSA( 2858): default	: format = 0, channelCount = 2, rate = 16000
D/AudioHardwareTinyALSA( 2858): AudioStreamOps::set set IN_Channels : 10
D/AudioHardwareTinyALSA( 2858): mInputs.size : 1
,D/GalleryCacheReady(10257): Receive : home resume
,I/AudioFlinger( 2858): AudioFlinger's thread 0xaf312000 ready to run
D/AudioHardwareTinyALSA( 2858): Entering AudioStreamInALSA standby mode
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/AudioHardwareTinyALSA( 2858): Entering AudioStreamInALSA standby mode
,I/EDMNativeHelperService( 3521): isMicrophoneEnabled
,V/AudioPolicyManager( 2858): startInput() input 20
V/AudioPolicyManager( 2858): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager( 2858): getNewInputDevice() selected device 80000004
I/AudioPolicyManager( 2858): ### Device reset for Normal
V/AudioPolicyManager( 2858): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager( 2858): DeviceVector::getDevicesFromType() for type 80000004 found 0xb235b280
,I/AudioHardwareTinyALSA( 2858): virtual android::status_t android::AudioStreamInALSA::setParameters(const android::String8&): input_source=6;keyIsHotword=true;routing=-2147483644
I/samsungRecord( 2858): [samsungrecord] SamsungRecInit 
I/samsungRecord( 2858): [samsungrecordMIC]Use HardCoding Values
E/samsungRecord( 2858): miccalib file can't created. (/data/snd/miccalib.txt)
I/samsungRecord( 2858): 1
D/AudioHardwareTinyALSA( 2858): InALSA::setDevice: mode = 0, newDevice=0x80000004, currentDevice=0x0 ,force= 0
I/AudioHardwareTinyALSA( 2858): InALSA::setDevice: mode[0], Device[80000004] force=0
D/AudioHardwareTinyALSA( 2858): getInputScenario: input scenario = Voice
D/TinyUCM ( 2858): Enable Input dev(0x80000004)
,D/TinyUCM ( 2858): setScenario: Voice
D/TinyUCM ( 2858): set default scenario
,D/TinyUCM ( 2858): Disable Output dev(0x0)
D/TinyUCM ( 2858): getInputChannel: inputs = 0x80000004
D/TinyUCM ( 2858): set channel: Left
I/AudioHardwareTinyALSA( 2858): InALSA::setDevice: mHandle NULL mode[0], Device[80000004]
I/AudioHardwareTinyALSA( 2858): Open:+ mDefaults->direction=10000000 device=0
D/AudioHardwareTinyALSA( 2858): Channel: 2, Samplerate: 48000, Format: 0, Period Size: 960, Period Count: 2
,E/Zygote  (10730): MountEmulatedStorage()
E/Zygote  (10730): v2
I/libpersona(10730): KNOX_SDCARD checking this for 1000
I/libpersona(10730): KNOX_SDCARD not a persona
,I/SELinux (10730): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10730): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3521): Start proc com.android.settings for broadcast com.android.settings/.accessibilitywidget.AccessibilityWidgetProviderAssistiveLight: pid=10730 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux (10730): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10744): MountEmulatedStorage()
E/Zygote  (10744): v2
I/libpersona(10744): KNOX_SDCARD checking this for 10052
I/libpersona(10744): KNOX_SDCARD not a persona
,I/SELinux (10744): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3521): Start proc com.android.mms for broadcast com.android.mms/.UIEventReceiver: pid=10744 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
I/SELinux (10744): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10744): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 3521): handle home activity for 0
I/WallpaperManagerService( 3521): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 3521): post home show event for user 0
D/ActivityManager( 3521): post active user change for 0
D/KnoxTimeoutHandler( 3521): postActiveUserChange for user 0
D/WallpaperManagerService( 3521):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 3521): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 3521): handleActiveUserChange for user 0
,D/TimaKeyStoreProvider(10730): TimaSignature is unavailable
,D/ActivityThread(10730): Added TimaKeyStore provider
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/PushAndAttach(10039): mAssignedMemoMap.size() :0
,E/Zygote  (10758): MountEmulatedStorage()
E/Zygote  (10758): v2
I/libpersona(10758): KNOX_SDCARD checking this for 10173
I/libpersona(10758): KNOX_SDCARD not a persona
,I/SELinux (10758): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/StatusBarManagerService( 3521): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/SELinux (10758): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3521): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=10758 uid=10173 gids={50173, 9997, 1028, 1015} abi=armeabi-v7a
,E/SELinux (10758): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/Timeline( 4003): Timeline: Activity_idle id: android.os.BinderProxy@39f1c456 time:101252
D/TimaKeyStoreProvider(10744): TimaSignature is unavailable
,D/ActivityThread(10744): Added TimaKeyStore provider
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager(10730): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager(10730): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager(10730): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager(10730): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
D/TimaKeyStoreProvider(10758): TimaSignature is unavailable
W/ResourcesManager(10730): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(10730): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10730): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ActivityThread(10758): Added TimaKeyStore provider
W/ResourcesManager(10730): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/Zygote  (10775): MountEmulatedStorage()
E/Zygote  (10775): v2
I/libpersona(10775): KNOX_SDCARD checking this for 10168
I/libpersona(10775): KNOX_SDCARD not a persona
,I/SELinux (10775): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10775): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10775): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=10775 uid=10168 gids={50168, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,I/AudioHardwareTinyALSA( 2858): Open:- mDefaults->direction=10000000 device=0 mHandle: aea230c0
D/AudioHardwareTinyALSA( 2858): setInputVolume
D/TinyUCM ( 2858): setModifier Recognition, en=1
,D/TinyUCM ( 2858): Recognition doesn't have param
D/AudioHardwareTinyALSA( 2858): setPcmInterface: Stream=0x2, iSamplerate=16000++
D/AudioHardwareTinyALSA( 2858): setPcmInterface--
V/AudioPolicyManager( 2858): setInputDevice() createAudioPatch returned -22 patchHandle 0
V/AudioPolicyManager( 2858): AudioPolicyManager::startInput() input source = 1999
I/MicrophoneInputStream( 4054): mic_started gfk@23e84e30
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/TimaKeyStoreProvider(10775): TimaSignature is unavailable
,D/ActivityThread(10775): Added TimaKeyStore provider
,D/ResourcesManager(10758): creating new AssetManager and set to /system/app/SamsungWidget_ActiveApplication/SamsungWidget_ActiveApplication.apk
D/ResourcesManager(10744): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager(10744): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager(10744): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager(10744): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(10744): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10744): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(10744): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager(10775): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,V/TaskCloserActivity(10758): TaskCloserActivity enter()
W/ResourcesManager(10775): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager(10775): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(10775): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager(10775): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,V/TaskCloserActivity(10758): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,I/ActivityManager( 3521): Killing 9771:com.osp.app.signin/u0a45 (adj 15): bgCount ##31
,D/MySettingsProvider(10730): DatabaseHelper(Context context):DATABASE_VERSION=1
,E/SQLiteLog(10730): (283) recovered 10 frames from WAL file /data/data/com.android.settings/databases/mysettings.db-wal
,D/MySettingsProvider(10730): onCreate():(mDB == null)? false:true  =true
,I/ActivityManager( 3521): Killing 9824:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,I/HotwordWorker( 4054): onReady
,D/Mms/MmsApp(10744): [start]    onCreate() consume time = 0.0
,D/Mms/ArtClassLoader(10744): init before art
,D/Mms/TelephonyPermission(10744): start operation mode monitor
D/Mms/ArtClassLoader(10744): init [DONE] art
,D/ResourcesManager(10744): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(10744): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/BroadcastQueue( 3521): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=4003, uid=10008) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
,D/Mms/TelephonyPermission(10744): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission(10744): isDefault true
,I/ActivityManager( 3521): Killing 9752:com.sec.android.automotive.drivelink/u0a102 (adj 15): bgCount ##31
D/Mms/MmsApp(10744): onCreate() com.android.mms
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/Mms/MmsApp(10744): [start]    initCountryIso consume time = 23.125584
,D/CountryDetector( 3521): The first listener is added
,E/Zygote  (10794): MountEmulatedStorage()
E/Zygote  (10794): v2
I/libpersona(10794): KNOX_SDCARD checking this for 10097
I/libpersona(10794): KNOX_SDCARD not a persona
,I/SELinux (10794): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/Mms/MmsApp(10744): [end]    initCountryIso consume time = 3.832291
D/Mms/MmsConfig(10744): [start]    MmsConfig.init() consume time = 0.063167
,I/SELinux (10794): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10794): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=10794 uid=10097 gids={50097, 9997} abi=armeabi-v7a
,D/Mms/MmsConfig(10744): before partial update
,D/Mms/MmsConfig(10744): Load Resize quality : 80
,D/Mms/MmsConfig(10744):  enable multiwindow = true
,D/TimaKeyStoreProvider(10794): TimaSignature is unavailable
,D/ActivityThread(10794): Added TimaKeyStore provider
,E/Mms/MessageUtils(10744): setCountryDetector : update country detector info 
E/Mms/MessageUtils(10744): updateCountryIso : update country iso info 
,D/Mms/PackageInfo(10744): com.sec.imsservice is not installed
D/Mms/MmsConfig(10744): [end]    init() consume time = 24.451417
,D/Mms/Contact(10744): [start]    init() consume time = 0.348291
,D/ResourcesManager(10794): creating new AssetManager and set to /system/app/DigitalClock/DigitalClock.apk
,W/ResourcesManager(10794): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/TP/MmsSmsProvider( 3979): query,matched:13, calling pid = 10744
,D/TP/MmsSmsProvider( 3979): match 13:Elapsed time : 1.447 ms
,D/Mms/Contact(10744): [end]    init consume time = 7.389834
,D/Mms/DraftCache(10744): [start]    rebuildCache consume time = 0.938541
,D/TP/MmsSmsProvider( 3979): query,matched:12, calling pid = 10744
,D/TP/MmsSmsProvider( 3979): match 12:Elapsed time : 1.616 ms
,D/Mms/TelephonyUtils(10744): getSubId from simSlot 0, return Value = -1
,D/Mms/DownloadManager(10744): roaming -> false (slotId = 0)
D/Mms/DownloadManager(10744): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager(10744): auto download without roaming -> true
D/Mms/DownloadManager(10744): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,E/Mms/TelephonyUtils(10744): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils(10744): getSubId from simSlot 1, return Value = 9223372036854775807
D/Mms/DownloadManager(10744): roaming -> false (slotId = 1)
D/Mms/DownloadManager(10744): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager(10744): auto download without roaming -> true
D/Mms/DownloadManager(10744): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager(10744): auto download during roaming secondary -> false
D/Mms/DownloadManager(10744): mAutoDownload ------> true
,D/Mms/DraftCache(10744): [end]    rebuildCache consume time = 7.63225
,D/Mms/Conversation(10744): [start]    init() consume time = 1.326
D/Mms/MmsApp(10744): [end]    onCreate() consume time = 0.019959
,D/Mms/UIEventReceiver(10744): ui event
D/Mms/DownloadManager(10744): Service state changed: Bundle[mParcelledData.dataSize=692]
,D/Mms/DownloadManager(10744): roaming ------> false, mSimSlot = 0
D/Mms/TelephonyUtils(10744): getSubId from simSlot 0, return Value = -1
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,D/Mms/DownloadManager(10744): roaming -> false (slotId = 0)
D/Mms/DownloadManager(10744): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager(10744): auto download without roaming -> true
D/Mms/DownloadManager(10744): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager(10744): mAutoDownload ------> true
,E/Zygote  (10815): MountEmulatedStorage()
I/libpersona(10815): KNOX_SDCARD checking this for 10105
E/Zygote  (10815): v2
I/libpersona(10815): KNOX_SDCARD not a persona
,I/SELinux (10815): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10815): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=10815 uid=10105 gids={50105, 9997, 3003} abi=armeabi-v7a
E/SELinux (10815): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3521): Killing 9907:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,I/ActivityManager( 3521): Killing 9942:com.samsung.android.app.watchmanagerstub/u0a121 (adj 13): bgCount ##31
,D/TP/MmsSmsProvider( 3979): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 3979): delete URI_CONVERSATIONS_MESSAGES affectedRows=0
,E/SQLiteLog( 3979): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3979): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3979): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3979): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3979): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3979): (284) automatic index on im_threads(normal_thread_id)
,D/TP/MmsSmsProvider( 3979): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 3979): need read changed broadcast:false
I/art     ( 2877): Explicit concurrent mark sweep GC freed 8731(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 590us total 11.461ms
,D/Mms/Conversation(10744): [end]    init consume time = 26.264458
,D/Mms/MessagingNotification(10744): [start]    init() consume time = 0.808
,D/Mms/MessagingNotification(10744): [end]    init consume time = 3.431833
,D/TimaKeyStoreProvider(10815): TimaSignature is unavailable
,D/ActivityThread(10815): Added TimaKeyStore provider
,D/Mms/SpamFilter(10744): [start]    SpamFilter fill() begin consume time = 1.271375
,D/Mms/Synchronizer(10744): [start]    doSync consume time = 1.716834
I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 252us total 8.355ms
,D/CustomFrequencyManagerService( 3521): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3521  tag : ACTIVITY_RESUME_BOOSTER@2
,W/ActivityManager( 3521): mDVFSHelper.release()
I/Timeline( 3521): Timeline: Activity_windows_visible id: ActivityRecord{b0d6a8e u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t30} time:101444
,D/ResourcesManager(10815): creating new AssetManager and set to /system/app/DualClockDigital/DualClockDigital.apk
,I/art     ( 2877): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 260us total 9.011ms
,W/ResourcesManager(10815): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10815): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,D/CustomFrequencyManagerService( 3521): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3521  pkgName : ACTIVITY_RESUME_BOOSTER@6
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/splitIntent( 3521): Queue : backgroundsplit_0 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 3521): Killing 9957:com.sec.android.app.samsungapps/u0a13 (adj 15): bgCount ##31
,I/art     ( 3521): Explicit concurrent mark sweep GC freed 56090(3MB) AllocSpace objects, 14(2MB) LOS objects, 23% free, 50MB/66MB, paused 1.257ms total 81.276ms
,D/TP/MmsSmsProvider( 3979): query,matched:400, calling pid = 10744
,D/Mms/SpamFilter(10744): [end]    SpamFilter fill() finished consume time = 83.620708
D/TP/MmsSmsProvider( 3979): query,matched:0, calling pid = 10744
V/TP/MmsSmsProvider( 3979): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 3979): update uri: content://mms-sms/db_synchronization
V/TP/MmsSmsProvider( 3979): syncDBData start
V/TP/MmsSmsProvider( 3979): syncDBData sms end
,V/TP/MmsSmsProvider( 3979): syncDBData mms end
V/TP/MmsSmsProvider( 3979): syncDBData end
D/TP/MmsSmsProvider( 3979): match 0:Elapsed time : 1.527 ms
D/Mms/Synchronizer(10744): [end]    doSync consume time = 1.922958
,D/Mms/MessagingNotification(10744): checkBadgeCount unreadCount=0 badgeCount=0
,D/TP/SmsProvider( 3979): query,matched:26, calling pid = 10744
,D/TP/SmsProvider( 3979): match 26:Elapsed time : 0.553 ms
,D/TP/MmsSmsProvider( 3979): query,matched:6, calling pid = 10744
,D/TP/MmsSmsProvider( 3979): match 6:Elapsed time : 0.539 ms
,I/Mms/ReservationManager(10744): ReservationManager()
,I/Mms/ReservationManager(10744): resetAfterConnected()
,D/TP/MmsSmsProvider( 3979): query,matched:7, calling pid = 10744
,D/TP/MmsSmsProvider( 3979): match 7:Elapsed time : 1.159 ms
,I/Mms/ReservationManager(10744): getReservedSendMessageCount(): retMessageCount=0
,E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10833): MountEmulatedStorage()
I/libpersona(10833): KNOX_SDCARD checking this for 10028
E/Zygote  (10833): v2
I/libpersona(10833): KNOX_SDCARD not a persona
,I/SELinux (10833): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10833): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3521): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=10833 uid=10028 gids={50028, 9997} abi=armeabi-v7a
E/SELinux (10833): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(10833): TimaSignature is unavailable
,D/ActivityThread(10833): Added TimaKeyStore provider
,I/ActivityManager( 3521): Killing 9892:com.android.providers.calendar/u0a47 (adj 15): bgCount ##31
,D/ResourcesManager(10833): creating new AssetManager and set to /system/priv-app/OmaCP/OmaCP.apk
,W/ResourcesManager(10833): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/OMACP   (10833): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,I/SurfaceFlinger( 2853): id=11 Removed YUIInstallC (6/8)
I/SurfaceFlinger( 2853): id=11 Removed YUIInstallC (-2/8)
,D/Mms/Omacp(10744): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,D/Mms/ArtClassLoader(10744): init before art
D/Mms/ArtClassLoader(10744): init [DONE] art
,D/Mms/PerformanceUtils(10744): link cahcing start
,I/OMACP   (10833): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   (10833): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   (10833): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   (10833): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   (10833): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   (10833): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   (10833): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/OMACP   (10833): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   (10833): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   (10833): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   (10833): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   (10833): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,D/Mms/PerformanceUtils(10744): link cahcing done
I/OMACP   (10833): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/CustomFrequencyManagerService( 3521): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3521  tag : ACTIVITY_RESUME_BOOSTER@6
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
,D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/Watchdog( 3521): !@Sync 3
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/Mms/MmsApp(10744):  start initViewCache mms
,D/Mms/ComposeMessageFragment(10744): [start]    fillCache consume time = 1889.902292
D/Mms/ComposeMessageFragment(10744): fillCache, easy = false
,I/WifiStateMachine( 3521): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3521): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3521): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AbsListView(10744): Get MotionRecognitionManager
,D/MotionRecognitionService( 3521):  ssp status : true
,D/Mms/ComposeMessageFragment(10744): [end]    fillCache consume time = 144.935042
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/Mms/BubbleViewCache(10744): fillCache bubble = 8
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4364, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:-37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-146
D/PersonaManager( 3690): isKioskContainerExistOnDevice
D/PersonaManager( 3690): isKioskContainerExistOnDevice
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
I/PhoneStatusBar( 3690): Icon Only
I/StatusBar( 3690): Icon Only
,D/PanelView( 3690): There is/are notification(s) 
D/PanelView( 3690): There is/are notification(s) 
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5587): Disconnected process message: 10
,I/libencoder( 3521): width= 768, height = 768, colot_type= 6, bit_depth= 8
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/PanelView( 3690): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/SSRM:n  ( 3521): SIOP:: AP = 280, PST = 304, CUR = -37
,D/TaskPersister( 3521): removeObsoleteFile: deleting file=31_task_thumbnail.png
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/WifiStateMachine( 3521): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3521): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine( 3521): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
,I/WifiStateMachine( 3521): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3521): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3521): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/AlarmManager( 3521): waitForAlarm result :4
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,I/WifiStateMachine( 3521): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3521): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3521): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/PowerManagerService( 3521): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10060 pid=3690 (0x0)
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:84
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/SSRM:n  ( 3521): SIOP:: AP = 270, PST = 300, CUR = 26
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
,I/WifiStateMachine( 3521): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3521): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3521): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3521): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 3521): [s] UserActivityState : 1 -> 2
D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 3521): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  ( 3521): lcd : 10 +
,D/lights  ( 3521): lcd : 10 -
,D/lights  ( 3521): lcd : 1 +
D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 3521): lcd : 1 -
,D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
,D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,I/WifiStateMachine( 3521): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3521): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine( 3521): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
,I/WifiStateMachine( 3521): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3521): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3521): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3690): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3690): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
,D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3690): applyOpen
D/StatusBar.NetworkController( 3690): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3690): applyOpen
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3521): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 3521): [s] UserActivityState : 2 -> 4
I/PowerManagerService( 3521): !@[ps] Screen__Off - 1 : timeout (0x4) (2)
D/InputManager-JNI( 3521): setDeviceInteractive: 0
I/PowerManagerService( 3521): Going to sleep due to screen timeout (uid 1000)...
D/PowerManagerService( 3521): [PWL] sb acquire: PowerManagerService.Broadcasts
D/InputManager-JNI( 3521): sysfs_write +: /sys/class/input/event3/device/enabled: 0
D/PowerManagerService( 3521): SecHardwareInterface.setBatteryADC : false
D/InputManager-JNI( 3521): sysfs_write +: /sys/class/input/event2/device/enabled: 0
,D/InputManager-JNI( 3521): sysfs_write -: /sys/class/input/event3/device/enabled: 0
D/PowerManagerService( 3521): handleSandman : startDream()
D/InputManager-JNI( 3521): sysfs_write +: /sys/class/input/event1/device/enabled: 0
,E/PowerManagerService( 3521): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService( 3521): Sleeping (uid 1000)...
D/PowerManagerService( 3521): [s] UserActivityState : 4 -> 0
D/PowerManagerService( 3521): [input device light] setInputDeviceLightOn is called : 0
D/InputManager-JNI( 3521): sysfs_write -: /sys/class/input/event1/device/enabled: 0
D/PowerManagerService( 3521): [input device light] handleInputDeviceLightOff
,I/SurfaceFlinger( 2853): id=14 createSurf (1440x2560),2 flag=404, DolorFade
,D/InputManager-JNI( 3521): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/SContextService( 3521): 	.unregisterCallback : 1, client=
D/SContextService( 3521): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@2e87d028, Service = Auto Rotation, used = 1
,W/CAE     ( 3521): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     ( 3521): stop(ContextProvider.java:149)
,V/CAE     ( 3521): clear(AutoRotationRunner.java:182)
,V/CAE     ( 3521): disable(AutoRotationRunner.java:171)
,I/CAE     ( 3521): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
,D/SensorHubManager( 3521): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs( 2866): sendContextData: -78, 7, 0, 0
,D/PowerManagerService( 3521): Excessive delay in ColorFade : createSurface: 20ms,
,D/mali_winsys( 3521): new_window_surface returns 0x3000,  [1440x2560]-format:1
,D/CAE     ( 3521): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     ( 3521): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/PowerManagerService( 3521): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 37ms
,D/CAE     ( 3521): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     ( 3521): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
D/CAE     ( 3521): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     ( 3521): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService( 3521): removeSContextService() : service = Auto Rotation
D/SContextService( 3521): ===== SContext Service List =====
D/SContextManager( 3521):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@1708f86b, service=Auto Rotation
,D/KeyguardViewMediator( 3690): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 3690): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 3690): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 3690): notifyScreenOffLocked
,D/Launcher.HomeView( 4003): onPause
,D/KeyguardViewMediator( 3690): timeout : 5000
,D/Launcher( 4003): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/PowerManagerService( 3521): Excessive delay in ColorFade : initGLShaders: 36ms
,D/PowerManagerService( 3521): Excessive delay in ColorFade : draw: 13ms
,D/PowerManagerService( 3521): Excessive delay in ColorFade : draw: 13ms
,V/TaskCloserActivity(10758): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,D/StatusBarManagerService( 3521): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,V/ActivityThread( 4003): updateVisibility : ActivityRecord{22389c64 token=android.os.BinderProxy@39f1c456 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/Launcher.HomeView( 4003): onStop
D/PowerManagerService( 3521): Excessive delay in ColorFade : draw: 15ms
D/PowerManagerService( 3521): Excessive delay in ColorFade prepare: 143ms
D/DisplayPowerController( 3521): ColorFade: onAnimationStart
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 0
D/DisplayPowerController( 3521): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 0
D/DisplayPowerController( 3521): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/MicrophoneInputStream( 4054): mic_close gfk@23e84e30
,D/KeyguardViewMediator( 3690): setting alarm to turn off keyguard, seq = 2
,D/KeyguardViewMediator( 3690): handleNotifyScreenOff
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 0
D/lights  ( 3521): lcd : 0 +
D/DisplayPowerController( 3521): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 3521): lcd : 0 -
,V/AudioPolicyManager( 2858): stopInput() input 20
,V/AudioPolicyManager( 2858): releaseInput() 20
,V/AudioPolicyManager( 2858): closeInput(20)
,D/AudioHardwareTinyALSA( 2858): Entering AudioStreamInALSA standby mode
I/AudioHardwareTinyALSA( 2858): Close mHandle:aea230c0
,I/HotwordRecognitionRnr( 4054): Hotword detection finished
,I/HotwordRecognitionRnr( 4054): Stopping hotword detection.
,I/AudioHardwareTinyALSA( 2858): closeInputStream +
D/TinyUCM ( 2858): Disable Input dev(0x80000004)
,D/TinyUCM ( 2858): set channel: None
,D/AudioHardwareTinyALSA( 2858): Entering AudioStreamInALSA standby mode
,V/AudioPolicyManager( 2858): releaseInput() exit
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:47, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/LightsService( 3521): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 3521) 
D/LightsService( 3521): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
,D/LightsService( 3521): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 3521): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/BatteryService( 3521): turn on LED for fully charged
I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/SensorManager( 3521): unregisterListener ::   
D/lights  ( 3521): led_pattern : 5 +
,D/lights  ( 3521): led_pattern : 5 -
D/LightsService( 3521): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,I/CAE     ( 3521): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     ( 3521): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     ( 3521): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager( 3521): SendSensorHubData: send data = -76, 13, -46, 0
D/Sensorhubs( 2866): sendContextData: -76, 13, -46, 0
,I/CAE     ( 3521): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 8, 52, 55,
D/SensorHubManager( 3521): SendSensorHubData: send data = -63, 14, 8, 52, 55
D/Sensorhubs( 2866): sendContextData: -63, 14, 8, 52, 55
,D/DisplayPowerController( 3521): getFinalBrightness : 11 -> 0
D/DisplayPowerController( 3521): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/MotionRecognitionService( 3521):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService( 3521):  handler : SCREEN_OFF end 
,I/WifiTrafficPoller( 3521): evaluateTrafficStatsPolling
,D/NotificationService( 3521): ACTION_SCREEN_OFF
D/LightsService( 3521): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 3521) 
D/WifiStateMachine( 3521): backgroundScan enabled=false startBackgroundScanIfNeeded:false
D/LightsService( 3521): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
E/WifiStateMachine( 3521): handleScreenStateChanged Exit: false
,D/LightsService( 3521): [SvcLED]  onSensorChanged::light value = 0
,E/WifiStateMachine( 3521): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16900 - processMessage - processMsg
D/SensorManager( 3521): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,E/WifiStateMachine( 3521): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16900 - processMessage - processMsg
E/native  ( 3521): do suspend true
,D/SensorManager( 3521): unregisterListener ::   
D/LightsService( 3521): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/AudioHardwareTinyALSA( 2858): setParameters(screen_state=off)
,I/SecExternalDisplayIntents_Java( 3521): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController( 3521): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController( 3521): Bridge Server is not available
,D/VolumePanel( 3690): registerReceiver: onReceive start 
D/VolumePanel( 3690): registerReceiver ACTION_SCREEN_OFF start
D/VolumePanel( 3690): registerReceiver ACTION_SCREEN_OFF end
D/VolumePanel( 3690): registerReceiver: onReceive end 
,D/VolumePanel( 3690): mCoverBroadcastReceiver: onReceive() start : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
D/VolumePanel( 3690): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 3690): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 3690): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 3690): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/GpsLocationProvider( 3521): receive broadcast intent, action: android.intent.action.SCREEN_OFF
E/GpsLocationProvider( 3521): ++ Invoked android_location_GpsLocationProvider_set_lcd_mode --> mode:0 ++
E/GpsLocationProvider( 3521): sExerciseIterface is not available
,D/DisplayPowerState( 3521): !@ ColorFade entry
D/DisplayPowerController( 3521): ColorFade: onAnimationEnd
,D/AutomaticBrightnessController( 3521): mCallbacks.updateBrightness()
,D/AutomaticBrightnessController( 3521): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/AutomaticBrightnessController( 3521): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
I/AutomaticBrightnessController( 3521): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,I/AutomaticBrightnessController( 3521): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
,D/DisplayPowerController( 3521): getFinalBrightness : 0 -> 0
D/DisplayPowerController( 3521): animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/DisplayPowerController( 3521): getFinalBrightness : 0 -> 0
D/DisplayPowerController( 3521): animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/AutomaticBrightnessController( 3521): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
,I/Sensors ( 3521): Light old sensor_state 513, new sensor_state : 1 en : 0
D/DisplayPowerController( 3521): getFinalBrightness : 0 -> 0
,D/SurfaceFlinger( 2853): Set power mode=0, type=0 flinger=0xb6962000
,D/DisplayPowerController( 3521): animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
I/hwcomposer( 2853): int exynos5_blank(hwc_composer_device_1*, int, int):: disp(0), blank(1)
D/PowerManagerService( 3521): [s] DisplayPowerCallbacks : onStateChanged()
D/SensorManager( 3521): unregisterListener ::   ,
D/PowerManagerService( 3521): [PWL] sb release: PowerManagerService.Display
,I/Sensors ( 3521): Acc old sensor_state 1, new sensor_state : 0 en : 0
D/PersonaManagerService( 3521): ACTION_SCREEN_OFF onReceive
D/PersonaManagerServiceHandler( 3521): MSG_ACTION_SCREEN_OFF called
,I/DisplayManagerService( 3521): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1440 x 2560, 59.0 fps, supportedRefreshRates [59.0], density 640, 515.154 x 520.192 dpi, appVsyncOff 0, presDeadline 17949152, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
,V/ActivityManager( 3521): Display changed displayId=0
,D/SensorManager( 3521): unregisterListener ::   
,D/NfcService( 3966): call the applyRouting
,D/STATUSBAR-PhoneStatusBar( 3690):      ACTION_SCREEN_OFF is finished!!!! 
,E/StatusBar( 3690): onReceive : Intent.ACTION_SCREEN_OFF
,D/accuweather( 5188): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 5188): [KK AccuPhone]>>> UIM:118 [0:0] getInstance
,D/accuweather( 5188): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/SSRM:n  ( 3521): SIOP:: AP = 270, PST = 294, CUR = 47
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 5188): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5188): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5188): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
,D/accuweather( 5188): [KK AccuPhone]>>> UIM:311 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,I/SystemBroadcastReceiver(10200): [#DCM#] [DCM_Performance] onReceive completed in time  2202 microsec. 
,D/PowerManagerService( 3521): [PWL] sb release: PowerManagerService.Broadcasts
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,I/SystemBroadcastReceiver(10200): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager(10200): [#DCM#] onReceive action = EVENT_SCREEN_OFF
I/DCMController(10200): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_OFF
,D/daemonapp( 3777): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 5188): [KK AccuPhone]>>> UIM:157 [0:0] make widget 4x1 view!!! 
,D/accuweather( 5188): [KK AccuPhone]>>> UIM:159 [0:0] make widget 4x2 view!!! 
,D/accuweather( 5188): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 160span x = 4, span y = 2
,D/accuweather( 5188): [KK AccuPhone]>>> UIM:184 [0:0] get widget 4x2 view!!! wid = 2
,D/accuweather( 5188): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,D/accuweather( 5188): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 5188): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/SurfaceControl( 3521): Excessive delay in setPowerMode(): 223ms
D/PowerManagerService( 3521): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL( 3521): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 3521): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
D/PowerManagerService( 3521): Excessive delay in mPhotonicModulator.requestDisplayState(mRequestingState): 225ms
I/PowerManagerService( 3521): [PWL] Off : 0s ago
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3521): waitForAlarm result :8
,V/AlarmManager( 3521): waitForAlarm result :4
,V/AlarmManager( 3521): ___SyncScheduler (v3) ACTIVATED___
,V/AlarmManager( 3521): <AppSync3 Whitelist>
,V/AlarmManager( 3521): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3690): handleTimeUpdate
,D/KeyguardEffectViewController( 3690): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3690): *** don't update sliding image ***
,D/KeyguardViewMediator( 3690): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/KeyguardViewMediator( 3690): doKeyguard: not showing because lockscreen is off
,D/DateView( 3690): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3690): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/PowerManagerService( 3521): [PWL] Off : 5s ago
,E/Watchdog( 3521): !@Sync 4
,V/AlarmManager( 3521): waitForAlarm result :4
,V/AlarmManager( 3521): waitForAlarm result :8
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:55, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:96
D/BatteryService( 3521): stay LED for fully charged
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 260, PST = 285, CUR = 55
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3521): [PWL] Off : 15s ago
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:57, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:63
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 260, PST = 279, CUR = 57
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,V/AlarmManager( 3521): waitForAlarm result :4,
,D/BatteryService( 3521): online:4, current avg:58, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:51
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/SSRM:n  ( 3521): SIOP:: AP = 260, PST = 275, CUR = 58
D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3521): [PWL] Off : 30s ago
,E/Watchdog( 3521): !@Sync 5
,D/SSRM:n  ( 3521): SIOP:: AP = 260, PST = 270, CUR = 55
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:55, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:75
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3521): waitForAlarm result :4
,V/AlarmManager( 3521): waitForAlarm result :4
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 267, CUR = 55
,I/PowerManagerService( 3521): [PWL] Off : 50s ago
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:51, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 264, CUR = 51
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:49, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:43
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3521): waitForAlarm result :8
,E/Watchdog( 3521): !@Sync 6
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 262, CUR = 49
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:45, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:52
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3521): [PWL] Off : 75s ago
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 259, CUR = 45
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:43, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:48
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3521): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3690): handleTimeUpdate
,I/ClearcutLoggerApiImpl( 4659): disconnect managed GoogleApiClient
,D/KeyguardEffectViewController( 3690): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 3690): *** don't update sliding image ***
,D/DateView( 3690): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3690): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 258, CUR = 43
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:42, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:43
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 7
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 256, CUR = 42
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3521): [PWL] Off : 105s ago
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 255, CUR = 40
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:39, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 253, CUR = 39
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:41
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3521): waitForAlarm result :8
,E/Watchdog( 3521): !@Sync 8
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 252, CUR = 38
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:47,
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3521): [PWL] Off : 140s ago
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 252, CUR = 37
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35,
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged,
I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 251, CUR = 37
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:38,
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 9
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 251, CUR = 36
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:43
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 250, CUR = 34
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3521): [PWL] Off : 180s ago
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 250, CUR = 33
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:48
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 3521): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3521): TimaServiceHandler.handleMessage what =1
,D/TimaService( 3521): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 3521): initializing...
,I/TLC_TIMA_PKM_initialize( 3521): root = 0, root_strlen = 1
,I/TLC_TIMA_PKM_initialize( 3521): process = ffffffff00000000000000000000000a, process_strlen = 32
,I/TZ: mc_tlc_communication( 3521): input max_sendmsg_size = 262196
,I/TZ: mc_tlc_communication( 3521): input max_recvmsg_size = 262196
I/TZ: mc_tlc_communication( 3521): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 3521): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 3521): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 3521): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 3521): device_id = 0x0
I/TZ: mc_tlc_communication( 3521): tlc_open() was called
I/TZ: mc_tlc_communication( 3521): Opening MobiCore device
,I/TZ: mc_tlc_communication( 3521): Allocating WSM for TCI,
I/TZ: mc_tlc_communication( 3521): Opening the session
,I/TZ: mc_tlc_communication( 3521): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 3521): Trustlet response is completed
,E/Watchdog( 3521): !@Sync 10
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 250, CUR = 31
,I/TLC_TIMA_PKM_measure_kernel( 3521): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3521): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3521): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3521): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:37
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 250, CUR = 32
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27,
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 3521): Killing 9987:com.samsung.helphub/1000 (adj 15): bgCount ##31
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 250, CUR = 33
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 11
,D/SSRM:n  ( 3521): SIOP:: AP = 250, PST = 250, CUR = 32
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3521): [PWL] Off : 225s ago
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 249, CUR = 33
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 248, CUR = 32
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3521): !@Sync 12
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 247, CUR = 29
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31,
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 247, CUR = 30
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 247, CUR = 30
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0,
D/BatteryService( 3521): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3521): [PWL] Off : 275s ago
,E/Watchdog( 3521): !@Sync 13
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 246, CUR = 29
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 245, CUR = 29,
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 263, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 245, CUR = 28
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3521): waitForAlarm result :8
,E/Watchdog( 3521): !@Sync 14
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 245, CUR = 28
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 244, CUR = 27
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3521): [PWL] Off : 330s ago
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 243, CUR = 26
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 15
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 243, CUR = 25
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 243, CUR = 26
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged,
I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 242, CUR = 24
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 16
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 242, CUR = 26
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 242, CUR = 26
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 3521): [PWL] Off : 390s ago
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 241, CUR = 26
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:24, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 17
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 241, CUR = 24
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 241, CUR = 25
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0,
D/BatteryService( 3521): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 22
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 18
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 22,
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 22
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 22
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4400, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3521): [PWL] Off : 455s ago
,E/Watchdog( 3521): !@Sync 19
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 21
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8,
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 23
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 262, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 23
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/TimaService( 3521): TIMA: TimaService scheduler is intialized. 
D/TimaService( 3521): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 3521): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 3521): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 3521): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3521): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3521): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/TimaService( 3521): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 23
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 20
,W/ContextImpl( 3521): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 20
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 21
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 21
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3521): [PWL] Off : 525s ago
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 22
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 20
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 22
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 20
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 21
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
D/BatteryService( 3521): stay LED for fully charged
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.,
,I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 20
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 23
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 21
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 20
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 261, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:20, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3521): [PWL] Off : 600s ago
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 20,
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 24
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 18
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 17
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 17
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 25
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 17
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 17
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 18,
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3521): !@Sync 26
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 18
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20,
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3521): [PWL] Off : 680s ago
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 18,
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true,
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 17
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 27
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 17
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 16
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 16
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 28
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 16
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0,
,D/BatteryService( 3521): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.,
I/MotionRecognitionService( 3521): Plugged,
,I/MotionRecognitionService( 3521): setPowerConnected  = true,
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 16
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 15
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 29
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 15
,I/PowerManagerService( 3521): [PWL] Off : 765s ago
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-5
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 15,
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 260, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 16
,D/TimaService( 3521): TIMA: TimaService scheduler is intialized. 
D/TimaService( 3521): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 3521): TimaServiceHandler.handleMessage what =1
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:4
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 3521): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3521): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3521): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3521): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 15
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18,
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 14,
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10,
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 15
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-3,
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 31
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 14
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 14
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 13
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-7
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 32
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 14,
,I/PowerManagerService( 3521): [PWL] Off : 855s ago
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 15,
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 14
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-4
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3521): !@Sync 33
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 14
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 12
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7,
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 13
,E/Watchdog( 3521): !@Sync 34
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 13
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 13
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 13
,E/Watchdog( 3521): !@Sync 35
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23,
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 12
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3521): [PWL] Off : 950s ago
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 13
,V/AlarmManager( 3521): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3690): handleTimeUpdate
,D/KeyguardEffectViewController( 3690): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3690): *** don't update sliding image ***
,D/LightsService( 3521): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,I/Sensors ( 3521): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager( 3521): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/DateView( 3690): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3690): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/Sensors ( 3521): #>LightSensor r=0 g=0 b=0 c=1 atime=238 again=64 lux=0.000000
,D/LightsService( 3521): [SvcLED]  onSensorChanged::light value = 0
I/Sensors ( 3521): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager( 3521): unregisterListener ::   
D/LightsService( 3521): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-9
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 11
,V/AlarmManager( 3521): waitForAlarm result :8
,E/Watchdog( 3521): !@Sync 36
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 11,
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 11
,V/AlarmManager( 3521): waitForAlarm result :4
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3690): handleTimeUpdate
,D/KeyguardEffectViewController( 3690): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3690): *** don't update sliding image ***
,D/DateView( 3690): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3690): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 12,
,E/Watchdog( 3521): !@Sync 37
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 12,
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 12
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 13
,V/AlarmManager( 3521): waitForAlarm result :8
,E/Watchdog( 3521): !@Sync 38
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0,
,D/BatteryService( 3521): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30,
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.,
,I/MotionRecognitionService( 3521): Plugged,
,I/MotionRecognitionService( 3521): setPowerConnected  = true,
,D/BatteryService( 3521): stay LED for fully charged,
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 13,
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 11
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 259, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-5
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3521): [PWL] Off : 1050s ago
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 12
,E/Watchdog( 3521): !@Sync 39
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 11
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 11
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 12
,D/TimaService( 3521): TIMA: TimaService scheduler is intialized. 
D/TimaService( 3521): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 3521): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 3521): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 3521): handleMessage : MSG_UPDATE_USAGE_DB
,I/ApplicationUsage( 3521): Updating Usage Statistics in DB @ 1457946662975
,I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	,at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
,W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
,W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
,W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
,W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3521): ::getAppControlDB: Exception to create DB
W/System.err( 3521): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3521): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3521): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3521): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3521): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage( 3521): Done Updating Usage Statistics in DB @ 1457946663023
,E/Watchdog( 3521): !@Sync 40
,I/TLC_TIMA_PKM_measure_kernel( 3521): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3521): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3521): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3521): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 12
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 10
,I/art     ( 3521): Background sticky concurrent mark sweep GC freed 107623(10MB) AllocSpace objects, 344(5MB) LOS objects, 13% free, 51MB/59MB, paused 3.141ms total 114.530ms
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 10
,E/Watchdog( 3521): !@Sync 41
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 9,
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 9
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 10,
,E/Watchdog( 3521): !@Sync 42
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 10
,I/PowerManagerService( 3521): [PWL] Off : 1155s ago
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3521): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-5
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 9
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26,
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 8
,E/Watchdog( 3521): !@Sync 43
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 10,
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-3
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 10
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-5
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 9
,E/Watchdog( 3521): !@Sync 44
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-14
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 9
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 10
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:3
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 11
,E/Watchdog( 3521): !@Sync 45
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8,
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 11
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 9
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3521): stay LED for fully charged
,I/MotionRecognitionService( 3521): Plugged
I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 11
,I/PowerManagerService( 3521): [PWL] Off : 1265s ago
,E/Watchdog( 3521): !@Sync 46
,I/MMD     ( 2871): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 10
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED,
D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 12,
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 10,
,E/Watchdog( 3521): !@Sync 47
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 10,
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/BatteryService( 3521): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 9
,D/BatteryService( 3521): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3521): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 258, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3521): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3521): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3521): Plugged
,I/MotionRecognitionService( 3521): setPowerConnected  = true
,D/BatteryService( 3521): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3690): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3690): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3690):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/SSRM:n  ( 3521): SIOP:: AP = 240, PST = 240, CUR = 9
,V/HeadsetService( 5587): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5587): Disconnected process message: 10
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3690): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,TIME-OUT KILL (timeout was 1400000ms),D/AndroidRuntime(11616): 
D/AndroidRuntime(11616): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11616): CheckJNI is OFF
D/AndroidRuntime(11616): readGMSProperty: start
D/AndroidRuntime(11616): readGMSProperty: already setted!!
D/AndroidRuntime(11616): readGMSProperty: end
D/AndroidRuntime(11616): addProductProperty: start
E/AffinityControl(11616): AffinityControl: registerfunction enter
D/AndroidRuntime(11616): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 3521): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3521): START PACKAGE DELETE: observer{227175525}
D/PackageManager( 3521): pkg{<packageName>}
D/PackageManager( 3521): user{0}
D/PackageManager( 3521): caller{2000}
D/PackageManager( 3521): flags{2}
D/PersonaManagerService( 3521): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 3521): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 3521): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3521): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
D/PackageManager( 3521): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
D/PackageManagerService( 3521): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3521): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/PackageManager( 3521): !@killApplicatoin: 10208, uninstall pkg
D/ApplicationPolicy( 3521): getApplicationUninstallationEnabled
D/ApplicationPolicy( 3521): getApplicationUninstallationEnabled :  enabled true
I/ActivityManager( 3521): Force stopping com.test.thalitest appid=10208 user=-1: uninstall pkg
W/PackageSettings( 3521): Skipping PackageSetting{147a5b2 com.example.hello/10691} due to missing metadata
I/ActivityManager( 3521): Force stopping com.test.thalitest appid=10208 user=0: pkg removed
D/ResourcesManager( 3521): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
I/art     ( 9649): Explicit concurrent mark sweep GC freed 26237(1481KB) AllocSpace objects, 6(96KB) LOS objects, 37% free, 26MB/42MB, paused 1.076ms total 34.061ms
I/InputReader( 3521): Reconfiguring input devices.  changes=0x00000010
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
E/SamsungIME( 4471): mOCRHelper is null
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
I/art     ( 4054): Explicit concurrent mark sweep GC freed 34697(2MB) AllocSpace objects, 3(728KB) LOS objects, 35% free, 28MB/44MB, paused 1.326ms total 75.421ms
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
I/art     ( 6671): Explicit concurrent mark sweep GC freed 717(25KB) AllocSpace objects, 0(0B) LOS objects, 20% free, 30MB/38MB, paused 1.760ms total 82.380ms
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/LWLocationManager(10313): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(10313): getLastUiLocationId() : mLastUiLocationId = -100
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
D/ResourcesManager( 3521): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
E/Zygote  (11647): MountEmulatedStorage()
E/Zygote  (11647): v2
I/libpersona(11647): KNOX_SDCARD checking this for 10063
I/libpersona(11647): KNOX_SDCARD not a persona
I/SELinux (11647): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
W/ResourceType( 5235): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
I/SELinux (11647): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
W/ResourceType( 5235): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
E/SELinux (11647): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=11647 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/TimaKeyStoreProvider(11647): TimaSignature is unavailable
D/ActivityThread(11647): Added TimaKeyStore provider
D/ResourcesManager(10313): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
D/ResourcesManager(11647): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
D/ResourcesManager(10313): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
D/SecContentProvider2( 3521): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3521): mCursor = null
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/VRSetupWizardStub/PackageIntentReceiver(11647): onReceive()
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
D/VRSetupWizardStub/PackageIntentReceiver(11647): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(11647): packagename:com.test.thalitest
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(10313): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(10313): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
E/Zygote  (11664): MountEmulatedStorage()
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
E/Zygote  (11664): v2
I/libpersona(11664): KNOX_SDCARD checking this for 10021
I/libpersona(11664): KNOX_SDCARD not a persona
I/SELinux (11664): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
I/SELinux (11664): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3521): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=11664 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
E/SELinux (11664): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(10313): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
I/ActivityManager( 3521): Killing 10003:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Videos/Videos.apk
D/RegisteredServicesCache( 3966): empty dynamic service
D/ResourcesManager(10313): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(10313): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/TimaKeyStoreProvider(11664): TimaSignature is unavailable
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
D/ResourcesManager( 3521): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
D/ActivityThread(11664): Added TimaKeyStore provider
D/ResourcesManager(10313): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
D/RCPManagerService( 3521): PackageReceiver onReceive()
I/HarmonyEASService( 3521): onReceive : android.intent.action.PACKAGE_REMOVED for 0
D/ResourcesManager(10313): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/KnoxMUMContainerPolicy( 3521): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/art     ( 3521): Explicit concurrent mark sweep GC freed 38618(3MB) AllocSpace objects, 72(1152KB) LOS objects, 23% free, 51MB/67MB, paused 2.337ms total 151.517ms
D/BackupManagerService( 3521): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 3521): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3521): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3521): uID is 10208
V/EnterpriseBillingPolicy( 3521): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3521): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 3521): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3521): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3521): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3521): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 3521): getBillingProfileForVpnEngine - end - null
D/ResourcesManager(10313): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
W/ResourcesManager(10313): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/ResourcesManager(11664): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/ResourcesManager(10313): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(10313): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager(10313): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
I/KLMS-2.4.521: (11664): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Mar 14 10:15:00 GMT+01:00 2016
D/ResourcesManager(10313): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager(10313): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(10313): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10313): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10313): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
D/ResourcesManager(10313): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
I/KLMS-2.4.521: (11664): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 3521): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3521): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
D/PackageManager( 3521): delete codoeFile: 
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
I/AASAUninstall( 3521):  com.test.thalitest not target!
D/PackageManager( 3521): result of delete: 1{227175525}
D/ResourcesManager(10313): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
I/KLMS-2.4.521: (11664): KLMSIntentService(): onCreate()
I/KLMS-2.4.521: (11664): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
D/AndroidRuntime(11616): Shutting down VM
D/PackageManager( 3521): [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
D/PackageManager( 3521): userId{-1}
D/PackageManager( 3521): andCode{true}
D/ResourcesManager(10313): creating new AssetManager and set to /system/app/Videos/Videos.apk
E/Zygote  (11682): MountEmulatedStorage()
E/Zygote  (11682): v2
I/libpersona(11682): KNOX_SDCARD checking this for 10106
I/libpersona(11682): KNOX_SDCARD not a persona
I/SELinux (11682): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11682): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11682): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3521): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=11682 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
I/KLMS-2.4.521: (11664): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
I/KLMS-2.4.521: (11664): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
I/KLMS-2.4.521: (11664): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.4.521: (11664): KLMSIntentService(): listeningToPackageRemoved().START
D/ResourcesManager(10313): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
I/KLMS-2.4.521: (11664): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
D/ResourcesManager(10313): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
D/TimaKeyStoreProvider(11682): TimaSignature is unavailable
D/ActivityThread(11682): Added TimaKeyStore provider
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/talkback/talkback.apk
D/ResourcesManager(10313): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
D/EnterpriseDeviceManagerService( 3521): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3521): Admin package name: com.google.android.gms
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/ResourcesManager(11682): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
D/ResourcesManager(10313): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager(10313): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/elm:14491(11682): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14491(11682): ELMEngine.ELMEngine( context ).
D/elm:14491(11682): MDMBridge.setEnterpriseBridge()
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
D/elm:14491(11682): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
D/ResourcesManager(10313): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
D/elm:14491(11682): ElmAgentService : onCreate()
D/elm:14491(11682): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491(11682): MainReceiver.listeningToPackageRemoved()
D/elm:14491(11682): MDMBridge.getInstance()
D/elm:14491(11682): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14491(11682): MDMBridge.getAllLicenseInfoFromSDK()
D/ResourcesManager(10313): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
E/Zygote  (11699): MountEmulatedStorage()
E/Zygote  (11699): v2
I/libpersona(11699): KNOX_SDCARD checking this for 10019
I/libpersona(11699): KNOX_SDCARD not a persona
D/ResourcesManager(10313): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
I/SELinux (11699): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3521): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=11699 uid=10019 gids={50019, 9997} abi=armeabi-v7a
I/SELinux (11699): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/elm:14491(11682): ElmAgentService : onDestroy().
E/SELinux (11699): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(10313): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
I/ActivityManager( 3521): Killing 10057:com.samsung.android.snote:provider/u0a160 (adj 15): bgCount ##31
I/KLMS-2.4.521: (11664): KLMSIntentService(): Notification App List is Null. Remove Notification.
D/ResourcesManager(10313): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
D/TimaKeyStoreProvider(11699): TimaSignature is unavailable
D/ResourcesManager(10313): creating new AssetManager and set to /system/app/Books/Books.apk
D/ActivityThread(11699): Added TimaKeyStore provider
I/KLMS-2.4.521: (11664): KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
I/KLMS-2.4.521: (11664): KLMSIntentService(): listeningToPackageRemoved().END
W/ResourceType( 3521): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
D/ResourcesManager(10313): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
I/KLMS-2.4.521: (11664): KLMSIntentService(): onDestroy()
I/ActivityManager( 3521): Killing 10074:com.samsung.android.provider.shootingmodeprovider/u0a183 (adj 15): bgCount ##31
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
D/ResourcesManager(10313): creating new AssetManager and set to /system/app/Drive/Drive.apk
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(11699): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
D/ResourcesManager(10313): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
W/ResourcesManager( 3521): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3521): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3521): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3521): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
D/ResourcesManager( 3521): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
D/ResourcesManager(10313): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
D/com.sec.android.service.health.upgrade.UninstallReceiver(11699): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(11699): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver(11699): onReceive() : package name is not s health. Return !!!
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
D/ResourcesManager(10313): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
D/LocationWidgetApplication(10313): getLastUiLocationId() : mLastUiLocationId = -100
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3521): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager(10313): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
W/Resources( 3521): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/UsbSettingsManager( 3521): clearDefaults: com.test.thalitest
I/CrashAnrDetector( 3521): onPackageRemoved : com.test.thalitest
D/ResourcesManager(10313): creating new AssetManager and set to /system/app/Maps/Maps.apk
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(10313): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
E/Zygote  (11716): MountEmulatedStorage()
I/libpersona(11716): KNOX_SDCARD checking this for 1000
E/Zygote  (11716): v2
I/libpersona(11716): KNOX_SDCARD not a persona
I/SELinux (11716): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager(10313): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
I/ActivityManager( 3521): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11716 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 3521): Killing 10092:com.sec.android.widgetapp.tapandpay/u0a190 (adj 15): bgCount ##31
I/SELinux (11716): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11716): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(10313): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/ResourcesManager(10313): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
V/NetworkStats( 3521): removeUidsLocked() for UIDs [10208]
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
V/NetworkStats( 3521): performPollLocked(flags=0x3)
W/GeofencerStateMachine( 4659): Ignoring removeGeofence because network location is disabled.
D/NetworkStatsFactory( 3521): UpdateStatsForKnox
D/ResourcesManager(10313): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
D/TimaKeyStoreProvider(11716): TimaSignature is unavailable
V/NetworkStats( 3521): performPollLocked() took 7ms
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
D/ActivityThread(11716): Added TimaKeyStore provider
D/ResourcesManager(10313): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
D/ResourcesManager(11716): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
D/ResourcesManager(10313): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
I/PCWCLIENTTRACE_LOG(11716): DEFAULT_LOGON : true
D/ResourcesManager(10313): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
I/PCWCLIENTTRACE_LOG(11716): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper(11716): new DMDBOpenHelper instance
I/PCWCLIENTTRACE_PushUtil(11716): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil(11716): sales region : global
I/PCWCLIENTTRACE_PushUtil(11716): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver(11716): [onReceive] - android.intent.action.PACKAGE_REMOVED
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/Zygote  (11732): MountEmulatedStorage()
E/Zygote  (11732): v2
I/libpersona(11732): KNOX_SDCARD checking this for 10035
I/libpersona(11732): KNOX_SDCARD not a persona
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
D/NtpTrustedTime( 3521): currentTimeMillis() cache hit
I/SELinux (11732): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11732): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3521): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=11732 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/ActivityManager( 3521): Killing 10200:com.samsung.dcm:DCMService/u0a4 (adj 15): bgCount ##31
E/SELinux (11732): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/Zygote  (11747): MountEmulatedStorage()
E/Zygote  (11747): v2
I/libpersona(11747): KNOX_SDCARD checking this for 1000
I/libpersona(11747): KNOX_SDCARD not a persona
I/SELinux (11747): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3521): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=11747 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux (11747): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11747): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider(11732): TimaSignature is unavailable
D/ActivityThread(11732): Added TimaKeyStore provider
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3521): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(10313): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
E/SharedPreferencesImpl(10257): Couldn't rename file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml to backup file /data/data/com.sec.android.gallery3d/shared_prefs/com.sec.android.gallery3d_preferences.xml.bak
D/TimaKeyStoreProvider(11747): TimaSignature is unavailable
D/ActivityThread(11747): Added TimaKeyStore provider
E/Zygote  (11763): MountEmulatedStorage()
E/Zygote  (11763): v2
I/libpersona(11763): KNOX_SDCARD checking this for 10183
I/libpersona(11763): KNOX_SDCARD not a persona
I/SELinux (11763): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3521): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=11763 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
I/SELinux (11763): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11763): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/UsbHostManager( 3521): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3521): displayNotification : [02h,02h,01h]

```
