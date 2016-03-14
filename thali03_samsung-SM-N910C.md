#### Test 625090943f585e4_thali03_samsung-SM-N910C Logs


```
--------- beginning of main
I/GAV2    ( 8184): Thread[GAThread,5,main]: No campaign data found.
--------- beginning of system
W/ActivityManager( 3522): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
D/ActivityThread( 8947): Loading provider com.google.android.gmail.provider;com.android.mail.notifier;com.google.android.gm.email.provider;com.google.android.gm.email.notifier: com.android.email.provider.EmailProvider
W/ActivityManager( 3522): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager( 3522): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
W/ActivityManager( 3522): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
W/ActivityManager( 3522): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
V/GLSActivity( 4650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 4650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   ( 8947): getAccountsCursor
I/Gmail   ( 8947): Observing account changes for notifications
V/GLSActivity( 4650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ActivityManager( 3522): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
W/GAV2    ( 8947): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
W/ActivityManager( 3522): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/ActivityManager( 3522): Killing 8184:com.google.android.apps.plus/u0a147 (adj 13): bgCount ##31
E/Gmail   ( 8947): Error finding the version of the Email provider.....
E/Gmail   ( 8947): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 8947): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:137)
E/Gmail   ( 8947): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
E/Gmail   ( 8947): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 8947): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 8947): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 8947): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 8947): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 8947): We do not support migrating this version of the Email provider.
I/Gmail   ( 8947): getAccountsCursor
V/GLSActivity( 4650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 4650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
V/GLSActivity( 4650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
E/SQLiteLog( 8947): (283) recovered 74 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
I/ActivityManager( 3522): Killing 8372:com.wsomacp/u0a28 (adj 13): bgCount ##31
I/Gmail   ( 8947): notifyAccountChanged
I/Gmail   ( 8947): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 8947): getAccountsCursor
I/Gmail   ( 8947): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/Gmail   ( 8947): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/Gmail   ( 8947): calculateUnknownSyncRationalesAndPurgeInBackground: running
V/GLSActivity( 4650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/ActivityManager( 3522): Waited long enough for: ServiceRecord{1386607e u0 com.sec.android.app.SmartClipService/com.samsung.android.service.hermes.HermesServiceStarter}
I/Gmail   ( 8947): getAccountsCursor
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 8998): MountEmulatedStorage()
I/libpersona( 8998): KNOX_SDCARD checking this for 10125
E/Zygote  ( 8998): v2
I/libpersona( 8998): KNOX_SDCARD not a persona
I/SELinux ( 8998): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux ( 8998): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux ( 8998): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.realtimechat.RealTimeChatService$AlarmReceiver: pid=8998 uid=10125 gids={50125, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
I/ActivityManager( 3522): Waited long enough for: ServiceRecord{37c1762c u0 com.sec.android.app.SmartClipService/com.samsung.android.service.hermes.HermesCollectorService}
V/GLSActivity( 4650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
D/TimaKeyStoreProvider( 8998): TimaSignature is unavailable
D/ActivityThread( 8998): Added TimaKeyStore provider
D/ResourcesManager( 8998): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
W/ResourcesManager( 8998): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
D/AndroidRuntime( 8989): 
D/AndroidRuntime( 8989): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 8989): CheckJNI is OFF
D/AndroidRuntime( 8989): readGMSProperty: start
D/AndroidRuntime( 8989): readGMSProperty: already setted!!
D/AndroidRuntime( 8989): readGMSProperty: end
D/AndroidRuntime( 8989): addProductProperty: start
I/Babel   ( 8998): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 8998): MmsConfig.loadMmsSettings
I/Babel   ( 8998): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N910C, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N910C.xml
I/Babel   ( 8998): MmsConfig.loadFromDatabase
E/Babel   ( 8998): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 8998): MmsConfig.loadFromResources
E/Babel   ( 8998): canonicalizeMccMnc: invalid mccmnc nullnull
I/Babel   ( 8998): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N910C, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N910C.xml
D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
E/AffinityControl( 8989): AffinityControl: registerfunction enter
D/ResourcesManager( 8998): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
W/AudioCapabilities( 8998): Unsupported mime audio/mpeg-L1
W/AudioCapabilities( 8998): Unsupported mime audio/mpeg-L2
W/AudioCapabilities( 8998): Unsupported mime audio/x-ms-wma
D/AndroidRuntime( 8989): Calling main entry com.android.commands.am.Am
W/AudioCapabilities( 8998): Unsupported mime audio/x-ima
W/VideoCapabilities( 8998): Unrecognized profile/level 32768/2 for video/mp4v-es
W/VideoCapabilities( 8998): Unsupported mime video/wvc1
W/VideoCapabilities( 8998): Unsupported mime video/x-ms-wmv
W/VideoCapabilities( 8998): Unrecognized profile/level 32768/2 for video/mp4v-es
W/VideoCapabilities( 8998): Unsupported mime video/wvc1
W/VideoCapabilities( 8998): Unsupported mime video/x-ms-wmv
W/VideoCapabilities( 8998): Unsupported mime video/x-ms-wmv7
W/VideoCapabilities( 8998): Unsupported mime video/x-ms-wmv8
W/VideoCapabilities( 8998): Unsupported mime video/sorenson
E/PersonaManagerService( 3522): inState():  stateMachine is null !!
I/PersonaManagerService( 3522): PersonaId don't exist
I/ActivityManager( 3522): do not start freezing screen for locked container getKeyguardshowstate = false
W/VideoCapabilities( 8998): Unsupported mime video/mp43
I/ActivityManager( 3522): START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
D/AndroidRuntime( 8989): Shutting down VM
W/AudioCapabilities( 8998): Unsupported mime audio/mpeg-L1
W/AudioCapabilities( 8998): Unsupported mime audio/mpeg-L2
W/Settings( 8998): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
W/VideoCapabilities( 8998): Unrecognized profile/level 32768/2 for video/mp4v-es
I/art     ( 3522): Background partial concurrent mark sweep GC freed 352026(21MB) AllocSpace objects, 13(10MB) LOS objects, 22% free, 56MB/72MB, paused 15.239ms total 136.225ms
I/VideoCapabilities( 8998): Unsupported profile 4 for video/mp4v-es
D/GCM     ( 4650): GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
E/SQLiteLog( 8998): (284) automatic index on conversation_participants_view(conversation_id)
E/SQLiteLog( 8998): (284) automatic index on conversation_participants_view(conversation_id)
D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
E/SQLiteLog( 8998): (284) automatic index on conversation_participants_view(conversation_id)
W/GCoreFlp( 4650): No location to return for getLastLocation()
W/FusedLocationProvider( 4650): location=null
E/SQLiteLog( 8998): (284) automatic index on conversation_participants_view(conversation_id)
E/SQLiteLog( 8998): (284) automatic index on conversation_participants_view(conversation_id)
I/ActivityManager( 3522): Killing 8389:com.sec.esdk.elm/u0a106 (adj 13): bgCount ##31
,I/art     ( 6708): Explicit concurrent mark sweep GC freed 57113(3MB) AllocSpace objects, 44(704KB) LOS objects, 35% free, 29MB/45MB, paused 1.017ms total 30.480ms
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/ActivityManager( 3522): Waited long enough for: ServiceRecord{21b70a7 u0 com.trustonic.tuiservice/.TuiService}
,D/Widget  ( 8542): onReceive com.sec.android.snote.widget.ACTION_NOTE_UPDATE
,D/Widget  ( 8542): onReceive android.appwidget.action.APPWIDGET_UPDATE
,D/Widget  ( 8542): widgetUpdate 5
,D/RCPManagerService( 3522): exchangeData() failure , invalid userId
,D/SHealthUpgrade(SHealthUpgradeUtil)( 6961): isShealthServiceInstalled() : HealthService is Installed.
,D/SHealthUpgrade(SHealthUpgradeUtil)( 6961): isShealthService2xInstalled() : HEALTH SERVICE is INSTALLED.
D/SHealthUpgrade(SHealthUpgradeUtil)( 6961): isShealthService2xInstalled() : HEALTH SERVICE VERSION = 2.x
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/CscReceiver( 3985): onReceive android.intent.action.SIM_STATE_CHANGED
D/CscReceiver( 3985): Recieve Sim State Changed : ABSENT
,I/splitIntent( 3522): Split this intent : android.intent.action.SIM_STATE_CHANGED !!   mSplitNum[0]=4, mSplitNum[1]=7, mSplitNum[2]=10 divideNum= 2 r.nextReceiver= 1 receivers.size=12
I/splitIntent( 3522): finish to split intent : android.intent.action.SIM_STATE_CHANGED !! Enqueue -> schedule it!!
,W/BroadcastQueue( 3522): Permission Denial: broadcasting Intent { act=android.intent.action.SIM_STATE_CHANGED flg=0x20000010 (has extras) } from null (pid=3985, uid=1001) requires com.sec.android.permission.DSMLAWMO due to receiver com.fmm.dm/.XDMBroadcastReceiver
,I/WifiApBroadcastReceiver( 8489): onReceive: action android.intent.action.SIM_STATE_CHANGED
,D/StatusChecker( 8428): onReceive : android.intent.action.SIM_STATE_CHANGED
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9054): MountEmulatedStorage()
I/libpersona( 9054): KNOX_SDCARD checking this for 1000
E/Zygote  ( 9054): v2
I/libpersona( 9054): KNOX_SDCARD not a persona
,I/SELinux ( 9054): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9054): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9054): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.sec.modem.settings for broadcast com.sec.modem.settings/.cplogging.SilentLogReceiver: pid=9054 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,W/PackageManager( 3522): verifying app can be installed or not
D/ApplicationPolicy( 3522): isApplicationInstallationEnabled
,D/ApplicationPolicy( 3522): isApplicationInstallationEnabled :  Checking PKG WL - false
D/ApplicationPolicy( 3522): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy( 3522): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy( 3522): isApplicationInstallationEnabled :  Checking SIG BL - true
D/ApplicationPolicy( 3522): isApplicationInstallationEnabled :  Checking PKG WL - false
D/ApplicationPolicy( 3522): isApplicationInstallationEnabled :  Checking PKG BL - true
D/ApplicationPolicy( 3522): isApplicationInstallationEnabled :  Checking PERM BL - true
D/ApplicationPolicy( 3522): isApplicationInstallationEnabled :  Checking SIG BL - true
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/ApplicationPolicy( 3522): isApplicationInstallationEnabled :  enabled true
,I/AASAInstall( 3522): product true
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 8749(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 887us total 12.772ms
,D/TimaKeyStoreProvider( 9054): TimaSignature is unavailable
,D/ActivityThread( 9054): Added TimaKeyStore provider
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 308us total 8.921ms
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 306us total 8.547ms
,E/Zygote  ( 9069): MountEmulatedStorage()
I/libpersona( 9069): KNOX_SDCARD checking this for 10017
E/Zygote  ( 9069): v2
I/libpersona( 9069): KNOX_SDCARD not a persona
,I/SELinux ( 9069): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9069): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9069): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.PhoneStateReceiver: pid=9069 uid=10017 gids={50017, 9997, 3003} abi=armeabi-v7a
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/SettingsProvider( 3522): name = internet_call_settings_visibility
D/SettingsProvider( 3522): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3522): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3522): selectionArgs: false
D/SettingsProvider( 3522): selectionArgs: 1001
D/SecContentProvider( 3522): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3522): ret = -1
D/BootupListener( 3985): intent.getAction() = android.intent.action.SIM_STATE_CHANGED
,D/ResourcesManager( 9054): creating new AssetManager and set to /system/app/SilentLog/SilentLog.apk
,D/TimaKeyStoreProvider( 9069): TimaSignature is unavailable
,D/ActivityThread( 9069): Added TimaKeyStore provider
,E/Zygote  ( 9083): MountEmulatedStorage()
E/Zygote  ( 9083): v2
I/libpersona( 9083): KNOX_SDCARD checking this for 10156
I/libpersona( 9083): KNOX_SDCARD not a persona
,I/SELinux ( 9083): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9083): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.bookmarksDb.Controller.OperatorBookmarksSIMReceiver: pid=9083 uid=10156 gids={50156, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
E/SELinux ( 9083): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 9083): TimaSignature is unavailable
,D/ActivityThread( 9083): Added TimaKeyStore provider
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 9069): creating new AssetManager and set to /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk
,E/Zygote  ( 9099): MountEmulatedStorage()
E/Zygote  ( 9099): v2
I/libpersona( 9099): KNOX_SDCARD checking this for 1000
I/libpersona( 9099): KNOX_SDCARD not a persona
,I/SELinux ( 9099): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9099): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9099): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.sec.tcpdumpservice for broadcast com.sec.tcpdumpservice/.TcpDumpReceiver: pid=9099 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3522): Killing 7795:com.sec.spp.push/u0a39 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider( 9099): TimaSignature is unavailable
D/ResourcesManager( 9083): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ActivityThread( 9099): Added TimaKeyStore provider
,W/ResourcesManager( 9083): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 9083): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9083): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/Mms/SmsReceiver( 8788): filterMsgServiceIntent : intent.getAction() : android.intent.action.SIM_STATE_CHANGED
D/ResourcesManager( 9099): creating new AssetManager and set to /system/app/TcpdumpService/TcpdumpService.apk
,D/Mms/SmsReceiverService( 8788): onStart: #1, mResultCode: 0 = Unknown error code, action = android.intent.action.SIM_STATE_CHANGED
I/ActivityManager( 3522): Killing 8507:com.samsung.android.app.mirrorlink/1000 (adj 13): bgCount ##31
D/Mms/TelephonyPermission( 8788): isDefault true
D/Mms/SmsReceiverService( 8788): [SMS]Receiver handleMessage : Action =android.intent.action.SIM_STATE_CHANGED
D/Mms/SmsReceiverService( 8788): handleSIMStatus()
D/Mms/SmsReceiverService( 8788): handleSIMStatus(): SIM_STATUS = ABSENT
,I/ActivityManager( 3522): Killing 7381:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/art     ( 3522): Background partial concurrent mark sweep GC freed 285785(17MB) AllocSpace objects, 3(5MB) LOS objects, 23% free, 52MB/68MB, paused 2.607ms total 126.370ms
,I/Mms/MmsApp( 8788):  start initViewCache mms
,D/Mms/ComposeMessageFragment( 8788): [start]    fillCache consume time = 1951.636083
D/Mms/ComposeMessageFragment( 8788): fillCache, easy = false
,I/VerificationLog( 9083): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,E/OperatorBookmarksSIMReceiver( 9083): onReceive runs..android.intent.action.SIM_STATE_CHANGED
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9120): MountEmulatedStorage()
I/libpersona( 9120): KNOX_SDCARD checking this for 1000
E/Zygote  ( 9120): v2
I/libpersona( 9120): KNOX_SDCARD not a persona
,I/SELinux ( 9120): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3522): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=9120 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 9120): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9120): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Killing 8526:com.sec.factory/1000 (adj 13): bgCount ##31
,D/AbsListView( 8788): Get MotionRecognitionManager
,D/MotionRecognitionService( 3522):  ssp status : true
,D/TimaKeyStoreProvider( 9120): TimaSignature is unavailable
,D/Mms/ComposeMessageFragment( 8788): [end]    fillCache consume time = 57.636
D/ActivityThread( 9120): Added TimaKeyStore provider
,D/ResourcesManager( 9120): creating new AssetManager and set to /system/app/SecSetupWizard2013/SecSetupWizard2013.apk
,I/splitIntent( 3522): Queue : backgroundsplit_1 intent android.intent.action.SIM_STATE_CHANGED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 3522): Killing 7983:com.samsung.klmsagent/u0a21 (adj 13): bgCount ##31
,D/LocationWidgetUtils( 8445): getUpcommingInstances() start: 1457972205794, end: 1458514799999
,D/LocationWidgetUtils( 8445): getUpcommingInstances() DB begin time >= start:1457972205794, DB begin time <= end:1458514799999
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9139): MountEmulatedStorage()
,E/Zygote  ( 9139): v2
I/libpersona( 9139): KNOX_SDCARD checking this for 10047
I/libpersona( 9139): KNOX_SDCARD not a persona
,I/SELinux ( 9139): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9139): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9139): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=9139 uid=10047 gids={50047, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 9139): TimaSignature is unavailable
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 9139): Added TimaKeyStore provider
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9156): MountEmulatedStorage()
I/libpersona( 9156): KNOX_SDCARD checking this for 10037
E/Zygote  ( 9156): v2
I/libpersona( 9156): KNOX_SDCARD not a persona
,I/SELinux ( 9156): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9156): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9156): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.app.profile.SnsStatusStreamBroadcastReceiver: pid=9156 uid=10037 gids={50037, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/ActivityManager( 3522): Killing 8561:com.samsung.android.snote:provider/u0a160 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider( 9156): TimaSignature is unavailable
,D/ActivityThread( 9156): Added TimaKeyStore provider
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ResourcesManager( 9139): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,W/ResourcesManager( 9139): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,D/ResourcesManager( 9156): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,I/CalendarProvider2( 9139): CalendarProvider2.onCreate() called
,D/ResourcesManager( 9156): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/ResourcesManager( 9156): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 9156): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9156): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 9156): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 9156): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9156): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9156): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9156): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager( 9156): creating new AssetManager and set to /system/app/LegacyInCallUI/LegacyInCallUI.apk
,W/ResourcesManager( 9156): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 9156): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
,D/ResourcesManager( 9156): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
,W/ResourcesManager( 9156): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9156): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9156): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,D/Mms/BubbleViewCache( 8788): fillCache bubble = 8
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/AASAUninstall( 3522):  com.test.thalitest not target!
D/PackageManager( 3522): Renaming /data/app/vmdl368016632.tmp to /data/app/com.test.thalitest-1
,D/PackageManager( 3522): installNewPackageLI: Package{a9b9617 com.test.thalitest}
,I/SELinux ( 2864): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 2864): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/SELinux ( 2864): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 2864): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux ( 2864): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
E/SELinux ( 2864): [DEBUG] get_category: variable seinfo: app_data_file sensitivity: NULL, cateogry: NULL
,I/SELinux ( 2864): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 2864): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux ( 2864): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
E/SELinux ( 2864): [DEBUG] get_category: variable seinfo: app_data_file sensitivity: NULL, cateogry: NULL
,I/art     ( 3522): Background partial concurrent mark sweep GC freed 72051(3MB) AllocSpace objects, 2(32KB) LOS objects, 20% free, 63MB/79MB, paused 1.708ms total 120.695ms
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9188): MountEmulatedStorage()
I/libpersona( 9188): KNOX_SDCARD checking this for 10039
E/Zygote  ( 9188): v2
I/libpersona( 9188): KNOX_SDCARD not a persona
,I/SELinux ( 9188): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
I/SELinux ( 9188): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
I/ActivityManager( 3522): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.ForceUpdateAlarmReceiver: pid=9188 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 9188): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 9188): TimaSignature is unavailable
,D/ActivityThread( 9188): Added TimaKeyStore provider
,D/ResourcesManager( 9188): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,I/SELinux ( 2864): selinux_android_setcategory: no category for userid: 0, path: /data/data/com.test.thalitest/lib 
,I/art     ( 3522): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@app@com.test.thalitest-1@base.apk@classes.dex' for file location '/data/app/com.test.thalitest-1/base.apk': Failed to open oat filename for reading: No such file or directory
I/art     ( 3522): DexFile_isDexOptNeeded failed to open oat file '/data/app/com.test.thalitest-1/arm/base.odex' for file location '/data/app/com.test.thalitest-1/base.apk': Failed to open oat filename for reading: No such file or directory
D/PackageManager( 3522): Running dexopt on: /data/app/com.test.thalitest-1/base.apk pkg=com.test.thalitest isa=arm vmSafeMode=false interpret_only=false
,E/SPPClientService( 9188): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 9188): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 9188): PushLog.txt file is not deleted.
D/SPPClientService( 9188): PushLog.txt file is not deleted.
D/SPPClientService( 9188): ============PushLog. stop!
,E/SPPClientService( 9188): [ForceUpdateAlarmReceiver] Alarm Setting. After one day, it will alram.
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9206): MountEmulatedStorage()
I/libpersona( 9206): KNOX_SDCARD checking this for 10039
E/Zygote  ( 9206): v2
I/libpersona( 9206): KNOX_SDCARD not a persona
,I/SELinux ( 9206): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9206): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.sec.spp.push:RemoteDlcProcess for broadcast com.sec.spp.push/.dlc.sender.DlcRequestReceiver: pid=9206 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/WifiStateMachine( 3522): CMD_RSSI_POLL : calculateWifiScore in!
E/SELinux ( 9206): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/WifiStateMachine( 3522): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3522): CMD_RSSI_POLL : out!
,I/ActivityManager( 3522): Killing 8579:com.sec.android.app.SPenKeeper/u0a161 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider( 9206): TimaSignature is unavailable
,D/ActivityThread( 9206): Added TimaKeyStore provider
,D/ResourcesManager( 9206): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,I/dex2oat ( 9204): ----------------------------------------------------
I/dex2oat ( 9204): <SS>: S T A R T I N G . . .
I/dex2oat ( 9204): <SS>: going to process manifest for 32-bit...
,I/        ( 9204): SS_ART_lib [I]: Memory allocation: ctx
I/        ( 9204): SS_ART_lib [I]: Memory allocation: manifest_buf
I/        ( 9204): SS_ART_lib [I]: Parsing Manifest for SS stuff
I/        ( 9204): SS_ART_lib [I]: Memory allocation: ctx->libs
I/        ( 9204): SS_ART_lib [I]: Memory allocation: ctx->package_name
I/        ( 9204): SS_ART_lib [I]: Parsing completed
,I/        ( 9204): SS_ART_lib [I]: permission is absent: /data/app/com.test.thalitest-1/base.apk
I/        ( 9204): SS_ART_lib [I]: Closing zip file: /data/app/com.test.thalitest-1/base.apk
I/        ( 9204): SS_ART_lib [I]: access to SS denied
I/        ( 9204): SS_ART_lib [I]: ctx will be cleaned
I/        ( 9204): SS_ART_lib [I]: ctx component will be cleaned: ctx->libs
I/        ( 9204): SS_ART_lib [I]: ctx component is cleaned: ctx->libs
I/        ( 9204): SS_ART_lib [I]: ctx component will be cleaned: ctx->package_name
I/        ( 9204): SS_ART_lib [I]: ctx component is cleaned: ctx->package_name
I/        ( 9204): SS_ART_lib [I]: ctx is cleaned
,I/dex2oat ( 9204): /system/bin/dex2oat --zip-fd=11 --zip-location=/data/app/com.test.thalitest-1/base.apk --oat-fd=12 --art-fd=13 --oat-location=/data/dalvik-cache/arm/data@app@com.test.thalitest-1@base.apk@classes.dex --instruction-set=arm --instruction-set-features=div --runtime-arg -Xms64m --runtime-arg -Xmx512m
,E/SPPClientService( 9206): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 9206): [PushClientApplication] Push log off : This is Ship build version
,D/SPPClientService( 9206): PushLog.txt file is not deleted.
D/SPPClientService( 9206): PushLog.txt file is not deleted.
D/SPPClientService( 9206): ============PushLog. stop!
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9228): MountEmulatedStorage()
I/libpersona( 9228): KNOX_SDCARD checking this for 10039
E/Zygote  ( 9228): v2
I/libpersona( 9228): KNOX_SDCARD not a persona
,I/SELinux ( 9228): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9228): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9228): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PhoneStatusChangeReceiver: pid=9228 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3522): Killing 8597:com.sec.android.app.videoplayer/u0a56 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider( 9228): TimaSignature is unavailable
,D/ActivityThread( 9228): Added TimaKeyStore provider
,D/ResourcesManager( 9228): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/SPPClientService( 9228): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 9228): [PushClientApplication] Push log off : This is Ship build version
,E/LNoti   ( 9228): [PhoneStatusChangeReceiver] This device doesn't register yet.
,D/SPPClientService( 9228): PushLog.txt file is not deleted.
D/SPPClientService( 9228): PushLog.txt file is not deleted.
D/SPPClientService( 9228): ============PushLog. stop!
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/dex2oat ( 9204): Explicit concurrent mark sweep GC freed 785(206KB) AllocSpace objects, 0(0B) LOS objects, 69% free, 443KB/1467KB, paused 230us total 4.966ms
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/dex2oat ( 9204): dex2oat took 485.411ms (threads: 8)
,I/PackageManager( 3522): do mInstaller.dexopt : 0
D/PackageManager( 3522): Time to dexopt: 0.569 seconds
,W/System.err( 3522): java.io.FileNotFoundException: /data/app/com.test.thalitest-1: open failed: EISDIR (Is a directory)
,W/System.err( 3522): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/System.err( 3522): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/System.err( 3522): 	at android.content.pm.PackageParser.getHashValueOfPackage(PackageParser.java:5071)
W/System.err( 3522): 	at com.android.server.pm.PackageManagerService.saveHash(PackageManagerService.java:18002)
W/System.err( 3522): 	at com.android.server.pm.PackageManagerService.access$5100(PackageManagerService.java:322)
W/System.err( 3522): 	at com.android.server.pm.PackageManagerService$20.run(PackageManagerService.java:17987)
W/System.err( 3522): Caused by: android.system.ErrnoException: open failed: EISDIR (Is a directory)
W/System.err( 3522): 	at libcore.io.IoBridge.open(IoBridge.java:446)
W/System.err( 3522): 	... 5 more
,W/PackageSettings( 3522): Skipping PackageSetting{23997eba com.example.hello/10691} due to missing metadata
,D/PackageManager( 3522): New package installed
,I/CalendarProvider2( 9139): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,W/PackageSettings( 3522): Skipping PackageSetting{23997eba com.example.hello/10691} due to missing metadata
,I/HarmonyEASService( 3522): Updating for all 1
,D/PackageManager( 3522): doPostInstall for uid{10208}
,D/PackageManager( 3522): token 1 to BM for possible restore
V/BackupManagerService( 3522): restoreAtInstall pkg=com.test.thalitest token=1 restoreSet=0
V/BackupManagerService( 3522): Finishing install immediately
D/PackageManager( 3522): BM finishing package install for 1
,I/ActivityManager( 3522): Killing 8679:com.samsung.dcm:DCMService/u0a4 (adj 13): bgCount ##31
,D/PackageManager( 3522): [MSG] SEND_PENDING_BROADCAST
,D/PackageManager( 3522): [MSG] POST_INSTALL: observer{43961206}
D/PackageManager( 3522):           Handling post-install for 1
,D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
I/InputReader( 3522): Reconfiguring input devices.  changes=0x00000010
,I/PageBuddyNotiSvc( 4864): mCPBroadcastReceiver action=android.intent.action.PACKAGE_CHANGED mCpBitFlag=0
,D/ResourcesManager( 3985): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/ResourcesManager( 4001): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,I/LocationWidgetApplication( 8445): Intent.ACTION_PACKAGE_CHANGED has been called for com.google.android.gms
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager( 3985): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
W/ResourcesManager( 3985): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,W/Settings( 3522): Setting install_non_market_apps has moved from android.provider.Settings.Global to android.provider.Settings.Secure, returning read-only value.
,D/ResourcesManager( 5313): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Books/Books.apk
,W/ResourceType( 5313): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5313): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,I/InputReader( 3522): Reconfiguring input devices.  changes=0x00000010
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,E/SamsungIME( 4484): mOCRHelper is null
,D/RegisteredServicesCache( 3969): empty dynamic service
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,D/ResourcesManager( 5313): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/SecContentProvider2( 3522): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3522): mCursor = null
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,I/art     ( 3522): Explicit concurrent mark sweep GC freed 38255(3MB) AllocSpace objects, 9(144KB) LOS objects, 19% free, 64MB/80MB, paused 2.355ms total 156.656ms
D/PackageManager( 3522): result of install: 1{43961206}
,I/PackageManager( 3522): Observer no longer exists.
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager( 8445): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourceType( 5313): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
,W/ResourceType( 5313): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/RegisteredServicesCache( 3969): empty dynamic service
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/ResourcesManager( 4001): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,W/ResourcesManager( 8445): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8445): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8445): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8445): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/HancomOfficeViewer/HancomOfficeViewer.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/SecContentProvider2( 3522): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3522): mCursor = null
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,W/ResourceType( 3522): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Drive/Drive.apk
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/ResourcesManager( 8445): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,W/ResourcesManager( 3522): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3522): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3522): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3522): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/BackupManagerService( 3522): Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
I/BackupManagerService( 3522): Unbinding ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,I/BackupManagerService( 3522): Binding to transport host ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/Books/Books.apk
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/RCPManagerService( 3522): PackageReceiver onReceive()
D/RCPManagerService( 3522): App Installed with packageNAme = com.test.thalitest
E/RCPManagerService( 3522):  PackageReceiver onReceive() Failed to load meta-data, NullPointer: Attempt to invoke virtual method 'java.lang.String android.os.Bundle.getString(java.lang.String)' on a null object reference
D/RCPManagerService( 3522):  PackageReceiver onReceive() bundle null
,D/KnoxMUMContainerPolicy( 3522): mPackageReceiver : action - android.intent.action.PACKAGE_ADDED
D/BackupManagerService( 3522): Received broadcast Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,W/BackupManagerService( 3522): Removing schedule queue dupe of com.test.thalitest
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
V/EnterpriseBillingPolicy( 3522): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_ADDED
V/EnterpriseBillingPolicy( 3522): uID is 10208
V/EnterpriseBillingPolicy( 3522): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3522): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 3522): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3522): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3522): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3522): getBillingProfileForVpnEngine - start - com.test.thalitest
,V/EnterpriseBillingPolicyStorage( 3522): getBillingProfileForVpnEngine - end - null
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/PersonaPolicyManagerService( 3522): PersonaPolicyReceiver Receiver : android.intent.action.PACKAGE_ADDED
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/KnoxMUMContainerPolicy( 3522): packageInstalledForExternalStorage com.test.thalitest
,V/BackupManagerService( 3522): Connected to transport ComponentInfo{com.google.android.gms/com.google.android.gms.backup.BackupTransportService}
,V/BackupManagerService( 3522): Registering transport com.google.android.gms/.backup.BackupTransportService::com.google.android.gms/.backup.BackupTransportService = com.android.internal.backup.IBackupTransport$Stub$Proxy@3a183fba
,D/EnterpriseDeviceManagerService( 3522): Package has changed for user 0
D/EnterpriseDeviceManagerService( 3522): Admin package name: com.google.android.gms
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
,I/GCoreNlp( 4650): shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ResourceType( 3522): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
W/Resources( 3522): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/CrashAnrDetector( 3522): onPackageAdded : com.test.thalitest
,D/SettingsProvider( 3522): name = assisted_gps_enabled
D/SettingsProvider( 3522): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3522): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3522): selectionArgs: false
D/SettingsProvider( 3522): selectionArgs: 10014
D/SecContentProvider( 3522): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3522): ret = -1
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/Maps/Maps.apk
,I/System.out( 3522): Thread-155(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,D/LocationProviderProxy( 3522): applying state to connected service
,I/System.out( 3522): Thread-155(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 3522): Thread-155(ApacheHTTPLog):isShipBuild true
I/System.out( 3522): Thread-155(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/EnterpriseController( 2848): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2848): getNetworkForDns: using netid 502 for uid 1000
,D/LocationProviderProxy( 3522): applying state to connected service
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ResourcesManager( 8445): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager( 8445): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 8445): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 8445): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 8445): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 8445): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/Videos/Videos.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,D/LocationManagerService( 3522): getProviders()=[]
D/LocationManagerService( 3522): getProviders()=[passive]
D/LocationManagerService( 3522): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
,D/ResourcesManager( 8445): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/LWLocationManager( 8445): mPrivacy is null
,W/ContextImpl( 8445): Implicit intents with startService are not safe: Intent { act=com.samsung.android.providers.context.privacy.IPrivacyManager } android.content.ContextWrapper.bindService:559 com.samsung.android.providers.context.privacy.PrivacyManager.bindService:394 com.sec.android.widgetapp.locationwidget.data.LWLocationManager.bindPrivacyService:150 
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,D/ContextFramework:PrivacyManager( 8445): Service for PrivacyManager is connected
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/BluetoothManager( 6961): getConnectedDevices
D/BluetoothManager( 6961): getConnectedDevices
,D/LWLocationManager( 8445): Privacy service : STATUS_PLACE
D/LWLocationManager( 8445): updateLocationStatus()
,D/BluetoothManager( 6961): getConnectedDevices
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/LocationWidgetFuctionData( 8445): readDB
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
,I/LocationWidgetFuctionData( 8445): selectedAppSize: 3
I/LocationWidgetFuctionData( 8445): configPlaceList aroundMeItems
,D/BluetoothManager( 6961): getConnectedDevices
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/BluetoothManager( 6961): getConnectedDevices
,E/Zygote  ( 9271): MountEmulatedStorage()
,E/Zygote  ( 9271): v2
I/libpersona( 9271): KNOX_SDCARD checking this for 10003
I/libpersona( 9271): KNOX_SDCARD not a persona
I/SELinux ( 9271): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3522): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=9271 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 3006, 1007, 3001} abi=armeabi-v7a
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
I/SELinux ( 9271): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux ( 9271): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/BluetoothManager( 6961): getConnectedDevices
D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/TimaKeyStoreProvider( 9271): TimaSignature is unavailable
D/ActivityThread( 9271): Added TimaKeyStore provider
D/Widget  ( 8542): onReceive com.sec.android.snote.widget.ACTION_NOTE_UPDATE
D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
I/ActivityManager( 3522): Killing 8648:com.samsung.android.app.galaxyfinder:tagService/u0a35 (adj 13): bgCount ##31
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
,D/Widget  ( 8542): onReceive android.appwidget.action.APPWIDGET_UPDATE
,D/Widget  ( 8542): widgetUpdate 5
,D/RCPManagerService( 3522): exchangeData() failure , invalid userId
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
,D/ResourcesManager( 9271): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/Maps/Maps.apk
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/SQLiteLog( 9139): (284) automatic index on view_events(_id)
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/UserAnalysis.PlaceProvider( 9271): PlaceProvider onCreate()
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,D/UserAnalysis.SecureDbManager( 9271): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 9271): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider( 9271): Create SecureDbHelper
,E/Zygote  ( 9289): MountEmulatedStorage()
E/Zygote  ( 9289): v2
I/libpersona( 9289): KNOX_SDCARD checking this for 1000
I/libpersona( 9289): KNOX_SDCARD not a persona
,I/SELinux ( 9289): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3522): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/com.diagmondm.XDMBroadcastReceiver: pid=9289 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 9289): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
,E/SELinux ( 9289): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/IntelligenceServiceApplication( 9271): onCreate()
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 8764(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 888us total 22.349ms
,D/CalendarAlarmManager( 9139): sys current time:1457972208069
,D/CalendarAlarmManager( 9139): reminder amount:0
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 693us total 11.325ms
,D/TimaKeyStoreProvider( 9289): TimaSignature is unavailable,
,I/ActivityManager( 3522): Killing 8720:com.sec.android.app.music:service/u0a44 (adj 13): bgCount ##31
,D/ActivityThread( 9289): Added TimaKeyStore provider
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/ResourcesManager( 8445): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 504us total 9.744ms
,D/ResourcesManager( 8445): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,D/ResourcesManager( 9289): creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,I/LocationWidgetFuctionData( 8445): selectedAppSize: 3
,I/LocationWidgetFuctionData( 8445): selectedAppSize: 3
,I/LocationWidgetFuctionData( 8445): selectedAppSize: 3
,I/DIAGMON_AGENT( 9289): [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,I/LocationWidgetFuctionData( 8445): selectedAppSize: 3
,I/System.out( 3522): AsyncTask #3 calls detatch()
W/System.err( 3522): java.io.IOException: Not Found
,W/System.err( 3522): 	at a.d.b(Unknown Source)
W/System.err( 3522): 	at a.d.doInBackground(Unknown Source)
W/System.err( 3522): 	at android.os.AsyncTask$2.call(AsyncTask.java:288)
W/System.err( 3522): 	at java.util.concurrent.FutureTask.run(FutureTask.java:237)
W/System.err( 3522): 	at android.os.AsyncTask$SerialExecutor$1.run(AsyncTask.java:231)
W/System.err( 3522): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/System.err( 3522): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/System.err( 3522): 	at java.lang.Thread.run(Thread.java:818)
,E/LWLocationManager( 8445): findLocationType() : cursor_location.moveToFirst() return false!!
,D/LWLocationManager( 8445): Intent broadcast sent with action: com.sec.android.widgetapp.locationwidget.LOCATION_SOURCES_UPDATED
D/LWLocationManager( 8445): setShouldUpdateLocationId
D/LWLocationManager( 8445): setShouldUpdateLocationId return false
D/LWLocationManager( 8445): setShouldUpdateLocationId
D/LWLocationManager( 8445): setShouldUpdateLocationId return false
D/LWLocationManager( 8445): setShouldUpdateLocationId
D/LWLocationManager( 8445): setShouldUpdateLocationId return false
D/LWLocationManager( 8445): updateDeviceLocation() : lastDeviceLocationId = -100 mDeviceLocationId: -100 cocktailId: -1
,D/ResourcesManager( 8445): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,D/ResourcesManager( 8445): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,I/DIAGMON_AGENT( 9289): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,I/DIAGMON_AGENT( 9289): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,I/DIAGMON_AGENT( 9289): [com.diagmondm.XDMBroadcastReceiver(33/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,I/ActivityManager( 3522): Killing 8739:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31
,I/DBG_DM  ( 6257): [com.wssyncmldm.XDMBroadcastReceiver(153/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9304): MountEmulatedStorage()
I/libpersona( 9304): KNOX_SDCARD checking this for 1000
E/Zygote  ( 9304): v2
I/libpersona( 9304): KNOX_SDCARD not a persona
,I/SELinux ( 9304): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3522): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=9304 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 9304): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9304): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 9304): TimaSignature is unavailable
,D/ActivityThread( 9304): Added TimaKeyStore provider
,D/ResourcesManager( 9304): creating new AssetManager and set to /system/priv-app/MtpApplication/MtpApplication.apk
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/MTPRx   ( 9304): In MtpReceiverandroid.hardware.usb.action.USB_STATE
,D/SecContentProvider2( 3522): uri = 14 selection = getSealedState
D/SecContentProvider2( 3522): mCursor = null
,D/SecContentProvider2( 3522): uri = 14 selection = getSealedUsbMassStorageState
D/SecContentProvider2( 3522): mCursor = null
,V/MTPRx   ( 9304): sealedState: false
V/MTPRx   ( 9304): sealedUsbMassStorageState: false
E/MTPRx   ( 9304): check value of boot_completed is1
E/MTPRx   ( 9304): check booting is completed_sys.boot_completed
,E/MTPRx   ( 9304): Sd-Card path/storage/extSdCard
,E/MTPRx   ( 9304): Status for mount/Unmount :removed
E/MTPRx   ( 9304): SDcard is not available
,W/MTPRx   ( 9304): value of connected istrue
W/MTPRx   ( 9304): value of configured istrue
W/MTPRx   ( 9304): value of mtpEnabled isfalse
W/MTPRx   ( 9304): value of ptpEnabled istrue
,E/MTPRx   ( 9304): Received USB_STATE with sdCardLaunch = 0
,E/MTPRx   ( 9304): mFirstTime: false
,D/        ( 9304): MTP: reading debug level property
,E/MTPJNIInterface( 9304): Getting CryptionKey from JAVA
,E/MTPRx   ( 9304): currentUserId is 0
,E/MTPRx   ( 9304): Start observing USB_STATE_MATCH 
,E/MTPRx   ( 9304): usbMode is 0200
,E/MTPRx   ( 9304): is_Privatemode is NOT 1
,D/SettingsProvider( 3522): name = mtp_usb_conditions_met
,D/SecContentProvider( 3522): uri = 18 selection = isUsbMediaPlayerAvailable
E/MTPRx   ( 9304): sending PTP_ICON_ENABLED to stack 
,D/SettingsProvider( 3522): name = mtp_running_status
,D/SettingsProvider( 3522): name = mtp_usb_conditions_met
,E/MTPRx   ( 9304): else part ... so first time!!!
,E/MTPPlaObsrvr( 9304): inside setContext()
E/MTPPlaObsrvr( 9304):  inside createplafiles
,E/MTPPlaObsrvr( 9304): playlist count is0
E/MTPPlaObsrvr( 9304):  inside try branch createplafiles
,E/MTPPlaObsrvr( 9304):  inside deleteing plas createplafiles
,E/MTPPlaObsrvr( 9304): Inside registerContentObserver
,E/MtpAdbObserver( 9304): inside setContext()
E/MtpAdbObserver( 9304): Inside registerContentObserver
W/Settings( 9304): Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,D/SettingsProvider( 3522): name = mtp_running_status
,D/SettingsProvider( 3522): name = mtp_usb_conditions_met
,E/MtpService( 9304): onCreate.
,E/MtpService( 9304): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 9304): < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
,E/MtpService( 9304): < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,E/MtpService( 9304): onStartCommand.
,W/MTPRx   ( 9304): calling native method
E/MTPJNIInterface( 9304): < MTP > Registering BroadCast receiver :::::
,E/MtpService( 9304): handleMessage. msg= { when=0 what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
D/MtpService( 5420): updating state; isCurrentUser=true, mMtpLocked=false
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,E/Zygote  ( 9321): MountEmulatedStorage()
E/Zygote  ( 9321): v2
I/libpersona( 9321): KNOX_SDCARD checking this for 1000
I/libpersona( 9321): KNOX_SDCARD not a persona
,I/SELinux ( 9321): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3522): Start proc com.samsung.android.app.mirrorlink for broadcast com.samsung.android.app.mirrorlink/.TMNetworkReceiver: pid=9321 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 9321): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/MTPJNIInterface( 9304): < MTP > Registering BroadCast receiver :::::::
,E/SELinux ( 9321): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,E/MTPJNIInterface( 9304): noti = 11
,E/MtpService( 9304): onStartCommand.
,E/MtpService( 9304): handleMessage. msg= { when=0 what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
W/MTPRx   ( 9304): calling native method
E/MTPRx   ( 9304): Checking the driver time out
E/MTPJNIInterface( 9304): noti = 2
,D/        ( 9304): deleting sockets before message queue initialization
,D/        ( 9304): event handler thread is created, so set the flag
,E/MTPRx   ( 9304): called native method
E/MTPJNIInterface( 9304): setting Media scanner status0
E/MTPJNIInterface( 9304): After setting Media scanner status0
,W/MTPRx   ( 9304): notification from stack 1
,E/        ( 9304): Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
E/MTPJNIInterface( 9304): Getting media scanner status0
,E/MTPJNIInterface( 9304): DeviceName is Note4-1
,D/TimaKeyStoreProvider( 9321): TimaSignature is unavailable
,D/ActivityThread( 9321): Added TimaKeyStore provider
,D/ResourcesManager( 9321): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/TMNetworkReceiver( 9321): TMNetworkReceiver.TMNetworkReceiver() Enter 1 main
D/TMNetworkReceiver( 9321): TMNetworkReceiver.onReceive() Enter
D/TMNetworkReceiver( 9321): TMNetworkReceiver.onReceive() Action android.hardware.usb.action.USB_STATE
D/TMNetworkReceiver( 9321): TMNetworkReceiver.onReceive(): intent.getExtras() is not null
D/TMNetworkReceiver( 9321): TMNetworkReceiver.onReceive() on USB - connected:true, configured :true, mtp = false, mIsFileUpdated= false
D/TMNetworkReceiver( 9321): TMNetworkReceiver.onReceive() USB CONNECTED
D/TMNetworkReceiver( 9321): TMNetworkReceiver.onReceive() Exit 
,D/TMNetworkReceiver( 9321): TMNetworkReceiver.onReceive() UsbCheck Thread Enter
,D/TMSLogRemovalReceiver( 9321): TMLogRemovalReceiver.onReceive() Enter isCalled =false
D/TMSLogRemovalReceiver( 9321): TMLogRemovalReceiver.onReceive() action android.hardware.usb.action.USB_STATE
D/TMSLogRemovalReceiver( 9321): TMLogRemovalReceiver.onReceive() Exit
,I/ActivityManager( 3522): Killing 8614:com.google.android.music:main/u0a135 (adj 13): bgCount ##31
,D/MediaScannerReceiver( 5420): action: android.intent.action.MTP_FILE_SCAN
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9340): MountEmulatedStorage()
E/Zygote  ( 9340): v2
I/libpersona( 9340): KNOX_SDCARD checking this for 10173
I/libpersona( 9340): KNOX_SDCARD not a persona
,I/SELinux ( 9340): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9340): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9340): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=9340 uid=10173 gids={50173, 9997, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 9340): TimaSignature is unavailable
,D/ActivityThread( 9340): Added TimaKeyStore provider
,D/ResourcesManager( 9340): creating new AssetManager and set to /system/app/SamsungWidget_ActiveApplication/SamsungWidget_ActiveApplication.apk
,V/TaskCloserActivity( 9340): TaskCloserActivity enter()
,V/TaskCloserActivity( 9340): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,I/SettingSearch/SearchIntentReceiver( 8489): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
I/SettingSearch/SearchIntentReceiver( 8489): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,I/SettingSearch/SearchIntentReceiver( 8489): InitTitleDBThread start --> mDoingInitTitleDB : true
,I/SettingSearch/SearchIntentReceiver( 8489): action : android.settings.FINISH_SEARCHDB_EXTRA_APPS
I/SettingSearch/SearchIntentReceiver( 8489): FINISH_SEARCHDB_EXTRA_APPS call search titleinfo db init!!
,D/MediaScannerService( 5420): !@start scanning volume external: [/storage/emulated/0, /storage/extSdCard, /storage/Private, /storage/UsbDriveA, /storage/UsbDriveB, /storage/UsbDriveC, /storage/UsbDriveD, /storage/UsbDriveE, /storage/UsbDriveF]
,I/Avrcp   ( 5578): Received the onChange database event
I/Avrcp   ( 5578): onChange on thread: 1 Uri: content://media/ selfchange: false
I/Avrcp   ( 5578): send MSG_CHECK_NOW_PLAYING_CONTENT_CHANGED after 500ms
,D/MediaProvider( 5420): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 5420): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache existed
D/MediaProvider( 5420): savePlaylistTableInBulkDeleter started - audio_playlists_map_cache is empty
,D/MediaProvider( 5420): savePlaylistTableInBulkDeleter finished
,D/MediaProvider( 5420): savePlaylistTableInBulkDeleter started
,D/MediaProvider( 5420): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache existed
,D/MediaProvider( 5420): savePlaylistTableInBulkDeleter started - audio_playlists_map_personal_cache is empty
,D/MediaProvider( 5420): savePlaylistTableInBulkDeleter finished
,D/MediaScanner( 5420): Prescan. DB items number : 62 DB_FILES_NUMBER_CACHING_LIMITATION : 7000  Caching mode : true
,I/ActivityManager( 3522): Killing 8843:com.sec.android.app.popupuireceiver/1000 (adj 13): bgCount ##31
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/MediaScanner( 5420): processDirectory :  /storage/emulated/0
,D/MediaScanner( 5420): Skipping:
D/MediaScanner( 5420): 7klwibgf7fvntblfd7(75ebcf7
,D/MediaScanner( 5420): Skipping:
D/MediaScanner( 5420): 7klwibgf7fvntblfd7(7Budiwrd7dblb7
,I/iu.UploadsManager( 6708): #reloadSettings(); account: -1; IU: disabled; IS: disabled; IS account: -1; photoWiFi: true; videoWiFi: true; roam: false; battery: true; size: STANDARD; maxMobile: 157286400
,V/MediaScanner( 5420): processDirectory :  /storage/extSdCard
W/MediaScanner( 5420): Error opening directory, reason : Permission denied.
W/MediaScanner( 5420): 7klwibgf7fxlKdCbid7
,V/MediaScanner( 5420):  prescan time: 48ms (DB items: 62)
V/MediaScanner( 5420):     scan time: 28ms (Caching mode: true), (makeEntry time: 13ms ~46%),  (parsing time: 0ms ~0%),  (bitmapDecoding time: 0ms ~0%), (exifExtracting time : 0ms ~0%), (sefExtracting time : 0ms ~0%), (bulkInserter time : 0ms ~0%)
V/MediaScanner( 5420): postscan time: 4ms (bulkDeleter : 0), (delete DeadThumbnail time : 0ms)
V/MediaScanner( 5420):    total time: 80ms
V/MediaScanner( 5420): checked files: 19  directories : 36  (I: 0, U: 0)
,I/SettingSearch/SettingsSearchManager( 8489): Infomation -> numtitleinfo : 0 numSearchinfo : 367
,D/MediaScannerService( 5420): !@done scanning volume external
,E/MTPJNIInterface( 9304): In MTPJNIINterface onReceive:android.intent.action.MEDIA_SCANNER_FINISHED
,I/iu.UploadsManager( 6708): End new media; added: 0, uploading: 0, time: 90 ms
,I/SettingSearch/SettingsSearchManager( 8489):  Infomation -> getItem size : 367
,D/ResourcesManager( 8489): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager( 8489): creating new AssetManager and set to /system/priv-app/TeleService/TeleService.apk
,W/ResourcesManager( 8489): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 8489): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 8489): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 8489): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/BluetoothManager( 6961): getConnectedDevices
,D/ResourcesManager( 8489): creating new AssetManager and set to /system/app/AssistantMenu2/AssistantMenu2.apk
,D/BluetoothManager( 6961): getConnectedDevices
,D/BluetoothManager( 6961): getConnectedDevices
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/BluetoothManager( 6961): getConnectedDevices
,D/BluetoothManager( 6961): getConnectedDevices
,D/BluetoothManager( 6961): getConnectedDevices
,D/LocationWidgetUtils( 8445): getUpcommingInstances() start: 1457972208984, end: 1458514799999
D/LocationWidgetUtils( 8445): getUpcommingInstances() DB begin time >= start:1457972208984, DB begin time <= end:1458514799999
,D/LWLocationManager( 8445): getDeviceLocationId :  id = -100
D/LocationWidgetApplication( 8445): getLastUiLocationId() : mLastUiLocationId = -100
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9373): MountEmulatedStorage()
I/libpersona( 9373): KNOX_SDCARD checking this for 10035
E/Zygote  ( 9373): v2
I/libpersona( 9373): KNOX_SDCARD not a persona
,I/SELinux ( 9373): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9373): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=9373 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
E/SELinux ( 9373): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/TimaKeyStoreProvider( 9373): TimaSignature is unavailable
,D/ActivityThread( 9373): Added TimaKeyStore provider
,D/ResourcesManager( 9373): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,I/FeatureConfig( 9373): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,V/Avrcp   ( 5578): handleMessage, msg=207
D/BluetoothMediaBrowser( 5578):  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,D/BluetoothMediaBrowser( 5578): no now playing list
D/BluetoothMediaBrowser( 5578):  getNowPlayingId now playing id : -1
D/Avrcp   ( 5578):  checkNowPlayingList start
,D/ResourcesManager( 9373): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager( 9373): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 9373): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 9373): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 9373): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,W/ResourcesManager( 9373): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 9373): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 9373): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 9373): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/ResourcesManager( 9373): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,I/ActivityManager( 3522): Killing 8806:com.android.vending/u0a31 (adj 13): bgCount ##31
W/ResourcesManager( 9373): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager( 9373): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,W/ResourcesManager( 9373): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,E/Zygote  ( 9390): MountEmulatedStorage()
E/Zygote  ( 9390): v2
I/libpersona( 9390): KNOX_SDCARD checking this for 10050
I/libpersona( 9390): KNOX_SDCARD not a persona
D/ResourcesManager( 9373): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,I/SELinux ( 9390): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,W/ResourcesManager( 9373): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/ActivityManager( 3522): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=9390 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/SELinux ( 9390): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9390): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 9373): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 9373): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 9373): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 9373): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 9373): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,D/TimaKeyStoreProvider( 9390): TimaSignature is unavailable
,W/ResourcesManager( 9373): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ActivityThread( 9390): Added TimaKeyStore provider
,D/ResourcesManager( 9373): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,W/ResourcesManager( 9373): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/art     ( 3522): Explicit concurrent mark sweep GC freed 234341(15MB) AllocSpace objects, 23(9MB) LOS objects, 24% free, 48MB/64MB, paused 2.383ms total 166.014ms
,D/ResourcesManager( 9373): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,W/ResourcesManager( 9373): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/SettingSearch/SearchIntentReceiver( 8489): InitTitleDBThread end --> mDoingInitTitleDB : false
,I/SettingSearch/SearchIntentReceiver( 8489): LOCALE_CHANGED call search setting db finish!!
,D/ResourcesManager( 9390): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,D/ResourcesManager( 9373): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,W/ResourcesManager( 9390): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 9390): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/ResourcesManager( 9373): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/ResourcesManager( 9390): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 9390): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 9390): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
,W/ResourcesManager( 9390): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ResourcesManager( 9390): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 9373): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 9390): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager( 9373): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 9373): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,I/WifiStateMachine( 3522): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3522): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3522): CMD_RSSI_POLL : out!
,E/MTPJNIInterface( 9304): Status for mount/Unmount :removed
E/MTPJNIInterface( 9304): SDcard is not available
,D/ResourcesManager( 9373): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,W/ResourcesManager( 9373): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 9373): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/SettingSearch/SearchIntentReceiver( 8489): InitTitleDBThread start --> mDoingInitTitleDB : true
,W/GalaxyFinderApplication( 9373): system/finder_cp/cpdata.xml file not found
,E/        ( 9304): [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,E/MTPJNIInterface( 9304): Status for mount/Unmount :removed
E/MTPJNIInterface( 9304): SDcard is not available
,E/SQLiteLog( 9304): (21) API call with NULL database connection pointer
E/SQLiteLog( 9304): (21) misuse at line 105958 of [9491ba7d73]
E/SQLiteLog( 9304): (21) API call with NULL database connection pointer
E/SQLiteLog( 9304): (21) misuse at line 100622 of [9491ba7d73]
E/SQLiteLog( 9304): (21) API call with NULL database connection pointer
E/SQLiteLog( 9304): (21) misuse at line 100622 of [9491ba7d73]
E/SQLiteLog( 9304): (21) API call with NULL database connection pointer
E/SQLiteLog( 9304): (21) misuse at line 105958 of [9491ba7d73]
,W/MTPRx   ( 9304): notification from stack 2
,D/        ( 9304): [mtp_init_device] Library open with 32 bits.
D/        ( 9304): [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
,E/        ( 9304): [mtp_init_device 694]  After open the MTP fd = 32 and line = 694...
D/        ( 9304): [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
E/        ( 9304):  [sua_support_present:1277] returning false 
D/        ( 9304): *****Starting mtp_io()
,W/MTPRx   ( 9304): notification from stack 3
D/        ( 9304): [mtp_start_io] source_thread Creation 
D/        ( 9304): [mtp_start_io] sink_thread Creation 
,D/        ( 9304): [mtp_start_io:368] sink thread created so set th_sink
,I/SettingSearch/SearchIntentReceiver( 8489): InitTitleDBThread end --> mDoingInitTitleDB : false
I/SettingSearch/SearchIntentReceiver( 8489): LOCALE_CHANGED call search setting db finish!!
,D/PackageManager( 3522): findPreferredActivity: No PreferredActivities set
,D/SSRM:n  ( 3522): SIOP:: AP = 370, PST = 353, CUR = -783
,D/NearbySource( 9390): Nearby Source Create!
D/NearbyContext( 9390): Nearby Context Create!
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9390): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource( 9390): Samsung link source created
,D/WifiDisplayAdapter( 3522): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/ContactProvider( 9390): getAllContactInfoList Start
,D/WifiDisplayAdapter( 3522): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/UpdateIcingCorporaServi( 4039): Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,I/ActivityManager( 3522): Killing 8873:com.samsung.android.app.powersharing/u0a149 (adj 13): bgCount ##31
,I/GAV2    ( 8947): Thread[GAThread,5,main]: No campaign data found.
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9419): MountEmulatedStorage()
I/libpersona( 9419): KNOX_SDCARD checking this for 10079
E/Zygote  ( 9419): v2
I/libpersona( 9419): KNOX_SDCARD not a persona
,I/SELinux ( 9419): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9419): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3522): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=9419 uid=10079 gids={50079, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 9419): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/ContactProvider( 9390): getAllContactInfoList End
,I/syncContacts( 9390): thread: 1188, sync time = 93
,D/TimaKeyStoreProvider( 9419): TimaSignature is unavailable
,D/ActivityThread( 9419): Added TimaKeyStore provider
,D/ResourcesManager( 6708): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 9419): creating new AssetManager and set to /system/app/AllshareFileShareServer/AllshareFileShareServer.apk
,D/FileShare-Server( 9419): ServerBroadcastReceiver.onReceive - action android.intent.action.PACKAGE_CHANGED // package:com.google.android.gms
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/Zygote  ( 9436): MountEmulatedStorage()
E/Zygote  ( 9436): v2
I/libpersona( 9436): KNOX_SDCARD checking this for 1000
I/libpersona( 9436): KNOX_SDCARD not a persona
,I/SELinux ( 9436): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9436): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9436): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=9436 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3522): Killing 8890:com.sec.smartcard.manager/u0a187 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider( 9436): TimaSignature is unavailable
,D/ActivityThread( 9436): Added TimaKeyStore provider
,D/ResourcesManager( 9436): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
,W/ResourcesManager( 9436): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9451): MountEmulatedStorage()
E/Zygote  ( 9451): v2
I/libpersona( 9451): KNOX_SDCARD checking this for 1000
I/libpersona( 9451): KNOX_SDCARD not a persona
,I/SELinux ( 9451): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9451): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3522): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.shortcut.ShortcutReceiver: pid=9451 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux ( 9451): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/PackageManager( 3522): [MSG] MCS_UNBIND
,I/ActivityManager( 3522): Killing 8428:com.sec.android.app.mt/1000 (adj 13): bgCount ##31
,I/ActivityManager( 3522): Killing 9054:com.sec.modem.settings/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider( 9451): TimaSignature is unavailable
,D/ActivityThread( 9451): Added TimaKeyStore provider
,D/ResourcesManager( 9451): creating new AssetManager and set to /system/app/KnoxSetupWizardClient/KnoxSetupWizardClient.apk
,D/ShortcutReceiver( 9451):  ShortcutReceiver onReceive() intent: android.intent.action.PACKAGE_CHANGED
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9466): MountEmulatedStorage()
E/Zygote  ( 9466): v2
I/libpersona( 9466): KNOX_SDCARD checking this for 10147
I/libpersona( 9466): KNOX_SDCARD not a persona
,I/SELinux ( 9466): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9466): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9466): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.PackagesMediaMonitor: pid=9466 uid=10147 gids={50147, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3522): Killing 9069:com.google.android.partnersetup/u0a17 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider( 9466): TimaSignature is unavailable
,D/ActivityThread( 9466): Added TimaKeyStore provider
,E/Watchdog( 3522): !@Sync 1
,D/ResourcesManager( 9466): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/ResourcesManager( 9466): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/SettingsProvider( 3522): name = audio_safe_volume_state
,D/ResourcesManager( 4039): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,I/UpdateIcingCorporaServi( 4039): UpdateCorporaTask done [took 441 ms] updated apps [took 441 ms] 
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/PkgBroadcastIntentOp( 6708): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/PkgBroadcastIntentOp( 6708): Null package name or gms related package.  Ignoreing.
,E/Zygote  ( 9495): MountEmulatedStorage()
E/Zygote  ( 9495): v2
I/libpersona( 9495): KNOX_SDCARD checking this for 10031
I/libpersona( 9495): KNOX_SDCARD not a persona
,I/SELinux ( 9495): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3522): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=9495 uid=10031 gids={50031, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 9495): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9495): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:2, health:2, present:true, voltage: 4373, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:-712, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/TimaKeyStoreProvider( 9495): TimaSignature is unavailable
V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/ActivityThread( 9495): Added TimaKeyStore provider
,D/WearableController( 6708): Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,I/Icing   ( 6708): updateResources: need to parse f{com.google.android.gms}
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/ResourcesManager( 9495): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,V/GLSActivity( 4650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3692): applyOpen
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/Finsky  ( 9495): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,D/Finsky  ( 9495): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
W/Settings( 9495): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 9495): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Ads     ( 9495): Skipping gmscore version check
,D/Finsky  ( 9495): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 9495): [1] Libraries$2.run: Finished loading 1 libraries.
,D/Finsky  ( 9495): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/Finsky  ( 9495): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,E/Zygote  ( 9546): MountEmulatedStorage()
E/Zygote  ( 9546): v2
I/libpersona( 9546): KNOX_SDCARD checking this for 10063
I/libpersona( 9546): KNOX_SDCARD not a persona
,I/SELinux ( 9546): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9546): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=9546 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 9546): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Killing 9083:com.sec.android.app.sbrowser/u0a156 (adj 13): bgCount ##31
,I/ActivityManager( 3522): Waited long enough for: ServiceRecord{1b2a1f46 u0 com.sec.android.service.sm/.service.SecurityManagerService}
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 8767(373KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 872us total 24.359ms
,D/TimaKeyStoreProvider( 9546): TimaSignature is unavailable
,D/ActivityThread( 9546): Added TimaKeyStore provider
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ResourcesManager( 9546): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 1.269ms total 21.262ms
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 451us total 13.735ms
,D/VRSetupWizardStub/PackageIntentReceiver( 9546): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver( 9546): ACTION_PACKAGE_ADDED
,I/ActivityManager( 3522): Killing 9099:com.sec.tcpdumpservice/1000 (adj 13): bgCount ##31
,I/HomeSyncInstallReceiver( 3969): This pkg do not need BT addr. Do nothing
,I/splitIntent( 3522): Split this intent : android.intent.action.PACKAGE_ADDED !!   mSplitNum[0]=15, mSplitNum[1]=27, mSplitNum[2]=39 divideNum= 12 r.nextReceiver= 3 receivers.size=51
,I/splitIntent( 3522): finish to split intent : android.intent.action.PACKAGE_ADDED !! Enqueue -> schedule it!!
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9562): MountEmulatedStorage()
I/libpersona( 9562): KNOX_SDCARD checking this for 10017
E/Zygote  ( 9562): v2
I/libpersona( 9562): KNOX_SDCARD not a persona
,I/SELinux ( 9562): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9562): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.RlzPingBroadcastReceiver: pid=9562 uid=10017 gids={50017, 9997, 3003} abi=armeabi-v7a
,E/SELinux ( 9562): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 9562): TimaSignature is unavailable
,D/ActivityThread( 9562): Added TimaKeyStore provider
,E/Zygote  ( 9577): MountEmulatedStorage()
I/libpersona( 9577): KNOX_SDCARD checking this for 10101
E/Zygote  ( 9577): v2
I/libpersona( 9577): KNOX_SDCARD not a persona
,I/SELinux ( 9577): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9577): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=9577 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 9577): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 9577): TimaSignature is unavailable
,D/ResourcesManager( 9562): creating new AssetManager and set to /system/priv-app/GooglePartnerSetup/GooglePartnerSetup.apk
D/ActivityThread( 9577): Added TimaKeyStore provider
,D/ResourcesManager( 9577): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 6708): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,D/PkgBroadcastIntentOp( 6708): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,D/Mms/FreeMessageStatusReceiver( 8788): onReceive, action : android.intent.action.PACKAGE_ADDED
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/Mms/FreeMessageReceiverService( 8788): onHandleIntent, action : android.intent.action.PACKAGE_ADDED
D/Mms/FreeMessageReceiverService( 8788): onHandleIntent: ACTION_PACKAGE_ADDED
,E/Zygote  ( 9597): MountEmulatedStorage()
E/Zygote  ( 9597): v2
I/libpersona( 9597): KNOX_SDCARD checking this for 10019
I/libpersona( 9597): KNOX_SDCARD not a persona
,I/SELinux ( 9597): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9597): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=9597 uid=10019 gids={50019, 9997} abi=armeabi-v7a
,E/SELinux ( 9597): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/WearableController( 6708): Received broadcast action=android.intent.action.PACKAGE_ADDED and uri=com.test.thalitest
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,I/art     ( 6708): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.permission.PermissionUtils$1>
,D/TimaKeyStoreProvider( 9597): TimaSignature is unavailable
,E/Zygote  ( 9612): MountEmulatedStorage()
E/Zygote  ( 9612): v2
I/libpersona( 9612): KNOX_SDCARD checking this for 10053
D/ActivityThread( 9597): Added TimaKeyStore provider
I/libpersona( 9612): KNOX_SDCARD not a persona
,I/SELinux ( 9612): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9612): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9612): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=9612 uid=10053 gids={50053, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
,D/ResourcesManager( 9597): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,D/TimaKeyStoreProvider( 9612): TimaSignature is unavailable
,D/ActivityThread( 9612): Added TimaKeyStore provider
,D/com.sec.android.service.health.upgrade.UninstallReceiver( 9597): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver( 9597): onReceive called  PACKAGE_ADDED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver( 9597): onReceive() : package name is not s health. Return !!!
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 9612): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 9612): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 9612): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 9612): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  ( 9628): MountEmulatedStorage()
,E/Zygote  ( 9628): v2
I/libpersona( 9628): KNOX_SDCARD checking this for 1000
I/libpersona( 9628): KNOX_SDCARD not a persona
,I/SELinux ( 9628): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9628): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9628): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=9628 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 3522): Killing 9120:com.sec.android.app.SecSetupWizard/1000 (adj 13): bgCount ##31
,D/DocsApplication( 9577): Installing DEX configuration.
,D/TimaKeyStoreProvider( 9628): TimaSignature is unavailable
,D/ActivityThread( 9628): Added TimaKeyStore provider
,D/DexInstaller( 9577): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
,D/ResourcesManager( 9628): creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/PCWCLIENTTRACE_LOG( 9628): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 9628): DEFAULT_LOGLEVEL : 3
I/PCWCLIENTTRACE_DMDBOpenHelper( 9628): new DMDBOpenHelper instance
,I/ActivityManager( 3522): Killing 9156:com.sec.android.app.sns3/u0a37 (adj 13): bgCount ##31
,I/PackageInfoHelper( 9577): Provided clientMode=RELEASE, packageInfo=PackageInfo{1010f3fe com.google.android.apps.docs}
,I/PCWCLIENTTRACE_PushUtil( 9628): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 9628): sales region : global
I/PCWCLIENTTRACE_PushUtil( 9628): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 9628): [onReceive] - android.intent.action.PACKAGE_ADDED
,D/MyFiles ( 9612): MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
,D/TAG     ( 9577): onCreate()
,D/AsyncTaskServiceImpl( 6708): Submit a task: k
,I/TactileAssist( 3522): enable value -1
I/TactileAssist( 3522): internal enable value -1
I/TactileAssist( 3522): intensity value -1
I/TactileAssist( 3522): saveAppList value true
,I/TactileAssist( 3522): List of disabled apps :
,D/CrossAppStateProvider( 9577): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
,E/installd( 2864): system dir 0 : /system/app/
E/installd( 2864): system dir 1 : /system/priv-app/
E/installd( 2864): system dir 2 : /vendor/app/
E/installd( 2864): system dir 3 : /oem/app/
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/k       ( 6708): Processing package: com.test.thalitest
,E/Zygote  ( 9650): MountEmulatedStorage()
E/Zygote  ( 9650): v2
I/libpersona( 9650): KNOX_SDCARD checking this for 1000
I/libpersona( 9650): KNOX_SDCARD not a persona
,I/SELinux ( 9650): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3522): Start proc com.policydm for broadcast com.policydm/.XSPPReceiver: pid=9650 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 9650): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9650): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/PackageManager( 3522): remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
,D/GassUtils( 6708): Found app info for package com.test.thalitest:19. Hash: 3a6332e64e629141c2a938dcd325767951fafbc70df540f2afadc7f283ec0db2
,D/k       ( 6708): Found info for package com.test.thalitest in db.
,D/TimaKeyStoreProvider( 9650): TimaSignature is unavailable
,D/ActivityThread( 9650): Added TimaKeyStore provider
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9668): MountEmulatedStorage()
E/Zygote  ( 9668): v2
I/libpersona( 9668): KNOX_SDCARD checking this for 10059
I/libpersona( 9668): KNOX_SDCARD not a persona
,I/SELinux ( 9668): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9668): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9668): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=9668 uid=10059 gids={50059, 9997, 3003, 3002} abi=armeabi-v7a
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/TimaKeyStoreProvider( 9668): TimaSignature is unavailable
,D/ActivityThread( 9668): Added TimaKeyStore provider
,D/ResourcesManager( 9650): creating new AssetManager and set to /system/priv-app/SPDClient/SPDClient.apk
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 9668): creating new AssetManager and set to /system/priv-app/SoundAlive_20_L/SoundAlive_20_L.apk
,W/ResourcesManager( 9668): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,E/Zygote  ( 9684): MountEmulatedStorage()
E/Zygote  ( 9684): v2
I/libpersona( 9684): KNOX_SDCARD checking this for 10010
I/libpersona( 9684): KNOX_SDCARD not a persona
I/SELinux ( 9684): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux ( 9684): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux ( 9684): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.facebook.system for broadcast com.facebook.system/com.facebook.oxygen.installer.service.PackageReceiver: pid=9684 uid=10010 gids={50010, 9997} abi=armeabi-v7a
,W/BaseAppContext( 6708): Using Auth Proxy for data requests.
W/BaseAppContext( 6708): Using Auth Proxy for data requests.
,I/ActivityManager( 3522): Killing 9188:com.sec.spp.push/u0a39 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider( 9684): TimaSignature is unavailable
,D/ActivityThread( 9684): Added TimaKeyStore provider
,D/Compatibility( 9668): onReceive() it will make start service
,I/Icing   ( 6708): Indexing 24C12EC0A8A9103D64E8433CB9B0F00F2CE53D26 from com.google.android.gms
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 9684): creating new AssetManager and set to /data/app/com.facebook.system-1/base.apk
,E/Zygote  ( 9703): MountEmulatedStorage()
I/libpersona( 9703): KNOX_SDCARD checking this for 10035
E/Zygote  ( 9703): v2
I/libpersona( 9703): KNOX_SDCARD not a persona
,I/SELinux ( 9703): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9703): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9703): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.samsung.android.app.galaxyfinder:tagService for service com.samsung.android.app.galaxyfinder/.tag.TagReadyService: pid=9703 uid=10035 gids={50035, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,D/Compatibility( 9668): onHandleIntent()
,D/Compatibility( 9668): intentservice saw: Intent { act=android.intent.action.PACKAGE_ADDED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.UID=10208, android.intent.extra.user_handle=0}]
,D/Compatibility( 9668): found: 2
,I/UpdateIcingCorporaServi( 4039): Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,D/Compatibility( 9668): saved default: com.sec.android.app.soundalive.SAControlPanelActivity
D/Compatibility( 9668): skipping ResolveInfo{3603775f com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
D/Compatibility( 9668): considering ResolveInfo{52f5ac com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
D/Compatibility( 9668): default: com.sec.android.app.soundalive.SAControlPanelActivity
,D/Compatibility( 9668): enabling receiver ResolveInfo{19353275 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,D/TimaKeyStoreProvider( 9703): TimaSignature is unavailable
,D/ActivityThread( 9703): Added TimaKeyStore provider
,D/Compatibility( 9668): enabling receiver ResolveInfo{2c84520a com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,W/ContextImpl( 8925): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:147 android.app.ActivityThread.handleReceiver:2994 
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
,D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/Compatibility( 9668): enabling receiver ResolveInfo{3122a7b com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/Compatibility( 9668): enabling receiver ResolveInfo{2dcfc098 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,E/Zygote  ( 9723): MountEmulatedStorage()
E/Zygote  ( 9723): v2
I/libpersona( 9723): KNOX_SDCARD checking this for 10039
I/libpersona( 9723): KNOX_SDCARD not a persona
,I/SELinux ( 9723): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/Compatibility( 9668): wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,I/ActivityManager( 3522): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=9723 uid=10039 gids={50039, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 9723): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux ( 9723): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 9703): creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,I/art     ( 3522): Explicit concurrent mark sweep GC freed 31536(2000KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 48MB/64MB, paused 2.319ms total 143.766ms
,I/ActivityManager( 3522): Killing 9206:com.sec.spp.push:RemoteDlcProcess/u0a39 (adj 13): bgCount ##31
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 9723): TimaSignature is unavailable
,D/Finsky  ( 9495): [1] ExternalReferrer.access$200: Package state data is missing for com.test.thalitest
D/ActivityThread( 9723): Added TimaKeyStore provider
,D/ResourcesManager( 4039): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,I/art     ( 4125): Explicit concurrent mark sweep GC freed 3709(147KB) AllocSpace objects, 0(0B) LOS objects, 22% free, 27MB/35MB, paused 2.975ms total 32.850ms
,E/Zygote  ( 9740): MountEmulatedStorage()
E/Zygote  ( 9740): v2
I/libpersona( 9740): KNOX_SDCARD checking this for 10114
I/libpersona( 9740): KNOX_SDCARD not a persona
,I/SELinux ( 9740): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9740): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9740): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.facebook.katana for broadcast com.facebook.katana/com.facebook.feed.platformads.AppInstallReceiver: pid=9740 uid=10114 gids={50114, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 8749(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 776us total 24.324ms
,I/FeatureConfig( 9703): init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,I/ActivityManager( 3522): Killing 9228:com.sec.spp.push:RemoteNotiProcess/u0a39 (adj 13): bgCount ##31
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 513us total 16.074ms
,D/TimaKeyStoreProvider( 9740): TimaSignature is unavailable
,D/ActivityThread( 9740): Added TimaKeyStore provider
,W/BaseAppContext( 6708): Using Auth Proxy for data requests.
,D/ResourcesManager( 9703): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,D/ResourcesManager( 6708): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 510us total 9.894ms
,W/ResourcesManager( 9703): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,D/ResourcesManager( 9723): creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,W/ResourcesManager( 9703): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9703): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,W/ResourcesManager( 9703): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 9703): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 9703): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/PeopleDatabaseHelper( 6708): cleanUpNonGplusAccounts done.
,W/BaseAppContext( 6708): Using Auth Proxy for data requests.
,D/ResourcesManager( 9703): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
,D/ResourcesManager( 9740): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,I/ActivityManager( 3522): Killing 9271:com.samsung.android.intelligenceservice/u0a3 (adj 13): bgCount ##31
,W/ResourcesManager( 9703): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 9703): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,W/ResourcesManager( 9703): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ResourcesManager( 9703): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 9703): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 9703): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 9703): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 9703): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9703): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9703): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9703): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager( 9703): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,D/Icing   ( 6708): Loaded CLD2 Version V2.0 - 20141016
,D/ResourcesManager( 9703): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager( 9703): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9703): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9703): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9703): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,E/SPPClientService( 9723): ============PushLog. commonIsShipBuild. stop!
E/SPPClientService( 9723): [PushClientApplication] Push log off : This is Ship build version
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 9703): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
D/SPPClientService( 9723): PushLog.txt file is not deleted.
D/SPPClientService( 9723): PushLog.txt file is not deleted.
D/SPPClientService( 9723): ============PushLog. stop!
,W/ResourcesManager( 9703): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 9703): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9703): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager( 9703): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,W/ResourcesManager( 9703): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9703): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9703): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 9703): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9703): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 9703): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 9703): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 9703): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 9703): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
,W/ResourcesManager( 9703): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9703): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 9703): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/ResourcesManager( 9703): creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,W/ResourcesManager( 9703): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 9703): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9703): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 9703): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9703): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 9703): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,W/ResourcesManager( 9703): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 9703): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9703): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/Zygote  ( 9767): MountEmulatedStorage()
E/Zygote  ( 9767): v2
I/libpersona( 9767): KNOX_SDCARD checking this for 10042
I/libpersona( 9767): KNOX_SDCARD not a persona
,D/ResourcesManager( 9703): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
I/SELinux ( 9767): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,W/ResourcesManager( 9703): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,I/ActivityManager( 3522): Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=9767 uid=10042 gids={50042, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 9767): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9767): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 9703): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,I/UpdateIcingCorporaServi( 4039): UpdateCorporaTask done [took 298 ms] updated apps [took 298 ms] 
,W/ResourcesManager( 9703): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 9703): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9703): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 9703): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9703): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager( 9703): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ResourcesManager( 9740): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/BaseAppContext( 6708): Using Auth Proxy for data requests.
,D/ResourcesManager( 9703): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,I/ActivityManager( 3522): Killing 8542:com.samsung.android.snote/u0a160 (adj 13): bgCount ##31
,D/ResourcesManager( 9703): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,I/Icing   ( 6708): Indexing done 24C12EC0A8A9103D64E8433CB9B0F00F2CE53D26
,D/TimaKeyStoreProvider( 9767): TimaSignature is unavailable
,W/ResourcesManager( 9703): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager( 9703): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ActivityThread( 9767): Added TimaKeyStore provider
W/ResourcesManager( 9703): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/ResourcesManager( 9703): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager( 9703): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 9703): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 9703): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 9703): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager( 9703): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9703): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,D/ResourcesManager( 9703): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
,W/ResourcesManager( 9703): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 9703): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ResourcesManager( 9767): creating new AssetManager and set to /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk
,W/GalaxyFinderApplication( 9703): system/finder_cp/cpdata.xml file not found
,W/ResourcesManager( 9767): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 9767): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,I/AppStateLoggerExceptionHandler( 9740): Installed uncaught exception handler for app state logging
,D/AppStateLogger( 9740): Attempting to open app state logging file
,D/AppStateLogger( 9740): Successfully opened app state logging file: /data/data/com.facebook.katana/app_state_logs/5b8b5ab7-ffc2-e963-0656-6f993c3b26ab.txt
,D/ACRA    ( 9740): ACRA is enabled for com.facebook.katana, intializing...
,V/fb-UnpackingSoSource( 9740): locked dso store /data/data/com.facebook.katana/lib-main
I/fb-UnpackingSoSource( 9740): dso store is up-to-date: /data/data/com.facebook.katana/lib-main
V/fb-UnpackingSoSource( 9740): releasing dso store lock for /data/data/com.facebook.katana/lib-main
,V/fb-UnpackingSoSource( 9740): locked dso store /data/data/com.facebook.katana/lib-assets
,I/fb-UnpackingSoSource( 9740): dso store is up-to-date: /data/data/com.facebook.katana/lib-assets
V/fb-UnpackingSoSource( 9740): releasing dso store lock for /data/data/com.facebook.katana/lib-assets
,V/fb-UnpackingSoSource( 9740): locked dso store /data/data/com.facebook.katana/lib-xzs
I/fb-UnpackingSoSource( 9740): dso store is up-to-date: /data/data/com.facebook.katana/lib-xzs
V/fb-UnpackingSoSource( 9740): releasing dso store lock for /data/data/com.facebook.katana/lib-xzs
,I/art     ( 9740): Thread[1,tid=9740,WaitingForJniOnLoad,Thread*=0xb4e08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/app/com.facebook.katana-2/lib/arm/libfbjni.so"
,V/appstatelogger( 9740): Registered App State Logger stream with Breakpad
,V/MemoryEnlargementHack( 9740): largeHeap already enabled in manifest
V/DexLibLoader( 9740): DLL.loadAll betaBuild:false flags:0x00000004
,V/dalvik-internals( 9740): hooked _ZN3art12FaultManager35EnsureArtActionInFrontOfSignalChainEv using jump ()
V/dalvik-internals( 9740): hooked signal using trap ()
V/dalvik-internals( 9740): hooked sysv_signal using trap ()
V/dalvik-internals( 9740): hooked bsd_signal using trap ()
V/dalvik-internals( 9740): hooked sigaction using jump ()
V/dalvik-internals( 9740): hooked _ZN3art6mirror5Class19FindInterfaceMethodEPKNS0_8DexCacheEj using jump ()
V/dalvik-internals( 9740): hooked _ZN3art6mirror5Class25FindDeclaredVirtualMethodEPKNS0_8DexCacheEj using jump ()
V/dalvik-internals( 9740): hooked _ZN3art6mirror5Class17FindVirtualMethodEPKNS0_8DexCacheEj using jump ()
D/DexLibLoader( 9740): patched ART 5.0.x miranda bug
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/DexLibLoader( 9740): opening dex store /data/data/com.facebook.katana/dex
,V/DexLibLoader( 9740): Secondary program dex metadata: [.root_relative]
V/DexLibLoader( 9740): Secondary program dex metadata: [.locators]
V/DexLibLoader( 9740): Secondary program dex metadata: [classes2.dex 102b05d6536f178eac593d7d65578de2ddd6825a secondary.dex01.Canary]
V/DexLibLoader( 9740): Secondary program dex metadata: [classes3.dex 857a97620767f7e63fa9c0527067cd6c7a002041 secondary.dex02.Canary]
V/DexLibLoader( 9740): Secondary program dex metadata: [classes4.dex 9935231bfc9137654b613e0c3ad23e5d3c069eb5 secondary.dex03.Canary]
V/DexLibLoader( 9740): Secondary program dex metadata: [classes5.dex 08fa37bfdbdd915e303997b9b9eee7d09b51c215 secondary.dex04.Canary]
V/DexLibLoader( 9740): Secondary program dex metadata: [classes6.dex 82b91dbe59da3b655a867a417fbb83d9fc617838 secondary.dex05.Canary]
V/DexLibLoader( 9740): Secondary program dex metadata: [classes7.dex a8a078ec908ddaee0545b2315081ac33b68f213a secondary.dex06.Canary]
V/DexLibLoader( 9740): Secondary program dex metadata: [classes8.dex 294c9ad6031509e29eb40eb619940d45eeb3c245 secondary.dex07.Canary]
V/DexLibLoader( 9740): Secondary program dex metadata: [classes9.dex 43850a0126da4bbcbaf22e20c7357a75cf3a71aa secondary.dex08.Canary]
V/DexLibLoader( 9740): Secondary program dex metadata: [classes10.dex 3c65d9974656bb0f434d5d9e03c6534a2f64b58a secondary.dex09.Canary]
V/DexLibLoader( 9740): Secondary program dex metadata: [classes11.dex 5501f6915e13d4353ae2cf4cb583284b418d46c4 secondary.dex10.Canary]
,V/DexLibLoader( 9740): read status:9 check:faceb007faceb00e
,V/DexLibLoader( 9740): read saved dep file /data/data/com.facebook.katana/dex/deps (176 bytes)
V/DexLibLoader( 9740): verified deps file
I/DexLibLoader( 9740): current scheme: com.facebook.common.dextricks.OdexSchemeNoop next step: LA_LOAD_EXISTING
,V/MultiDexClassLoader( 9740): installing MultiDexClassLoader before application classloader
,D/MultiDexClassLoader( 9740): primary dex name: /data/app/com.facebook.katana-2/base.apk
D/MultiDexClassLoader( 9740): Found system/other dex /system/framework/com.google.android.maps.jar
D/MultiDexClassLoader( 9740): Found primary dex /data/app/com.facebook.katana-2/base.apk
D/MultiDexClassLoader( 9740): Setup multi dex took 0 ms.
V/DexLibLoader( 9740): optimization needed: no
,D/MemoryReductionHack( 9740): Marked as initialized entry corresponding to path /data/app/com.facebook.katana-2/base.apk
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,W/GAV2    ( 9577): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/Zygote  ( 9801): MountEmulatedStorage()
E/Zygote  ( 9801): v2
I/libpersona( 9801): KNOX_SDCARD checking this for 10102
I/libpersona( 9801): KNOX_SDCARD not a persona
,I/SELinux ( 9801): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9801): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9801): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.sec.android.automotive.drivelink for broadcast com.sec.android.automotive.drivelink/com.sec.android.app.automotive.carmode.framework.manager.update.UpdateManagerReceiver: pid=9801 uid=10102 gids={50102, 9997, 3002, 1028, 1015, 3001, 3003} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 9801): TimaSignature is unavailable
,D/ActivityThread( 9801): Added TimaKeyStore provider
,D/ResourcesManager( 9801): creating new AssetManager and set to /system/app/DriveLink/DriveLink.apk
,W/ResourcesManager( 9801): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/GMPM    ( 9740): App measurement is starting up
,I/SL_DEBUG( 9767): isLoggable:: isProductShip = 1
,I/SL_DEBUG( 9767): isLoggable:: SL_DEBUG_EXIST = false
,E/GMPM    ( 9740): getGoogleAppId failed with status: 10
,E/GMPM    ( 9740): Uploading is not possible. App measurement disabled
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/[CarMode]( 9801): [DLApplication]-onCreate: Applicatino Started!
,D/SampleAppCoreManager( 9801): SampleAppCoreManager VACVersion '2.2.0.11867'
D/SampleAppCoreManager( 9801): mContext is not null
,I/VlingoAndroidCore( 9801): AppName: SamsungCCTproject, Core: 2.2.0.11867, SDK: 2.0.1017, EDM:11867
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9825): MountEmulatedStorage()
E/Zygote  ( 9825): v2
I/libpersona( 9825): KNOX_SDCARD checking this for 10034
I/libpersona( 9825): KNOX_SDCARD not a persona
,I/SELinux ( 9825): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9825): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9825): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.vlingo.midas for content provider com.vlingo.midas/.provider.VlingoConfigProvider: pid=9825 uid=10034 gids={50034, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 9825): TimaSignature is unavailable
,D/ActivityThread( 9825): Added TimaKeyStore provider
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9767): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/files
,D/ResourcesManager( 9825): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9767): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.android.sdk.samsunglink/cache
,W/StaticBindingVerifier( 9740): Verify
,V/Transcoder( 9767): Transcoder(0xaeff1560)::constructor
V/Transcoder( 9767): addObitRecipient
V/TMI-JNI ( 9767): Mobile Transcoder JNI version 1.6.0/20131120/4.4
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 9854): MountEmulatedStorage()
I/libpersona( 9854): KNOX_SDCARD checking this for 10045
E/Zygote  ( 9854): v2
I/libpersona( 9854): KNOX_SDCARD not a persona
,I/SELinux ( 9854): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9854): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3522): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.app.pushmarketing.PushMarketingReceiver: pid=9854 uid=10045 gids={50045, 9997, 3003, 1028, 1015} abi=armeabi-v7a
E/SELinux ( 9854): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/System.out( 9825): Inside WakeupProvider
,E/DatabaseUtils( 9825): Writing exception to parcel
E/DatabaseUtils( 9825): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 9825): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 9825): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 9825): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1535)
E/DatabaseUtils( 9825): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 9825): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 9825): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 9825): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/DatabaseUtils( 9825): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/DatabaseUtils( 9825): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 9825): 	at android.os.Binder.execTransact(Binder.java:446)
,W/System.err( 9801): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
,W/System.err( 9801): 	at android.os.Parcel.readException(Parcel.java:1546)
,W/System.err( 9801): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 9801): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 9801): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
,W/System.err( 9801): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 9801): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 9801): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 9801): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 9801): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 9801): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 9801): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 9801): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 9801): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterLanguage(InternalMdsoUtils.java:134)
W/System.err( 9801): 	at com.vlingo.core.internal.lmtt.event.LmttEventHandler.onCoreInitialization(LmttEventHandler.java:176)
W/System.err( 9801): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:625)
W/System.err( 9801): 	at com.vlingo.core.internal.VlingoAndroidCore.init(VlingoAndroidCore.java:118)
W/System.err( 9801): 	at com.vlingo.core.facade.CoreManager.initCore(CoreManager.java:70)
W/System.err( 9801): 	at com.nuance.sample.coreaccess.SampleAppCoreManager.initCore(SampleAppCoreManager.java:131)
W/System.err( 9801): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:197)
W/System.err( 9801): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:126)
W/System.err( 9801): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 9801): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
W/System.err( 9801): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
W/System.err( 9801): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
W/System.err( 9801): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 9801): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 9801): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err( 9801): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 9801): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 9801): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 9801): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/DatabaseUtils( 9825): Writing exception to parcel
E/DatabaseUtils( 9825): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
E/DatabaseUtils( 9825): 	at android.preference.PreferenceManager.getDefaultSharedPreferencesName(PreferenceManager.java:374)
E/DatabaseUtils( 9825): 	at android.preference.PreferenceManager.getDefaultSharedPreferences(PreferenceManager.java:369)
E/DatabaseUtils( 9825): 	at com.vlingo.core.internal.settings.Settings.getSharedPreferences(Settings.java:1535)
E/DatabaseUtils( 9825): 	at com.vlingo.midas.provider.VlingoConfigProvider.queryInternal(VlingoConfigProvider.java:167)
E/DatabaseUtils( 9825): 	at com.vlingo.midas.provider.VlingoConfigProvider$VlingoConfigProviderQueryProxy.query(VlingoConfigProvider.java:322)
E/DatabaseUtils( 9825): 	at com.vlingo.midas.provider.VlingoConfigProvider.query(VlingoConfigProvider.java:148)
E/DatabaseUtils( 9825): 	at android.content.ContentProvider.query(ContentProvider.java:987)
E/DatabaseUtils( 9825): 	at android.content.ContentProvider$Transport.query(ContentProvider.java:217)
E/DatabaseUtils( 9825): 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:112)
E/DatabaseUtils( 9825): 	at android.os.Binder.execTransact(Binder.java:446)
D/TimaKeyStoreProvider( 9854): TimaSignature is unavailable
W/System.err( 9801): java.lang.NullPointerException: Attempt to invoke virtual method 'java.lang.String android.content.Context.getPackageName()' on a null object reference
W/System.err( 9801): 	at android.os.Parcel.readException(Parcel.java:1546)
W/System.err( 9801): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:185)
W/System.err( 9801): 	at android.database.DatabaseUtils.readExceptionFromParcel(DatabaseUtils.java:137)
W/System.err( 9801): 	at android.content.ContentProviderProxy.query(ContentProviderNative.java:420)
W/System.err( 9801): 	at android.content.ContentResolver.query(ContentResolver.java:484)
W/System.err( 9801): 	at android.content.ContentResolver.query(ContentResolver.java:428)
W/System.err( 9801): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getCursor(ApplicationQueryManager.java:169)
W/System.err( 9801): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.providerBaseIsWorking(ApplicationQueryManager.java:62)
W/System.err( 9801): 	at com.vlingo.core.internal.associatedservice.ApplicationQueryManager.getValue(ApplicationQueryManager.java:108)
W/System.err( 9801): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getSetting(InternalMdsoUtils.java:250)
W/System.err( 9801): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getBooleanSetting(InternalMdsoUtils.java:242)
W/System.err( 9801): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.getMasterConfigProvider(InternalMdsoUtils.java:212)
W/System.err( 9801): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.otherMasterExists(InternalMdsoUtils.java:98)
W/System.err( 9801): 	at com.vlingo.core.internal.lmtt.event.InternalMdsoUtils.isSlave(InternalMdsoUtils.java:32)
W/System.err( 9801): 	at com.vlingo.core.facade.lmtt.MdsoUtils.isSlave(MdsoUtils.java:13)
W/System.err( 9801): 	at com.nuance.drivelink.DLAppUiUpdater.init(DLAppUiUpdater.java:242)
W/System.err( 9801): 	at com.sec.android.automotive.drivelink.DLApplication.onCreate(DLApplication.java:126)
W/System.err( 9801): 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
W/System.err( 9801): 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5115)
W/System.err( 9801): 	at android.app.ActivityThread.access$1600(ActivityThread.java:178)
W/System.err( 9801): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1510)
W/System.err( 9801): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 9801): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 9801): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
W/System.err( 9801): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 9801): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 9801): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 9801): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
D/ActivityThread( 9854): Added TimaKeyStore provider
W/LightSharedPreferencesImpl( 9740): Failed to load preference file from Disk!
W/LightSharedPreferencesImpl( 9740): java.io.FileNotFoundException: /data/data/com.facebook.katana/app_light_prefs/com.facebook.katana/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl( 9740): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/LightSharedPreferencesImpl( 9740): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/LightSharedPreferencesImpl( 9740): 	at com.facebook.crudolib.prefs.LightSharedPreferencesStorage.a(update_current:56)
W/LightSharedPreferencesImpl( 9740): 	at com.facebook.crudolib.prefs.LightSharedPreferencesImpl$1.run(update_favorite_contacts:61)
W/LightSharedPreferencesImpl( 9740): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/LightSharedPreferencesImpl( 9740): 	at com.facebook.common.executors.WrappingExecutorService$1.run(video_home:77)
W/LightSharedPreferencesImpl( 9740): 	at com.facebook.common.executors.DefaultConstrainedListeningExecutorService$Worker.run(video_sleep_timeout_ms:327)
W/LightSharedPreferencesImpl( 9740): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/LightSharedPreferencesImpl( 9740): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/LightSharedPreferencesImpl( 9740): 	at com.facebook.common.executors.NamedThreadFactory$1.run(video_story:42)
W/LightSharedPreferencesImpl( 9740): 	at java.lang.Thread.run(Thread.java:818)
W/LightSharedPreferencesImpl( 9740): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/LightSharedPreferencesImpl( 9740): 	at libcore.io.Posix.open(Native Method)
W/LightSharedPreferencesImpl( 9740): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/LightSharedPreferencesImpl( 9740): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/LightSharedPreferencesImpl( 9740): 	... 10 more
E/[CarMode]( 9801): [DLApplication]-Init Called!:false
W/[CarMode]( 9801): [CommonUtil]-=========================================
W/[CarMode]( 9801): [CommonUtil]-CarMode Version:1.10.38.19768
W/[CarMode]( 9801): [CommonUtil]-=========================================
E/[CarMode]( 9801): [DLApplication]-Init Started!:true
I/[CarModeFW]( 9801): DriveLinkServiceInterfaceImp-drivelink framework initialize start
I/[CarModeFW]( 9801): ### com.sec.android.app.automotive.carmode.framework.DriveLinkServiceInterfaceImp::initialize(132)
I/[CarModeFW]( 9801): ### com.sec.android.automotive.drivelink.DLApplication::init(211)
I/[CarModeFW]( 9801): ### com.sec.android.automotive.drivelink.DLApplication::onCreate(135)
I/[CarModeFW]( 9801): ### android.app.Instrumentation::callApplicationOnCreate(1020)
I/[CarModeFW]( 9801): ### android.app.ActivityThread::handleBindApplication(5115)
I/[CarModeFW]( 9801): ### android.app.ActivityThread::access$1600(178)
I/[CarModeFW]( 9801): ### android.app.ActivityThread$H::handleMessage(1510)
I/[CarModeFW]( 9801): ### android.os.Handler::dispatchMessage(102)
I/[CarModeFW]( 9801): ### android.os.Looper::loop(145)
I/[CarModeFW]( 9801): ### android.app.ActivityThread::main(5944)
I/[CarModeFW]( 9801): ### java.lang.reflect.Method::invoke(372)
I/[CarModeFW]( 9801): ### com.android.internal.os.ZygoteInit$MethodAndArgsCaller::run(1399)
I/[CarModeFW]( 9801): ### com.android.internal.os.ZygoteInit::main(1194)
I/VlingoApplication( 9825): VlingoApplication appVersion ='11.7.0.1.39589', coreVersion = '2.5.2.15201', ro.csc.sales_code=XEO
D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/ResourcesManager( 9854): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
,I/VlingoAndroidCore( 9825): AppName: SamsungTproject, Core: 2.5.2.15201, SDK: 2.0.1657, EDM:15201
W/GAV2    ( 9577): Thread[main,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
D/WifiService( 3522): New client listening to asynchronous messages
I/ActivityManager( 3522): Killing 9139:com.android.providers.calendar/u0a47 (adj 13): bgCount ##31
I/MessageDataHandler( 9801): initialize
D/[CarModeFW]( 9801): CDH-initiazlieCaches : before sync
D/[CarModeFW]( 9801): CDH-initiazlieCaches : after sync
I/WifiStateMachine( 3522): CMD_RSSI_POLL : calculateWifiScore in!
I/WifiStateMachine( 3522): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3522): CMD_RSSI_POLL : out!
I/ActivityManager( 3522): Killing 9289:com.sec.android.diagmonagent/1000 (adj 13): bgCount ##31
,D/[CarModeFW]( 9801): CDH-buildContactCacheWireFrame : cur len =0
,D/[CarModeFW]( 9801): CDH-ContactDataHandler initiazlieCaches time : 28
,D/[CarModeFW]( 9801): CDH-initiazlieCaches : end sync
,I/SA      ( 9854): [SSP] onCreated
,D/[CarModeFW]( 9801): DrivingManager-initialize...
,I/SensorService( 3522): Skipped sensor HRMLED IR because it requires permission com.samsung.permission.SSENSOR_HRM_RAW_PPG
I/SensorService( 3522): Skipped sensor HRMLED RED because it requires permission com.samsung.permission.SSENSOR_HRM_RAW_PPG
I/SensorService( 3522): Skipped sensor MAX86902 because it requires permission 
I/SensorService( 3522): Skipped sensor HRM Sensor because it requires permission 
I/SensorService( 3522): Skipped sensor HeartRate Sensor because it requires permission android.permission.BODY_SENSORS
,I/Icing   ( 6708): Indexing 24C12EC0A8A9103D64E8433CB9B0F00F2CE53D26 from com.google.android.gms
,I/SA      ( 9854): [TPM] There is no property file
,D/VlingoApplication( 9825): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
I/Icing   ( 6708): Indexing done 24C12EC0A8A9103D64E8433CB9B0F00F2CE53D26
D/VlingoApplication( 9825): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,I/SA      ( 9854): [SCU] isHaveSA() - false
D/DialogFlow( 9825): initQueue()
,I/SA      ( 9854): [TPM] getModelProperty : null
I/SA      ( 9854): [TPM] getCSCProperty : null
,I/SA      ( 9854): [PMR] Received action : android.intent.action.PACKAGE_ADDED
,W/fb4a(:<default>):UserScope( 9740): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,I/SA      ( 9854): [DM] init START
,I/SA      ( 9854): [DM] This device is not a Vodafone
,I/SA      ( 9854): checkReactivationActive for LOLLIPOP
I/SA      ( 9854): checkReactivationActive for reactiveActive
I/SA      ( 9854): setSupportRL : true
,I/SA      ( 9854): [SCU] isHaveSA() - false
I/SA      ( 9854): support phone number id : false
,I/SA      ( 9854): [DM] init END
I/SA      ( 9854): [SUR] onReceive log=[SA = 2.1.0088 V = 21 HWD = 2560X1440 4.0 dpi = 640  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = trelte P = treltexx I = LRX22C M = SM-N910C OKLEFT false DIS LRX22C.N910CXXU1BOE3 PSS = 5.701614807006056  ]
,I/SA      ( 9854): [SUR] onReceive Intent=[ action.PACKAGE_ADDED. package extra.UID.:10208 extra.user_handle.:0 ]
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,W/fb4a(:<default>):UserScope( 9740): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,E/Zygote  ( 9904): MountEmulatedStorage()
E/Zygote  ( 9904): v2
I/libpersona( 9904): KNOX_SDCARD checking this for 10046
I/libpersona( 9904): KNOX_SDCARD not a persona
,I/SELinux ( 9904): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9904): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9904): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.samsung.android.app.pinboard:sync for broadcast com.samsung.android.app.pinboard/com.sec.android.sCloudRelayData.RelayReceiver: pid=9904 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,I/ActivityManager( 3522): Killing 9321:com.samsung.android.app.mirrorlink/1000 (adj 13): bgCount ##31
,I/MediaPlayer( 9801): Need to enable context aware info
,V/MediaPlayer-JNI( 9801): native_setup
V/MediaPlayer( 9801): constructor
,D/TimaKeyStoreProvider( 9904): TimaSignature is unavailable
,V/MediaPlayer( 9801): setListener
,D/ActivityThread( 9904): Added TimaKeyStore provider
,D/[CarModeFW]( 9801): MY_TAG-[YANG] MusicButtonReceiver construct MusicButtonReceiver() 
,I/[CarModeFW]( 9801): DriveLinkServiceInterfaceImp-drivelink framework initialize end
,D/[CarMode]( 9801): [DLServiceManager]-getOnDLLocationSuggestionListener..........
,D/[CarModeFW]( 9801): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => start time : 1457972212496
,D/[CarMode]( 9801): [DLServiceManager]-updateLocationList
D/[CarMode]( 9801): [DLServiceManager]-requestRecommendedLocationList
D/[CarModeFW]( 9801): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestInboxList => start time : 1457972212496
,D/ResourcesManager( 9904): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
D/[CarModeFW]( 9801): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestUnreadMessageCount => start time : 1457972212497
,D/[CarModeFW]( 9801): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestCallLogList => start time : 1457972212495
,W/ResourcesManager( 9904): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 9904): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
W/ResourcesManager( 9904): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/fb4a(:<default>):UserScope( 9740): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,D/[CarModeFW]( 9801): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedLocationList => start time : 1457972212506
D/[CarModeFW]( 9801): insertNavigationAvailable-sql: select distinct nav_package from tb_location_navigation_available
,D/[CarModeFW]( 9801): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForCall => start time : 1457972212507
,D/[CarModeFW]( 9801): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => start time : 1457972212507
D/TP/SmsProvider( 3985): query,matched:2, calling pid = 9801
,F/DLApplication( 9801): DLApplication mListNavitationAvailable: [com.skt.skaf.l001mtm091, com.google.android.apps.maps, kt.navi, com.mnsoft.lgunavi, com.autonavi.xmgd.navigator.samsung, com.here.app.maps]
,I/[CarMode]( 9801): [LogNotNull]-Package name is: com.here.app.maps
,D/[CarModeFW]( 9801): ContactDataHandler-getFavoriteContactList : cur len = 0
,D/[CarModeFW]( 9801): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => execute time : 16
,D/TP/SmsProvider( 3985): match 2:Elapsed time : 8.868 ms
,V/AlarmManager( 3522): waitForAlarm result :8
,D/[CarModeFW]( 9801): ContactDataHandler-getFavoriteContactList : cur len = 0
,E/[CarMode]( 9801): [DLApplication]-Init End!:true
,D/[CarMode]( 9801): [TAG]-phone sound mode is: 0
V/[CarMode]( 9801): [DLApplication]-savePreviousGpsState
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/TP/SmsProvider( 3985): query,matched:2, calling pid = 9801
,D/[CarModeFW]( 9801): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForCall => execute time : 25
D/[CarModeFW]( 9801): ContactDataHandler-getFavoriteContactList : cur len = 0
D/TP/SmsProvider( 3985): match 2:Elapsed time : 1.718 ms
D/[CarModeFW]( 9801): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedContactListForMessage => execute time : 26
,E/Zygote  ( 9920): MountEmulatedStorage()
E/Zygote  ( 9920): v2
I/libpersona( 9920): KNOX_SDCARD checking this for 10047
I/libpersona( 9920): KNOX_SDCARD not a persona
,I/SELinux ( 9920): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9920): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3522): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=9920 uid=10047 gids={50047, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 9920): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,V/xAnalytics( 9740): java/com/facebook/xanalytics/jni/XAnalyticsNative.cpp - jint JNI_OnLoad(JavaVM*, void*)
V/xAnalytics( 9740): JNI_OnLoad XAnalyticsNative entered
,V/xAnalytics( 9740): JNI_OnLoad XAnalyticsNative complete
,D/[CarModeFW]( 9801): CalllogDataHandler-getCalllogList : cur len = 0
,D/MessageDataHandler( 9801):  getInboxList smsCursor : 58
,V/xAnalytics( 9740): tigon: 0x0 - xanalytics: 0xffffffff93714220
,V/xAnalytics( 9740): xplat/fbacore/fbacore/FbaBeaconLogger.cpp - void facebook::xanalytics::FbaBeaconLogger::init(const string&, const string&, uint32_t) 0 0
V/xAnalytics( 9740): xplat/fbacore/fbacore/FbaBeaconLogger.cpp - void facebook::xanalytics::FbaBeaconLogger::init(const string&, const string&, uint32_t) 0 0
W/art     ( 9740): Attempt to remove local handle scope entry from IRT, ignoring
,D/TP/MmsProvider( 3985): Query uri=content://mms/inbox, match=2, calling pid = 9801
D/[CarModeFW]( 9801): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestCallLogList => execute time : 67
,V/[CarMode]( 9801): [DLApplication]-savePreviousGpsState: Previous state = 0
,E/Minikin ( 9904): addFont failed to create font /system/fonts/SamsungSans-light.ttf
,D/TP/MmsProvider( 3985): Query uri=content://mms, match=0, calling pid = 9801
,D/MessageDataHandler( 9801):  getInboxList mmsCursor : 13
,I/MessageDataHandler( 9801): getUnreadMessageCount :0
D/[CarModeFW]( 9801): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestUnreadMessageCount => execute time : 75
,I/RelayReceiver_PinBoard( 9904): onReceive... android.intent.action.PACKAGE_ADDED
D/MessageDataHandler( 9801):  getInboxList mms,sms cursor join : 9
,D/EnterpriseController( 2848): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2848): getNetworkForDns: using netid 502 for uid 10064
,I/RelayService_PinBoard( 9904): RelayService Started!! : android.intent.action.PACKAGE_ADDED
,D/TP/MmsSmsProvider( 3985): query,matched:0, calling pid = 9801
V/TP/MmsSmsProvider( 3985): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 3985): match 0:Elapsed time : 1.913 ms
,D/TimaKeyStoreProvider( 9920): TimaSignature is unavailable
,D/ActivityThread( 9920): Added TimaKeyStore provider
,V/GLSActivity( 4650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/[CarMode]( 9801): [DLApplication]-GooglePlayServices SUCCESS.
E/[CarMode]( 9801): [DLApplication]-PREF_CAR_APP_RUNNING is set to false
,V/GLSActivity( 4650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/[CarMode]( 9801): [[DLUncaughtExceptionHandler]]-setDLUncaughtExceptionHandler
E/[CarMode]( 9801): [[DLUncaughtExceptionHandler]]-DLUncaughtExceptionHandler is created!
,D/TP/MmsSmsProvider( 3985): query,matched:13, calling pid = 9801
,I/UpdateManagerReceiver( 9801): Intent : android.intent.action.PACKAGE_ADDEDMon Mar 14 17:16:52 GMT+01:00 2016
,D/TP/MmsSmsProvider( 3985): match 13:Elapsed time : 2.262 ms
,D/DialogFlow( 9801): initQueue()
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 9920): creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,W/ResourcesManager( 9920): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,E/Zygote  ( 9945): MountEmulatedStorage()
E/Zygote  ( 9945): v2
I/libpersona( 9945): KNOX_SDCARD checking this for 1000
I/libpersona( 9945): KNOX_SDCARD not a persona
,I/SELinux ( 9945): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9945): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9945): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=9945 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/CalendarProvider2( 9920): CalendarProvider2.onCreate() called
,I/ActivityManager( 3522): Killing 8947:com.google.android.gm/u0a122 (adj 13): bgCount ##31
,I/ActivityManager( 3522): Killing 8910:com.sec.providers.settingsearch/u0a181 (adj 15): bgCount ##32
,I/ActivityManager( 3522): Killing 9340:com.sec.android.widgetapp.activeapplicationwidget/u0a173 (adj 15): bgCount ##33
,D/MessageDataHandler( 9801):  getInboxList address cursor : 64
,D/TimaKeyStoreProvider( 9945): TimaSignature is unavailable
D/TP/MmsSmsProvider( 3985): query,matched:0, calling pid = 9801
V/TP/MmsSmsProvider( 3985): getSimpleConversations entered.
,D/ResourcesManager( 9703): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
,D/TP/MmsSmsProvider( 3985): match 0:Elapsed time : 1.438 ms
,D/ActivityThread( 9945): Added TimaKeyStore provider
,D/MessageDataHandler( 9801):  getInboxList thread cursor : 12
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
,D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ResourcesManager( 9703): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/ResourcesManager( 9703): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager( 9703): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/ResourcesManager( 9703): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/ResourcesManager( 9703): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,D/ResourcesManager( 9945): creating new AssetManager and set to /system/app/FilterInstaller/FilterInstaller.apk
,D/MessageDataHandler( 9801):  thread, addr result: 18
I/[CarModeFW]( 9801): ContentManager-com.sec.android.app.automotive.carmode.framework.manager.content.ContentManager end getInboxList() : 210
I/[CarModeFW]( 9801): ContentManager-com.sec.android.app.automotive.carmode.framework.manager.content.ContentManager end getInboxListWithContactData() : 0
,D/[CarModeFW]( 9801): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestInboxList => execute time : 212
,D/ResourcesManager( 9703): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,I/System.out( 9825): INFO:Resource not found:/Common.properties Using default values
,D/ResourcesManager( 9703): creating new AssetManager and set to /system/app/Videos/Videos.apk
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 9703): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,W/ContextImpl( 9945): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2994 
,D/ResourcesManager( 9703): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,D/ResourcesManager( 9703): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,E/Zygote  ( 9965): MountEmulatedStorage()
,E/Zygote  ( 9965): v2
I/libpersona( 9965): KNOX_SDCARD checking this for 10110
D/ResourcesManager( 9703): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
I/libpersona( 9965): KNOX_SDCARD not a persona
,I/SELinux ( 9965): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ResourcesManager( 9703): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,I/ActivityManager( 3522): Start proc com.facebook.appmanager for broadcast com.facebook.appmanager/com.facebook.oxygen.appmanager.common.packages.PackageReceiver: pid=9965 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 9965): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux ( 9965): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,D/ResourcesManager( 9703): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
,D/ResourcesManager( 9703): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,D/ResourcesManager( 9703): creating new AssetManager and set to /system/app/Books/Books.apk
,D/ResourcesManager( 9703): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
,D/ResourcesManager( 9703): creating new AssetManager and set to /system/app/Drive/Drive.apk
,D/ResourcesManager( 9703): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,D/ResourcesManager( 9703): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
,D/ResourcesManager( 9703): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
,D/ResourcesManager( 9703): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
,D/ResourcesManager( 9945): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,D/ResourcesManager( 9703): creating new AssetManager and set to /system/app/Maps/Maps.apk
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/ResourcesManager( 9703): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,D/ResourcesManager( 9703): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
,D/TimaKeyStoreProvider( 9965): TimaSignature is unavailable
,D/ActivityThread( 9965): Added TimaKeyStore provider
,D/ResourcesManager( 9703): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
,D/ResourcesManager( 9703): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
,D/ResourcesManager( 9703): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
,E/Zygote  ( 9981): MountEmulatedStorage()
E/Zygote  ( 9981): v2
D/ResourcesManager( 9703): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,I/libpersona( 9981): KNOX_SDCARD checking this for 10121
I/libpersona( 9981): KNOX_SDCARD not a persona
,I/SELinux ( 9981): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3522): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=9981 uid=10121 gids={50121, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,D/ResourcesManager( 9703): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
,I/SELinux ( 9981): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/FilterInstaller( 9945): installFilters
,E/FilterInstaller( 9945): There is no requred permission
,E/SELinux ( 9981): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/[CarModeFW]( 9801): LocationDataHandler-No schedules found.
,D/[CarModeFW]( 9801): MyPlaceProvider-Provider uri: content://com.samsung.android.internal.intelligence.useranalysis/place
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,I/Icing   ( 6708): Indexing 5F814D61A0DCF2E8041D271E5054F7C0773240D3 from com.google.android.googlequicksearchbox
,D/ResourcesManager( 9965): creating new AssetManager and set to /data/app/com.facebook.appmanager-1/base.apk
,D/TimaKeyStoreProvider( 9981): TimaSignature is unavailable
,D/ActivityThread( 9981): Added TimaKeyStore provider
,E/Zygote  ( 9996): MountEmulatedStorage()
E/Zygote  ( 9996): v2
I/libpersona( 9996): KNOX_SDCARD checking this for 10003
I/libpersona( 9996): KNOX_SDCARD not a persona
,I/SELinux ( 9996): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux ( 9996): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3522): Start proc com.samsung.android.intelligenceservice for content provider com.samsung.android.intelligenceservice/.useranalysis.PlaceProvider: pid=9996 uid=10003 gids={50003, 9997, 3002, 3003, 1023, 1028, 1015, 3006, 1007, 3001} abi=armeabi-v7a
,E/SELinux ( 9996): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Killing 8407:com.sec.android.widgetapp.SPlannerAppWidget/u0a163 (adj 15): bgCount ##31
,D/ResourcesManager( 9703): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,D/ResourcesManager( 9703): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,D/TimaKeyStoreProvider( 9996): TimaSignature is unavailable
,D/ActivityThread( 9996): Added TimaKeyStore provider
,I/ActivityManager( 3522): Killing 8270:com.android.calendar/u0a164 (adj 15): bgCount ##31
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ResourcesManager( 9981): creating new AssetManager and set to /system/app/GearManagerStub/GearManagerStub.apk
,D/AppStateLogger( 9740): Successfully dumped app state to log file
,D/ResourcesManager( 9996): creating new AssetManager and set to /system/priv-app/intelligenceservice/intelligenceservice.apk
,D/PackageIntentReceiver( 9981): ACTION_PACKAGE_ADDED
D/PackageIntentReceiver( 9981): Not GearManger package! 
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/UserAnalysis.PlaceProvider( 9996): PlaceProvider onCreate()
,E/Zygote  (10011): MountEmulatedStorage()
,E/Zygote  (10011): v2
I/libpersona(10011): KNOX_SDCARD checking this for 1000
I/libpersona(10011): KNOX_SDCARD not a persona
,I/SELinux (10011): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10011): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10011): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=10011 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3522): Killing 8998:com.google.android.talk/u0a125 (adj 15): bgCount ##31
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 8755(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 492us total 16.613ms
D/UserAnalysis.SecureDbManager( 9996): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 9996): SecurePlaceDbHelper() 
D/UserAnalysis.PlaceProvider( 9996): Create SecureDbHelper
,D/IntelligenceServiceApplication( 9996): onCreate()
,D/TimaKeyStoreProvider(10011): TimaSignature is unavailable
,D/ActivityThread(10011): Added TimaKeyStore provider
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 335us total 9.033ms
,D/ResourcesManager(10011): creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 339us total 9.647ms
,I/art     ( 3522): Explicit concurrent mark sweep GC freed 15734(1008KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 48MB/64MB, paused 1.947ms total 115.881ms
,V/fb-UnpackingSoSource( 9965): locked dso store /data/data/com.facebook.appmanager/lib-main
,I/fb-UnpackingSoSource( 9965): dso store is up-to-date: /data/data/com.facebook.appmanager/lib-main
V/fb-UnpackingSoSource( 9965): releasing dso store lock for /data/data/com.facebook.appmanager/lib-main
V/fb-UnpackingSoSource( 9965): locked dso store /data/data/com.facebook.appmanager/lib-assets
I/fb-UnpackingSoSource( 9965): dso store is up-to-date: /data/data/com.facebook.appmanager/lib-assets
V/fb-UnpackingSoSource( 9965): releasing dso store lock for /data/data/com.facebook.appmanager/lib-assets
,V/fb-UnpackingSoSource( 9965): locked dso store /data/data/com.facebook.appmanager/lib-xzs
I/fb-UnpackingSoSource( 9965): dso store is up-to-date: /data/data/com.facebook.appmanager/lib-xzs
V/fb-UnpackingSoSource( 9965): releasing dso store lock for /data/data/com.facebook.appmanager/lib-xzs
,D/ACRA    ( 9965): ACRA is enabled for com.facebook.appmanager, intializing...
,V/DexLibLoader( 9965): DLL.loadAll betaBuild:true flags:0x00000001
,D/[CarModeFW]( 9801): MyPlaceProvider-+++Begin print all data in content provider+++
D/[CarModeFW]( 9801): MyPlaceProvider-=============
D/[CarModeFW]( 9801): MyPlaceProvider-=============
D/[CarModeFW]( 9801): MyPlaceProvider-=============
D/[CarModeFW]( 9801): MyPlaceProvider-=============
D/[CarModeFW]( 9801): MyPlaceProvider-=============
D/[CarModeFW]( 9801): MyPlaceProvider-=============
D/[CarModeFW]( 9801): MyPlaceProvider----End print all data in content provider---
D/[CarModeFW]( 9801): MyPlaceProvider-==============
D/[CarModeFW]( 9801): MyPlaceProvider-==============
D/[CarModeFW]( 9801): MyPlaceProvider-==============
D/[CarModeFW]( 9801): MyPlaceProvider-==============
D/[CarModeFW]( 9801): MyPlaceProvider-==============
V/dalvik-internals( 9965): hooked _ZN3art12FaultManager35EnsureArtActionInFrontOfSignalChainEv using jump ()
V/dalvik-internals( 9965): hooked signal using trap ()
V/dalvik-internals( 9965): hooked sysv_signal using trap ()
V/dalvik-internals( 9965): hooked bsd_signal using trap ()
,V/dalvik-internals( 9965): hooked sigaction using jump ()
V/DexLibLoader( 9965): opening dex store /data/data/com.facebook.appmanager/dex
,D/[CarModeFW]( 9801): DestinationAvailableTableHandler-sql: select dest_name from tb_destination_list_available where ((1457972212990 - dest_date ) / 360000 ) <= 24 ORDER BY dest_date DESC LIMIT 100
V/DexLibLoader( 9965): Secondary program dex metadata: [classes2.dex 810147d6f366c39a471d8dcf6e02fd5ad5c640fa secondary.dex01.Canary]
,V/DexLibLoader( 9965): read status:9 check:faceb007faceb00e
E/[CarModeFW]( 9801): DestinationAvailableTableHandler-insert FAIL!
E/DestinationList( 9801): loadLocationDestinationList is null
D/[CarModeFW]( 9801): Framework-Request-com.sec.android.app.automotive.carmode.framework.command.RequestRecommendedLocationList => execute time : 485
V/DexLibLoader( 9965): read saved dep file /data/data/com.facebook.appmanager/dex/deps (176 bytes)
V/DexLibLoader( 9965): verified deps file
I/DexLibLoader( 9965): current scheme: com.facebook.common.dextricks.OdexSchemeNoop next step: LA_LOAD_EXISTING
,V/MultiDexClassLoader( 9965): installing MultiDexClassLoader before application classloader
,D/MultiDexClassLoader( 9965): Found primary dex /data/app/com.facebook.appmanager-1/base.apk
D/MultiDexClassLoader( 9965): Setup multi dex took 0 ms.
V/DexLibLoader( 9965): optimization needed: no
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,I/Icing   ( 6708): Indexing done 5F814D61A0DCF2E8041D271E5054F7C0773240D3
,E/Zygote  (10027): MountEmulatedStorage()
I/libpersona(10027): KNOX_SDCARD checking this for 1000
E/Zygote  (10027): v2
I/libpersona(10027): KNOX_SDCARD not a persona
,I/SELinux (10027): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10027): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10027): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc ACMS.Process for broadcast com.samsung.android.app.mirrorlink/com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener: pid=10027 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 3522): Killing 8445:com.sec.android.widgetapp.locationwidget/u0a22 (adj 15): bgCount ##31
,I/GMPM    ( 9965): App measurement is starting up
,D/TimaKeyStoreProvider(10027): TimaSignature is unavailable
,D/ActivityThread(10027): Added TimaKeyStore provider
,E/GMPM    ( 9965): getGoogleAppId failed with status: 10
,W/cn      ( 9965): Verify
,E/GMPM    ( 9965): Uploading is not possible. App measurement disabled
,D/ResourcesManager(10027): creating new AssetManager and set to /system/app/MirrorLink/MirrorLink.apk
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/AcmsPackageEventListener(10027): Received: android.intent.action.PACKAGE_ADDED
,W/ContextImpl(10027): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2064 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:54 com.samsung.android.mirrorlink.acms.receivers.AcmsPackageEventListener$asyncstart.doInBackground:1 
,E/Zygote  (10050): MountEmulatedStorage()
E/Zygote  (10050): v2
I/libpersona(10050): KNOX_SDCARD checking this for 10013
I/libpersona(10050): KNOX_SDCARD not a persona
,I/SELinux (10050): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10050): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3522): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.MyPackageReplacedReceiver: pid=10050 uid=10013 gids={50013, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,E/SELinux (10050): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/AcmsService(10027): Enter Oncreate
D/AcmsServiceMonitor(10027): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsService(10027): creating AcmsCore
D/AcmsCore(10027): AcmsCore.getAcmsCore() - Enter
D/AcmsCore(10027): AcmsCore
,D/AcmsCore(10027): init
D/AcmsCore(10027): Looper handler is not null
D/AcmsCore(10027): Post to AcmsCoreHandler
D/AcmsServiceMonitor(10027): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(10027): Incrementing - Counter value: 1
D/AcmsCore(10027): Incremented Counter Value: postToAcmsCoreHandler =>1
D/AcmsService(10027): onStartCommand
D/AcmsService(10027): Action: android.intent.action.PACKAGE_ADDED
D/AcmsServiceMonitor(10027): Enter incrementSvcCounter with startId 1
D/AcmsServiceMonitor(10027): Incrementing - Counter value: 2
D/AcmsService(10027): Incremented Counter Value : onStartCommand
,D/AcmsCertificateMngr(10027): AcmsCertificateMngr
D/AcmsRevocationMngr(10027): AcmsRevocationMngr
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
W/appmanager(:<default>):LightSharedPreferencesImpl( 9965): Failed to load preference file from Disk!
W/appmanager(:<default>):LightSharedPreferencesImpl( 9965): java.io.FileNotFoundException: /data/data/com.facebook.appmanager/app_light_prefs/com.facebook.appmanager/analytics_flexible_sampling_policy: open failed: ENOENT (No such file or directory)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9965): 	at libcore.io.IoBridge.open(IoBridge.java:456)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9965): 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9965): 	at com.facebook.crudolib.d.k.a(LightSharedPreferencesStorage.java:56)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9965): 	at com.facebook.crudolib.d.g.run(LightSharedPreferencesImpl.java:61)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9965): 	at java.util.concurrent.Executors$RunnableAdapter.call(Executors.java:422)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9965): 	at com.facebook.common.executors.dt.run(WrappingExecutorService.java:77)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9965): 	at com.facebook.common.executors.aa.run(DefaultConstrainedListeningExecutorService.java:327)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9965): 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1112)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9965): 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:587)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9965): 	at com.facebook.common.executors.cs.run(NamedThreadFactory.java:42)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9965): 	at java.lang.Thread.run(Thread.java:818)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9965): Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9965): 	at libcore.io.Posix.open(Native Method)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9965): 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9965): 	at libcore.io.IoBridge.open(IoBridge.java:442)
W/appmanager(:<default>):LightSharedPreferencesImpl( 9965): 	... 10 more
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/ActivityThread(10027): Loading provider com.samsung.mirrorlink.acms.pkgnames: com.samsung.android.mirrorlink.acms.provider.AcmsPkgNameProvide
,D/TimaKeyStoreProvider(10050): TimaSignature is unavailable
,D/ActivityThread(10050): Added TimaKeyStore provider
,W/appmanager(:<default>):b( 9965): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/appmanager(:<default>):b( 9965): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,D/ResourcesManager(10050): creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,D/AcmsService(10027): Inside handle Intent
D/AcmsService(10027): App added - package name: com.test.thalitest
D/AcmsCore(10027): Post to AcmsCoreHandler
D/AcmsServiceMonitor(10027): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(10027): Incrementing - Counter value: 3
D/AcmsCore(10027): Incremented Counter Value: postToAcmsCoreHandler =>2
D/AcmsService(10027): Decremented Counter Value : handleStartIntent
D/AcmsServiceMonitor(10027): Decrementing - Counter value: 2
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,W/appmanager(:<default>):QuickExperimentControllerImpl( 9965): Exposure of experiment com.facebook.http.g.c@35d08d83 occurred when no user was logged in
,E/Zygote  (10083): MountEmulatedStorage()
I/libpersona(10083): KNOX_SDCARD checking this for 10160
E/Zygote  (10083): v2
I/libpersona(10083): KNOX_SDCARD not a persona
,I/SELinux (10083): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10083): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/art     ( 9965): Rejecting re-init on previously-failed class java.lang.Class<com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper>
I/art     ( 9965): Rejecting re-init on previously-failed class java.lang.Class<com.facebook.ssl.openssl.TicketEnabledOpenSSLSocketImplWrapper>
,E/SELinux (10083): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.samsung.android.snote for broadcast com.samsung.android.snote/.library.plugin.PluginBroadcastReceiver: pid=10083 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
,I/ActivityManager( 3522): Killing 9419:com.samsung.android.app.FileShareServer/u0a79 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(10083): TimaSignature is unavailable
,D/ActivityThread(10083): Added TimaKeyStore provider
,I/System.out( 9965): Thread-1331(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out( 9965): Thread-1331(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 9965): Thread-1331(ApacheHTTPLog):isShipBuild true
I/System.out( 9965): Thread-1331(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2848): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2848): getNetworkForDns: using netid 502 for uid 10110
,D/ResourcesManager(10083): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,W/ResourcesManager(10083): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(10083): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10083): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,V/Common  (10083): getScreenSize 1440 2560
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,I/JAM     (10083): Load The ApaService JNI
,I/JAM     (10083): version: ProfessionalAudio_v1.0.b5
I/JAM     (10083): Try v1.0.b3 ...
,D/Spen    (10083): SpenSdk version level = 55
D/Spen    (10083): SpenSdk jar version = 3.0.243
E/Zygote  (10105): MountEmulatedStorage()
I/libpersona(10105): KNOX_SDCARD checking this for 10160
E/Zygote  (10105): v2
I/libpersona(10105): KNOX_SDCARD not a persona
,I/SELinux (10105): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/Spen    (10083): SpenSdk apk version = 3.0.235
D/Spen    (10083): Server UPDATE Check
W/linker  (10083): libSPenBase.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
I/SELinux (10105): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/SPenError(10083): JNI_OnLoad
E/SELinux (10105): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.samsung.android.snote:provider for content provider com.samsung.android.snote/.model.provider.SNoteProvider: pid=10105 uid=10160 gids={50160, 9997, 1028, 1015, 3002, 1023, 3003} abi=armeabi-v7a
,D/JNI_Bitmap(10083): Init .. Done
D/SPenSpiDecoder(10083): JNI_OnLoad .. Done
D/SPenError(10083): JNI_OnLoad Success
,D/PluginManager(10083): Registering com/samsung/android/sdk/pen/plugin/framework/JniPluginManager natives
D/PluginManager(10083): Registering com/samsung/android/sdk/pen/plugin/framework/SpenPluginManager$PluginListener natives
,D/Init_SPenSdk_Jni(10083): JNI_OnLoad
,D/Init_SPenSdk_Jni(10083): AndroidSDK: 21
D/Init_SPenSdk_Jni(10083): JNI_OnLoad .. Done
,D/Model_ObjectBase_Jni(10083): JNI_OnLoad .. Done
D/Model_ObjectStroke_Jni(10083): JNI_OnLoad .. Done
,D/Model_ObjectImage_Jni(10083): JNI_OnLoad .. Done
,D/Model_ObjectText_Jni(10083): JNI_OnLoad .. Done
D/Model_ObjectContainer_Jni(10083): JNI_OnLoad .. Done
,D/Model_PageDoc_Jni(10083): JNI_OnLoad .. Done
,D/Model_NoteDoc_Jni(10083): check build type eng[0]
D/Model_NoteDoc_Jni(10083): JNI_OnLoad .. Done
,D/Model_NoteFile_Jni(10083): JNI_OnLoad .. Done
D/Model_ObjectUtil_Jni(10083): JNI_OnLoad .. Done
D/Model   (10083): OnLoad class Done
,D/TimaKeyStoreProvider(10105): TimaSignature is unavailable
,D/ActivityThread(10105): Added TimaKeyStore provider
,D/spe_log (10083): SPen::GLRenderThreadImpl::GLRenderThreadImpl() Initialize: 0
,D/SPen_Library(10083): Draw Engine JNI_OnLoad enter!!
D/SPen_Library(10083): Canvas JNI_OnLoad enter!!
,D/SPen_Library(10083): Canvas JNI_OnLoad Success
D/SPen_Library(10083): TextView JNI_OnLoad enter!!
,D/SPen_Library(10083): TextView JNI_OnLoad Success
D/SPen_Library(10083): Text JNI_OnLoad enter!!
D/SPen_Library(10083): Text JNI_OnLoad Success
D/SPen_Library(10083): FontManager JNI_OnLoad enter!!
D/SPen_Library(10083): FontManager JNI_OnLoad Success
D/SPen_Library(10083): CapturePage JNI_OnLoad enter!!
D/SPen_Library(10083): CapturePage JNI_OnLoad Success
D/SPen_Library(10083): Multi JNI_OnLoad enter!!
,D/SPen_Library(10083): Multi JNI_OnLoad Success
D/SPen_Library(10083): Draw Engine JNI_OnLoad Success
,D/SPen_Library(10083): Brush JNI_OnLoad enter!!
,D/SPen_Library(10083): Brush JNI_OnLoad Success
,D/SPen_Library(10083): ChineseBrush JNI_OnLoad enter!!
,D/SPen_Library(10083): ChineseBrush JNI_OnLoad Success
,D/ResourcesManager(10105): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/SPen_Library(10083): InkPen JNI_OnLoad enter!!
,D/SPen_Library(10083): InkPen JNI_OnLoad Success
,D/SPen_Library(10083): Marker JNI_OnLoad enter!!
,D/SPen_Library(10083): Marker JNI_OnLoad Success
,D/SPen_Library(10083): Pencil JNI_OnLoad enter!!
,D/SPen_Library(10083): Pencil JNI_OnLoad Success
,D/SPen_Library(10083): NativePen JNI_OnLoad enter!!
D/SPen_Library(10083): NativePen JNI_OnLoad Success
,W/ResourcesManager(10105): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
W/ResourcesManager(10105): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10105): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/SPen_Library(10083): MontblancFountainPen JNI_OnLoad enter!!
,D/SPen_Library(10083): MontblancFountainPen JNI_OnLoad Success
,D/SPen_Library(10083): MontblancCalligraphyPen JNI_OnLoad enter!!
,D/SPen_Library(10083): MontblancCalligraphyPen JNI_OnLoad Success
,D/SPen_Library(10083): MagicPen JNI_OnLoad enter!!
,D/SPen_Library(10083): MagicPen JNI_OnLoad Success
,D/SPen_Library(10083): ObliquePen JNI_OnLoad enter!!
,D/SPen_Library(10083): ObliquePen JNI_OnLoad Success
,D/SPen_Library(10083): FountainPen JNI_OnLoad enter!!
,D/SPen_Library(10083): FountainPen JNI_OnLoad Success
D/Spen    (10083): SpenSdk Libraries are loaded.
D/Init_SPenSdk_Jni(10083): SPenSdk_init2
D/Init_SPenSdk(10083): Init - screen_width = 1440, screen_height = 2560, maxCacheSize = 100 M
D/Init_SPenSdk(10083): Total S Pen SDK Directory Size = 0
D/Spen    (10083): initialize complete
,W/linker  (10083): libSPenImageFilterLibs.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,D/ResourcesManager(10083): creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10122): MountEmulatedStorage()
E/Zygote  (10122): v2
I/libpersona(10122): KNOX_SDCARD checking this for 10183
I/libpersona(10122): KNOX_SDCARD not a persona
,I/SELinux (10122): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10122): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/SNoteProvider(10105): onCreate enableSnoteSync = true
,E/SELinux (10122): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.samsung.android.provider.shootingmodeprovider for broadcast com.samsung.android.provider.shootingmodeprovider/com.samsung.android.app.shootingmodeinstaller.PackageIntentReceiver: pid=10122 uid=10183 gids={50183, 9997, 1023} abi=armeabi-v7a
,I/ActivityManager( 3522): Killing 9451:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): bgCount ##31
,I/ActivityManager( 3522): Killing 9436:com.sec.knox.bridge/1000 (adj 15): bgCount ##32
,D/SNoteProvider(10105): ===query=== 
,V/Common  (10105): getScreenSize 1440 2560
,D/TimaKeyStoreProvider(10122): TimaSignature is unavailable
,D/ActivityThread(10122): Added TimaKeyStore provider
,D/ResourcesManager(10122): creating new AssetManager and set to /system/app/ShootingModeProvider/ShootingModeProvider.apk
,D/SNoteProvider(10105): ===query=== 
,E/SQLiteLog(10122): (284) automatic index on shooting_modes(title_id)
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10142): MountEmulatedStorage()
E/Zygote  (10142): v2
I/libpersona(10142): KNOX_SDCARD checking this for 10190
I/libpersona(10142): KNOX_SDCARD not a persona
,I/SELinux (10142): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10142): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10142): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.sec.android.widgetapp.tapandpay for broadcast com.sec.android.widgetapp.tapandpay/.TanpandpayAppWidgetProvider: pid=10142 uid=10190 gids={50190, 9997} abi=armeabi-v7a
,I/ActivityManager( 3522): Killing 9546:com.samsung.android.app.vrsetupwizardstub/u0a63 (adj 15): bgCount ##31
,D/TimaKeyStoreProvider(10142): TimaSignature is unavailable
,D/ActivityThread(10142): Added TimaKeyStore provider
,D/ResourcesManager(10142): creating new AssetManager and set to /system/app/TapandpayWidget/TapandpayWidget.apk
,I/TapandpayWidget:TanpandpayAppWidgetProvider(10142): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(10142): onReceive() - action : android.intent.action.PACKAGE_ADDED / mCurIndex :-10
,I/TapandpayWidget:Utils(10142): Clear T&P info.
,D/TapandpayWidget:TanpandpayAppWidgetProvider(10142): Widget is not attached.
,I/splitIntent( 3522): Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,I/ActivityManager( 3522): Killing 9390:com.sec.android.gallery3d/u0a50 (adj 13): bgCount ##31
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10158): MountEmulatedStorage()
I/libpersona(10158): KNOX_SDCARD checking this for 10135
E/Zygote  (10158): v2
I/libpersona(10158): KNOX_SDCARD not a persona
,I/SELinux (10158): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10158): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10158): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.AutoCacheSchedulingService$EnablingReceiver: pid=10158 uid=10135 gids={50135, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider(10158): TimaSignature is unavailable
,D/ActivityThread(10158): Added TimaKeyStore provider
,D/ResourcesManager(10158): creating new AssetManager and set to /system/app/Music2/Music2.apk
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/MusicStore(10158): Database version: 104
,D/ResourcesManager(10158): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,W/ResourcesManager(10158): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(10158): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/JNIHelp (10158): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(10158): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (10158): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@321cdc35: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(10158): Installed default security provider GmsCore_OpenSSL
D/AndroidMusic(10158): GMSCore installation verified
,I/ConfigStore(10158): Config Database version: 1
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10158): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10158): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10158): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,D/WifiDisplayAdapter( 3522): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3522): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 3522): getStreamVolume 3 index 0
,I/MediaRouter(10158): Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/NetworkMonitor(10158): type=WIFI subType= reason=null isConnected=true
,D/WifiDisplayAdapter( 3522): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WearableService( 4650): callingUid 10014, callindPid: 4650
,I/NetworkMonitor(10158): type=WIFI subType= reason=null isConnected=true
,I/MusicLeanback(10158): Stop autocaching.
,I/MusicLeanback(10158): Stop autocaching.
,I/MusicLeanback(10158): Stop autocaching.
,I/MusicLeanback(10158): Stop autocaching.
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/GoogleHttpClient(10158): Failed to load SSLCertificateSocketFactory from package
I/GoogleHttpClient(10158): Falling back to old SSLCertificateSocketFactory
I/GHttpClientFactory(10158): Using the GMSCore's GoogleHttpClient
,I/MusicLeanback(10158): Conditions not met for autocaching.
I/MusicLeanback(10158): Stop autocaching.
,D/WearableClient(10158): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(10158): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(10158): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(10158): WearableClientImpl.onPostInitHandler: done
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10191): MountEmulatedStorage()
I/libpersona(10191): KNOX_SDCARD checking this for 10122
E/Zygote  (10191): v2
I/libpersona(10191): KNOX_SDCARD not a persona
,I/SELinux (10191): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10191): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10191): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.google.android.gm for broadcast com.google.android.gm/.widget.GmailWidgetProvider: pid=10191 uid=10122 gids={50122, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/GmsUtils(10158): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/GmsUtils(10158): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,E/ActivityThread(10158): Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@1a396ad7 that was originally bound here
E/ActivityThread(10158): android.app.ServiceConnectionLeaked: Service com.google.android.music.download.TrackDownloadQueueService has leaked ServiceConnection com.google.android.gms.http.GoogleURLConnectionFactory$1@1a396ad7 that was originally bound here
E/ActivityThread(10158): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(10158): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(10158): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(10158): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(10158): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(10158): 	at com.google.android.gms.http.GoogleURLConnectionFactory.<init>(Unknown Source)
E/ActivityThread(10158): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(10158): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(10158): 	at com.google.android.gms.http.GoogleHttpClient.<init>(Unknown Source)
E/ActivityThread(10158): 	at com.google.android.music.GoogleHttpClientFactory.createGoogleHttpClient(GoogleHttpClientFactory.java:81)
E/ActivityThread(10158): 	at com.google.android.music.cloudclient.MusicRequest.createHttpClient(MusicRequest.java:110)
E/ActivityThread(10158): 	at com.google.android.music.cloudclient.MusicRequest.getSharedHttpClient(MusicRequest.java:100)
E/ActivityThread(10158): 	at com.google.android.music.download.BaseDownloadQueueManager.<init>(BaseDownloadQueueManager.java:110)
E/ActivityThread(10158): 	at com.google.android.music.download.TrackDownloadQueueManager.<init>(TrackDownloadQueueManager.java:10)
E/ActivityThread(10158): 	at com.google.android.music.download.TrackDownloadQueueService.onCreate(TrackDownloadQueueService.java:25)
E/ActivityThread(10158): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(10158): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(10158): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(10158): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(10158): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(10158): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(10158): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(10158): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(10158): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(10158): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,I/ActivityManager( 3522): Killing 8788:com.android.mms/u0a52 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(10191): TimaSignature is unavailable
,D/ActivityThread(10191): Added TimaKeyStore provider
,W/ActivityThread( 9965): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,D/ResourcesManager(10191): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/CountryDetector( 3522): No listener is left
,W/ActivityManager( 3522): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/CheckinService( 6708): Done disabling old GoogleServicesFramework version
,W/ActivityManager( 3522): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
I/Gmail   (10191): getAccountsCursor
,V/GLSActivity( 4650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 3522): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,V/GLSActivity( 4650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
I/Gmail   (10191): Observing account changes for notifications
,W/GAV2    (10191): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,W/ActivityManager( 3522): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,E/CscFactoryReceiver( 3985): onReceive android.intent.action.MEDIA_SCANNER_FINISHED
D/CscFactoryReceiver( 3985): Media DB Scanner finished.
,D/CscFactoryReceiver( 3985): start service to Set Ringtone
I/CalendarProvider2( 9920): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,D/CscFactoryReceiver( 3985): start service to Set Notification
,D/CscFactoryReceiver( 3985): start service to Set Alarmtone
,E/Gmail   (10191): Error finding the version of the Email provider.....
E/Gmail   (10191): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   (10191): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:137)
E/Gmail   (10191): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
E/Gmail   (10191): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   (10191): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   (10191): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   (10191): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   (10191): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/Gmail   (10191): getAccountsCursor
W/EmailMigration(10191): We do not support migrating this version of the Email provider.
,D/CscUpdateService( 3985): onStart
E/CscUpdateService( 3985): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 3985): only ringtone update
,D/CscUpdateService( 3985): onStart
E/CscUpdateService( 3985): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 3985): only notification update
,E/CscParser( 3985): update(): xml file exist
D/CscUpdateService( 3985): onStart
E/CscUpdateService( 3985): costomer file is exists : it has been preconfiged.
D/CscUpdateService( 3985): only alarmtone update
,V/GLSActivity( 4650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,W/CSCSettings( 3985): Setting Ringtones (type) : 1
D/CscParser( 3985): RingTone: null
W/CSCSettings( 3985): 1. Tag_Str: null
,E/CscParser( 3985): update(): xml file exist
,E/CscParser( 3985): update(): xml file exist
,W/CSCSettings( 3985): Setting Ringtones (type) : 2
,D/CscParser( 3985): MessageTone: null
W/CSCSettings( 3985): 1. Tag_Str: null
W/CSCSettings( 3985): Setting Ringtones (type) : 4
,D/CscParser( 3985): AlarmTone: null
W/CSCSettings( 3985): 1. Tag_Str: null
,E/Zygote  (10232): MountEmulatedStorage()
I/libpersona(10232): KNOX_SDCARD checking this for 10004
E/Zygote  (10232): v2
I/libpersona(10232): KNOX_SDCARD not a persona
,I/SELinux (10232): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10232): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10232): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.samsung.dcm:DCMService for broadcast com.samsung.dcm/.framework.broadcastreceivers.SystemBroadcastReceiver$DCMBroadcastReceiver: pid=10232 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3522): Killing 9562:com.google.android.partnersetup/u0a17 (adj 13): bgCount ##31
,I/ActivityManager( 3522): Killing 9597:com.sec.android.service.health/u0a19 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(10232): TimaSignature is unavailable
,D/ActivityThread(10232): Added TimaKeyStore provider
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ResourcesManager(10232): creating new AssetManager and set to /system/priv-app/DCMProvider/DCMProvider.apk
,I/art     ( 4650): Explicit concurrent mark sweep GC freed 34446(2MB) AllocSpace objects, 20(320KB) LOS objects, 35% free, 29MB/45MB, paused 956us total 30.681ms
,V/GLSActivity( 4650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/SQLiteLog(10191): (283) recovered 75 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,I/DCMProvider(10232): [#DCM#] onCreate this Instance = com.sec.dcm.provider.DCMProvider@1010f3fe Provider Ref Count:1
,I/DCMConfig(10232): [#DCM#] initializeTransport.SystemBroadcastReceiver  1 ms
,I/StorageController(10232): [#DCM#]  state through storage volume =  mounted
,I/StorageController(10232): [#DCM#]  storageId =  65537 removable = false path = /storage/emulated/0 state = mounted subsystem = fuse
I/StorageController(10232): [#DCM#]  state through storage volume =  removed
,I/StorageController(10232): [#DCM#]  storageId =  131073 removable = true path = /storage/extSdCard state = removed subsystem = sd
I/StorageController(10232): [#DCM#]  state through storage volume =  unmounted
,I/StorageController(10232): [#DCM#]  storageId =  196609 removable = false path = /storage/Private state = unmounted subsystem = private
I/StorageController(10232): [#DCM#]  state through storage volume =  removed
,I/StorageController(10232): [#DCM#]  storageId =  262145 removable = true path = /storage/UsbDriveA state = removed subsystem = usb
I/StorageController(10232): [#DCM#]  state through storage volume =  removed
,I/StorageController(10232): [#DCM#]  storageId =  327681 removable = true path = /storage/UsbDriveB state = removed subsystem = usb
I/StorageController(10232): [#DCM#]  state through storage volume =  removed
,I/StorageController(10232): [#DCM#]  storageId =  393217 removable = true path = /storage/UsbDriveC state = removed subsystem = usb
I/StorageController(10232): [#DCM#]  state through storage volume =  removed
I/StorageController(10232): [#DCM#]  storageId =  458753 removable = true path = /storage/UsbDriveD state = removed subsystem = usb
I/StorageController(10232): [#DCM#]  state through storage volume =  removed
,I/StorageController(10232): [#DCM#]  storageId =  524289 removable = true path = /storage/UsbDriveE state = removed subsystem = usb
I/StorageController(10232): [#DCM#]  state through storage volume =  removed
,I/StorageController(10232): [#DCM#]  storageId =  589825 removable = true path = /storage/UsbDriveF state = removed subsystem = usb
,D/ResourcesManager( 6708): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,I/DCMPolicyManager(10232): [#DCM#] setCriticalStateFromSystem screenOn =  true high siop = false camera running = false
,I/DCMPolicyManager(10232): [#DCM#] opening file DCMRules.txt 
,I/DCMConfig(10232): [#DCM#] initializeTransport.DCMPolicyManager  16 ms
,I/DCMConfig(10232): [#DCM#] initializeTransport.MediaManager  17 ms
,I/DCMConfig(10232): [#DCM#] initializeTransport.DCMNRTManager  21 ms
,I/DCMConfig(10232): [#DCM#] No of CPU Core 8
I/DCMConfig(10232): [#DCM#] initializeTransport took  22 ms
I/DCMProvider(10232): [#DCM#] onCreate end 
,I/DCMNRTManager(10232): [#DCM#] intialize 
,I/SystemBroadcastReceiver(10232): [#DCM#] [DCM_Performance] onReceive completed in time  13 microsec. 
I/SystemBroadcastReceiver(10232): [#DCM#] [DCM_Performance] onReceive completed in time  5 microsec. 
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,I/SystemBroadcastReceiver(10232): [#DCM#] Calling notifyListeners. 
,I/StorageController(10232): [#DCM#]  state through storage volume =  mounted
I/Gmail   (10191): notifyAccountChanged
,I/StorageController(10232): [#DCM#]  storageId =  65537 removable = false path = /storage/emulated/0 state = mounted subsystem = fuse
I/StorageController(10232): [#DCM#]  state through storage volume =  removed
,I/StorageController(10232): [#DCM#]  storageId =  131073 removable = true path = /storage/extSdCard state = removed subsystem = sd
I/StorageController(10232): [#DCM#]  state through storage volume =  unmounted
,I/StorageController(10232): [#DCM#]  storageId =  196609 removable = false path = /storage/Private state = unmounted subsystem = private
I/StorageController(10232): [#DCM#]  state through storage volume =  removed
,I/StorageController(10232): [#DCM#]  storageId =  262145 removable = true path = /storage/UsbDriveA state = removed subsystem = usb
I/StorageController(10232): [#DCM#]  state through storage volume =  removed
I/StorageController(10232): [#DCM#]  storageId =  327681 removable = true path = /storage/UsbDriveB state = removed subsystem = usb
I/StorageController(10232): [#DCM#]  state through storage volume =  removed
,I/StorageController(10232): [#DCM#]  storageId =  393217 removable = true path = /storage/UsbDriveC state = removed subsystem = usb
I/StorageController(10232): [#DCM#]  state through storage volume =  removed
,I/StorageController(10232): [#DCM#]  storageId =  458753 removable = true path = /storage/UsbDriveD state = removed subsystem = usb
I/StorageController(10232): [#DCM#]  state through storage volume =  removed
I/Gmail   (10191): getAccountsCursor
,I/StorageController(10232): [#DCM#]  storageId =  524289 removable = true path = /storage/UsbDriveE state = removed subsystem = usb
I/StorageController(10232): [#DCM#]  state through storage volume =  removed
I/WriterFactory(10232): [#DCM#] verifyLuceneDB ++ 
,I/Gmail   (10191): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
I/StorageController(10232): [#DCM#]  storageId =  589825 removable = true path = /storage/UsbDriveF state = removed subsystem = usb
I/StorageController(10232): [#DCM#] Bundle =  Bundle[{path=file:///storage/emulated/0, CleanBuffer=false}]
I/StorageController(10232): [#DCM#] Sending intent for OS Upgrade for Phone contents 
,I/DCMUtilities(10232): [#DCM#] Scan Completed:Check if lucene upgrade is required for OS upgrade 
,E/Zygote  (10258): MountEmulatedStorage()
E/Zygote  (10258): v2
I/libpersona(10258): KNOX_SDCARD checking this for 10007
I/libpersona(10258): KNOX_SDCARD not a persona
,I/SELinux (10258): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/Gmail   (10191): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/SELinux (10258): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10258): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.samsung.indexservice for broadcast com.samsung.indexservice/com.samsung.index.indexservice.service.DocumentBroadcastReceiver: pid=10258 uid=10007 gids={50007, 9997, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 3522): Killing 9612:com.sec.android.app.myfiles/u0a53 (adj 13): bgCount ##31
,I/Gmail   (10191): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/Gmail   (10191): calculateUnknownSyncRationalesAndPurgeInBackground: running
,I/System.out( 9965): P[5]_NetworkDispatch1 calls detatch()
,I/WriterFactory(10232): [#DCM#] verifyLuceneDB OK breaking 
I/WriterFactory(10232): [#DCM#] verifyLuceneDB OK -- 
I/WriterFactory(10232): [#DCM#] TAXO in mode CREATE_OR_APPEND
,I/ActivityManager( 3522): Killing 9628:com.sec.pcw.device/1000 (adj 13): bgCount ##31
,V/GLSActivity( 4650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SystemUtils(10232): [#DCM#] pref_value getOSUpgradeSharedPrefForMedia is = true
I/SystemUtils(10232): [#DCM#] setOSUpgradeSharedPrefForMedia set as  true
I/DCMUtilities(10232): [#DCM#] OSUpgrade not required 
I/SystemBroadcastReceiver(10232): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager(10232): [#DCM#] onReceive action = EVENT_SIOP
I/SystemBroadcastReceiver(10232): [#DCM#] Calling notifyListeners. 
I/SystemBroadcastReceiver(10232): [#DCM#] No one is registered with Event Id EVENT_NETWORK_CHANGED
,D/TimaKeyStoreProvider(10258): TimaSignature is unavailable
D/ActivityThread(10258): Added TimaKeyStore provider
,I/WriterFactory(10232): [#DCM#] Before facet 
,I/WriterFactory(10232): [#DCM#] After facet=!null ? true
,W/BroadcastQueue( 3522): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{2e10c85d u0 ReceiverList{12391234 9965 com.facebook.appmanager/10110/u0 remote:10459107}}
,W/BroadcastQueue( 3522): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{2e10c85d u0 ReceiverList{12391234 9965 com.facebook.appmanager/10110/u0 remote:10459107}}
D/ResourcesManager(10258): creating new AssetManager and set to /system/priv-app/DocumentService/DocumentService.apk
,I/DCMUtilities(10232): [#DCM#] isCommitOk; kKeyOnCommit = true
I/DCMController(10232): [#DCM#] isCommitOk:  true, isIntentFinished: trueisRebuildDone = true
,I/DCMConfig(10232): [#DCM#] setSuccessState =  true
,W/BroadcastQueue( 3522): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{1b7599ff u0 ReceiverList{21817d1e 9965 com.facebook.appmanager/10110/u0 remote:21168d59}}
,I/ThumbnailProvider(10258): ThumbnailProvider onCreate()
,I/DocumentBroadcastReceiver(10258): DocumentService onReceive android.intent.action.MEDIA_SCANNER_FINISHED
,I/BroadcastProcessorService(10258): [START] processBroadcastIntent ...
,I/BroadcastProcessorService(10258): DocumentService onHandleIntent ACTION_MEDIA_SCANNER_FINISHED
,I/SystemInfo(10258): [SYSTEM STATUS] Battery and Storage levels are OK:
I/BroadcastProcessorService(10258): [CURRENT_STATE] DocumentService state: SERVICE_NOT_STARTED
,I/BroadcastProcessorService(10258): [START] DocumentService startDocumentService
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10289): MountEmulatedStorage()
I/libpersona(10289): KNOX_SDCARD checking this for 10044
E/Zygote  (10289): v2
I/libpersona(10289): KNOX_SDCARD not a persona
,I/SELinux (10289): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10289): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.sec.android.app.music:service for broadcast com.sec.android.app.music/.appwidget.MusicAppWidgetProvider: pid=10289 uid=10044 gids={50044, 9997, 3003, 3002, 1028, 1015, 1023, 1007} abi=armeabi-v7a
E/SELinux (10289): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DocumentService(10258): DocumentService onCreate ... service
,I/art     ( 3522): Explicit concurrent mark sweep GC freed 16246(1010KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 48MB/64MB, paused 1.809ms total 92.222ms
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 8745(372KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 349us total 12.762ms
E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10258): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10258): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 472us total 9.307ms
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/TimaKeyStoreProvider(10289): TimaSignature is unavailable
,D/ActivityThread(10289): Added TimaKeyStore provider
,E/SystemInfo(10258): [SIOP LEVEL] : -2
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 305us total 10.890ms
,D/ResourcesManager(10289): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,W/ResourcesManager(10289): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,W/ResourcesManager(10289): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager(10289): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(10289): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(10289): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10289): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,I/DocumentServiceUtils(10258):  Total PDF: 0 PDF size: 0 OtherFiles Size: 0
E/SystemInfo(10258): DocumentService [SIOP LEVEL] changed to -2
E/SystemInfo(10258): DocumentService Resume indexing as [SIOP LEVEL] changed to < 2
I/DocumentService(10258): [BEGIN SYNC] DocumentService beginIndexing :17
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10258): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,I/Gmail   (10191): getAccountsCursor
,V/GLSActivity( 4650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/art     ( 5420): Explicit concurrent mark sweep GC freed 9556(570KB) AllocSpace objects, 0(0B) LOS objects, 22% free, 26MB/34MB, paused 509us total 12.907ms
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10316): MountEmulatedStorage()
E/Zygote  (10316): v2
I/libpersona(10316): KNOX_SDCARD checking this for 10050
I/libpersona(10316): KNOX_SDCARD not a persona
,I/SELinux (10316): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10316): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=10316 uid=10050 gids={50050, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
E/SELinux (10316): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Killing 9373:com.samsung.android.app.galaxyfinder/u0a35 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(10316): TimaSignature is unavailable
,D/ActivityThread(10316): Added TimaKeyStore provider
,D/ResourcesManager(10316): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
,I/SystemInfo(10258): [SYSTEM STATUS] Battery and Storage levels are OK:
I/DocumentService(10258): [BEGIN SYNC] DocumentService beginIndexing :16
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10258): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
W/ResourcesManager(10316): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(10316): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10316): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(10316): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10316): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager(10316): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager(10316): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager(10316): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/SystemInfo(10258): [SYSTEM STATUS] Battery and Storage levels are OK:
,I/DocumentService(10258): [VERIFY] verifyThumbnailImages
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.samsung.indexservice/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10258): Failed to ensure directory: /storage/extSdCard/Android/data/com.samsung.indexservice/files
,I/DocumentService(10258): [STOP DOCUMENTSERVICE] Attempting to stop the Service
E/DocumentService(10258): [THUMBNAIL AND INDEX] Thumbnail and indexing is Completed Total Time taken for both :89
E/DocumentService(10258): [THUMBNAIL] Total Time taken for each file :0
E/        (10258): [INDEX] Total time taken for each file :0
,I/DocumentService(10258): DocumentService onDestroy start
I/DocumentService(10258): DocumentService onDestroy end
,I/DocumentService(10258): DocumentService cleanupEverything start
I/ActivityManager( 3522): Killing 6961:com.sec.android.app.shealth/u0a36 (adj 13): bgCount ##31
,I/IndexParserThreadsManager(10258): InterruptedException: null
,I/SystemInfo(10258): [SYSTEM STATUS] Battery and Storage levels are OK:
I/DocumentService(10258): DocumentService cleanupEverything end
I/Process (10258): Sending signal. PID: 10258 SIG: 9
,I/ActivityManager( 3522): Process com.samsung.indexservice (pid 10258)(adj 9) has died(101,1263)
,D/PackageManager( 3522): findPreferredActivity: No PreferredActivities set
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9965): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
D/NearbySource(10316): Nearby Source Create!
D/NearbyContext(10316): Nearby Context Create!
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.appmanager/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 9965): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.appmanager/files
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10316): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
D/SLinkSource(10316): Samsung link source created
,D/ContactProvider(10316): getAllContactInfoList Start
,D/WifiDisplayAdapter( 3522): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiDisplayAdapter( 3522): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/GalleryCacheReady(10316): Receive action.ACTION_MEDIA_SCANNER_FINISHED
,D/GalleryCacheReady(10316): handleMeidaScanFinish()
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/ContextImpl(10316): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10316): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl(10316): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,D/ContactProvider(10316): getAllContactInfoList End
I/syncContacts(10316): thread: 1388, sync time = 26
E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
W/ContextImpl(10316): Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,D/FaceInterface(10316): requestFaceScan() is called.
,I/FaceInterface(10316): startFaceScan() : waiting 5 sec
,W/LocalSuggestAlbumData(10316): query fail: 
,W/LocalSuggestAlbumData(10316): query fail: 
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10345): MountEmulatedStorage()
I/libpersona(10345): KNOX_SDCARD checking this for 10022
E/Zygote  (10345): v2
I/libpersona(10345): KNOX_SDCARD not a persona
,I/SELinux (10345): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10345): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10345): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Start proc com.sec.android.widgetapp.locationwidget for broadcast com.sec.android.widgetapp.locationwidget/.cocktail.LocationWidgetCocktailProvider: pid=10345 uid=10022 gids={50022, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,D/TimaKeyStoreProvider(10345): TimaSignature is unavailable
,D/ActivityThread(10345): Added TimaKeyStore provider
,D/ResourcesManager(10345): creating new AssetManager and set to /system/priv-app/LocationWidget/LocationWidget.apk
,W/ResourcesManager(10345): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10345): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10345): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,I/MediaStoreImporter(10158): Update: incremental Added music: 0 Updated music: 0 Deleted music: 0 Created playlists: 0 Updated playlists: 0 Deleted playlists: 0 Inserted playlist items: 0 Deleted playlist items: 0 Removed orphaned playlist items: 0
,I/LocationWidgetApplication(10345): onCreate() : start
,D/LocationWidgetApplication(10345): countryCode = POLAND
,D/LocationManagerService( 3522): getProviders()=[]
D/LocationManagerService( 3522): getProviders()=[passive]
D/LocationManagerService( 3522): getBestProvider(Criteria[power=LOW acc=LOW], true)=passive
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/LWLocationManager(10345): mPrivacy is null
,W/ContextImpl(10345): Implicit intents with startService are not safe: Intent { act=com.samsung.android.providers.context.privacy.IPrivacyManager } android.content.ContextWrapper.bindService:559 com.samsung.android.providers.context.privacy.PrivacyManager.bindService:394 com.sec.android.widgetapp.locationwidget.data.LWLocationManager.bindPrivacyService:150 
,I/ActivityManager( 3522): Killing 8489:com.android.settings/1000 (adj 13): bgCount ##31
,D/ContextFramework:PrivacyManager(10345): Service for PrivacyManager is connected
,D/BootupListener( 3985): ACTION_DRIVELINK
,D/SettingsProvider( 3522): name = drivelink_navigation
D/SettingsProvider( 3522): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3522): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3522): selectionArgs: false
D/SettingsProvider( 3522): selectionArgs: 1001
,D/SecContentProvider( 3522): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3522): ret = -1
,D/BootupListener( 3985): NAVI : com.here.app.maps
D/SettingsProvider( 3522): name = internet_call_settings_visibility
D/SettingsProvider( 3522): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3522): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3522): selectionArgs: false
D/SettingsProvider( 3522): selectionArgs: 1001
D/SecContentProvider( 3522): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3522): ret = -1
,D/BootupListener( 3985): intent.getAction() = com.sec.android.automotive.drivelink.NAVIGATION_PACKAGE_NAME
,D/Widget  (10083): onReceive android.appwidget.action.APPWIDGET_UPDATE
,D/LWLocationManager(10345): Privacy service : STATUS_PLACE
D/LWLocationManager(10345): updateLocationStatus()
,D/Widget  (10083): widgetUpdate 5
,D/RCPManagerService( 3522): exchangeData() failure , invalid userId
,I/LocationWidgetFuctionData(10345): readDB
,I/LocationWidgetFuctionData(10345): selectedAppSize: 3
I/LocationWidgetFuctionData(10345): configPlaceList aroundMeItems
,D/Widget  (10083): onReceive com.sec.android.snote.widget.ACTION_NOTE_UPDATE
,I/LocationWidgetFuctionData(10345): selectedAppSize: 3
,I/LocationWidgetFuctionData(10345): selectedAppSize: 3
,I/LocationWidgetFuctionData(10345): selectedAppSize: 3
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
I/LocationWidgetFuctionData(10345): selectedAppSize: 3
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/LWLocationManager(10345): findLocationType() : cursor_location.moveToFirst() return false!!
,D/LWLocationManager(10345): Intent broadcast sent with action: com.sec.android.widgetapp.locationwidget.LOCATION_SOURCES_UPDATED
D/LWLocationManager(10345): setShouldUpdateLocationId
D/LWLocationManager(10345): setShouldUpdateLocationId return false
D/LWLocationManager(10345): setShouldUpdateLocationId
D/LWLocationManager(10345): setShouldUpdateLocationId return false
D/LWLocationManager(10345): setShouldUpdateLocationId
D/LWLocationManager(10345): setShouldUpdateLocationId return false
D/LWLocationManager(10345): updateDeviceLocation() : lastDeviceLocationId = -100 mDeviceLocationId: -100 cocktailId: -1
,D/LocationWidgetUtils(10345): getUpcommingInstances() start: 1457972214417, end: 1458514799999
D/LocationWidgetUtils(10345): getUpcommingInstances() DB begin time >= start:1457972214417, DB begin time <= end:1458514799999
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10371): MountEmulatedStorage()
I/libpersona(10371): KNOX_SDCARD checking this for 10163
E/Zygote  (10371): v2
I/libpersona(10371): KNOX_SDCARD not a persona
,I/SELinux (10371): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10371): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3522): Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=10371 uid=10163 gids={50163, 9997} abi=armeabi-v7a
,E/SELinux (10371): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(10371): TimaSignature is unavailable
,D/ActivityThread(10371): Added TimaKeyStore provider
,D/ResourcesManager(10371): creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG_Transparent/SPlannerWidget_OS_UPG_Transparent.apk
,W/ResourcesManager(10371): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10371): Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10387): MountEmulatedStorage()
E/Zygote  (10387): v2
I/libpersona(10387): KNOX_SDCARD checking this for 10164
I/libpersona(10387): KNOX_SDCARD not a persona
,I/SELinux (10387): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10387): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=10387 uid=10164 gids={50164, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
E/SELinux (10387): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Killing 9650:com.policydm/1000 (adj 13): bgCount ##31
,D/TimaKeyStoreProvider(10387): TimaSignature is unavailable
,D/ActivityThread(10387): Added TimaKeyStore provider
,D/ResourcesManager(10387): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
,W/ResourcesManager(10387): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager(10387): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10387): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10387): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
,D/daemonapp( 3772): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/ActivityManager( 3522): Killing 9684:com.facebook.system/u0a10 (adj 13): bgCount ##31
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/GAV2    ( 9466): Thread[GAThread,5,main]: No campaign data found.
,W/SQLiteConnectionPool( 6708): A SQLiteConnection object for database '+data+data+com_google_android_gms+databases+networkstatistics_sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,D/AcmsKeyStoreHelper(10027):  getKeyStoreForApplication Enter
,I/AcmsKeyStoreHelper(10027): Key Store exist
I/AcmsKeyStoreHelper(10027): Hence loading the keystore file
,D/AcmsKeyStoreHelper(10027):  getKeyStoreForApplication Exit
I/AcmsCertificateMngr(10027): getKeyStoreForApplication success 
D/AcmsCore(10027): Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
D/AcmsServiceMonitor(10027): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(10027): Decrementing - Counter value: 1
D/AcmsCore(10027): AcmsCore: ACMS_APP_INSTALLED
,D/AcmsCore(10027): This is NOT a valid MirrorLink app
D/AcmsCore(10027): Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
D/AcmsServiceMonitor(10027): AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
D/AcmsServiceMonitor(10027): Decrementing - Counter value: 0
D/AcmsServiceMonitor(10027): Counter value is 0: Stopping ACMS service
,D/AcmsServiceMonitor(10027): getSvcCounter - Counter value: 0
D/AcmsService(10027): Enter onDestroy
D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
I/AcmsService(10027): cleanUp(): inside service clean up
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/AcmsCore(10027): AcmsCore: inside DeInit
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/AcmsCore(10027): AcmsCore: mLooperHandler is not null and making it null
D/AcmsCertificateMngr(10027): AcmsCertificateMngr: inside cleanup
D/AcmsRevocationMngr(10027): AcmsRevocationMngr: inside cleanup
D/AcmsKeyStoreHelper(10027): KeyStoreHelper: inside cleanup
D/AcmsAppEntryInterface(10027): AppEntryInterface: Inside CleanUp
D/AcmsServiceMonitor(10027): getSvcCounter - Counter value: 0
D/AcmsService(10027): killing acms process
I/Process (10027): Sending signal. PID: 10027 SIG: 9
,I/WifiStateMachine( 3522): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3522): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3522): CMD_RSSI_POLL : out!
,I/ActivityManager( 3522): Process ACMS.Process (pid 10027)(adj 0) has died(128,1263)
,W/ProcessCpuTracker( 3522): Skipping unknown process pid 10027
,I/ActivityManager( 3522): Killing 9668:com.sec.android.app.soundalive/u0a59 (adj 13): bgCount ##31
,E/lowmemorykiller( 2827): Error writing /proc/9668/oom_score_adj; errno=22
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,I/GAV2    ( 9577): Thread[GAThread,5,main]: No campaign data found.
,W/fb4a(:<default>):UserScope( 9740): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,I/art     ( 9740): Thread[1,tid=9740,WaitingForJniOnLoad,Thread*=0xb4e08000,peer=0x86f7a000,"main"] recursive attempt to load library "/data/data/com.facebook.katana/lib-xzs/libomnistore.so"
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/art     ( 9740): JNI RegisterNativeMethods: attempt to register 0 native methods for com.facebook.compactdisk.DiskCache
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching, sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImp,l( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/BroadcastQueue( 3522): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{22ae2124 u0 ReceiverList{2e9ac5b7 9740 com.facebook.katana/10114/u0 remote:3645a4b6}}
W/BroadcastQueue( 3522): Permission Denial: broadcasting Intent { act=android.net.conn.INET_CONDITION_ACTION flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{22ae2124 u0 ReceiverList{2e9ac5b7 9740 com.facebook.katana/10114/u0 remote:3645a4b6}}
,W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,D/GcOptimizer( 9740): Configure for next cold start: disable
,W/BroadcastQueue( 3522): Permission Denial: broadcasting Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) } from null (pid=-1, uid=-1) requires com.facebook.permission.prod.FB_APP_COMMUNICATION due to registered receiver BroadcastFilter{11b0948e u0 ReceiverList{2e1e9c89 9740 com.facebook.katana/10114/u0 remote:53e2b90}}
,W/fb4a(:<default>):UserScope( 9740): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/AlarmManager( 3522): waitForAlarm result :4
,W/fb4a(:<default>):QuickExperimentControllerImpl( 9740): Exposure of experiment com.facebook.placetips.gpscore.abtest.GeneratedPlaceTipsGpsMainExperiment@15f38e8c occurred when no user was logged in
,W/fb4a(:<default>):QuickExperimentControllerImpl( 9740): Exposure of experiment com.facebook.placetips.gpscore.abtest.GeneratedPlaceTipsGpsPassiveListenerExperiment@1a6a89d5 occurred when no user was logged in
,W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,W/fb4a(:<default>):QuickExperimentControllerImpl( 9740): Exposure of experiment com.facebook.inject.init.GeneratedFbInjectorWeakrefExperiment@1c3142ec occurred when no user was logged in
,W/fb4a(:<default>):UserScope( 9740): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):QeInternalImpl( 9740): The sessioned store is not available. Are you fetching sessioned quick experiment data while the user is logged out?
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10452): MountEmulatedStorage()
I/libpersona(10452): KNOX_SDCARD checking this for 10082
E/Zygote  (10452): v2
I/libpersona(10452): KNOX_SDCARD not a persona
,I/SELinux (10452): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10452): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=10452 uid=10082 gids={50082, 9997} abi=armeabi-v7a
,E/SELinux (10452): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(10452): TimaSignature is unavailable
,D/ActivityThread(10452): Added TimaKeyStore provider
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ResourcesManager(10452): creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,D/BadgeProvider(10452): onCreate
D/BadgeProvider(10452): DatabaseHelper
,D/BadgeProvider(10452): sendNotify entered. [uri] : content://com.sec.badge/apps
D/BadgeProvider(10452): sendNotify, [notify] : null
D/BadgeProvider(10452): update, [uri] : content://com.sec.badge/apps
D/BadgeProvider(10452): update, [BadgeCount] : badgecount=0
D/BadgeProvider(10452): update, [UpdateCount] : 1
,D/Launcher.Model( 4001): reloadBadges entered.
,I/ActivityManager( 3522): Killing 8925:com.samsung.android.app.assistantmenu/1000 (adj 13): bgCount ##31
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.katana/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9740): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.katana/files
,E/Vold    ( 2829): Failed to find mounted volume for /storage/extSdCard/Android/data/com.facebook.katana/files/
W/Vold    ( 2829): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 9740): Failed to ensure directory: /storage/extSdCard/Android/data/com.facebook.katana/files
,W/fb4a(:<default>):UserScope( 9740): Called user scoped provider with no viewer. ViewerContextManager was created with no ViewerContext. Using EmptyViewerContextManager to return fake logged in instance.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
W/fb4a(:<default>):ViewerContextManagerForUserScope( 9740): User no longer logged in. Original uid: 0, viewer context: null, is_logged_in: false. Returning original viewer context.
,I/System.out( 9965): P[5]_NetworkDispatch2 calls detatch()
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/System.out( 9965): P[5]_NetworkDispatch3 calls detatch()
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/WifiStateMachine( 3522): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3522): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3522): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/WearableClient(10158): WearableClientImpl.onPostInitHandler: done
,D/WearableClient(10158): WearableClientImpl.onPostInitHandler: done
,I/MusicLeanback(10158): Conditions not met for autocaching.
I/MusicLeanback(10158): Stop autocaching.
,D/WearableClient(10158): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(10158): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,D/WearableClient(10158): WearableClientImpl.onPostInitHandler: done
,E/GmsUtils(10158): Failed to connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null}
,V/AlarmManager( 3522): waitForAlarm result :4
,I/iu.UploadsManager( 6708): End new media; added: 0, uploading: 0, time: 51 ms
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/GAV2    (10191): Thread[GAThread,5,main]: No campaign data found.
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/FaceInterface(10316): startFaceScan() : going on
D/FaceInterface(10316): startFaceScan() is called.
,D/ContentApp( 5420): startScan() is called.
,D/FaceValue( 5420): mSleepTime: 800
,D/FaceValue( 5420): mMaxThreadNum: 2
,D/ContentApp( 5420): startScan() is end.
,D/ContentApp( 5420): face_restore FINISHED_TYPE: 3
D/FaceScanner( 5420): isNeedToRestore : start
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,I/art     ( 3522): Explicit concurrent mark sweep GC freed 22155(1400KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 48MB/64MB, paused 2.142ms total 141.546ms
D/SSRM:n  ( 3522): SIOP:: AP = 360, PST = 355, CUR = -712
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/AlarmManager( 3522): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.TIME_TICK
D/KeyguardUpdateMonitor( 3692): handleTimeUpdate
,D/KeyguardEffectViewController( 3692): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3692): *** don't update sliding image ***
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/accuweather( 5195): [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK
,D/accuweather( 5195): [KK AccuPhone]>>> UIM:118 [0:0] getInstance
,D/accuweather( 5195): [KK AccuPhone]>>> UIM:288 [0:0] direct update clock
,D/accuweather( 5195): [KK AccuPhone]>>> UIM:157 [0:0] make widget 4x1 view!!! 
,D/accuweather( 5195): [KK AccuPhone]>>> UIM:159 [0:0] make widget 4x2 view!!! 
,D/accuweather( 5195): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 160span x = 4, span y = 2
,D/accuweather( 5195): [KK AccuPhone]>>> UIM:1426 [0:0] mc sy = 2
,D/accuweather( 5195): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 160span x = 4, span y = 2
,D/accuweather( 5195): [KK AccuPhone]>>> UIM:184 [0:0] get widget 4x2 view!!! wid = 2
,E/accuweather( 5195): [KK AccuPhone]>>> UIM:1464 [0:0] bTM 17 17
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3522): level:100, scale:100, status:2, health:2, present:true, voltage: 4382, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:-481, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:115
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
,D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PackageManager( 3522): [MSG] MCS_UNBIND
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
I/WifiStateMachine( 3522): CMD_RSSI_POLL : calculateWifiScore in!
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/ActivityManager( 3522): Killing 9495:com.android.vending/u0a31 (adj 13): bgCount ##31
,I/WifiStateMachine( 3522): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3522): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen,
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/ActivityManager( 3522): Waited long enough for: ServiceRecord{3c77f80c u0 com.samsung.android.MtpApplication/.MtpService}
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
,D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/WifiStateMachine( 3522): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3522): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine( 3522): CMD_RSSI_POLL : out!
,D/PowerManagerService( 3522): [s] UserActivityState : 1 -> 2
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 3522): [s] DisplayPowerCallbacks : onStateChanged()
,D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
,D/lights  ( 3522): lcd : 1 +
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 3522): lcd : 1 -
,D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/AlarmManager( 3522): waitForAlarm result :4
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10494): MountEmulatedStorage()
,I/libpersona(10494): KNOX_SDCARD checking this for 10031
E/Zygote  (10494): v2
I/libpersona(10494): KNOX_SDCARD not a persona
,I/SELinux (10494): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10494): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.android.vending for service com.android.vending/com.google.android.finsky.services.DailyHygiene: pid=10494 uid=10031 gids={50031, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux (10494): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/TimaKeyStoreProvider(10494): TimaSignature is unavailable
,D/ActivityThread(10494): Added TimaKeyStore provider
,D/ResourcesManager(10494): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/Finsky  (10494): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/,
,D/Finsky  (10494): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/Settings(10494): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings(10494): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,D/Finsky  (10494): [1] DailyHygiene.onStartCommand: Beginning daily hygiene
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/Ads     (10494): Skipping gmscore version check
,D/Finsky  (10494): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  (10494): [1] Libraries$2.run: Finished loading 1 libraries.
,V/GLSActivity( 4650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  (10494): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,V/GLSActivity( 4650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/Finsky  (10494): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,V/GLSActivity( 4650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out(10494): Thread-1417(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,I/System.out(10494): Thread-1417(ApacheHTTPLog):isSBSettingEnabled false
I/System.out(10494): Thread-1417(ApacheHTTPLog):isShipBuild true
I/System.out(10494): Thread-1417(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,D/EnterpriseController( 2848): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2848): getNetworkForDns: using netid 502 for uid 10031
,I/qtaguid (10494): Tagging socket 44 with tag e8d195d100000000{3906049489,0} uid -1, pid: 10494, getuid(): 10031
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
,D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/qtaguid (10494): Tagging socket 48 with tag e8d195d100000000{3906049489,0} uid -1, pid: 10494, getuid(): 10031
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/qtaguid (10494): Untagging socket 44
,I/System.out(10494): Thread-1417 calls detatch()
,V/GLSActivity( 4650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/qtaguid (10494): Untagging socket 44
,I/qtaguid (10494): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid (10494): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger(10494): untagSocket(44) failed with errno -22
I/System.out(10494): Thread-1418 calls detatch()
,D/Finsky  (10494): [1] SelfUpdateScheduler.checkForSelfUpdate: Skipping DFE self-update. Local Version [80430500] >= Server Version [-1]
,V/GLSActivity( 4650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10536): MountEmulatedStorage()
E/Zygote  (10536): v2
I/libpersona(10536): KNOX_SDCARD checking this for 10014
I/libpersona(10536): KNOX_SDCARD not a persona
,I/SELinux (10536): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10536): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.google.android.gms:car for service com.google.android.gms/.car.CarService: pid=10536 uid=10014 gids={50014, 9997, 2001, 3003, 1007, 3006, 1028, 1015, 3002, 3001, 3007} abi=armeabi-v7a
E/SELinux (10536): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/ActivityManager( 3522): Waited long enough for: ServiceRecord{1189a383 u0 com.samsung.android.app.galaxyfinder/.tag.TagReadyService}
,D/TimaKeyStoreProvider(10536): TimaSignature is unavailable
,D/ActivityThread(10536): Added TimaKeyStore provider
,D/ResourcesManager(10536): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,W/ResourcesManager(10536): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(10536): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,V/AlarmManager( 3522): waitForAlarm result :4
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/MultiDex(10536): VM with version 2.1.0 has multidex support
I/MultiDex(10536): install
I/MultiDex(10536): VM has multidex support, MultiDex support library is disabled.
,V/JNIHelp (10536): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,W/ActivityThread(10536): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,W/System  (10536): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1a584d72: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller(10536): Installed default security provider GmsCore_OpenSSL
,I/splitIntent( 3522): Split this intent : com.google.android.gms.INITIALIZE !!   mSplitNum[0]=4, mSplitNum[1]=7, mSplitNum[2]=9 divideNum= 2 r.nextReceiver= 1 receivers.size=11
I/splitIntent( 3522): finish to split intent : com.google.android.gms.INITIALIZE !! Enqueue -> schedule it!!
,D/ChimeraCfgMgr(10536): Reading stored module config
,D/AuthorizationBluetoothService( 4650): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,I/qtaguid (10494): Untagging socket 44
,I/qtaguid (10494): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid (10494): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger(10494): untagSocket(44) failed with errno -22
I/System.out(10494): Thread-1417 calls detatch()
,D/LocationInitializer( 6708): Restart initialization of location
,D/WearableService( 4650): callingUid 10014, callindPid: 4650
,E/MDM     ( 4650): [313] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/GCoreFlp( 4650): No location to return for getLastLocation()
,W/FusedLocationProvider( 4650): location=null
,V/GLSActivity( 4650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/NativeLibraryUtils(10536): Install completed successfully. count=14 extracted=0
,I/splitIntent( 3522): Queue : backgroundsplit_1 intent com.google.android.gms.INITIALIZE is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,D/CAR.SERVICE(10536): Connecting to CarCallService...
,I/art     (10536): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,I/art     (10536): Rejecting re-init on previously-failed class java.lang.Class<com.google.android.gms.common.j.c>
,D/CAR.SERVICE(10536): com.google.android.projection.gearhead isn't installed.
,D/CAR.TEL.Service(10536): Creating a new CarCallService.
,D/CAR.TEL.PhoneAdapter(10536): Creating a new PhoneAdapter instance
,W/ActivityManager( 3522): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
D/CAR.TEL.PhoneAdapter(10536): setListener: com.google.android.gms.car.dn@310bdae9
,W/ActivityManager( 3522): Unable to start service Intent { act=local_bind cmp=com.google.android.gms/.car.InCallServiceImpl } U=0: not found
,D/CAR.TEL.PhoneAdapter(10536): Returning an existing PhoneAdapter instance.
D/CAR.TEL.Service(10536): Starting CarCallService with initial phone null
,D/CAR.SERVICE(10536): Package validated; name: com.android.vending
,V/Finsky  (10494): [1] GearheadStateMonitor.access$100: mIsProjecting:false
,D/Finsky  (10494): [1430] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  (10494): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/WifiStateMachine( 3522): CMD_RSSI_POLL : calculateWifiScore in!
D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/WifiStateMachine( 3522): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3522): CMD_RSSI_POLL : out!
,I/ActivityManager( 3522): Waited long enough for: ServiceRecord{32b47852 u0 com.samsung.android.app.pinboard/com.sec.android.sCloudRelayData.RelayService}
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/GLSActivity( 4650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/qtaguid (10494): Untagging socket 44
I/qtaguid (10494): Failed write_ctrl(u 44) res=-1 errno=22
I/qtaguid (10494): Untagging socket 44 failed errno=-22
W/NetworkManagementSocketTagger(10494): untagSocket(44) failed with errno -22
I/System.out(10494): Thread-1418 calls detatch()
,D/ResourcesManager(10494): creating new AssetManager and set to /system/framework/framework-res.apk
,D/ResourcesManager(10494): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,D/ResourcesManager(10494): creating new AssetManager and set to /system/app/ANTRadioService/ANTRadioService.apk
,D/ResourcesManager(10494): creating new AssetManager and set to /system/app/AntHalService/AntHalService.apk
,W/ResourcesManager(10494): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/ResourcesManager(10494): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/ResourcesManager(10494): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager(10494): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ResourcesManager(10494): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/ResourcesManager(10494): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,W/ResourcesManager(10494): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,D/Finsky  (10494): [1] DailyHygiene.access$600: Logging device features
,V/AlarmManager( 3522): waitForAlarm result :4
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/DeviceConnectionService( 4650): client connected with version: 8296000
,D/Finsky  (10494): [1439] FlushLogsService.onHandleIntent: Flushing event logs for [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  (10494): [1] WearSupportService$8.onConnectionFailed: onConnectionFailed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,D/Finsky  (10494): [1] WearSupportService.access$100: Dropping command=hygiene due to Gms not connected
,V/GLSActivity( 4650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/System.out(10494): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out(10494): (HTTPLog)-Static: isShipBuild true
I/System.out(10494): (HTTPLog)-Thread-1428-902860163: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out(10494): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2848): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2848): getNetworkForDns: using netid 502 for uid 10031
,I/System.out(10494): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/SSRM:n  ( 3522): SIOP:: AP = 320, PST = 348, CUR = -481
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/ActivityManager( 3522): Killing 9577:com.google.android.apps.docs/u0a101 (adj 13): bgCount ##31
,I/ActivityManager( 3522): Killing 9723:com.sec.spp.push/u0a39 (adj 15): bgCount ##32
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/WifiStateMachine( 3522): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3522): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3522): CMD_RSSI_POLL : out!
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:2, health:2, present:true, voltage: 4393, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:-173, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:129
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/PowerManagerService( 3522): [s] UserActivityState : 2 -> 4
I/PowerManagerService( 3522): !@[ps] Screen__Off - 0 : timeout (0x4) (2)
I/PowerManagerService( 3522): Going to sleep due to screen timeout (uid 1000)...
,D/InputManager-JNI( 3522): setDeviceInteractive: 0
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 3522): [s] DisplayPowerCallbacks : onStateChanged()
,D/InputManager-JNI( 3522): sysfs_write +: /sys/class/input/event2/device/enabled: 0
D/InputManager-JNI( 3522): sysfs_write +: /sys/class/input/event3/device/enabled: 0
D/PowerManagerService( 3522): [PWL] sb acquire: PowerManagerService.Broadcasts
D/InputManager-JNI( 3522): sysfs_write +: /sys/class/input/event1/device/enabled: 0
D/InputManager-JNI( 3522): sysfs_write -: /sys/class/input/event3/device/enabled: 0
D/PowerManagerService( 3522): SecHardwareInterface.setBatteryADC : false
,D/InputManager-JNI( 3522): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/InputManager-JNI( 3522): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/PowerManagerService( 3522): handleSandman : startDream()
,D/SContextService( 3522): 	.unregisterCallback : 1, client=
D/SContextService( 3522): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@34795941, Service = Auto Rotation, used = 1
E/PowerManagerService( 3522): handleSandman : startDreaming, but isDreaming false
I/PowerManagerService( 3522): Sleeping (uid 1000)...
D/PowerManagerService( 3522): [s] UserActivityState : 4 -> 0
D/PowerManagerService( 3522): [input device light] setInputDeviceLightOn is called : 0
,D/PowerManagerService( 3522): [input device light] handleInputDeviceLightOff
,I/SurfaceFlinger( 2852): id=12 createSurf (1440x2560),2 flag=404, DolorFade
,W/CAE     ( 3522): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
,V/CAE     ( 3522): stop(ContextProvider.java:149)
,V/CAE     ( 3522): clear(AutoRotationRunner.java:182)
,V/CAE     ( 3522): disable(AutoRotationRunner.java:171)
,I/CAE     ( 3522): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager( 3522): SendSensorHubData: send data = -78, 7, 0, 0,
,D/Sensorhubs( 2869): sendContextData: -78, 7, 0, 0
,D/CAE     ( 3522): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     ( 3522): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/PowerManagerService( 3522): Excessive delay in ColorFade : createEglContext: 26ms
,D/mali_winsys( 3522): new_window_surface returns 0x3000,  [1440x2560]-format:1
,D/PermissionCache( 2852): checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (226 us)
,D/CAE     ( 3522): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     ( 3522): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
D/CAE     ( 3522): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     ( 3522): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService( 3522): removeSContextService() : service = Auto Rotation
D/SContextService( 3522): ===== SContext Service List =====
D/SContextManager( 3522):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@1ef27209, service=Auto Rotation
,D/KeyguardViewMediator( 3692): onScreenTurnedOff(3)
,I/KeyguardEffectViewController( 3692): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 3692): changeWallpaperByScreenOff()
,D/KeyguardViewMediator( 3692): notifyScreenOffLocked
,I/DBG_DM  ( 6257): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
,D/PowerManagerService( 3522): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 38ms
,D/KeyguardViewMediator( 3692): timeout : 5000
,V/ActivityThread( 6257): updateVisibility : ActivityRecord{5fbf7c6 token=android.os.BinderProxy@2948382b {com.wssyncmldm/com.wssyncmldm.ui.XUIInstallConfirmActivity}} show : true
,D/KeyguardViewMediator( 3692): setting alarm to turn off keyguard, seq = 1
,D/KeyguardViewMediator( 3692): handleNotifyScreenOff
,I/CAE     ( 3522): handleMessage(CaPowerManager.java:188) - AP_WAKEUP
,I/CAE     ( 3522): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_WAKEUP
,I/CAE     ( 3522): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -47, 0,
D/SensorHubManager( 3522): SendSensorHubData: send data = -76, 13, -47, 0
D/Sensorhubs( 2869): sendContextData: -76, 13, -47, 0
,D/PowerManagerService( 3522): Excessive delay in ColorFade : initGLShaders: 44ms
,D/InputMethodManagerService( 3522): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,D/MotionRecognitionService( 3522):   mReceiver.onReceive : ACTION_SCREEN_ON
,I/WifiTrafficPoller( 3522): evaluateTrafficStatsPolling
D/PowerManagerService( 3522): Excessive delay in ColorFade : draw: 18ms
E/MotionRecognitionService( 3522):  handler : SCREEN_ON end
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3692): applyOpen
,D/WifiStateMachine( 3522): backgroundScan enabled=false startBackgroundScanIfNeeded:false
D/NotificationService( 3522): ACTION_SCREEN_ON
E/WifiStateMachine( 3522): handleScreenStateChanged Exit: true
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/LightsService( 3522): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 3522) 
D/PowerManagerService( 3522): Excessive delay in ColorFade : draw: 15ms
D/LightsService( 3522): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
,D/StatusBar.NetworkController( 3692): applyOpen
,D/LightsService( 3522): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService( 3522): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/AudioHardwareTinyALSA( 2857): setParameters(screen_state=on)
,D/PowerManagerService( 3522): Excessive delay in ColorFade : draw: 20ms
D/PowerManagerService( 3522): Excessive delay in ColorFade prepare: 183ms
,E/WifiStateMachine( 3522): setSuspendOptimizationsNative: 4 false -want true stack:setSuspendOptimizationsNative - access$16900 - processMessage - processMsg
E/native  ( 3522): do suspend false
D/DisplayPowerController( 3522): ColorFade: onAnimationStart
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 0
D/DisplayPowerController( 3522): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 0
D/DisplayPowerController( 3522): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/SecExternalDisplayIntents_Java( 3522): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,I/wpa_supplicant( 3831): reset timer : RESET_TIMER 1
I/wpa_supplicant( 3831): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3831): P2P: Current p2p state = IDLE
,I/wpa_supplicant( 3831): Scan requested (ret=0) - scan timeout 30 seconds
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 0
D/lights  ( 3522): lcd : 0 +
D/IpRemoteDisplayController( 3522): intent received android.intent.action.SCREEN_ON
D/IpRemoteDisplayController( 3522): Bridge Server is not available
D/DisplayPowerController( 3522): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 3522): lcd : 0 -
,D/GpsLocationProvider( 3522): receive broadcast intent, action: android.intent.action.SCREEN_ON
,E/GpsLocationProvider( 3522): ++ Invoked android_location_GpsLocationProvider_set_lcd_mode --> mode:1 ++
E/GpsLocationProvider( 3522): sExerciseIterface is not available
,D/PersonaManagerService( 3522): ACTION_SCREEN_ON onReceive
,D/PersonaManagerServiceHandler( 3522): MSG_ACTION_SCREEN_ON called
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,I/NfcService( 3969): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 3969): call the applyRouting
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 0
D/DisplayPowerController( 3522): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/SamsungIME( 4484): getNextShiftState() cursorCapsMode : 0
,D/accuweather( 5195): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 5195): [KK AccuPhone]>>> UIM:118 [0:0] getInstance
,D/accuweather( 5195): [KK AccuPhone]>>> UIM:118 [0:0] getInstance
,D/accuweather( 5195): [KK AccuPhone]>>> UIM:281 [0:0] update clock event, is not screen on!!
,D/SSRM:n  ( 3522): SIOP:: AP = 320, PST = 343, CUR = -173
,I/SystemBroadcastReceiver(10232): [#DCM#] [DCM_Performance] onReceive completed in time  2441 microsec. 
,I/SystemBroadcastReceiver(10232): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager(10232): [#DCM#] onReceive action = EVENT_SCREEN_ON
I/DCMController(10232): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_ON
,D/daemonapp( 3772): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 3772): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 3772): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 3772): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 3772): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 3772): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 3772): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 3772): [MSC_Daemon]>>> daemonapp [Version : 15022501 ] [ 3 ] 
,D/comsamsunglog( 3772): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 3772): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 3772): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 3772): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
D/daemonapp( 3772): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/LightsService( 3522): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 10, onMS = 0, offMS = 0,  (uid: 1000 pid: 3522) 
D/LightsService( 3522): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x10 | SvcLED(id=3) set On
,D/daemonapp( 3772): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 3772): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1457993760000
D/LightsService( 3522): [SvcLED]  onSensorChanged::light value = 0
,D/daemonapp( 3772): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1457972230962
,D/SensorManager( 3522): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/BatteryService( 3522): turn on LED for charging
,D/SensorManager( 3522): unregisterListener ::   
D/lights  ( 3522): led_pattern : 1 +
,D/daemonapp( 3772): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/lights  ( 3522): led_pattern : 1 -
D/LightsService( 3522): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/daemonapp( 3772): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,D/daemonapp( 3772): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 3772): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
I/CAE     ( 3522): handleMessage(CaPowerManager.java:182) - AP_SLEEP
D/daemonapp( 3772): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
I/CAE     ( 3522): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
,I/CAE     ( 3522): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager( 3522): SendSensorHubData: send data = -76, 13, -46, 0
D/Sensorhubs( 2869): sendContextData: -76, 13, -46, 0
,D/daemonapp( 3772): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,I/CAE     ( 3522): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 16, 17, 10,
D/SensorHubManager( 3522): SendSensorHubData: send data = -63, 14, 16, 17, 10
D/Sensorhubs( 2869): sendContextData: -63, 14, 16, 17, 10
,E/daemonapp( 3772): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/MotionRecognitionService( 3522):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService( 3522):  handler : SCREEN_OFF end 
,I/WifiTrafficPoller( 3522): evaluateTrafficStatsPolling
,D/NotificationService( 3522): ACTION_SCREEN_OFF
D/LightsService( 3522): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 3522) 
D/LightsService( 3522): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x10 | SvcLED(id=4) set Off
D/WifiStateMachine( 3522): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine( 3522): handleScreenStateChanged Exit: false
,D/LightsService( 3522): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 3522): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,E/WifiStateMachine( 3522): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16900 - processMessage - processMsg
,E/WifiStateMachine( 3522): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16900 - processMessage - processMsg
D/SensorManager( 3522): unregisterListener ::   
D/LightsService( 3522): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
E/native  ( 3522): do suspend true
,I/AudioHardwareTinyALSA( 2857): setParameters(screen_state=off)
,I/SecExternalDisplayIntents_Java( 3522): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
D/DisplayPowerState( 3522): !@ ColorFade entry
D/DisplayPowerController( 3522): ColorFade: onAnimationEnd
,D/IpRemoteDisplayController( 3522): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController( 3522): Bridge Server is not available
,D/VolumePanel( 3692): registerReceiver: onReceive start 
D/VolumePanel( 3692): registerReceiver ACTION_SCREEN_OFF start
D/VolumePanel( 3692): registerReceiver ACTION_SCREEN_OFF end
D/VolumePanel( 3692): registerReceiver: onReceive end 
,D/VolumePanel( 3692): mCoverBroadcastReceiver: onReceive() start : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
D/VolumePanel( 3692): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 3692): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 3692): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 3692): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/GpsLocationProvider( 3522): receive broadcast intent, action: android.intent.action.SCREEN_OFF
,D/AutomaticBrightnessController( 3522): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
E/GpsLocationProvider( 3522): ++ Invoked android_location_GpsLocationProvider_set_lcd_mode --> mode:0 ++
I/AutomaticBrightnessController( 3522): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
E/GpsLocationProvider( 3522): sExerciseIterface is not available
I/AutomaticBrightnessController( 3522): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
D/AutomaticBrightnessController( 3522): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
,I/Sensors ( 3522): Light old sensor_state 513, new sensor_state : 1 en : 0
I/AutomaticBrightnessController( 3522): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
D/DisplayPowerController( 3522): getFinalBrightness : 0 -> 0
D/DisplayPowerController( 3522): animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/DisplayPowerController( 3522): getFinalBrightness : 0 -> 0
D/DisplayPowerController( 3522): animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/SurfaceFlinger( 2852): Set power mode=0, type=0 flinger=0xb6962000
I/hwcomposer( 2852): int exynos5_blank(hwc_composer_device_1*, int, int):: disp(0), blank(1)
I/DisplayManagerService( 3522): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1440 x 2560, 59.0 fps, supportedRefreshRates [59.0], density 640, 515.154 x 520.192 dpi, appVsyncOff 0, presDeadline 17949152, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/DisplayPowerController( 3522): getFinalBrightness : 0 -> 0
D/DisplayPowerController( 3522): animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/SensorManager( 3522): unregisterListener ::   
D/PowerManagerService( 3522): [s] DisplayPowerCallbacks : onStateChanged()
I/Sensors ( 3522): Acc old sensor_state 1, new sensor_state : 0 en : 0
D/PowerManagerService( 3522): [PWL] sb release: PowerManagerService.Display
,D/SensorManager( 3522): unregisterListener ::   
,V/ActivityManager( 3522): Display changed displayId=0
,D/PersonaManagerService( 3522): ACTION_SCREEN_OFF onReceive
,D/PersonaManagerServiceHandler( 3522): MSG_ACTION_SCREEN_OFF called
,D/NfcService( 3969): call the applyRouting
,D/STATUSBAR-PhoneStatusBar( 3692):      ACTION_SCREEN_OFF is finished!!!! 
,E/StatusBar( 3692): onReceive : Intent.ACTION_SCREEN_OFF
,D/accuweather( 5195): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 5195): [KK AccuPhone]>>> UIM:118 [0:0] getInstance
,D/accuweather( 5195): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/SSRM:n  ( 3522): SIOP:: AP = 320, PST = 340, CUR = -173
,D/daemonapp( 3772): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,D/accuweather( 5195): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5195): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5195): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
,D/accuweather( 5195): [KK AccuPhone]>>> UIM:311 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,D/daemonapp( 3772): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,I/SystemBroadcastReceiver(10232): [#DCM#] [DCM_Performance] onReceive completed in time  114 microsec. 
,I/SystemBroadcastReceiver(10232): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager(10232): [#DCM#] onReceive action = EVENT_SCREEN_OFF
,I/DCMController(10232): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_OFF
,D/PowerManagerService( 3522): [PWL] sb release: PowerManagerService.Broadcasts
,D/daemonapp( 3772): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 5195): [KK AccuPhone]>>> UIM:157 [0:0] make widget 4x1 view!!! 
,D/accuweather( 5195): [KK AccuPhone]>>> UIM:159 [0:0] make widget 4x2 view!!! 
,D/accuweather( 5195): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 160span x = 4, span y = 2
D/accuweather( 5195): [KK AccuPhone]>>> UIM:184 [0:0] get widget 4x2 view!!! wid = 2
,D/accuweather( 5195): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,D/accuweather( 5195): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 5195): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/SurfaceControl( 3522): Excessive delay in setPowerMode(): 194ms
D/PowerManagerService( 3522): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL( 3522): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 3522): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,D/PowerManagerService( 3522): Excessive delay in mPhotonicModulator.requestDisplayState(mRequestingState): 196ms
,I/PowerManagerService( 3522): [PWL] Off : 0s ago
,W/IcingInternalCorpora( 6708): getNumBytesRead when not calculated.
,D/SSRM:a  ( 3522): DeviceInfo:: 000000100000
D/SSRM:a  ( 3522): SettingsAirViewInfo:: 000000000
,D/CAR.SERVICE(10536): mConnectedToCar = false, abort
,E/ActivityThread(10536): Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2acc06b1 that was originally bound here
E/ActivityThread(10536): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarService has leaked ServiceConnection com.google.android.gms.car.hr@2acc06b1 that was originally bound here
E/ActivityThread(10536): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(10536): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(10536): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(10536): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(10536): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(10536): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(10536): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(10536): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
E/ActivityThread(10536): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
E/ActivityThread(10536): 	at com.google.android.gms.car.hc.<init>(:com.google.android.gms:319)
E/ActivityThread(10536): 	at com.google.android.gms.car.CarChimeraService.onCreate(:com.google.android.gms:74)
E/ActivityThread(10536): 	at com.google.android.chimera.container.ServiceProxy.setImpl(:com.google.android.gms:119)
E/ActivityThread(10536): 	at com.google.android.chimera.container.ServiceProxy.onCreate(:com.google.android.gms:109)
E/ActivityThread(10536): 	at android.app.ActivityThread.handleCreateService(ActivityThread.java:3149)
E/ActivityThread(10536): 	at android.app.ActivityThread.access$1900(ActivityThread.java:178)
E/ActivityThread(10536): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1532)
E/ActivityThread(10536): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(10536): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(10536): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(10536): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(10536): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(10536): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(10536): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/ActivityThread(10536): Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@879e770 that was originally bound here
E/ActivityThread(10536): android.app.ServiceConnectionLeaked: Service com.google.android.gms.car.CarCallService has leaked ServiceConnection com.google.android.gms.car.dq@879e770 that was originally bound here
E/ActivityThread(10536): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1134)
E/ActivityThread(10536): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1028)
E/ActivityThread(10536): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2155)
E/ActivityThread(10536): 	at android.app.ContextImpl.bindService(ContextImpl.java:2138)
E/ActivityThread(10536): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread(10536): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:128)
E/ActivityThread(10536): 	at com.google.android.gms.common.stats.g.a(:com.google.android.gms:145)
E/ActivityThread(10536): 	at com.google.android.gms.car.dp.a(:com.google.android.gms:586)
E/ActivityThread(10536): 	at com.google.android.gms.car.dp.<init>(:com.google.android.gms:511)
E/ActivityThread(10536): 	at com.google.android.gms.car.dp.a(:com.google.android.gms:488)
E/ActivityThread(10536): 	at com.google.android.gms.car.dm.<init>(:com.google.android.gms:112)
E/ActivityThread(10536): 	at com.google.android.gms.car.CarCallService.onBind(:com.google.android.gms:79)
E/ActivityThread(10536): 	at android.app.ActivityThread.handleBindService(ActivityThread.java:3181)
E/ActivityThread(10536): 	at android.app.ActivityThread.access$2000(ActivityThread.java:178)
E/ActivityThread(10536): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1537)
E/ActivityThread(10536): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread(10536): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread(10536): 	at android.app.ActivityThread.main(ActivityThread.java:5944)
E/ActivityThread(10536): 	at java.lang.reflect.Method.invoke(Native Method)
E/ActivityThread(10536): 	at java.lang.reflect.Method.invoke(Method.java:372)
E/ActivityThread(10536): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
E/ActivityThread(10536): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,W/ActivityManager( 3522): Unbind failed: could not find connection for android.os.BinderProxy@1cc61b22
,W/IdleConnectionHandler( 9965): Removing a connection that never existed!,
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/wpa_supplicant( 3831): nl80211: Received scan results (15 BSSes)
,D/WifiP2pService( 3522): InactiveState{ what=147461 }
,D/WifiP2pService( 3522): P2pEnabledState{ what=147461 }
D/WifiP2pService( 3522): DefaultState{ what=147461 }
,E/WifiStateMachine( 3522): [1,457,972,234,653 ms] noteScanEnd no scan source
,E/WifiStateMachine( 3522): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@38ce2f3b sup_state=COMPLETED debouncing=false
,V/AlarmManager( 3522): waitForAlarm result :4
,D/KeyguardViewMediator( 3692): received DELAYED_KEYGUARD_ACTION with seq = 1, mDelayedShowingSequence = 1
,D/KeyguardViewMediator( 3692): doKeyguard: not showing because lockscreen is off
,I/PowerManagerService( 3522): [PWL] Off : 5s ago
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3522): waitForAlarm result :8
,E/Watchdog( 3522): !@Sync 2
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:2, health:2, present:true, voltage: 4396, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:-6, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:160
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for charging,
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,W/ProcessCpuTracker( 3522): Skipping unknown process pid 10646
,V/AlarmManager( 3522): waitForAlarm result :4
,D/SSRM:n  ( 3522): SIOP:: AP = 300, PST = 335, CUR = -6
,V/AlarmManager( 3522): waitForAlarm result :4
,V/xAnalytics( 9740): xplat/fbacore/fbacore/XAnalytics.cpp - virtual void facebook::xanalytics::XAnalytics::resumeUploadFromStorage(const string&)
,D/Finsky  (10494): [1430] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,D/Finsky  (10494): [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:4/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 ,
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3522): [PWL] Off : 15s ago
,V/AlarmManager( 3522): waitForAlarm result :4
,E/ActivityThread( 6708): Failed to find provider info for com.android.contacts.metadata
,D/SyncManager( 3522): failed sync operation thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 53251, reason: UserStart, SyncResult: databaseError: true stats []
D/SyncManager( 3522): not retrying sync operation because the error is a hard error: thalitester@gmail.com u0 (com.google), com.android.contacts.metadata, POLL, currentRunTime 146129, reason: UserStart
,W/ResourceType( 5313): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5313): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
,D/SecContentProvider2( 3522): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 3522): mCursor = null
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:2, health:2, present:true, voltage: 4395, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:61, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:127
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for charging
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 290, PST = 330, CUR = 61
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:85, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:92
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
D/LightsService( 3522): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 3522) 
D/LightsService( 3522): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x10 -> 0x40 | SvcLED(id=3) set On
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,I/Sensors ( 3522): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager( 3522): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/BatteryService( 3522): turn on LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/SecContentProvider2( 3522): uri = 14 selection = getSealedState
D/SecContentProvider2( 3522): mCursor = null
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/ApplicationPolicy( 3522): isStatusBarNotificationAllowedAsUser: packageName = com.android.systemui,userId = -2
V/ApplicationPolicy( 3522): isApplicationStateBlocked userId -2 pkgname com.android.systemui
,D/WindowManager( 3522): showStatusBarByNotification() mOpenByNotification=false
,D/PowerManagerService( 3522): [api] acquire WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10060 pid=3692
I/PowerManagerService( 3522): !@[ps] Screen__On  - 1 :  wl: PowerUI.Notification
I/PowerManagerService( 3522): Waking up from sleep (uid 10060)...
,D/PowerManagerService( 3522): [PWL] sb acquire: PowerManagerService.Broadcasts
,D/PowerManagerService( 3522): [s] UserActivityState : 0 -> 1
V/KeyguardServiceDelegate( 3522): onScreenTurnedOn(showListener = com.android.internal.policy.impl.PhoneWindowManager$2@74de710)
,D/PowerManagerService( 3522): [PWL] sb acquire: PowerManagerService.Display
,I/DisplayPowerController( 3522): Blocking screen on until initial contents have been drawn.
,D/KeyguardViewMediator( 3692): onScreenTurnedOn, seq = 2
D/KeyguardViewMediator( 3692): notifyScreenOnLocked
,D/SContextService( 3522): 	.registerCallback : 1, client=
,W/CAE     ( 3522): setCAProperty(ContextAwareService.java:464) - [setProperty 01] Mutex is locked for AUTO_ROTATION
,D/AutomaticBrightnessController( 3522): [DAB] setLightSensorEnabled : Send Update registerListener mLightSensor
D/DisplayPowerController( 3522): getFinalBrightness : 0 -> 0
D/DisplayPowerController( 3522): animation target = 0, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)), PendingAutoBrightness)
D/AutomaticBrightnessController( 3522): [DAB] setLightSensorEnabled : registerListener mLightSensor
,D/PowerManagerService( 3522): !@[s] unblankAllDisplays() : unblankAllDisplaysFromPowerManager
D/AutomaticBrightnessController( 3522): [api] [DAB] onSensorChanged : 1st lux : 0.0
D/AutomaticBrightnessController( 3522): [DAB] updateAutoBrightnessSEC : 11(11.0)    0.0 < 0.0 < 15.0 (0.6)
D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
I/AutomaticBrightnessController( 3522): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 1
I/AutomaticBrightnessController( 3522): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 1
,D/MISC PowerHAL( 3522): sysfs_write +: /sys/class/power_supply/battery/lcd: 1
I/AutomaticBrightnessController( 3522): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 1
D/MISC PowerHAL( 3522): sysfs_write -: /sys/class/power_supply/battery/lcd: 1
I/CAE     ( 3522): setPropertyValue(AutoRotationRunner.java:119) - Device Type = 0.0
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
I/CAE     ( 3522): setCAProperty(ContextAwareService.java:469) - result : true
D/DisplayPowerController( 3522): animation target = 11, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/SurfaceFlinger( 2852): Set power mode=2, type=0 flinger=0xb6962000
I/hwcomposer( 2852): int exynos5_blank(hwc_composer_device_1*, int, int):: disp(0), blank(0)
,W/CAE     ( 3522): setCAProperty(ContextAwareService.java:470) - [setProperty 02] Mutex is unlocked for AUTO_ROTATION
D/SensorManager( 3522): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/SContextService( 3522): sendAttribute() : service = Auto Rotation
,D/PowerManagerService( 3522): Excessive delay in setLightSensorEnabled::registerListener(LightSensor): 6ms
,W/CAE     ( 3522): registerCallback(ContextAwareService.java:137) - [regi 01] Mutex is locked for AUTO_ROTATION
,I/Sensors ( 3522): Acc old sensor_state 512, new sensor_state : 513 en : 1
,V/CAE     ( 3522): start(ContextProvider.java:126)
,V/CAE     ( 3522): clear(AutoRotationRunner.java:182)
,V/CAE     ( 3522): enable(AutoRotationRunner.java:158)
,I/CAE     ( 3522): sendCmdToSensorHub(SensorHubCommManager.java:144) - -79, 7, 0, 0,
D/SensorHubManager( 3522): SendSensorHubData: send data = -79, 7, 0, 0
,D/Sensorhubs( 2869): sendContextData: -79, 7, 0, 0
,D/SensorManager( 3522): registerListener :: 0, ICM20610 Acceleration Sensor, 200000, 0,  
D/PowerManagerService( 3522): Excessive delay in setLightSensorEnabled::registerListener(TiltSensor): 8ms
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
,D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/CAE     ( 3522): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     ( 3522): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/CAE     ( 3522): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.,
,I/CAE     ( 3522): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 1, serviceCount = 1, subCollectionCount = 0,
,D/CAE     ( 3522): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,I/CAE     ( 3522): showListenerList(ContextAwareService.java:256) - Listener : com.samsung.android.contextaware.manager.ContextAwareService$Listener@287256cc, Service : AUTO_ROTATION(1)
,W/CAE     ( 3522): registerCallback(ContextAwareService.java:173) - [regi 02] Mutex is unlocked for AUTO_ROTATION,
,D/SContextService( 3522): addSContextService() : service = Auto Rotation
,D/SContextService( 3522): ===== SContext Service List =====
,D/SContextService( 3522): Listener : android.hardware.scontext.SContextService$Listener@3ce94d15, Service : Auto Rotation
D/SContextManager( 3522):   .registerListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@1ef27209, service=Auto Rotation
,V/ActivityManager( 3522): Display changed displayId=0
,I/DisplayManagerService( 3522): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1440 x 2560, 59.0 fps, supportedRefreshRates [59.0], density 640, 515.154 x 520.192 dpi, appVsyncOff 0, presDeadline 17949152, touch INTERNAL, rotation 0, type BUILT_IN, state ON, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS},
,I/Sensors ( 3522): #>LightSensor r=0 g=0 b=0 c=1 atime=238 again=64 lux=0.000000
,D/LightsService( 3522): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 3522): unregisterListener ::   
D/lights  ( 3522): led_pattern : 5 +
,D/KeyguardViewMediator( 3692): handleNotifyScreenOn
D/StatusBarKeyguardViewManager( 3692): onScreenTurnedOn()
,V/ActivityManager( 3522): Display changed displayId=0
,I/DBG_DM  ( 6257): [com.wssyncmldm.ui.XUIInstallConfirmActivity(456/onResume)] 
,D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/talkback/talkback.apk
,D/PalmMotion( 3522): 2014 - SURFACE_MOTION_ENGINE: 1 MOTION_MERGED_MUTE_PAUSE & SURFACE_PALM_TOUCH: 1
,D/PalmMotion( 3522): SURFACE_PALM_SWIPE: 1
,E/MotionRecognitionService( 3522):   mReceiver.onReceive : ACTION_USER_PRESENT  :: UNLOCK SCREEN
D/LightsService( 3522): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 3522) 
,D/lights  ( 3522): led_pattern : 5 -
D/LightsService( 3522): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/LightsService( 3522): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/SensorManager( 3522): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SSRM:a  ( 3522): DeviceInfo:: 000000100000
,D/SSRM:a  ( 3522): SettingsAirViewInfo:: 000000000
,V/AlarmManager( 3522): waitForAlarm result :4
,D/InputManager-JNI( 3522): setDeviceInteractive: 1
,D/SamsungIME( 4484): showDlgMsgBox : false true true
,I/DBG_DM  ( 6257): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 30,
,D/SurfaceControl( 3522): Excessive delay in setPowerMode(): 235ms
D/PowerManagerService( 3522): Excessive delay in mPhotonicModulator.requestDisplayState(mRequestingState): 238ms
,D/NfcService( 3969): call the applyRouting
,D/InputManager-JNI( 3522): sysfs_write +: /sys/class/input/event3/device/enabled: 1
D/InputManager-JNI( 3522): sysfs_write -: /sys/class/input/event3/device/enabled: 1
,D/InputManager-JNI( 3522): sysfs_write +: /sys/class/input/event1/device/enabled: 1
,I/DBG_DM  ( 6257): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,D/InputManager-JNI( 3522): sysfs_write +: /sys/class/input/event2/device/enabled: 1
,D/LightsService( 3522): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 3522): unregisterListener ::   
D/LightsService( 3522): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/KnoxNotification( 3692): ----- inflateViews : modified publicViewLocal -----
,D/SSRM:n  ( 3522): SIOP:: AP = 280, PST = 325, CUR = 85
,V/UserPresentBroadcastReceiver( 4650): Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,I/DBG_DM  ( 6257): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6257): [com.wssyncmldm.ui.XUIInstallConfirmActivity(466/onResume)] Postpone Count : 30
,D/KnoxNotification( 3692): ----- inflateViews : modified KnoxViewLocal -----
,D/PersonaManager( 3692): PersonaID is invalid or persona doesn't exists. : 0
,D/PhoneStatusBar( 3692): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@3c5614b2
,I/DBG_DM  ( 6257): [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Download Postpone status : 0
,D/PersonaManager( 3692): isKioskContainerExistOnDevice
D/PersonaManager( 3692): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3692): Icon Only
,I/StatusBar( 3692): Icon Only
D/PanelView( 3692): There is/are notification(s) 
D/PanelView( 3692): There is/are notification(s) 
,D/PersonaManager( 3692): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3692): Icon Only
I/StatusBar( 3692): Icon Only
D/PanelView( 3692): There is/are notification(s) 
,D/StatusBarKeyguardViewManager( 3692): callback.onShown()
V/KeyguardServiceDelegate( 3522): **** SHOWN CALLED ****
,D/DisplayPowerController( 3522): [api] WindowManagerPolicy.ScreenOnListener : Received onScreenOn().
,I/DisplayPowerController( 3522): Unblocked screen on after 314 ms
D/DisplayPowerState( 3522): !@ ColorFade exit
,I/SurfaceFlinger( 2852): id=12 Removed DolorFade (8/8)
I/SurfaceFlinger( 2852): id=12 Removed DolorFade (-2/8)
,E/libEGL  ( 3522): call to OpenGL ES API with no current context (logged once per thread)
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 3522): lcd : 11 +
,D/lights  ( 3522): lcd : 11 -
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 3522): [s] DisplayPowerCallbacks : onStateChanged()
D/PowerManagerService( 3522): SecHardwareInterface.setBatteryADC : true
D/PowerManagerService( 3522): [input device light] setInputDeviceLightOn is called : 1
,D/PowerManagerService( 3522): [input device light] handleInputDeviceLightOn
D/lights  ( 3522): button : 1 +
D/lights  ( 3522): button : 1 -
,D/LightsService( 3522): [api] [SvcLED] turnOff:: id = 3 (uid: 1000 pid: 3522) 
D/LightsService( 3522): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x0 | SvcLED(id=3) set Off
D/BatteryService( 3522): turn off LED
D/LightsService( 3522): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
I/DBG_DM  ( 6257): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
D/BatteryMeterView( 3692): onDraw batteryColor : -1
D/lights  ( 3522): led_pattern : 0 +
,D/lights  ( 3522): led_pattern : 0 -
D/LightsService( 3522): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/DBG_DM  ( 6257): [com.wssyncmldm.db.file.XDB(5114/lIIllllllIlllllIlIIl)] Get Priority : 0
,I/CAE     ( 3522): handleMessage(CaPowerManager.java:188) - AP_WAKEUP
I/CAE     ( 3522): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_WAKEUP
,I/CAE     ( 3522): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -47, 0,
D/SensorHubManager( 3522): SendSensorHubData: send data = -76, 13, -47, 0
D/Sensorhubs( 2869): sendContextData: -76, 13, -47, 0
,D/InputMethodManagerService( 3522): [HARDWARE_KEYBOARD] (refreshImeWindowVisibilityLocked) mImeWindowVis= 0 inputVisible = falsehaveHardKeyboard = false hardKeyShown = false
,I/Sensors ( 3522): #>LightSensor r=0 g=0 b=0 c=1 atime=238 again=64 lux=0.000000
,D/SecContentProvider2( 3522): uri = 14 selection = getSealedState
D/SecContentProvider2( 3522): mCursor = null
,D/MotionRecognitionService( 3522):   mReceiver.onReceive : ACTION_SCREEN_ON
,I/WifiTrafficPoller( 3522): evaluateTrafficStatsPolling
,E/MotionRecognitionService( 3522):  handler : SCREEN_ON end
,D/ApplicationPolicy( 3522): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3522): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,D/NotificationService( 3522): ACTION_SCREEN_ON
D/LightsService( 3522): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 3522) 
D/LightsService( 3522): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 3522): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService( 3522): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/WifiStateMachine( 3522): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine( 3522): handleScreenStateChanged Exit: true
,I/AudioHardwareTinyALSA( 2857): setParameters(screen_state=on)
,I/DBG_DM  ( 6257): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 30
,E/WifiStateMachine( 3522): setSuspendOptimizationsNative: 4 false -want true stack:setSuspendOptimizationsNative - access$16900 - processMessage - processMsg
E/native  ( 3522): do suspend false
,I/SecExternalDisplayIntents_Java( 3522): Intent Recieved ..  -android.intent.action.SCREEN_ONBroadCast Map value - 19
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,I/wpa_supplicant( 3831): reset timer : RESET_TIMER 1
I/wpa_supplicant( 3831): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 3831): P2P: Current p2p state = IDLE
,I/wpa_supplicant( 3831): Scan requested (ret=0) - scan timeout 30 seconds
I/DBG_DM  ( 6257): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,D/IpRemoteDisplayController( 3522): intent received android.intent.action.SCREEN_ON
,D/IpRemoteDisplayController( 3522): Bridge Server is not available
,I/DBG_DM  ( 6257): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6257): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
D/GpsLocationProvider( 3522): receive broadcast intent, action: android.intent.action.SCREEN_ON
E/GpsLocationProvider( 3522): ++ Invoked android_location_GpsLocationProvider_set_lcd_mode --> mode:1 ++
,E/GpsLocationProvider( 3522): sExerciseIterface is not available
I/DBG_DM  ( 6257): [llIIlIIlIllIllIlllII(376/llIIllllIIlllIIIIlll)] 
,I/DBG_DM  ( 6257): [IIlIIIlllllIIlIIIlII(339/llllIlIIIllllIIlIlll)] No need to check encryption status
,I/DBG_DM  ( 6257): [llIIlIIlIllIllIlllII(405/llIIllllIIlllIIIIlll)] InternalEncrypted : [false]
,D/ActivityManager( 3522): post active user change for 0
D/KnoxTimeoutHandler( 3522): postActiveUserChange for user 0
D/KnoxTimeoutHandler( 3522): handleActiveUserChange for user 0
,D/StatusBar( 3692): ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,D/PersonaManager( 3692): isKioskContainerExistOnDevice
D/PersonaManager( 3692): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3692): Icon Only
I/StatusBar( 3692): Icon Only
D/PanelView( 3692): There is/are notification(s) 
,D/PanelView( 3692): There is/are notification(s) 
D/PersonaManager( 3692): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3692): Icon Only
I/StatusBar( 3692): Icon Only
D/PanelView( 3692): There is/are notification(s) 
,D/PanelView( 3692): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,D/PersonaManagerService( 3522): ACTION_SCREEN_ON onReceive
D/PersonaManagerServiceHandler( 3522): MSG_ACTION_SCREEN_ON called
,I/NfcService( 3969): When receiving ACTION_SCREEN_ON, S view cover is already opened. So screenState is ON_UNLOCKED by isKeyguardLocked()
,D/NfcService( 3969): call the applyRouting
,I/Timeline( 6257): Timeline: Activity_idle id: android.os.BinderProxy@2948382b time:94445
,I/SamsungIME( 4484): getNextShiftState() cursorCapsMode : 0
,D/InputManager-JNI( 3522): sysfs_write -: /sys/class/input/event2/device/enabled: 1
,D/accuweather( 5195): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_ON
,D/accuweather( 5195): [KK AccuPhone]>>> UIM:118 [0:0] getInstance
D/accuweather( 5195): [KK AccuPhone]>>> UIM:118 [0:0] getInstance
,D/accuweather( 5195): [KK AccuPhone]>>> UIM:288 [0:0] direct update clock
,D/InputManager-JNI( 3522): sysfs_write -: /sys/class/input/event1/device/enabled: 1
,D/accuweather( 5195): [KK AccuPhone]>>> UIM:157 [0:0] make widget 4x1 view!!! 
,D/accuweather( 5195): [KK AccuPhone]>>> UIM:159 [0:0] make widget 4x2 view!!! 
,D/accuweather( 5195): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 160span x = 4, span y = 2
,D/accuweather( 5195): [KK AccuPhone]>>> UIM:1426 [0:0] mc sy = 2
,D/accuweather( 5195): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 160span x = 4, span y = 2
,D/accuweather( 5195): [KK AccuPhone]>>> UIM:184 [0:0] get widget 4x2 view!!! wid = 2
,E/accuweather( 5195): [KK AccuPhone]>>> UIM:1464 [0:0] bTM 17 17
,D/PanelView( 3692): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,D/SSRM:n  ( 3522): SIOP:: AP = 280, PST = 320, CUR = 85
,I/SystemBroadcastReceiver(10232): [#DCM#] [DCM_Performance] onReceive completed in time  392 microsec. 
,I/SystemBroadcastReceiver(10232): [#DCM#] Calling notifyListeners. 
I/DCMPolicyManager(10232): [#DCM#] onReceive action = EVENT_SCREEN_ON
I/DCMController(10232): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_ON
,D/PowerManagerService( 3522): [PWL] sb release: PowerManagerService.Broadcasts
,D/daemonapp( 3772): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 3772): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 3772): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 3772): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 3772): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 3772): [MSC_Daemon]>>> WDSM:54 [0:0] Act : comsamsungssrmSCREEN_ON, run:true
,D/comsamsunglog( 3772): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 3772): [MSC_Daemon]>>> daemonapp [Version : 15022501 ] [ 3 ] 
,D/comsamsunglog( 3772): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 3772): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 3772): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 3772): [MSC_Daemon]>>> WDSM:441 [0:0]  ==> Act: SCREEN_ON or COVER_OPEN <==
,D/daemonapp( 3772): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 3772): [MSC_Daemon]>>> WDSM:444 [0:0] [ASO][AUTOREFRESHKEY] --> 3
,D/daemonapp( 3772): [MSC_Daemon]>>> WDSM:445 [0:0] [ASO][NUT] = 1457993760000
D/daemonapp( 3772): [MSC_Daemon]>>> WDSM:446 [0:0] [ASO][CT] = 1457972261446
,D/daemonapp( 3772): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 3772): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,I/Sensors ( 3522): #>LightSensor r=0 g=0 b=1 c=2 atime=238 again=64 lux=0.000000
,D/daemonapp( 3772): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 3772): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 3772): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,D/daemonapp( 3772): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,E/daemonapp( 3772): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,D/SSRM:a  ( 3522): DeviceInfo:: 000000100000
D/SSRM:a  ( 3522): SettingsAirViewInfo:: 000000000
,D/PowerManagerService( 3522): [input device light] handleInputDeviceLightOff
D/lights  ( 3522): button : 0 +
,D/lights  ( 3522): button : 0 -
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/WifiStateMachine( 3522): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3522): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine( 3522): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/wpa_supplicant( 3831): nl80211: Received scan results (9 BSSes)
,D/WifiP2pService( 3522): InactiveState{ what=147461 }
,E/WifiStateMachine( 3522): [1,457,972,265,074 ms] noteScanEnd no scan source
D/WifiP2pService( 3522): P2pEnabledState{ what=147461 }
D/WifiP2pService( 3522): DefaultState{ what=147461 }
,E/WifiStateMachine( 3522): wifi setScanResults statecom.android.server.wifi.WifiStateMachine$ConnectedState@38ce2f3b sup_state=COMPLETED debouncing=false
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/AlarmManager( 3522): waitForAlarm result :4
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3692): applyOpen
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
I/art     ( 3522): Explicit concurrent mark sweep GC freed 75836(4MB) AllocSpace objects, 22(352KB) LOS objects, 24% free, 48MB/64MB, paused 2.108ms total 161.924ms
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/GLSActivity( 4650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/VacuumService( 4650): Vacuum at: now=1457972265674 tag=VacuumService
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/PhenotypeConfigurator( 4650): Scheduling Phenotype for one-off execution 12702 seconds from now (1457972266077)
,I/PhenotypeFlagCommitter( 4650): Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,I/GoogleURLConnFactory( 4650): Using platform SSLCertificateSocketFactory
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/LocationManagerService( 3522): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,V/GLSActivity( 4650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,V/GLSActivity( 4650): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/System.out( 4650): (HTTPLog)-Static: isSBSettingEnabled false
I/System.out( 4650): (HTTPLog)-Static: isShipBuild true
I/System.out( 4650): (HTTPLog)-Thread-321-554026939: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
I/System.out( 4650): (HTTPLog)-Static: isSBSettingEnabled false
,D/EnterpriseController( 2848): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    ( 2848): getNetworkForDns: using netid 502 for uid 10014
,I/System.out( 4650): KnoxVpnUidStorageknoxVpnSupported API value returned is false
,I/qtaguid ( 4650): Tagging socket 77 with tag 3000120100000000{805310977,0} uid -1, pid: 4650, getuid(): 10014
,I/qtaguid ( 4650): Tagging socket 81 with tag 3000120100000000{805310977,0} uid -1, pid: 4650, getuid(): 10014
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
,D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/LocationManagerService( 3522): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 4650): (HTTPLog)-Static: isSBSettingEnabled false
I/qtaguid ( 4650): Tagging socket 77 with tag 3000120100000000{805310977,0} uid -1, pid: 4650, getuid(): 10014
,I/WifiStateMachine( 3522): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3522): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3522): CMD_RSSI_POLL : out!
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020552/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/LocationManagerService( 3522): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 4650): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4650): Tagging socket 77 with tag 3000120100000000{805310977,0} uid -1, pid: 4650, getuid(): 10014
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/LocationManagerService( 3522): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 4650): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4650): Tagging socket 77 with tag 3000120100000000{805310977,0} uid -1, pid: 4650, getuid(): 10014
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/LocationManagerService( 3522): getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,I/System.out( 4650): (HTTPLog)-Static: isSBSettingEnabled false
,I/qtaguid ( 4650): Tagging socket 77 with tag 3000120100000000{805310977,0} uid -1, pid: 4650, getuid(): 10014
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/FactoryTest( 9304): Not factory mode
D/FactoryTest( 9304): Not factory mode. isFactoryMode() returend false
,D/MTPRx   ( 9304): DRIVER_TIME_OUT 60s lapsed
D/MTPRx   ( 9304): still no open session command from host, so toast
,W/ContextImpl( 9304): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:717 android.os.Handler.dispatchMessage:102 
,W/ContextImpl( 9304): Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1608 android.app.ContextImpl.startActivity:1597 android.content.ContextWrapper.startActivity:337 android.content.ContextWrapper.startActivity:337 com.samsung.android.MtpApplication.MtpReceiver$3.handleMessage:717 
I/Timeline( 9304): Timeline: Activity_launch_request id:com.android.settings time:101689
,E/PersonaManagerService( 3522): inState():  stateMachine is null !!
,I/PersonaManagerService( 3522): PersonaId don't exist
I/ActivityManager( 3522): do not start freezing screen for locked container getKeyguardshowstate = false
,V/ApplicationPolicy( 3522): isApplicationStateBlocked userId 0 pkgname com.android.settings
,I/ActivityManager( 3522): START u0 {flg=0x10000000 cmp=com.android.settings/.SettingsReceiverActivity} from uid 1000 on display 0
,D/CustomFrequencyManagerService( 3522): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3522  pkgName : ACTIVITY_RESUME_BOOSTER@2
,W/ActivityManager( 3522): mDVFSHelper.acquire()
,I/DBG_DM  ( 6257): [com.wssyncmldm.ui.XUIInstallConfirmActivity(394/onUserLeaveHint)] 
,E/MTPRx   ( 9304): started activity for popup
,D/PointerIcon( 3522): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3522): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3522): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3522): setHoveringSpenCustomIcon IconType is same.1
,I/DBG_DM  ( 6257): [com.wssyncmldm.db.file.XDB(5235/IllIIIIllIllIIllllll)] Get Postpone Count : 30
,I/DBG_DM  ( 6257): [com.wssyncmldm.db.file.XDB(5034/IIllIIllIIIlllIlIIll)] Get Force status : 0
,I/DBG_DM  ( 6257): [com.wssyncmldm.db.file.XDB(5257/llllIIlIlIIIIllIlIIl)] Get Postpone Max Count : 0
,I/DBG_DM  ( 6257): [com.wssyncmldm.ui.XUIInstallConfirmActivity(552/llIIIIlllllIIllIIllI)] Check Force Install : false
,I/DBG_DM  ( 6257): [com.wssyncmldm.ui.XUIInstallConfirmActivity(399/onUserLeaveHint)] Home Key!!
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/DBG_DM  ( 6257): [com.wssyncmldm.ui.XUIFotaPostponeActivity(329/lllIlIlIIIllIIlIllIl)] 
,I/DBG_DM  ( 6257): [com.wssyncmldm.db.file.XDB(3646/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,I/DBG_DM  ( 6257): [com.wssyncmldm.db.file.XDB(5276/IIIIIlIlIlIllIlIIllI)] Set Download Postpone status : 3
,I/DBG_DM  ( 6257): [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(326/llIIIIlllllIIllIIllI)] NotificationID : 3 / Notification IndicatorState : 3
,D/SecContentProvider2( 3522): uri = 14 selection = getSealedState
D/SecContentProvider2( 3522): mCursor = null
,D/LightsService( 3522): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 3522) 
D/LightsService( 3522): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x0 | SvcLED(id=4) set Off
D/LightsService( 3522): [SvcLED] Lux failed to be updated in 700ms. -> handleForcedSvcLEDTasK
D/LightsService( 3522): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,D/PersonaManager( 3692): isKioskContainerExistOnDevice
D/PersonaManager( 3692): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3692): Icon Only
,D/ApplicationPolicy( 3522): isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
V/ApplicationPolicy( 3522): isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
D/WindowManager( 3522): showStatusBarByNotification() mOpenByNotification=false
,I/DBG_DM  ( 6257): [com.wssyncmldm.db.file.XDB(3657/llIIIIlllllIIllllllI)] FUMO_Status : 220
,I/StatusBar( 3692): Icon Only
D/PanelView( 3692): There is/are notification(s) 
,D/PanelView( 3692): There is/are notification(s) 
,D/PersonaManager( 3692): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3692): Icon Only
I/StatusBar( 3692): Icon Only
D/PanelView( 3692): There is/are notification(s) 
,I/DBG_DM  ( 6257): [com.wssyncmldm.ui.XUIFotaPostponeActivity(373/lllIlIlIIIllIIlIllIl)] xdbSetFUMOStatus  to XDL_STATE_POSTPONE_TO_UPDATE
,I/DBG_DM  ( 6257): [com.wssyncmldm.ui.XUIFotaPostponeActivity(466/llIIIIlllllIIllIIllI)] 
,I/DBG_DM  ( 6257): [com.wssyncmldm.ui.XUIInstallConfirmActivity(448/onPause)] 
,V/ActivityManager( 3522): Display changed displayId=0
,D/KnoxNotification( 3692): ----- inflateViews : modified publicViewLocal -----
,V/WindowOrientationListener( 3522): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3522): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
V/WindowManager( 3522): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 3522): mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
V/WindowOrientationListener( 3522): mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,D/Launcher( 4001): onRestart, Launcher: 233716525
,D/KnoxNotification( 3692): ----- inflateViews : modified KnoxViewLocal -----
,D/Launcher( 4001): onStart, Launcher: 233716525
D/Launcher.HomeView( 4001): onStart
,V/ActivityThread( 4001): updateVisibility : ActivityRecord{1924ac83 token=android.os.BinderProxy@2f172d1d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,D/PersonaManager( 3692): PersonaID is invalid or persona doesn't exists. : 0
,D/PhoneStatusBar( 3692): tick(): knoxCustomManager = android.app.enterprise.knoxcustom.KnoxCustomManager@3c5614b2
,D/PersonaManager( 3692): isKioskContainerExistOnDevice
D/PersonaManager( 3692): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3692): Icon Only
,I/StatusBar( 3692): Icon Only
,D/PanelView( 3692): There is/are notification(s) 
D/PanelView( 3692): There is/are notification(s) 
D/PersonaManager( 3692): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3692): Icon Only
I/StatusBar( 3692): Icon Only
D/PanelView( 3692): There is/are notification(s) 
,D/ResourcesManager( 9304): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager( 9304): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager( 9304): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 9304): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
W/ResourcesManager( 9304): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,W/ResourcesManager( 9304): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 9304): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 9304): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/SurfaceFlinger( 2852): id=13 createSurf (1440x2560),1 flag=4, Mauncher
,D/mali_winsys( 4001): new_window_surface returns 0x3000,  [1440x2560]-format:1
,E/SettingsReceiverActivity( 9304): PREF_DONT_ASK_AGAIN : true
,D/FocusedStackFrame( 3522): Set to : 0
,D/StatusBarManagerService( 3522): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,E/ActivityManager( 3522): Invalid thumbnail dimensions: 768x768
,D/PointerIcon( 3522): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 3522): setMouseCustomIcon IconType is same.101
D/PointerIcon( 3522): setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
D/PointerIcon( 3522): setHoveringSpenCustomIcon IconType is same.1
,D/PanelView( 3692): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,W/OpenGLRenderer( 4001): SFEffectCache::get: create texture(0xa0c1a6f4): name, size, mSize = 41, 552980, 1394064
,D/InputMethodManagerService( 3522): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/PanelView( 3692): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,D/SettingsReceiverActivity( 9304): dev.kiessupport is : TRUE
,D/Activity( 9304): performCreate Call secproduct feature valuefalse
D/Activity( 9304): performCreate Call debug elastic valuetrue
,D/Launcher( 4001): onResume, Launcher: 233716525
,D/SettingsProvider( 3522): name = kids_home_mode
D/SettingsProvider( 3522): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 3522): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 3522): selectionArgs: false
D/SettingsProvider( 3522): selectionArgs: 10008
D/SecContentProvider( 3522): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 3522): ret = -1
D/Launcher.HomeView( 4001): onResume
,D/StatusBarManagerService( 3522): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/Launcher( 4001): setSystemUiTransparency.SettingNotFoundException : set as TRUE
,D/Launcher( 4001): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/MenuAppsGridFragment( 4001): onResume
,D/WallpaperManager( 4001): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,I/splitIntent( 3522): Split this intent : com.sec.android.intent.action.HOME_RESUME !!   mSplitNum[0]=3, mSplitNum[1]=7, mSplitNum[2]=9 divideNum= 2 r.nextReceiver= 1 receivers.size=11
D/WallpaperManager( 4001): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
I/splitIntent( 3522): finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,D/GalleryCacheReady(10316): Receive : home resume
I/MicrophoneInputStream( 4039): mic_starting gfk@26b4f478
,V/AudioPolicyManager( 2857): getInput() inputSource 1999, samplingRate 16000, format 8, channelMask 1, session 0, flags 0x10
V/AudioPolicyManager( 2857): getDeviceForInputSource()input source 1999, device 80000004
E/AudioHardwareTinyALSA( 2857): AudioStreamInALSA userDefined 0, pSize 960, pCount 2, buffer 1920, latency 120000
I/HotwordRecognitionRnr( 4039): Starting hotword detection.
,E/AudioHardwareTinyALSA( 2857): can not make /data/snd/input_after_ns2.pcm
E/AudioHardwareTinyALSA( 2857): can not make /data/snd/input_before_ns2.pcm
E/AudioHardwareTinyALSA( 2857): can not make /data/snd/input2.pcm
E/AudioHardwareTinyALSA( 2857): can not make /data/snd/seamless_compress_16k_mono.bin
E/AudioHardwareTinyALSA( 2857): can not make /data/snd/seamless_decode_16k_stereo.pcm
D/AudioHardwareTinyALSA( 2857): Input	: format = 1, channels = 16, rate = 16000
D/AudioHardwareTinyALSA( 2857): default	: format = 0, channelCount = 2, rate = 16000
D/AudioHardwareTinyALSA( 2857): AudioStreamOps::set set IN_Channels : 10
D/AudioHardwareTinyALSA( 2857): mInputs.size : 1
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
I/AudioFlinger( 2857): AudioFlinger's thread 0xaf522000 ready to run
D/AudioHardwareTinyALSA( 2857): Entering AudioStreamInALSA standby mode
,D/AudioHardwareTinyALSA( 2857): Entering AudioStreamInALSA standby mode
,I/EDMNativeHelperService( 3522): isMicrophoneEnabled
,E/Zygote  (10768): MountEmulatedStorage()
E/Zygote  (10768): v2
I/libpersona(10768): KNOX_SDCARD checking this for 1000
I/libpersona(10768): KNOX_SDCARD not a persona
,I/SELinux (10768): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3522): Start proc com.android.settings for broadcast com.android.settings/.accessibilitywidget.AccessibilityWidgetProviderAssistiveLight: pid=10768 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux (10768): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
V/AudioPolicyManager( 2857): startInput() input 20
V/AudioPolicyManager( 2857): getDeviceForInputSource()input source 1999, device 80000004
V/AudioPolicyManager( 2857): getNewInputDevice() selected device 80000004
I/AudioPolicyManager( 2857): ### Device reset for Normal
V/AudioPolicyManager( 2857): DeviceVector::refreshTypes() mDeviceTypes 80000004
V/AudioPolicyManager( 2857): DeviceVector::getDevicesFromType() for type 80000004 found 0xb235b280
,I/AudioHardwareTinyALSA( 2857): virtual android::status_t android::AudioStreamInALSA::setParameters(const android::String8&): input_source=6;keyIsHotword=true;routing=-2147483644
E/SELinux (10768): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/samsungRecord( 2857): [samsungrecord] SamsungRecInit 
I/samsungRecord( 2857): [samsungrecordMIC]Use HardCoding Values
E/samsungRecord( 2857): miccalib file can't created. (/data/snd/miccalib.txt)
I/samsungRecord( 2857): 1
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/AudioHardwareTinyALSA( 2857): InALSA::setDevice: mode = 0, newDevice=0x80000004, currentDevice=0x0 ,force= 0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
I/AudioHardwareTinyALSA( 2857): InALSA::setDevice: mode[0], Device[80000004] force=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/AudioHardwareTinyALSA( 2857): getInputScenario: input scenario = Voice
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/TinyUCM ( 2857): Enable Input dev(0x80000004)
D/TinyUCM ( 2857): setScenario: Voice
D/TinyUCM ( 2857): set default scenario
,D/TinyUCM ( 2857): Disable Output dev(0x0)
D/TinyUCM ( 2857): getInputChannel: inputs = 0x80000004
D/TinyUCM ( 2857): set channel: Left
I/AudioHardwareTinyALSA( 2857): InALSA::setDevice: mHandle NULL mode[0], Device[80000004]
I/AudioHardwareTinyALSA( 2857): Open:+ mDefaults->direction=10000000 device=0
D/AudioHardwareTinyALSA( 2857): Channel: 2, Samplerate: 48000, Format: 0, Period Size: 960, Period Count: 2
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/Zygote  (10782): MountEmulatedStorage()
E/Zygote  (10782): v2
I/libpersona(10782): KNOX_SDCARD checking this for 10052
I/libpersona(10782): KNOX_SDCARD not a persona
,I/SELinux (10782): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3522): Start proc com.android.mms for broadcast com.android.mms/.UIEventReceiver: pid=10782 uid=10052 gids={50052, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,I/SELinux (10782): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10782): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,D/ActivityManager( 3522): handle home activity for 0
I/WallpaperManagerService( 3522): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 3522): post home show event for user 0
D/ActivityManager( 3522): post active user change for 0
D/KnoxTimeoutHandler( 3522): postActiveUserChange for user 0
D/WallpaperManagerService( 3522):  force update = false; persona id = 0; current user =0; current persona = 0
D/KnoxTimeoutHandler( 3522): handleHomeShow for 0 and current 0
D/KnoxTimeoutHandler( 3522): handleActiveUserChange for user 0
,D/TimaKeyStoreProvider(10768): TimaSignature is unavailable
,D/ActivityThread(10768): Added TimaKeyStore provider
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/PushAndAttach(10083): mAssignedMemoMap.size() :0
,D/StatusBarManagerService( 3522): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
E/Zygote  (10795): MountEmulatedStorage()
E/Zygote  (10795): v2
I/libpersona(10795): KNOX_SDCARD checking this for 10173
I/libpersona(10795): KNOX_SDCARD not a persona
,I/SELinux (10795): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/ActivityManager( 3522): Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=10795 uid=10173 gids={50173, 9997, 1028, 1015} abi=armeabi-v7a
,I/SELinux (10795): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10795): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/Timeline( 4001): Timeline: Activity_idle id: android.os.BinderProxy@2f172d1d time:101976
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider(10782): TimaSignature is unavailable
,D/ActivityThread(10782): Added TimaKeyStore provider
,D/ResourcesManager(10768): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,W/ResourcesManager(10768): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
W/ResourcesManager(10768): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager(10768): Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
,W/ResourcesManager(10768): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(10768): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10768): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10768): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,E/Zygote  (10813): MountEmulatedStorage()
E/Zygote  (10813): v2
I/libpersona(10813): KNOX_SDCARD checking this for 10168
I/libpersona(10813): KNOX_SDCARD not a persona
,D/TimaKeyStoreProvider(10795): TimaSignature is unavailable
I/SELinux (10813): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/ActivityThread(10795): Added TimaKeyStore provider
,I/SELinux (10813): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10813): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=10813 uid=10168 gids={50168, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,I/AudioHardwareTinyALSA( 2857): Open:- mDefaults->direction=10000000 device=0 mHandle: b01a9600
D/AudioHardwareTinyALSA( 2857): setInputVolume
D/TinyUCM ( 2857): setModifier Recognition, en=1
D/TinyUCM ( 2857): Recognition doesn't have param
D/AudioHardwareTinyALSA( 2857): setPcmInterface: Stream=0x2, iSamplerate=16000++
D/AudioHardwareTinyALSA( 2857): setPcmInterface--
,V/AudioPolicyManager( 2857): setInputDevice() createAudioPatch returned -22 patchHandle 0
V/AudioPolicyManager( 2857): AudioPolicyManager::startInput() input source = 1999
,I/MicrophoneInputStream( 4039): mic_started gfk@26b4f478
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 8729(371KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 748us total 11.456ms
,D/TimaKeyStoreProvider(10813): TimaSignature is unavailable
,D/ActivityThread(10813): Added TimaKeyStore provider
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 513us total 9.390ms
D/ResourcesManager(10782): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,W/ResourcesManager(10782): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager(10782): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10782): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
W/ResourcesManager(10782): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10782): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager(10782): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/ResourcesManager(10795): creating new AssetManager and set to /system/app/SamsungWidget_ActiveApplication/SamsungWidget_ActiveApplication.apk
,I/art     ( 2879): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 265us total 8.685ms
,V/TaskCloserActivity(10795): TaskCloserActivity enter()
,V/TaskCloserActivity(10795): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,D/ResourcesManager(10813): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
,W/ResourcesManager(10813): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager(10813): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(10813): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager(10813): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
D/MySettingsProvider(10768): DatabaseHelper(Context context):DATABASE_VERSION=1
,I/ActivityManager( 3522): Killing 9767:com.samsung.android.sdk.samsunglink/u0a42 (adj 15): bgCount ##31
,E/SQLiteLog(10768): (283) recovered 10 frames from WAL file /data/data/com.android.settings/databases/mysettings.db-wal
,D/MySettingsProvider(10768): onCreate():(mDB == null)? false:true  =true
,I/HotwordWorker( 4039): onReady
,I/ActivityManager( 3522): Killing 9825:com.vlingo.midas/u0a34 (adj 15): bgCount ##31
,D/Mms/MmsApp(10782): [start]    onCreate() consume time = 0.0
,D/Mms/ArtClassLoader(10782): init before art
,D/Mms/ArtClassLoader(10782): init [DONE] art
D/Mms/TelephonyPermission(10782): start operation mode monitor
,D/ResourcesManager(10782): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,W/ResourcesManager(10782): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,D/Mms/TelephonyPermission(10782): DefaultSmsApp is com.android.mms
D/Mms/TelephonyPermission(10782): isDefault true
,D/Mms/MmsApp(10782): onCreate() com.android.mms
,W/BroadcastQueue( 3522): Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=4001, uid=10008) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
,I/ActivityManager( 3522): Killing 9801:com.sec.android.automotive.drivelink/u0a102 (adj 15): bgCount ##31
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,D/Mms/MmsApp(10782): [start]    initCountryIso consume time = 20.603167
,D/CountryDetector( 3522): The first listener is added
,E/Zygote  (10832): MountEmulatedStorage()
I/libpersona(10832): KNOX_SDCARD checking this for 10097
E/Zygote  (10832): v2
I/libpersona(10832): KNOX_SDCARD not a persona
,I/SELinux (10832): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,D/Mms/MmsApp(10782): [end]    initCountryIso consume time = 10.020625
D/Mms/MmsConfig(10782): [start]    MmsConfig.init() consume time = 0.062917
,I/SELinux (10832): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,E/SELinux (10832): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,D/Mms/MmsConfig(10782): before partial update
,I/ActivityManager( 3522): Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=10832 uid=10097 gids={50097, 9997} abi=armeabi-v7a
,D/Mms/MmsConfig(10782): Load Resize quality : 80
,D/Mms/MmsConfig(10782):  enable multiwindow = true
,D/TimaKeyStoreProvider(10832): TimaSignature is unavailable
,E/Mms/MessageUtils(10782): setCountryDetector : update country detector info 
D/ActivityThread(10832): Added TimaKeyStore provider
E/Mms/MessageUtils(10782): updateCountryIso : update country iso info 
,D/Mms/PackageInfo(10782): com.sec.imsservice is not installed
D/Mms/MmsConfig(10782): [end]    init() consume time = 24.787208
,D/Mms/Contact(10782): [start]    init() consume time = 0.353125
,D/Mms/Contact(10782): [end]    init consume time = 5.540083
,D/TP/MmsSmsProvider( 3985): query,matched:13, calling pid = 10782
,D/Mms/DraftCache(10782): [start]    rebuildCache consume time = 1.02825
,D/TP/MmsSmsProvider( 3985): match 13:Elapsed time : 0.867 ms
,D/TP/MmsSmsProvider( 3985): query,matched:12, calling pid = 10782
D/ResourcesManager(10832): creating new AssetManager and set to /system/app/DigitalClock/DigitalClock.apk
,D/Mms/TelephonyUtils(10782): getSubId from simSlot 0, return Value = -1
,D/Mms/DownloadManager(10782): roaming -> false (slotId = 0)
W/ResourcesManager(10832): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/Mms/DownloadManager(10782): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager(10782): auto download without roaming -> true
D/Mms/DownloadManager(10782): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
,E/Mms/TelephonyUtils(10782): subID is null or 0 length, so get DefaultSubId!!
D/Mms/TelephonyUtils(10782): getSubId from simSlot 1, return Value = 9223372036854775807
D/Mms/DownloadManager(10782): roaming -> false (slotId = 1)
D/Mms/DownloadManager(10782): [NotificationTransaction] getAutoDownloadState simSlot : 1
D/Mms/DownloadManager(10782): auto download without roaming -> true
D/Mms/DownloadManager(10782): [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
D/Mms/DownloadManager(10782): auto download during roaming secondary -> false
D/Mms/DownloadManager(10782): mAutoDownload ------> true
,D/TP/MmsSmsProvider( 3985): match 12:Elapsed time : 5.112 ms
,D/Mms/Conversation(10782): [start]    init() consume time = 9.740875
,D/Mms/DraftCache(10782): [end]    rebuildCache consume time = 0.430292
D/TP/MmsSmsProvider( 3985): deleteConversation threadId: 9223372036854775807
,D/TP/MmsSmsProvider( 3985): delete URI_CONVERSATIONS_MESSAGES affectedRows=0
,D/Mms/MmsApp(10782): [end]    onCreate() consume time = 1.824958
,D/Mms/UIEventReceiver(10782): ui event
D/Mms/DownloadManager(10782): Service state changed: Bundle[mParcelledData.dataSize=692]
D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/Mms/DownloadManager(10782): roaming ------> false, mSimSlot = 0
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/SQLiteLog( 3985): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3985): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3985): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3985): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3985): (284) automatic index on im_threads(normal_thread_id)
E/SQLiteLog( 3985): (284) automatic index on im_threads(normal_thread_id)
,D/Mms/TelephonyUtils(10782): getSubId from simSlot 0, return Value = -1
,D/Mms/DownloadManager(10782): roaming -> false (slotId = 0)
D/Mms/DownloadManager(10782): [NotificationTransaction] getAutoDownloadState simSlot : 0
D/Mms/DownloadManager(10782): auto download without roaming -> true
D/Mms/DownloadManager(10782): [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
D/Mms/DownloadManager(10782): mAutoDownload ------> true
,D/TP/MmsSmsProvider( 3985): delete threadId: 9223372036854775807
D/TP/MmsSmsProvider( 3985): need read changed broadcast:false
,I/ActivityManager( 3522): Killing 9854:com.osp.app.signin/u0a45 (adj 15): bgCount ##31
,E/lowmemorykiller( 2827): Error writing /proc/9854/oom_score_adj; errno=22
,D/Mms/Conversation(10782): [end]    init consume time = 9.219375
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/Mms/MessagingNotification(10782): [start]    init() consume time = 0.819584
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10853): MountEmulatedStorage()
E/Zygote  (10853): v2
I/libpersona(10853): KNOX_SDCARD checking this for 10105
I/libpersona(10853): KNOX_SDCARD not a persona
,I/SELinux (10853): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10853): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=10853 uid=10105 gids={50105, 9997, 3003} abi=armeabi-v7a
E/SELinux (10853): [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 3522): Killing 9945:com.samsung.android.app.filterinstaller/1000 (adj 13): bgCount ##31
,D/CustomFrequencyManagerService( 3522): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3522  tag : ACTIVITY_RESUME_BOOSTER@2
,I/Timeline( 3522): Timeline: Activity_windows_visible id: ActivityRecord{344a3797 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t30} time:102163
W/ActivityManager( 3522): mDVFSHelper.release()
,D/TimaKeyStoreProvider(10853): TimaSignature is unavailable
,D/ActivityThread(10853): Added TimaKeyStore provider
D/CustomFrequencyManagerService( 3522): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3522  pkgName : ACTIVITY_RESUME_BOOSTER@6
D/Mms/MessagingNotification(10782): [end]    init consume time = 28.078
,D/Mms/SpamFilter(10782): [start]    SpamFilter fill() begin consume time = 1.40825
,D/Mms/Synchronizer(10782): [start]    doSync consume time = 0.715291
,D/TP/MmsSmsProvider( 3985): query,matched:0, calling pid = 10782
V/TP/MmsSmsProvider( 3985): getSimpleConversations entered.
,D/TP/MmsSmsProvider( 3985): match 0:Elapsed time : 0.644 ms
,D/TP/MmsSmsProvider( 3985): query,matched:400, calling pid = 10782
,D/ResourcesManager(10853): creating new AssetManager and set to /system/app/DualClockDigital/DualClockDigital.apk
,D/TP/MmsSmsProvider( 3985): update uri: content://mms-sms/db_synchronization
V/TP/MmsSmsProvider( 3985): syncDBData start
D/Mms/SpamFilter(10782): [end]    SpamFilter fill() finished consume time = 10.867209
V/TP/MmsSmsProvider( 3985): syncDBData sms end
,V/TP/MmsSmsProvider( 3985): syncDBData mms end
W/ResourcesManager(10853): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10853): Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
V/TP/MmsSmsProvider( 3985): syncDBData end
,D/Mms/Synchronizer(10782): [end]    doSync consume time = 1.528833
,D/Mms/MessagingNotification(10782): checkBadgeCount unreadCount=0 badgeCount=0
,D/TP/SmsProvider( 3985): query,matched:26, calling pid = 10782
,D/TP/SmsProvider( 3985): match 26:Elapsed time : 0.647 ms
,D/TP/MmsSmsProvider( 3985): query,matched:6, calling pid = 10782
,D/TP/MmsSmsProvider( 3985): match 6:Elapsed time : 0.828 ms
,I/Mms/ReservationManager(10782): ReservationManager()
,I/Mms/ReservationManager(10782): resetAfterConnected()
,I/splitIntent( 3522): Queue : backgroundsplit_0 intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
,D/TP/MmsSmsProvider( 3985): query,matched:7, calling pid = 10782
I/ActivityManager( 3522): Killing 9920:com.android.providers.calendar/u0a47 (adj 15): bgCount ##31
,D/TP/MmsSmsProvider( 3985): match 7:Elapsed time : 3.154 ms
,I/Mms/ReservationManager(10782): getReservedSendMessageCount(): retMessageCount=0
,E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
,E/Zygote  (10871): MountEmulatedStorage()
E/Zygote  (10871): v2
I/libpersona(10871): KNOX_SDCARD checking this for 10028
I/libpersona(10871): KNOX_SDCARD not a persona
,I/SELinux (10871): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
,I/SELinux (10871): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
,I/ActivityManager( 3522): Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=10871 uid=10028 gids={50028, 9997} abi=armeabi-v7a
E/SELinux (10871): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider(10871): TimaSignature is unavailable
,D/ActivityThread(10871): Added TimaKeyStore provider
,I/ActivityManager( 3522): Killing 9981:com.samsung.android.app.watchmanagerstub/u0a121 (adj 15): bgCount ##31
,D/ResourcesManager(10871): creating new AssetManager and set to /system/priv-app/OmaCP/OmaCP.apk
,W/ResourcesManager(10871): Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,I/OMACP   (10871): [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,D/Mms/Omacp(10782): checkOmacp()  old OmacpCount 0 current OmacpCount = 0
,D/Mms/ArtClassLoader(10782): init before art
D/Mms/ArtClassLoader(10782): init [DONE] art
,D/Mms/PerformanceUtils(10782): link cahcing start
,I/OMACP   (10871): [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
,I/OMACP   (10871): [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
,I/OMACP   (10871): [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
,I/OMACP   (10871): [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
,I/OMACP   (10871): [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
,I/OMACP   (10871): [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
,I/OMACP   (10871): [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
,I/OMACP   (10871): [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
,I/OMACP   (10871): [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
,I/OMACP   (10871): [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
,I/OMACP   (10871): [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
,I/OMACP   (10871): [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
,I/OMACP   (10871): [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
,D/Mms/PerformanceUtils(10782): link cahcing done
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/SurfaceFlinger( 2852): id=11 Removed YUIInstallC (6/8)
I/SurfaceFlinger( 2852): id=11 Removed YUIInstallC (-2/8)
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/CustomFrequencyManagerService( 3522): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1800000  uid : 1000  pid : 3522  tag : ACTIVITY_RESUME_BOOSTER@6
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,E/Watchdog( 3522): !@Sync 3
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,I/WifiStateMachine( 3522): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3522): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3522): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4394, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:-17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:93
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/PersonaManager( 3692): isKioskContainerExistOnDevice
,D/PersonaManager( 3692): isKioskContainerExistOnDevice
I/PhoneStatusBar( 3692): Icon Only
I/StatusBar( 3692): Icon Only
,D/PanelView( 3692): There is/are notification(s) 
,D/PanelView( 3692): There is/are notification(s) 
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/Mms/MmsApp(10782):  start initViewCache mms
,D/Mms/ComposeMessageFragment(10782): [start]    fillCache consume time = 1950.506375
D/Mms/ComposeMessageFragment(10782): fillCache, easy = false
,D/PanelView( 3692): mClearAll.setVisibility - mIsFullyOpened : false isKeyGuard : false mIsDetailviewMode : false mHasNotification : true mStatusBar.isBouncerShowing() : false isShadeLocked : false mClearAllVisible : false
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AbsListView(10782): Get MotionRecognitionManager
,D/MotionRecognitionService( 3522):  ssp status : true
,D/Mms/ComposeMessageFragment(10782): [end]    fillCache consume time = 98.602042
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/Mms/BubbleViewCache(10782): fillCache bubble = 8
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/SSRM:n  ( 3522): SIOP:: AP = 290, PST = 318, CUR = -17
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/libencoder( 3522): width= 768, height = 768, colot_type= 6, bit_depth= 8
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/TaskPersister( 3522): removeObsoleteFile: deleting file=31_task_thumbnail.png
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3692): applyOpen
,I/WifiStateMachine( 3522): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3522): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine( 3522): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/WifiStateMachine( 3522): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3522): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3522): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
,D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/AlarmManager( 3522): waitForAlarm result :4
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,I/WifiStateMachine( 3522): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3522): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3522): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,V/AlarmManager( 3522): waitForAlarm result :8
,V/AlarmManager( 3522): ___SyncScheduler (v3) ACTIVATED___
V/AlarmManager( 3522): <AppSync3 Whitelist>
V/AlarmManager( 3522): (AppSync) ### 0 added ###
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.TIME_TICK,
D/KeyguardUpdateMonitor( 3692): handleTimeUpdate
,D/KeyguardEffectViewController( 3692): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3692): *** don't update sliding image ***
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/accuweather( 5195): [KK AccuPhone]>>> WCS:144 [0:0] action : androidintentactionTIME_TICK
,D/accuweather( 5195): [KK AccuPhone]>>> UIM:118 [0:0] getInstance
,D/accuweather( 5195): [KK AccuPhone]>>> UIM:288 [0:0] direct update clock
,D/accuweather( 5195): [KK AccuPhone]>>> UIM:157 [0:0] make widget 4x1 view!!! 
,D/accuweather( 5195): [KK AccuPhone]>>> UIM:159 [0:0] make widget 4x2 view!!! 
,D/accuweather( 5195): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 160span x = 4, span y = 2
D/accuweather( 5195): [KK AccuPhone]>>> UIM:1426 [0:0] mc sy = 2
,D/accuweather( 5195): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 160span x = 4, span y = 2
,D/accuweather( 5195): [KK AccuPhone]>>> UIM:184 [0:0] get widget 4x2 view!!! wid = 2
,E/accuweather( 5195): [KK AccuPhone]>>> UIM:1464 [0:0] bTM 17 18
,W/OpenGLRenderer( 4001): SFEffectCache::get: create texture(0xa0c1a6f4): name, size, mSize = 43, 571152, 1965216
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 3522): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10060 pid=3692 (0x0)
D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:97
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/SSRM:n  ( 3522): SIOP:: AP = 280, PST = 314, CUR = 31
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,I/WifiStateMachine( 3522): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3522): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3522): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/StatusBar.NetworkController( 3692): applyOpen
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 11
D/DisplayPowerController( 3522): animation target = 11, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 3522): [s] UserActivityState : 1 -> 2
,D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 3522): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  ( 3522): lcd : 9 +
,D/lights  ( 3522): lcd : 9 -
,D/lights  ( 3522): lcd : 1 +
,D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 3522): lcd : 1 -
,D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/WifiStateMachine( 3522): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3522): CMD_RSSI_POLL : calculateWifiScore out!
,I/WifiStateMachine( 3522): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,I/WifiStateMachine( 3522): CMD_RSSI_POLL : calculateWifiScore in!
,I/WifiStateMachine( 3522): CMD_RSSI_POLL : calculateWifiScore out!
I/WifiStateMachine( 3522): CMD_RSSI_POLL : out!
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020554/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBar.NetworkController( 3692): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020581/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f020158/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020550/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808ef/android:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 3692): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 3692): applyOpen
D/StatusBar.NetworkController( 3692): refreshSignalCluster - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 3692): applyOpen
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 1 -> 1
D/DisplayPowerController( 3522): animation target = 1, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 3522): [s] UserActivityState : 2 -> 4
I/PowerManagerService( 3522): !@[ps] Screen__Off - 1 : timeout (0x4) (2)
D/InputManager-JNI( 3522): setDeviceInteractive: 0
I/PowerManagerService( 3522): Going to sleep due to screen timeout (uid 1000)...
D/PowerManagerService( 3522): [PWL] sb acquire: PowerManagerService.Broadcasts
D/PowerManagerService( 3522): SecHardwareInterface.setBatteryADC : false
D/InputManager-JNI( 3522): sysfs_write +: /sys/class/input/event3/device/enabled: 0
,D/InputManager-JNI( 3522): sysfs_write -: /sys/class/input/event3/device/enabled: 0
D/PowerManagerService( 3522): handleSandman : startDream()
,D/InputManager-JNI( 3522): sysfs_write +: /sys/class/input/event1/device/enabled: 0
E/PowerManagerService( 3522): handleSandman : startDreaming, but isDreaming false
,D/InputManager-JNI( 3522): sysfs_write +: /sys/class/input/event2/device/enabled: 0
I/PowerManagerService( 3522): Sleeping (uid 1000)...
D/PowerManagerService( 3522): [s] UserActivityState : 4 -> 0
D/PowerManagerService( 3522): [input device light] setInputDeviceLightOn is called : 0
,I/SurfaceFlinger( 2852): id=14 createSurf (1440x2560),2 flag=404, DolorFade
D/PowerManagerService( 3522): [input device light] handleInputDeviceLightOff
,D/InputManager-JNI( 3522): sysfs_write -: /sys/class/input/event1/device/enabled: 0
,D/InputManager-JNI( 3522): sysfs_write -: /sys/class/input/event2/device/enabled: 0
,D/SContextService( 3522): 	.unregisterCallback : 1, client=
D/SContextService( 3522): unregisterCallback() : Listener = android.hardware.scontext.SContextService$Listener@3ce94d15, Service = Auto Rotation, used = 1
D/PowerManagerService( 3522): Excessive delay in ColorFade : createSurface: 13ms
,W/CAE     ( 3522): unregisterCallback(ContextAwareService.java:199) - [unregi 01] Mutex is locked for AUTO_ROTATION
D/mali_winsys( 3522): new_window_surface returns 0x3000,  [1440x2560]-format:1
V/CAE     ( 3522): stop(ContextProvider.java:149)
V/CAE     ( 3522): clear(AutoRotationRunner.java:182)
V/CAE     ( 3522): disable(AutoRotationRunner.java:171)
,I/CAE     ( 3522): sendCmdToSensorHub(SensorHubCommManager.java:144) - -78, 7, 0, 0,
D/SensorHubManager( 3522): SendSensorHubData: send data = -78, 7, 0, 0
,D/Sensorhubs( 2869): sendContextData: -78, 7, 0, 0
,D/CAE     ( 3522): getFaultDetectionResult(AutoRotationRunner.java:195) - true
,I/CAE     ( 3522): notifyCmdProcessResultObserver(ContextProvider.java:617) - CheckResult = 0, Cause = Success
,D/PowerManagerService( 3522): Excessive delay in ColorFade : captureScreenshotTextureAndSetViewport: 39ms
,D/CAE     ( 3522): doCommendProcess(ContextAwareService.java:314) - complete notify the operation result.
,I/CAE     ( 3522): displayUsedCountForService(ContextAwareService.java:406) - totalCnt = 0, serviceCount = 0, subCollectionCount = 0
D/CAE     ( 3522): showListenerList(ContextAwareService.java:247) - ===== Context Aware Service List =====
,W/CAE     ( 3522): unregisterCallback(ContextAwareService.java:234) - [unregi 02] Mutex is unlocked for AUTO_ROTATION
D/SContextService( 3522): removeSContextService() : service = Auto Rotation
D/SContextService( 3522): ===== SContext Service List =====
D/SContextManager( 3522):   .unregisterListener : listener = com.android.internal.policy.impl.WindowOrientationListener$SContextListenerImpl@1ef27209, service=Auto Rotation
,D/KeyguardViewMediator( 3692): onScreenTurnedOff(3)
I/KeyguardEffectViewController( 3692): *** KeyguardEffectView getInstanceIfExists ***
D/KeyguardEffectViewController( 3692): changeWallpaperByScreenOff()
D/KeyguardViewMediator( 3692): notifyScreenOffLocked
,D/KeyguardViewMediator( 3692): timeout : 5000
D/Launcher.HomeView( 4001): onPause
,D/Launcher( 4001): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/PowerManagerService( 3522): Excessive delay in ColorFade : initGLShaders: 42ms
,D/PowerManagerService( 3522): Excessive delay in ColorFade : draw: 18ms
,D/PowerManagerService( 3522): Excessive delay in ColorFade : draw: 13ms
,D/KeyguardViewMediator( 3692): setting alarm to turn off keyguard, seq = 2
D/KeyguardViewMediator( 3692): handleNotifyScreenOff
,D/PowerManagerService( 3522): Excessive delay in ColorFade : draw: 12ms
,D/PowerManagerService( 3522): Excessive delay in ColorFade prepare: 144ms
D/DisplayPowerController( 3522): ColorFade: onAnimationStart
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 0
D/DisplayPowerController( 3522): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 0
D/DisplayPowerController( 3522): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/StatusBarManagerService( 3522): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
V/TaskCloserActivity(10795): TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
,V/ActivityThread( 4001): updateVisibility : ActivityRecord{1924ac83 token=android.os.BinderProxy@2f172d1d {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
D/Launcher.HomeView( 4001): onStop
,I/MicrophoneInputStream( 4039): mic_close gfk@26b4f478
,V/AudioPolicyManager( 2857): stopInput() input 20
,V/AudioPolicyManager( 2857): releaseInput() 20
,V/AudioPolicyManager( 2857): closeInput(20)
I/HotwordRecognitionRnr( 4039): Hotword detection finished
I/HotwordRecognitionRnr( 4039): Stopping hotword detection.
,D/AudioHardwareTinyALSA( 2857): Entering AudioStreamInALSA standby mode
I/AudioHardwareTinyALSA( 2857): Close mHandle:b01a9600
,D/lights  ( 3522): lcd : 0 +
D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 0
,D/DisplayPowerController( 3522): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/lights  ( 3522): lcd : 0 -
,I/AudioHardwareTinyALSA( 2857): closeInputStream +
D/TinyUCM ( 2857): Disable Input dev(0x80000004)
,D/TinyUCM ( 2857): set channel: None
,D/AudioHardwareTinyALSA( 2857): Entering AudioStreamInALSA standby mode
,V/AudioPolicyManager( 2857): releaseInput() exit
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4377, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:50, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-154
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/AutomaticBrightnessController( 3522): mCallbacks.updateBrightness()
,D/LightsService( 3522): [api] [SvcLED] setFlashing :: id = 3, color = 0, mode = 14, onMS = 0, offMS = 0,  (uid: 1000 pid: 3522) 
D/LightsService( 3522): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x0 -> 0x40 | SvcLED(id=3) set On
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/LightsService( 3522): [SvcLED]  onSensorChanged::light value = 0
,D/SensorManager( 3522): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
D/BatteryService( 3522): turn on LED for fully charged
,D/SensorManager( 3522): unregisterListener ::   
D/lights  ( 3522): led_pattern : 5 +
,D/lights  ( 3522): led_pattern : 5 -
D/LightsService( 3522): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/CAE     ( 3522): handleMessage(CaPowerManager.java:182) - AP_SLEEP
,I/CAE     ( 3522): updateApPowerStatus(SensorHubParserProvider.java:421) - AP_SLEEP
I/CAE     ( 3522): sendCmdToSensorHub(SensorHubCommManager.java:144) - -76, 13, -46, 0,
D/SensorHubManager( 3522): SendSensorHubData: send data = -76, 13, -46, 0
,D/Sensorhubs( 2869): sendContextData: -76, 13, -46, 0
,I/CAE     ( 3522): sendCmdToSensorHub(SensorHubCommManager.java:144) - -63, 14, 16, 18, 11,
D/SensorHubManager( 3522): SendSensorHubData: send data = -63, 14, 16, 18, 11
D/Sensorhubs( 2869): sendContextData: -63, 14, 16, 18, 11
,D/MotionRecognitionService( 3522):   mReceiver.onReceive : ACTION_SCREEN_OFF
,E/MotionRecognitionService( 3522):  handler : SCREEN_OFF end 
,D/DisplayPowerController( 3522): getFinalBrightness : 11 -> 0
D/DisplayPowerController( 3522): animation target = 0, rate=500 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,I/WifiTrafficPoller( 3522): evaluateTrafficStatsPolling
,D/WifiStateMachine( 3522): backgroundScan enabled=false startBackgroundScanIfNeeded:false
E/WifiStateMachine( 3522): handleScreenStateChanged Exit: false
,D/NotificationService( 3522): ACTION_SCREEN_OFF
D/LightsService( 3522): [api] [SvcLED] turnOff:: id = 4 (uid: 1000 pid: 3522) 
D/LightsService( 3522): [SvcLED] setSvcLedStateLocked:: SvcLEDState : 0x40 -> 0x40 | SvcLED(id=4) set Off
,D/LightsService( 3522): [SvcLED]  onSensorChanged::light value = 0
,E/WifiStateMachine( 3522): setSuspendOptimizationsNative: 4 true -want true stack:setSuspendOptimizationsNative - access$16900 - processMessage - processMsg
,E/WifiStateMachine( 3522): setSuspendOptimizationsNative do it 4 true stack:setSuspendOptimizationsNative - access$16900 - processMessage - processMsg
E/native  ( 3522): do suspend true
D/SensorManager( 3522): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/SensorManager( 3522): unregisterListener ::   
D/LightsService( 3522): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/AudioHardwareTinyALSA( 2857): setParameters(screen_state=off)
,I/SecExternalDisplayIntents_Java( 3522): Intent Recieved ..  -android.intent.action.SCREEN_OFFBroadCast Map value - 18
,D/IpRemoteDisplayController( 3522): intent received android.intent.action.SCREEN_OFF
D/IpRemoteDisplayController( 3522): Bridge Server is not available
,D/VolumePanel( 3692): registerReceiver: onReceive start 
D/VolumePanel( 3692): registerReceiver ACTION_SCREEN_OFF start
D/VolumePanel( 3692): registerReceiver ACTION_SCREEN_OFF end
D/VolumePanel( 3692): registerReceiver: onReceive end 
,D/VolumePanel( 3692): mCoverBroadcastReceiver: onReceive() start : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
D/VolumePanel( 3692): mCoverBroadcastReceiver: Screen OFF start
D/VolumePanel( 3692): mCoverBroadcastReceiver : call onDismissSafeVolumeWarning() #1
,D/VolumePanel( 3692): mCoverBroadcastReceiver: Screen OFF end
D/VolumePanel( 3692): mCoverBroadcastReceiver: onReceive() end : intent=Intent { act=android.intent.action.SCREEN_OFF flg=0x50000010 (has extras) }
,D/GpsLocationProvider( 3522): receive broadcast intent, action: android.intent.action.SCREEN_OFF
E/GpsLocationProvider( 3522): ++ Invoked android_location_GpsLocationProvider_set_lcd_mode --> mode:0 ++
E/GpsLocationProvider( 3522): sExerciseIterface is not available
,D/DisplayPowerState( 3522): !@ ColorFade entry
D/DisplayPowerController( 3522): ColorFade: onAnimationEnd
,D/PersonaManagerService( 3522): ACTION_SCREEN_OFF onReceive
D/PersonaManagerServiceHandler( 3522): MSG_ACTION_SCREEN_OFF called
,I/Sensors ( 3522): Light old sensor_state 513, new sensor_state : 1 en : 0
D/AutomaticBrightnessController( 3522): [DAB] setLightSensorEnabled : Send Update unregisterListener mLightSensor
I/AutomaticBrightnessController( 3522): [DAB] fileWriteInt : /sys/class/tcon/tcon/auto_br  value : 0
D/AutomaticBrightnessController( 3522): [DAB] setLightSensorEnabled : unregisterListener mLightSensor
I/AutomaticBrightnessController( 3522): [DAB] fileWriteInt : /sys/class/backlight/panel/auto_brightness  value : 0
,D/SensorManager( 3522): unregisterListener ::   
I/Sensors ( 3522): Acc old sensor_state 1, new sensor_state : 0 en : 0
,I/AutomaticBrightnessController( 3522): [DAB] fileWriteInt : /sys/class/mdnie/mdnie/auto_brightness  value : 0
,D/DisplayPowerController( 3522): getFinalBrightness : 0 -> 0
,D/DisplayPowerController( 3522): animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/SensorManager( 3522): unregisterListener ::   
,D/NfcService( 3969): call the applyRouting
I/DisplayManagerService( 3522): Display device changed: DisplayDeviceInfo{"Built-in Screen": 1440 x 2560, 59.0 fps, supportedRefreshRates [59.0], density 640, 515.154 x 520.192 dpi, appVsyncOff 0, presDeadline 17949152, touch INTERNAL, rotation 0, type BUILT_IN, state OFF, FLAG_DEFAULT_DISPLAY, FLAG_ROTATES_WITH_CONTENT, FLAG_SECURE, FLAG_SUPPORTS_PROTECTED_BUFFERS}
D/DisplayPowerController( 3522): getFinalBrightness : 0 -> 0
D/SurfaceFlinger( 2852): Set power mode=0, type=0 flinger=0xb6962000
I/hwcomposer( 2852): int exynos5_blank(hwc_composer_device_1*, int, int):: disp(0), blank(1)
V/ActivityManager( 3522): Display changed displayId=0
,D/DisplayPowerController( 3522): animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/DisplayPowerController( 3522): getFinalBrightness : 0 -> 0
,D/DisplayPowerController( 3522): animation target = 0, rate=0 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
D/PowerManagerService( 3522): [s] DisplayPowerCallbacks : onStateChanged()
,D/PowerManagerService( 3522): [PWL] sb release: PowerManagerService.Display
,D/STATUSBAR-PhoneStatusBar( 3692):      ACTION_SCREEN_OFF is finished!!!! 
,E/StatusBar( 3692): onReceive : Intent.ACTION_SCREEN_OFF
,D/accuweather( 5195): [KK AccuPhone]>>> WCSS:80 [0:0] action : androidintentactionSCREEN_OFF
,D/accuweather( 5195): [KK AccuPhone]>>> UIM:118 [0:0] getInstance
,D/accuweather( 5195): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/SSRM:n  ( 3522): SIOP:: AP = 280, PST = 307, CUR = 50
,D/daemonapp( 3772): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 5
,D/accuweather( 5195): [KK AccuPhone]>>> U:4072 [0:0] getPWC : surface = 0, remote = 1
,D/accuweather( 5195): [KK AccuPhone]>>> U:4191 [0:0] Store PWC = 1
D/accuweather( 5195): [KK AccuPhone]>>> U:4124 [0:0] addPWC = 1
,D/accuweather( 5195): [KK AccuPhone]>>> UIM:311 [0:0]  action:widgetactionWEATHER_SCREEN_OFF
,I/SystemBroadcastReceiver(10232): [#DCM#] [DCM_Performance] onReceive completed in time  287 microsec. 
,I/SystemBroadcastReceiver(10232): [#DCM#] Calling notifyListeners. 
,I/DCMPolicyManager(10232): [#DCM#] onReceive action = EVENT_SCREEN_OFF
I/DCMController(10232): [#DCM#] onIntentReceived eventid = EVENT_SCREEN_OFF
,D/PowerManagerService( 3522): [PWL] sb release: PowerManagerService.Broadcasts
,D/daemonapp( 3772): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 3772): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 5195): [KK AccuPhone]>>> UIM:157 [0:0] make widget 4x1 view!!! 
,D/accuweather( 5195): [KK AccuPhone]>>> UIM:159 [0:0] make widget 4x2 view!!! 
,D/accuweather( 5195): [KK AccuPhone]>>> RU:73 [0:0] get ww = 339, wh = 160span x = 4, span y = 2
D/accuweather( 5195): [KK AccuPhone]>>> UIM:184 [0:0] get widget 4x2 view!!! wid = 2
,D/accuweather( 5195): [KK AccuPhone]>>> WCS:113 [0:0] onDestroy : End
,D/accuweather( 5195): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionWEATHER_SCREEN_OFF
,D/accuweather( 5195): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/SurfaceControl( 3522): Excessive delay in setPowerMode(): 217ms
D/PowerManagerService( 3522): !@[s] blankAllDisplays() : blankAllDisplaysFromPowerManage
D/MISC PowerHAL( 3522): sysfs_write +: /sys/class/power_supply/battery/lcd: 0
D/MISC PowerHAL( 3522): sysfs_write -: /sys/class/power_supply/battery/lcd: 0
,I/PowerManagerService( 3522): [PWL] Off : 0s ago
,D/PowerManagerService( 3522): Excessive delay in mPhotonicModulator.requestDisplayState(mRequestingState): 220ms
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3522): waitForAlarm result :4
,D/KeyguardViewMediator( 3692): received DELAYED_KEYGUARD_ACTION with seq = 2, mDelayedShowingSequence = 2
,D/KeyguardViewMediator( 3692): doKeyguard: not showing because lockscreen is off
,I/PowerManagerService( 3522): [PWL] Off : 5s ago
,E/Watchdog( 3522): !@Sync 4
,V/AlarmManager( 3522): waitForAlarm result :4
,V/AlarmManager( 3522): waitForAlarm result :8
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:58, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:95
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 280, PST = 300, CUR = 58
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3522): [PWL] Off : 15s ago
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:60, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:64
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 270, PST = 292, CUR = 60
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:59, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:53
V/AlarmManager( 3522): waitForAlarm result :4
,D/BatteryService( 3522): stay LED for fully charged
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/SSRM:n  ( 3522): SIOP:: AP = 270, PST = 288, CUR = 59
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3522): [PWL] Off : 30s ago
,E/Watchdog( 3522): !@Sync 5
,D/SSRM:n  ( 3522): SIOP:: AP = 270, PST = 282, CUR = 59
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:57, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:51
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3522): waitForAlarm result :4
,V/AlarmManager( 3522): waitForAlarm result :4
,V/AlarmManager( 3522): waitForAlarm result :8
,D/SSRM:n  ( 3522): SIOP:: AP = 270, PST = 278, CUR = 57
,I/PowerManagerService( 3522): [PWL] Off : 50s ago
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:52, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:53
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 270, PST = 276, CUR = 52
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:49, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3522): !@Sync 6
,D/SSRM:n  ( 3522): SIOP:: AP = 270, PST = 275, CUR = 49
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:45, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:47
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3522): [PWL] Off : 75s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 260, PST = 273, CUR = 45
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:43, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:63
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3522): waitForAlarm result :4
,I/ClearcutLoggerApiImpl( 4650): disconnect managed GoogleApiClient
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3692): handleTimeUpdate
,D/KeyguardEffectViewController( 3692): onReceive action : android.intent.action.TIME_TICK
I/KeyguardEffectViewController( 3692): *** don't update sliding image ***
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 3522): SIOP:: AP = 260, PST = 271, CUR = 43
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:42, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:42
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 7
,D/SSRM:n  ( 3522): SIOP:: AP = 260, PST = 270, CUR = 42
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33,
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3522): [PWL] Off : 105s ago
,V/AlarmManager( 3522): waitForAlarm result :8
,D/SSRM:n  ( 3522): SIOP:: AP = 260, PST = 268, CUR = 40
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:40, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 260, PST = 266, CUR = 40
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:28
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3522): !@Sync 8
,D/SSRM:n  ( 3522): SIOP:: AP = 260, PST = 265, CUR = 37
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:37, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,I/PowerManagerService( 3522): [PWL] Off : 140s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 260, PST = 265, CUR = 37
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:38, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:39,
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged,
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3522): SIOP:: AP = 260, PST = 264, CUR = 38
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:36, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 9
,D/SSRM:n  ( 3522): SIOP:: AP = 260, PST = 263, CUR = 36
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:49
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3522): SIOP:: AP = 260, PST = 263, CUR = 35
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:34, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:38
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3522): [PWL] Off : 180s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 260, PST = 262, CUR = 34
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:35, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/TimaService( 3522): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3522): TimaServiceHandler.handleMessage what =1
,D/TimaService( 3522): TIMA: checkEvent, operation: 50000 subject: 10000
,I/TLC_TIMA_PKM_initialize( 3522): initializing...
,I/TLC_TIMA_PKM_initialize( 3522): root = 0, root_strlen = 1
I/TLC_TIMA_PKM_initialize( 3522): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 3522): input max_sendmsg_size = 262196
I/TZ: mc_tlc_communication( 3522): input max_recvmsg_size = 262196
,I/TZ: mc_tlc_communication( 3522): root = 0, root_len = 1
I/TZ: mc_tlc_communication( 3522): process = ffffffff00000000000000000000000a, process_strlen = 32
I/TZ: mc_tlc_communication( 3522): aligned max_sendmsg_size = 262208
I/TZ: mc_tlc_communication( 3522): aligned max_recvmsg_size = 262208
I/TZ: mc_tlc_communication( 3522): device_id = 0x0
,I/TZ: mc_tlc_communication( 3522): tlc_open() was called
I/TZ: mc_tlc_communication( 3522): Opening MobiCore device
,I/TZ: mc_tlc_communication( 3522): Allocating WSM for TCI
,I/TZ: mc_tlc_communication( 3522): Opening the session
,I/TZ: mc_tlc_communication( 3522): tlc_open() succeeded
,I/TLC_TIMA_PKM_initialize( 3522): Trustlet response is completed
,E/Watchdog( 3522): !@Sync 10
,D/SSRM:n  ( 3522): SIOP:: AP = 260, PST = 262, CUR = 35
,I/TLC_TIMA_PKM_measure_kernel( 3522): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3522): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3522): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3522): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:33, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:32
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 260, PST = 261, CUR = 33,
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:38
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/ActivityManager( 3522): Killing 10011:com.samsung.helphub/1000 (adj 15): bgCount ##31
,D/SSRM:n  ( 3522): SIOP:: AP = 260, PST = 260, CUR = 32
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:31, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 11
,D/SSRM:n  ( 3522): SIOP:: AP = 260, PST = 260, CUR = 31
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3522): [PWL] Off : 225s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 260, PST = 260, CUR = 31
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:32, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:52
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 260, PST = 260, CUR = 32
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:30, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25,
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3522): !@Sync 12
,D/SSRM:n  ( 3522): SIOP:: AP = 260, PST = 260, CUR = 30
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11,
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 260, PST = 260, CUR = 29
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/SSRM:n  ( 3522): SIOP:: AP = 260, PST = 260, CUR = 28
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:29, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3522): [PWL] Off : 275s ago
,E/Watchdog( 3522): !@Sync 13
,D/SSRM:n  ( 3522): SIOP:: AP = 260, PST = 260, CUR = 29,
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,V/AlarmManager( 3522): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3692): handleTimeUpdate
,D/KeyguardEffectViewController( 3692): onReceive action : android.intent.action.TIME_TICK
,I/KeyguardEffectViewController( 3692): *** don't update sliding image ***
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/SSRM:n  ( 3522): SIOP:: AP = 260, PST = 260, CUR = 26
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ProcessCpuTracker( 3522): Skipping unknown process pid 11096
,D/SSRM:n  ( 3522): SIOP:: AP = 260, PST = 260, CUR = 25
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:51,
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Watchdog( 3522): !@Sync 14
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 259, CUR = 28
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:33,
D/BatteryService( 3522): stay LED for fully charged,
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 258, CUR = 28,
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:27, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate,
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/PowerManagerService( 3522): [PWL] Off : 330s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 258, CUR = 27
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24,
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 15
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 257, CUR = 26,
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3522): waitForAlarm result :8
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 257, CUR = 25
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 274, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:28, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:52
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 256, CUR = 28
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:26, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 16
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 256, CUR = 26
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:25, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:44
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 256, CUR = 25
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED,
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3522): [PWL] Off : 390s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 255, CUR = 23
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 17
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 255, CUR = 22
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-7,
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 255, CUR = 21
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 254, CUR = 23,
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 18
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 254, CUR = 23
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16,
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 254, CUR = 23
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:30,
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 253, CUR = 21,
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,I/PowerManagerService( 3522): [PWL] Off : 455s ago
,E/Watchdog( 3522): !@Sync 19
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 253, CUR = 21,
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:23, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13,
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 253, CUR = 23
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:22, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:34
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 252, CUR = 22
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/TimaService( 3522): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3522): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 3522): TimaServiceHandler.handleMessage what =1
,E/Watchdog( 3522): !@Sync 20
,I/TLC_TIMA_PKM_measure_kernel( 3522): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3522): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3522): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/TimaService( 3522): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;,
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 252, CUR = 22
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:21, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 252, CUR = 21
,W/ContextImpl( 3522): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1699 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!,
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 251, CUR = 19
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 21
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 251, CUR = 19
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9,
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3522): [PWL] Off : 525s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 251, CUR = 18
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:20
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 18
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 22
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 18
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4400, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:27
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 18
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 18
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0,
D/BatteryService( 3522): online:4, current avg:19, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:15
D/BatteryService( 3522): stay LED for fully charged
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 23
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 19
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:2
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 18
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-5,
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3522): [PWL] Off : 600s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 17
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 24
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 18
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-5
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 17
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:18, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 18
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 25
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 17
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 16
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 272, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23,
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 17
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7,
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 26
,V/AlarmManager( 3522): waitForAlarm result :8
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.TIME_TICK
,D/KeyguardUpdateMonitor( 3692): handleTimeUpdate
,D/LightsService( 3522): [api] onReceive : SvcLEDReceiver re-enables LightSenor and sends MSG_FORCEDSVCLEDTASK
,D/KeyguardEffectViewController( 3692): onReceive action : android.intent.action.TIME_TICK,
I/KeyguardEffectViewController( 3692): *** don't update sliding image ***
,I/Sensors ( 3522): Light old sensor_state 0, new sensor_state : 512 en : 1
,D/SensorManager( 3522): registerListener :: 6, TMG399X RGB Sensor, 200000, 0,  
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,D/DateView( 3692): regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,I/Sensors ( 3522): #>LightSensor r=0 g=0 b=0 c=1 atime=238 again=64 lux=0.000000
,D/LightsService( 3522): [SvcLED]  onSensorChanged::light value = 0
I/Sensors ( 3522): Light old sensor_state 512, new sensor_state : 0 en : 0
,D/SensorManager( 3522): unregisterListener ::   
D/LightsService( 3522): [SvcLED]  setSvcLedLightLocked :: Current SvcLED(id=3) maintains its priority right
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 17
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3522): [PWL] Off : 680s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 17
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 17
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:17, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 27
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 17
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:16
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,V/AlarmManager( 3522): waitForAlarm result :8
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 15
,I/art     ( 3522): Background sticky concurrent mark sweep GC freed 88962(7MB) AllocSpace objects, 224(5MB) LOS objects, 13% free, 51MB/59MB, paused 3.252ms total 118.401ms
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:14
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 14
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 28
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 14
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 14
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 14
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 29
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 13
,I/PowerManagerService( 3522): [PWL] Off : 765s ago
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:10
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 12,
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 15
,D/TimaService( 3522): TIMA: TimaService scheduler is intialized. 
D/TimaService( 3522): TIMA: checkEvent, operation: 50000 subject: 10000
D/TimaService( 3522): TimaServiceHandler.handleMessage what =1
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 30
,I/TLC_TIMA_PKM_measure_kernel( 3522): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3522): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3522): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3522): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 16,
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 15
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 271, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 13
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:22
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 31
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 12
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 16
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:16, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 16
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,E/Watchdog( 3522): !@Sync 32
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 16
,I/PowerManagerService( 3522): [PWL] Off : 855s ago
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 14
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 13
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,E/Watchdog( 3522): !@Sync 33
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 13
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:7
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 13
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:36
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 13
,E/Watchdog( 3522): !@Sync 34
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:46
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 14
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 14
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-8,
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 14
,E/Watchdog( 3522): !@Sync 35
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:15, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 15,
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:6
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3522): [PWL] Off : 950s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 13
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 13
,E/Watchdog( 3522): !@Sync 36
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:14, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 14
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-3
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 13
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-1
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 13
,E/Watchdog( 3522): !@Sync 37
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:24
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 12
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:13
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 10
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 270, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:25
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 11
,E/Watchdog( 3522): !@Sync 38
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:1
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 12,
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 10
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4399, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:13, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/PowerManagerService( 3522): [PWL] Off : 1050s ago
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 13
,E/Watchdog( 3522): !@Sync 39
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:12, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-5,
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 12
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 12
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:40
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 11
,D/TimaService( 3522): TIMA: TimaService scheduler is intialized. 
,D/TimaService( 3522): TIMA: checkEvent, operation: 50000 subject: 10000
,D/TimaService( 3522): TimaServiceHandler.handleMessage what =1
,I/UsageStatsService( 3522): User[0] Flushing usage stats to disk
,I/ApplicationUsage( 3522): handleMessage : MSG_UPDATE_USAGE_DB
I/ApplicationUsage( 3522): Updating Usage Statistics in DB @ 1457973378533
,I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:271)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145),
,W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
,W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3522): ,	,at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateForeGroundUsageDetails(ApplicationUsageDb.java:82)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateForeGroundUsageData(ApplicationUsage.java:275)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:252)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): ,	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB,
,W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): ,	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	,at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): ,	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): ,	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): ,	,at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): ,	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253),
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	,at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): ,	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
,W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): ,	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): ,	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3522): ,	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
,W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
,W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
,W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
,W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
,W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
,W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
,W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
,W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
,W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.a,ndroid.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:304)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsageDb( 3522): ::getAppControlDB: Exception to create DB
W/System.err( 3522): java.lang.NullPointerException: Attempt to invoke virtual method 'android.database.sqlite.SQLiteDatabase android.content.Context.openOrCreateDatabase(java.lang.String, int, android.database.sqlite.SQLiteDatabase$CursorFactory)' on a null object reference
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.getAppControlDB(ApplicationUsageDb.java:350)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsageDb.updateBackGroundUsageDetails(ApplicationUsageDb.java:134)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage.updateBackGroundUsageDetails(ApplicationUsage.java:299)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage._insertToAppControlDB(ApplicationUsage.java:253)
W/System.err( 3522): 	at com.android.server.enterprise.application.ApplicationUsage$UsageHandler.handleMessage(ApplicationUsage.java:128)
W/System.err( 3522): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 3522): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 3522): 	at android.os.HandlerThread.run(HandlerThread.java:61)
I/ApplicationUsage( 3522): Done Updating Usage Statistics in DB @ 1457973378693
,E/Watchdog( 3522): !@Sync 40,
,I/TLC_TIMA_PKM_measure_kernel( 3522): TIMA: response_id = 3
I/TLC_TIMA_PKM_measure_kernel( 3522): TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
,D/TimaService( 3522): TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/TimaService( 3522): TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:12
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 10
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 10
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:11
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 9
,E/Watchdog( 3522): !@Sync 41
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:21
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 11
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 11,
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:0
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 10
,E/Watchdog( 3522): !@Sync 42
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-10
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 11
,I/PowerManagerService( 3522): [PWL] Off : 1155s ago
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 11
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 11
,E/Watchdog( 3522): !@Sync 43
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:19
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 9
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
D/BatteryService( 3522): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:26
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 10
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 8
,E/Watchdog( 3522): !@Sync 44
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-2
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 11
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:31
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 10
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:8
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 11
,E/Watchdog( 3522): !@Sync 45
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:11, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 11
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:18
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 10
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:10, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:23,
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 10,
,I/PowerManagerService( 3522): [PWL] Off : 1265s ago
,E/Watchdog( 3522): !@Sync 46
,I/MMD     ( 2873): [timer_stat, 906] MMD 5.4 (to/from modem) tot:8/0 ACC_DMX:0/0 APP_DMX:0/0 ACC_TV:0/0 APP_TV:0/0 ACC_3P_EOP:0/0 APP_3P_EOP:0/0 ACC_EOP_2:0/0 APP_EOP_2:0/0 AT_RMM:0/0 ACC_FLUSH:0/0 APP_FLUSH:0/0 AUDIO_PROBE:0/0 
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4398, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:9
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,D/BatteryService( 3522): stay LED for fully charged
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 9
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 9
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4395, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:17
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 9
,E/Watchdog( 3522): !@Sync 47
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:-14
D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 9
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4397, temperature: 269, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:8, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:5
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/BatteryService( 3522): stay LED for fully charged
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 8,
,D/BatteryService( 3522): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 3522): level:100, scale:100, status:5, health:2, present:true, voltage: 4396, temperature: 268, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303722, invalid charger:0
,D/BatteryService( 3522): online:4, current avg:9, charge type:1, power sharing:false, high voltage charger:false, capacity:322000, current_now:35,
,D/BatteryService( 3522): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 3522): Plugged
,I/MotionRecognitionService( 3522): setPowerConnected  = true
,D/KeyguardUpdateMonitor( 3692): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 3692): handleBatteryUpdate
,D/BatteryService( 3522): stay LED for fully charged
,D/STATUSBAR-PhoneStatusBar( 3692):  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,V/HeadsetService( 5578): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,D/HeadsetStateMachine( 5578): Disconnected process message: 10
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 3692): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/SSRM:n  ( 3522): SIOP:: AP = 250, PST = 250, CUR = 9
,TIME-OUT KILL (timeout was 1400000ms),D/AndroidRuntime(11616): 
D/AndroidRuntime(11616): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime(11616): CheckJNI is OFF
D/AndroidRuntime(11616): readGMSProperty: start
D/AndroidRuntime(11616): readGMSProperty: already setted!!
D/AndroidRuntime(11616): readGMSProperty: end
D/AndroidRuntime(11616): addProductProperty: start
E/AffinityControl(11616): AffinityControl: registerfunction enter
D/AndroidRuntime(11616): Calling main entry com.android.commands.pm.Pm
D/PersonaManagerService( 3522): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PackageManager( 3522): START PACKAGE DELETE: observer{229489063}
D/PackageManager( 3522): pkg{<packageName>}
D/PackageManager( 3522): user{0}
D/PackageManager( 3522): caller{2000}
D/PackageManager( 3522): flags{2}
D/PersonaManagerService( 3522): isFromApprovedUnInstaller: isApproved : true
D/PackageManager( 3522): [MSG] DELETE_PACKAGE_AS_USER
D/PersonaManagerService( 3522): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 3522): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
D/PackageManager( 3522): deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
D/PackageManagerService( 3522): deletePackage- pkg:com.test.thalitest, edmuserId:0
D/PackageManagerService( 3522): deletePackage- pkg:com.test.thalitest, edmuserId:-1
D/ApplicationPolicy( 3522): getApplicationUninstallationEnabled
D/PackageManager( 3522): !@killApplicatoin: 10208, uninstall pkg
D/ApplicationPolicy( 3522): getApplicationUninstallationEnabled :  enabled true
I/ActivityManager( 3522): Force stopping com.test.thalitest appid=10208 user=-1: uninstall pkg
W/PackageSettings( 3522): Skipping PackageSetting{23997eba com.example.hello/10691} due to missing metadata
I/ActivityManager( 3522): Force stopping com.test.thalitest appid=10208 user=0: pkg removed
I/art     ( 3522): Background partial concurrent mark sweep GC freed 62911(6MB) AllocSpace objects, 190(2MB) LOS objects, 23% free, 51MB/67MB, paused 2.018ms total 151.401ms
D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/Samsungservice2_xxxhdpi/Samsungservice2_xxxhdpi.apk
W/GeofencerStateMachine( 4650): Ignoring removeGeofence because network location is disabled.
I/InputReader( 3522): Reconfiguring input devices.  changes=0x00000010
I/art     ( 9703): Explicit concurrent mark sweep GC freed 28618(1582KB) AllocSpace objects, 6(96KB) LOS objects, 37% free, 26MB/42MB, paused 1.136ms total 43.671ms
I/art     ( 4039): Explicit concurrent mark sweep GC freed 36978(2MB) AllocSpace objects, 2(689KB) LOS objects, 35% free, 28MB/44MB, paused 3.129ms total 74.098ms
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
D/LWLocationManager(10345): getDeviceLocationId :  id = -100
D/LocationWidgetApplication(10345): getLastUiLocationId() : mLastUiLocationId = -100
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
E/SamsungIME( 4484): mOCRHelper is null
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
E/Zygote  (11634): MountEmulatedStorage()
E/Zygote  (11634): v2
I/libpersona(11634): KNOX_SDCARD checking this for 10063
I/libpersona(11634): KNOX_SDCARD not a persona
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
I/SELinux (11634): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
W/ResourceType( 5313): For resource 0x7f02055f, entry index(1375) is beyond type entryCount(725)
W/ResourceType( 5313): Failure getting entry for 0x7f02055f (t=1 e=1375) (error -75)
I/ActivityManager( 3522): Start proc com.samsung.android.app.vrsetupwizardstub for broadcast com.samsung.android.app.vrsetupwizardstub/.system.PackageIntentReceiver: pid=11634 uid=10063 gids={50063, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (11634): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
E/SELinux (11634): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/art     ( 6708): Explicit concurrent mark sweep GC freed 768(28KB) AllocSpace objects, 0(0B) LOS objects, 20% free, 30MB/38MB, paused 900us total 117.397ms
V/NetworkStats( 3522): removeUidsLocked() for UIDs [10208]
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
V/NetworkStats( 3522): performPollLocked(flags=0x3)
D/NetworkStatsFactory( 3522): UpdateStatsForKnox
V/NetworkStats( 3522): performPollLocked() took 26ms
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
D/TimaKeyStoreProvider(11634): TimaSignature is unavailable
D/ActivityThread(11634): Added TimaKeyStore provider
D/ResourcesManager(10345): creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
D/ResourcesManager(11634): creating new AssetManager and set to /system/priv-app/VRSetupWizardStub/VRSetupWizardStub.apk
D/SecContentProvider2( 3522): uri = 11 selection = getMyKnoxAdmin
D/SecContentProvider2( 3522): mCursor = null
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
D/ResourcesManager(10345): creating new AssetManager and set to /system/priv-app/SecContacts_Note/SecContacts_Note.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/VRSetupWizardStub/PackageIntentReceiver(11634): onReceive()
D/VRSetupWizardStub/PackageIntentReceiver(11634): Action Package Remove
D/VRSetupWizardStub/PackageIntentReceiver(11634): packagename:com.test.thalitest
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/sCloudSyncMemo/sCloudSyncMemo.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Books/Books.apk
E/Zygote  (11651): MountEmulatedStorage()
I/libpersona(11651): KNOX_SDCARD checking this for 10021
E/Zygote  (11651): v2
I/libpersona(11651): KNOX_SDCARD not a persona
I/SELinux (11651): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
I/SELinux (11651): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/ResourcesManager(10345): creating new AssetManager and set to /system/priv-app/SecGallery2014L/SecGallery2014L.apk
E/SELinux (11651): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=11651 uid=10021 gids={50021, 9997, 3003} abi=armeabi-v7a
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Drive/Drive.apk
I/ActivityManager( 3522): Killing 10050:com.sec.android.app.samsungapps/u0a13 (adj 15): bgCount ##31
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
D/ResourcesManager(10345): creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
D/NtpTrustedTime( 3522): currentTimeMillis() cache hit
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
D/ResourcesManager(10345): creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/TimaKeyStoreProvider(11651): TimaSignature is unavailable
D/ActivityThread(11651): Added TimaKeyStore provider
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/Videos/Videos.apk
I/art     ( 3522): Explicit concurrent mark sweep GC freed 14574(1281KB) AllocSpace objects, 2(32KB) LOS objects, 23% free, 51MB/67MB, paused 2.809ms total 154.433ms
D/ResourcesManager(10345): creating new AssetManager and set to /system/app/Chrome/Chrome.apk
D/ResourcesManager(10345): creating new AssetManager and set to /system/app/Evernote/Evernote.apk
D/RegisteredServicesCache( 3969): empty dynamic service
D/ResourcesManager(11651): creating new AssetManager and set to /system/priv-app/KLMSAgent/KLMSAgent.apk
D/ResourcesManager(10345): creating new AssetManager and set to /system/app/Flipboard/Flipboard.apk
D/ResourcesManager(10345): creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
D/ResourcesManager(10345): creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
W/ResourcesManager(10345): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/KLMS-2.4.521: (11651): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Mon Mar 14 17:40:16 GMT+01:00 2016
D/ResourcesManager(10345): creating new AssetManager and set to /system/app/Music2/Music2.apk
D/ResourcesManager( 3522): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
I/KLMS-2.4.521: (11651): KLMSAbstractReciever(): onReceive().END.
I/splitIntent( 3522): Split this intent : android.intent.action.PACKAGE_REMOVED !!   mSplitNum[0]=13, mSplitNum[1]=23, mSplitNum[2]=33 divideNum= 10 r.nextReceiver= 2 receivers.size=43
I/splitIntent( 3522): finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
I/KLMS-2.4.521: (11651): KLMSIntentService(): onCreate()
I/KLMS-2.4.521: (11651): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/RCPManagerService( 3522): PackageReceiver onReceive()
I/HarmonyEASService( 3522): onReceive : android.intent.action.PACKAGE_REMOVED for 0
I/KLMS-2.4.521: (11651): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
D/KnoxMUMContainerPolicy( 3522): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
I/KLMS-2.4.521: (11651): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
D/ResourcesManager(10345): creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
I/KLMS-2.4.521: (11651): KLMSIntentService(): PACKAGE_REMOVED
I/KLMS-2.4.521: (11651): KLMSIntentService(): listeningToPackageRemoved().START
D/BackupManagerService( 3522): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
D/JobSchedulerService( 3522): Receieved: android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3522): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 3522): uID is 10208
V/EnterpriseBillingPolicy( 3522): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 3522): getProfileForApplication - enter
V/EnterpriseBillingPolicyStorage( 3522): getProfileForApplication - exit null
V/EnterpriseBillingPolicy( 3522): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 3522): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 3522): getBillingProfileForVpnEngine - start - com.test.thalitest
V/EnterpriseBillingPolicyStorage( 3522): getBillingProfileForVpnEngine - end - null
I/KLMS-2.4.521: (11651): KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
D/ResourcesManager(10345): creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
D/PackageManager( 3522): delete codoeFile: 
D/ResourcesManager(10345): creating new AssetManager and set to /system/app/SPlanner_OS_UPG/SPlanner_OS_UPG.apk
W/ResourcesManager(10345): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager(10345): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager(10345): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager(10345): Asset path '/system/framework/SmpsManager.jar' does not exist or contains no resources.
I/AASAUninstall( 3522):  com.test.thalitest not target!
D/PackageManager( 3522): result of delete: 1{229489063}
D/AndroidRuntime(11616): Shutting down VM
D/PackageManager( 3522): [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
D/PackageManager( 3522): userId{-1}
D/PackageManager( 3522): andCode{true}
D/ResourcesManager(10345): creating new AssetManager and set to /system/app/SamsungCamera3/SamsungCamera3.apk
E/Zygote  (11669): MountEmulatedStorage()
E/Zygote  (11669): v2
I/libpersona(11669): KNOX_SDCARD checking this for 1000
I/libpersona(11669): KNOX_SDCARD not a persona
D/ResourcesManager(10345): creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
I/SELinux (11669): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/SELinux (11669): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11669): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(10345): creating new AssetManager and set to /system/app/Videos/Videos.apk
I/ActivityManager( 3522): Start proc com.sec.knox.bridge for broadcast com.sec.knox.bridge/.PersonaShortcutReceiver: pid=11669 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
I/KLMS-2.4.521: (11651): KLMSIntentService(): Notification App List is Null. Remove Notification.
D/ResourcesManager(10345): creating new AssetManager and set to /system/app/YouTube/YouTube.apk
I/KLMS-2.4.521: (11651): KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
E/Zygote  (11681): MountEmulatedStorage()
E/Zygote  (11681): v2
I/libpersona(11681): KNOX_SDCARD checking this for 10106
I/libpersona(11681): KNOX_SDCARD not a persona
I/SELinux (11681): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/KLMS-2.4.521: (11651): KLMSIntentService(): listeningToPackageRemoved().END
I/SELinux (11681): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11681): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=11681 uid=10106 gids={50106, 9997, 3003} abi=armeabi-v7a
D/ResourcesManager(10345): creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
D/TimaKeyStoreProvider(11669): TimaSignature is unavailable
D/ActivityThread(11669): Added TimaKeyStore provider
D/ResourcesManager(10345): creating new AssetManager and set to /data/app/com.android.vending-1/base.apk
D/TimaKeyStoreProvider(11681): TimaSignature is unavailable
D/ActivityThread(11681): Added TimaKeyStore provider
D/ResourcesManager(10345): creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
I/KLMS-2.4.521: (11651): KLMSIntentService(): onDestroy()
D/ResourcesManager(10345): creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
D/ResourcesManager(11669): creating new AssetManager and set to /system/app/Bridge/Bridge.apk
W/ResourcesManager(11669): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
D/ResourcesManager(10345): creating new AssetManager and set to /system/priv-app/Scrapbook/Scrapbook.apk
D/ResourcesManager(11681): creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
D/ResourcesManager(10345): creating new AssetManager and set to /system/priv-app/SecMyFiles2014/SecMyFiles2014.apk
D/RCPManager(11669):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3522):  in createShortcut() for packageName: com.test.thalitest userId0
D/RCPManagerService( 3522): queryAllProviders():  providerCallBack is not register for 0
D/Mms/FreeMessageStatusReceiver(10782): onReceive, action : android.intent.action.PACKAGE_REMOVED
D/ResourcesManager(10345): creating new AssetManager and set to /system/priv-app/SecVideo/SecVideo.apk
I/TapandpayWidget:TanpandpayAppWidgetProvider(10142): onReceive()
D/TapandpayWidget:TanpandpayAppWidgetProvider(10142): onReceive() - action : android.intent.action.PACKAGE_REMOVED / mCurIndex :-10
I/TapandpayWidget:Utils(10142): Clear T&P info.
D/elm:14491(11681): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:14491(11681): ELMEngine.ELMEngine( context ).
D/elm:14491(11681): MDMBridge.setEnterpriseBridge()
D/TapandpayWidget:TanpandpayAppWidgetProvider(10142): Widget is not attached.
D/elm:14491(11681): ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
D/Mms/FreeMessageReceiverService(10782): onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
D/Mms/FreeMessageReceiverService(10782): onHandleIntent: ACTION_PACKAGE_REMOVED
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/elm:14491(11681): ElmAgentService : onCreate()
D/elm:14491(11681): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:14491(11681): MainReceiver.listeningToPackageRemoved()
D/elm:14491(11681): MDMBridge.getInstance()
D/elm:14491(11681): MDMBridge.getAllLicenseInfoFromSDK()
D/elm:14491(11681): MDMBridge.getAllLicenseInfoFromSDK()
D/ResourcesManager(10345): creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
E/Zygote  (11706): MountEmulatedStorage()
E/Zygote  (11706): v2
I/libpersona(11706): KNOX_SDCARD checking this for 10101
I/libpersona(11706): KNOX_SDCARD not a persona
I/SELinux (11706): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3522): Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=11706 uid=10101 gids={50101, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux (11706): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11706): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
D/elm:14491(11681): ElmAgentService : onDestroy().
D/ResourcesManager(10345): creating new AssetManager and set to /system/priv-app/VoiceNote4T/VoiceNote4T.apk
D/ResourcesManager(10345): creating new AssetManager and set to /system/app/Books/Books.apk
D/ResourcesManager(10345): creating new AssetManager and set to /system/app/ClockPackage_Osup_T/ClockPackage_Osup_T.apk
I/TactileAssist( 3522): enable value -1
I/TactileAssist( 3522): internal enable value -1
I/TactileAssist( 3522): intensity value -1
I/TactileAssist( 3522): saveAppList value true
D/TimaKeyStoreProvider(11706): TimaSignature is unavailable
D/ActivityThread(11706): Added TimaKeyStore provider
I/TactileAssist( 3522): List of disabled apps :
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(10345): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/PkgBroadcastIntentOp( 6708): Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
D/AccountUtils( 6708): Clearing selected account for com.test.thalitest
D/ResourcesManager(10345): creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
E/Zygote  (11724): MountEmulatedStorage()
E/Zygote  (11724): v2
I/libpersona(11724): KNOX_SDCARD checking this for 10019
I/libpersona(11724): KNOX_SDCARD not a persona
I/SELinux (11724): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3522): Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=11724 uid=10019 gids={50019, 9997} abi=armeabi-v7a
I/SELinux (11724): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
D/ResourcesManager(10345): creating new AssetManager and set to /system/app/FBInstagram_stub/FBInstagram_stub.apk
E/SELinux (11724): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ResourcesManager(10345): creating new AssetManager and set to /system/app/FBMessenger_stub/FBMessenger_stub.apk
I/LocationSettingsChecker( 6708): Removing dialog suppression flag for package com.test.thalitest
D/ResourcesManager(10345): creating new AssetManager and set to /system/app/FBPagesManager_stub/FBPagesManager_stub.apk
D/ResourcesManager(10345): creating new AssetManager and set to /system/app/Maps/Maps.apk
D/TimaKeyStoreProvider(11724): TimaSignature is unavailable
D/ActivityThread(11724): Added TimaKeyStore provider
D/ResourcesManager(11706): creating new AssetManager and set to /system/app/Drive/Drive.apk
D/ResourcesManager(10345): creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
D/ResourcesManager(11724): creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(10345): creating new AssetManager and set to /system/app/PENUP/PENUP.apk
E/Zygote  (11743): MountEmulatedStorage()
I/libpersona(11743): KNOX_SDCARD checking this for 10059
E/Zygote  (11743): v2
I/libpersona(11743): KNOX_SDCARD not a persona
I/SELinux (11743): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/ActivityManager( 3522): Start proc com.sec.android.app.soundalive for broadcast com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver: pid=11743 uid=10059 gids={50059, 9997, 3003, 3002} abi=armeabi-v7a
I/ActivityManager( 3522): Killing 9466:com.google.android.apps.plus/u0a147 (adj 15): bgCount ##31
I/SELinux (11743): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
E/SELinux (11743): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/com.sec.android.service.health.upgrade.UninstallReceiver(11724): onReceive()
I/com.sec.android.service.health.upgrade.UninstallReceiver(11724): onReceive called  PACKAGE_REMOVED package:com.test.thalitest
D/com.sec.android.service.health.upgrade.UninstallReceiver(11724): onReceive() : package name is not s health. Return !!!
D/DocsApplication(11706): Installing DEX configuration.
D/ResourcesManager( 6708): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
D/ResourcesManager(10345): creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
D/UsbHostManager( 3522): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/2/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.0
D/UsbHostManager( 3522): displayNotification : [02h,02h,01h]
D/UsbHostManager( 3522): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.1
D/UsbHostManager( 3522): displayNotification : [0ah,00h,00h]
D/UsbHostManager( 3522): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 2/13/0, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.2
D/UsbHostManager( 3522): displayNotification : [02h,0dh,00h]
D/UsbHostManager( 3522): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 4cc/2342/0, type = 2/0/0, interface = 10/0/1, devpath = /devices/15510000.usb/usb1/1-2/1-2:1.3
D/UsbHostManager( 3522): displayNotification : [0ah,00h,01h]
D/UsbHostManager( 3522): onUEvent(device) :: action = remove, devtype = usb_interface, device = null, product = 1d6b/2/310, type = 9/0/0, interface = 9/0/0, devpath = /devices/15510000.usb/usb1/1-0:1.0
D/UsbHostManager( 3522): displayNotification : [09h,00h,00h]
D/LocationWidgetApplication(10345): getLastUiLocationId() : mLastUiLocationId = -100
D/DexInstaller(11706): Dex configuration file eager_dex_configuration.xml not found. Skipping dex installation.
D/ResourcesManager(10345): creating new AssetManager and set to /system/app/SecCalculator2/SecCalculator2.apk
D/UsbHostManager( 3522): usbDeviceRemoved : /dev/bus/usb/001/003
E/UsbHostManager( 3522): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/003
I/PackageInfoHelper(11706): Provided clientMode=RELEASE, packageInfo=PackageInfo{1010f3fe com.google.android.apps.docs}
D/UsbSettingsManager( 3522): usbDeviceRemoved, sending Intent { act=android.hardware.usb.action.USB_DEVICE_DETACHED (has extras) }
D/TAG     (11706): onCreate()
D/CrossAppStateProvider(11706): Initialized StateProvider with authority: com.google.android.apps.docs.statesyncer
D/ResourcesManager(10345): creating new AssetManager and set to /system/app/SmartRemote_T/SmartRemote_T.apk
D/TimaKeyStoreProvider(11743): TimaSignature is unavailable
D/ActivityThread(11743): Added TimaKeyStore provider
D/MtpClient(10316): onReceive, deviceName : /dev/bus/usb/001/003 Action : android.hardware.usb.action.USB_DEVICE_DETACHED
D/MtpClient(10316): ACTION_USB_DEVICE_DETACHED : /dev/bus/usb/001/003
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 3522): checkUser: useridlist=null, currentuser=0
D/ResourcesManager(10345): creating new AssetManager and set to /system/app/WhatsApp/WhatsApp.apk
D/UsbHostManager( 3522): usbDeviceRemoved : /dev/bus/usb/001/001
E/UsbHostManager( 3522): usbDeviceRemoved :: deviceName = /dev/bus/usb/001/001
E/SQLiteLog( 4650): (10) POSIX Error : 9 SQLite Error : 3850
E/SQLiteLog( 4650): (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
D/AndroidRuntime( 4650): Shutting down VM
D/ResourcesManager(10345): creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
E/Zygote  (11767): MountEmulatedStorage()
E/Zygote  (11767): v2
I/libpersona(11767): KNOX_SDCARD checking this for 1000
I/libpersona(11767): KNOX_SDCARD not a persona
I/SELinux (11767): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N910C_5.0.1 ver=27
I/EventHub( 3522): Removing device '/dev/input/event10' due to inotify event
I/SELinux (11767): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-N910C_5.0.1_0027
I/ActivityManager( 3522): Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=11767 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SELinux (11767): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 3522): Killing 10105:com.samsung.android.snote:provider/u0a160 (adj 15): bgCount ##31
I/EventHub( 3522): Removing device '/dev/input/event7' due to inotify event
I/art     ( 2879): Explicit concurrent mark sweep GC freed 8712(370KB) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 682us total 44.446ms
I/GMPM-SVC( 6708): App measurement is starting up, version: 8703
I/GMPM-SVC( 6708): To enable debug logging run: adb shell setprop log.tag.GMPM VERBOSE
I/art     ( 2879): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 913us total 25.359ms
E/SQLiteLog( 6708): (10) POSIX Error : 9 SQLite Error : 3850
I/EventHub( 3522): Removing device '/dev/input/event8' due to inotify event
E/SQLiteLog( 6708): (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
D/TimaKeyStoreProvider(11767): TimaSignature is unavailable
D/ActivityThread(11767): Added TimaKeyStore provider
I/art     ( 2879): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 37% free, 26MB/42MB, paused 939us total 25.871ms
D/ResourcesManager(10345): creating new AssetManager and set to /data/app/com.facebook.katana-2/base.apk
I/EventHub( 3522): Removing device '/dev/input/event9' due to inotify event
E/SQLiteLog( 6708): (28) failed to open "/data/data/com.google.android.gms/databases/DocList.db" with flag (131138) and mode_t (0) due to error (30)

```
