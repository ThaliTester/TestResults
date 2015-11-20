#### Test 50388019aa1a16d_thali08_samsung-SM-A300FU Logs


```
--------- beginning of main
E/Zygote  ( 3156): MountEmulatedStorage()
E/Zygote  ( 3156): v2
I/SELinux ( 3156): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3156): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
--------- beginning of system
I/libpersona( 3156): KNOX_SDCARD checking this for 1000
I/libpersona( 3156): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonBootCompletedReceiver: pid=3156 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 2259:com.google.android.apps.magazines/u0a110 (adj 15): empty #31
D/TimaKeyStoreProvider( 3141): TimaSignature is unavailable
D/ActivityThread( 3141): Added TimaKeyStore provider
V/[0]UMC:Utils( 3058): checkAppScreen() : com.sec.android.app.launcher
I/[0]UMC:Core( 3058): shutdown
I/art     ( 3058): System.exit called, status: 0
I/AndroidRuntime( 3058): VM exiting with result code 0, cleanup skipped.
E/SELinux ( 3156): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/PsynchoHelperImpl( 2688): Error fetching or saving configuration
W/PsynchoHelperImpl( 2688): bdz: 404 Not Found
W/PsynchoHelperImpl( 2688): {
W/PsynchoHelperImpl( 2688):   "errors": [
W/PsynchoHelperImpl( 2688):     {
W/PsynchoHelperImpl( 2688):       "domain": "global",
W/PsynchoHelperImpl( 2688):       "reason": "notFound",
W/PsynchoHelperImpl( 2688):       "message": "Setting psyncho_auto_backup_promo in namespace FEATURE_SWITCH was not found",
W/PsynchoHelperImpl( 2688):       "locationType": "other",
W/PsynchoHelperImpl( 2688):       "location": "setting"
W/PsynchoHelperImpl( 2688):     }
W/PsynchoHelperImpl( 2688):   ],
W/PsynchoHelperImpl( 2688):   "code": 404,
W/PsynchoHelperImpl( 2688):   "message": "Setting psyncho_auto_backup_promo in namespace FEATURE_SWITCH was not found"
W/PsynchoHelperImpl( 2688): }
W/PsynchoHelperImpl( 2688): 	at bdP.newExceptionOnError(AbstractGoogleJsonClientRequest.java:113)
W/PsynchoHelperImpl( 2688): 	at bdP.newExceptionOnError(AbstractGoogleJsonClientRequest.java:40)
W/PsynchoHelperImpl( 2688): 	at bdK.a(AbstractGoogleClientRequest.java:321)
W/PsynchoHelperImpl( 2688): 	at bei.a(HttpRequest.java:1049)
W/PsynchoHelperImpl( 2688): 	at bdJ.executeUnparsed(AbstractGoogleClientRequest.java:419)
W/PsynchoHelperImpl( 2688): 	at bdJ.executeUnparsed(AbstractGoogleClientRequest.java:352)
W/PsynchoHelperImpl( 2688): 	at bdJ.execute(AbstractGoogleClientRequest.java:469)
W/PsynchoHelperImpl( 2688): 	at Op.a(ApiaryPsynchoConfigurationAccessor.java:142)
W/PsynchoHelperImpl( 2688): 	at Op.a(ApiaryPsynchoConfigurationAccessor.java:215)
W/PsynchoHelperImpl( 2688): 	at OQ.a(PsynchoHelperImpl.java:60)
W/PsynchoHelperImpl( 2688): 	at agr.a(DriveSpecificSyncManager.java:27)
W/PsynchoHelperImpl( 2688): 	at agO.a(LegacySyncManager.java:678)
W/PsynchoHelperImpl( 2688): 	at agO.b(LegacySyncManager.java:582)
W/PsynchoHelperImpl( 2688): 	at agO.a(LegacySyncManager.java:467)
W/PsynchoHelperImpl( 2688): 	at agO.a(LegacySyncManager.java:97)
W/PsynchoHelperImpl( 2688): 	at agQ.run(LegacySyncManager.java:419)
W/PsynchoHelperImpl( 2688): 	at ami.a(NetworkUtilitiesImpl.java:31)
W/PsynchoHelperImpl( 2688): 	at agP.run(LegacySyncManager.java:416)
I/SmartcardBootCompleteReceiver( 1316): SmartcardBootCompleteReceiver - onReceive() 
I/SmartcardBootCompleteReceiver( 1316): Received intent with action - android.intent.action.BOOT_COMPLETED
V/GLSActivity( 1627): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/ContextImpl( 1316): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 android.content.ContextWrapper.sendBroadcast:391 com.android.settings.SmartcardBootCompleteReceiver.onReceive:43 android.app.ActivityThread.handleReceiver:3125 
I/SmartcardBootCompleteReceiver( 1316): Broadcast sent with current lockscreen type
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/TimaKeyStoreProvider( 3156): TimaSignature is unavailable
W/ProcessCpuTracker( 1018): Skipping unknown process pid 3139
D/ActivityThread( 3156): Added TimaKeyStore provider
D/Launcher.Model( 1480): reloadBadges entered.
D/BadgeProvider( 1582): sendNotify entered. [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1582): sendNotify, [notify] : null
D/BadgeProvider( 1582): update, [uri] : content://com.sec.badge/apps/2
D/BadgeProvider( 1582): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 1582): update, [UpdateCount] : 1
D/Mms/MessagingNotification( 2317): setBadgeCount(), count=0
D/Mms/MessagingNotification( 2317): remove alarm
I/System.out( 2688): Thread-324(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 2688): Thread-324(ApacheHTTPLog):isShipBuild true
I/System.out( 2688): Thread-324(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 2688): Thread-324(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10087
I/ActivityManager( 1018): Killing 1497:com.android.printspooler/u0a132 (adj 15): empty #31
D/Mms/MessagingNotification( 2317): updateAllHistoryAsRead()
D/TP/SmsProvider( 1449): query,matched:0, calling pid = 2317
D/TP/SmsProvider( 1449): match 0:Elapsed time : 8.870 ms
D/[SBeam] ( 1316): SBeamEnabler.initPreferenceForSbeam : 0
D/Mms/SmsReceiverService( 2317): [end]    handleBootCompleted() consume time = 267.127135
I/ActivityManager( 1018): Process com.sec.enterprise.knox.cloudmdm.smdms (pid 3058)(adj 0) has died(53,672)
D/daemonapp( 1752): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1752): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
I/ActivityManager( 1018): Killing 2362:com.wsomacp/u0a23 (adj 15): empty #31
D/daemonapp( 1752): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1752): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1752): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
D/daemonapp( 1752): [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionBOOT_COMPLETED, run:true
D/comsamsunglog( 1752): [MSC_Daemon]>>> ====================================================================================================================
D/comsamsunglog( 1752): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
D/comsamsunglog( 1752): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1752): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1752): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
D/daemonapp( 1752): [MSC_Daemon]>>> WDSM:97 [0:0] ABOOTCOPLD
D/SettingsProvider( 1018): name = aw_daemon_service_key_version_check
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10157
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10157
D/daemonapp( 1752): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
D/daemonapp( 1752): [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
D/daemonapp( 1752): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
D/daemonapp( 1752): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
D/daemonapp( 1752): [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
D/daemonapp( 1752): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
E/daemonapp( 1752): [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
D/daemonapp( 1752): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
D/daemonapp( 1752): [MSC_Daemon]>>> WU:2118 [0:0] [boot]now           :1448020203153
D/daemonapp( 1752): [MSC_Daemon]>>> WU:2119 [0:0] [boot]NUT :1448041740000
D/daemonapp( 1752): [MSC_Daemon]>>> WU:2120 [0:0] [boot]interval       :3 (21600000 ms)
D/daemonapp( 1752): [MSC_Daemon]>>> WU:2121 [0:0] [boot]NUT - now :true
D/daemonapp( 1752): [MSC_Daemon]>>> WDBH:2249 [0:0] ud NT1448041740000
I/DIAGMON_AGENT( 3156): [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
I/SettingSearch/SearchIntentReceiver( 1316): action : android.intent.action.BOOT_COMPLETED
I/SettingSearch/SearchIntentReceiver( 1316): search setting db init!!
D/daemonapp( 1752): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 35
D/daemonapp( 1752): [MSC_Daemon]>>> WU:2131 [0:0] Boot set AR_nexttime :1448041740000
W/ContextImpl( 1316): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver.restoredb:41 com.android.settings.settingssearch.SettingsSearchIntentReceiver.onReceive:61 
I/SettingSearch/SearchIntentReceiver( 1316): BOOT_COMPLETED call InitSerachDBThread thread start!
W/libprocessgroup( 1018): failed to open /acct/uid_10110/pid_2259/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10132/pid_1497/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10023/pid_2362/cgroup.procs: No such file or directory
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3179): MountEmulatedStorage()
E/Zygote  ( 3179): v2
I/libpersona( 3179): KNOX_SDCARD checking this for 1000
I/libpersona( 3179): KNOX_SDCARD not a persona
I/SELinux ( 3179): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.wssyncmldm for broadcast com.wssyncmldm/.XDMBroadcastReceiver: pid=3179 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 3179): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.dropbox.android, destAppInfo.processName = com.dropbox.android
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/SELinux ( 3179): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/USB_UICC(  298): Timeout! No signal received. Retry num = 27
E/Zygote  ( 3188): MountEmulatedStorage()
E/Zygote  ( 3188): v2
I/libpersona( 3188): KNOX_SDCARD checking this for 10088
I/libpersona( 3188): KNOX_SDCARD not a persona
D/comdaemonstockapp( 1752): [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionBOOT_COMPLETED
D/comdaemonstockapp( 1752): [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
I/SELinux ( 3188): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.dropbox.android:crash_uploader for service com.dropbox.android/.exception.CrashUploaderService: pid=3188 uid=10088 gids={50088, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 3188): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/TimaKeyStoreProvider( 3179): TimaSignature is unavailable
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/SELinux ( 3188): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 3179): Added TimaKeyStore provider
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/ServiceManager(  315): Waiting for service AtCmdFwd...
E/Zygote  ( 3209): MountEmulatedStorage()
E/Zygote  ( 3209): v2
I/libpersona( 3209): KNOX_SDCARD checking this for 10161
I/libpersona( 3209): KNOX_SDCARD not a persona
I/SELinux ( 3209): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3209): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3209): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.google.android.youtube for broadcast com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService$BootReceiver: pid=3209 uid=10161 gids={50161, 9997, 3003, 1028, 1015} abi=armeabi-v7a
D/TimaKeyStoreProvider( 3188): TimaSignature is unavailable
D/ActivityThread( 3188): Added TimaKeyStore provider
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/TimaKeyStoreProvider( 3209): TimaSignature is unavailable
D/ActivityThread( 3209): Added TimaKeyStore provider
W/ResourcesManager( 3179): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
E/Zygote  ( 3226): MountEmulatedStorage()
E/Zygote  ( 3226): v2
I/libpersona( 3226): KNOX_SDCARD checking this for 10146
I/libpersona( 3226): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.sec.providers.settingsearch for content provider com.sec.providers.settingsearch/.SettingSearchProvider: pid=3226 uid=10146 gids={50146, 9997} abi=armeabi-v7a
I/SELinux ( 3226): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3226): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3226): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
I/DIAGMON_AGENT( 3156): [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
D/TimaKeyStoreProvider( 3226): TimaSignature is unavailable
I/com.dropbox.android.service.DropboxNetworkReceiver( 3141): Setting receiver enabled: false
D/ActivityThread( 3226): Added TimaKeyStore provider
I/DIAGMON_AGENT( 3156): [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
I/DIAGMON_AGENT( 3156): [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.intent.action.BOOT_COMPLETED
I/DIAGMON_AGENT( 3156): [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
I/DIAGMON_AGENT( 3156): [lllIIIIlIIlIlllIlIIl(68/lllIlIlIIIllIIlIllIl)] Running with BootCompletedReceiver adapter
I/DIAGMON_AGENT( 3156): [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
I/ActivityManager( 1018): Killing 2411:com.sec.android.widgetapp.activeapplicationwidget/u0a139 (adj 15): empty #31
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.gms/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/ContextImpl( 2053): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.gms/files
E/ActivityThread( 3141): Failed to find provider info for com.dropbox.carousel.CuOwnerCheckProvider
I/System.out( 2688): SyncManager calls detatch()
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3243): MountEmulatedStorage()
E/Zygote  ( 3243): v2
I/libpersona( 3243): KNOX_SDCARD checking this for 1000
I/libpersona( 3243): KNOX_SDCARD not a persona
I/SELinux ( 3243): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.policydm for content provider com.policydm/com.sec.android.policydm.log.MasterLogProvider: pid=3243 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 3243): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3243): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/dbxyzptlk.db240408.D.h( 3141): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_breakpadinstaller_1dc04d6d96cbb2962385ec13f5f77649aec85e95_arm
W/libprocessgroup( 1018): failed to open /acct/uid_10139/pid_2411/cgroup.procs: No such file or directory
D/TimaKeyStoreProvider( 3243): TimaSignature is unavailable
D/ActivityThread( 3243): Added TimaKeyStore provider
I/FOTA    ( 3179): [com.wssyncmldm.db.sql.XDMDbContentProvider(95/onCreate)] 
I/dbxyzptlk.db240408.D.h( 3141): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dbxfileobserver_59d9546785d1f42b870763ef906fd65c59b55c56_arm
I/dbxyzptlk.db240408.D.h( 3141): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_dropboxsync_cf9d7b2df44b0b78b581431109195f96d492fc70_arm
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
W/ResourcesManager( 3209): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
W/ResourcesManager( 3209): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
E/Zygote  ( 3265): MountEmulatedStorage()
E/Zygote  ( 3265): v2
I/libpersona( 3265): KNOX_SDCARD checking this for 10008
I/libpersona( 3265): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=3265 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/SELinux ( 3265): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3265): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3265): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 3265): TimaSignature is unavailable
D/ActivityThread( 3265): Added TimaKeyStore provider
I/DBG_POLICYDM( 3243): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
I/DBG_POLICYDM( 3243): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
V/JNIHelp ( 3209): Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
I/DBG_POLICYDM( 3243): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
I/DBG_POLICYDM( 3243): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
I/DBG_POLICYDM( 3243): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
I/DBG_POLICYDM( 3243): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
I/DBG_POLICYDM( 3243): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
I/DBG_POLICYDM( 3243): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
I/DBG_POLICYDM( 3243): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/user/0/com.policydm/cache]
I/DBG_POLICYDM( 3243): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
I/DBG_POLICYDM( 3243): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
I/DBG_POLICYDM( 3243): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
I/DBG_POLICYDM( 3243): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
I/DBG_POLICYDM( 3243): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
I/DBG_POLICYDM( 3243): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
I/DBG_POLICYDM( 3243): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
W/ActivityThread( 3209): ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
W/System  ( 3209): Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@186d4266: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
I/ProviderInstaller( 3209): Installed default security provider GmsCore_OpenSSL
,I/DBG_DM  ( 3179): [llIIlIIlIllIllIlllII(316/llIlIIIIlIIIIIlIlIII)] Voice : true
I/DBG_DM  ( 3179): [llIIlIIlIllIllIlllII(317/llIlIIIIlIIIIIlIlIII)] SMS : true
I/dbxyzptlk.db240408.D.h( 3141): Loading /data/data/com.dropbox.android/files/extracted_libs/lib_mupdf_391432aaa92f053af59645394b5734622378199a_arm
I/DBG_DM  ( 3179): [llIIlIIlIllIllIlllII(318/llIlIIIIlIIIIIlIlIII)] isDataOnly : false
D/breakpad( 3141): breakpad loaded; target path "/data/data/com.dropbox.android/app_crashdumps"
W/DriveInitializer( 2053): Background init thread ended
W/GAV2    ( 2688): SyncManager-thalitester@gmail.com: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
I/DBG_POLICYDM( 3243): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
W/art     ( 2688): Suspending all threads took: 18.819ms
W/ContextImpl( 3209): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
I/DBG_POLICYDM( 3243): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
I/com.dropbox.sync.android.a( 3141): Prepared cache dir '/data/data/com.dropbox.android/app_DropboxSyncCache/hizqkiq3952astb'.
I/DBG_POLICYDM( 3243): [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
I/DBG_POLICYDM( 3243): [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
I/DBG_POLICYDM( 3243): [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
I/DBG_POLICYDM( 3243): [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
I/DBG_DM  ( 3179): [com.wssyncmldm.db.sql.llllIIIllIlIIIIllllI(2693/lllIlIlIIIllIIlIllIl)] xdbsqlGetFUMOStatus : 220
I/DBG_DM  ( 3179): [com.wssyncmldm.XDMApplication(80/onCreate)] XDMApplication Start ! - Fumo State
W/ContextImpl( 3179): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 com.wssyncmldm.XDMApplication.onCreate:81 android.app.Instrumentation.callApplicationOnCreate:1020 android.app.ActivityThread.handleBindApplication:5256 
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
I/art     ( 1018): Explicit concurrent mark sweep GC freed 31761(1521KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/33MB, paused 2.182ms total 153.124ms
E/SMD     (  289): DCD OFF
E/USB_UICC(  298): Timeout! No signal received. Retry num = 28
I/DBG_DM  ( 3179): [com.wssyncmldm.XDMBroadcastReceiver(152/onReceive)] android.intent.action.BOOT_COMPLETED
I/DBG_DM  ( 3179): [com.wssyncmldm.XDMService(1598/IlIlllIIlIlIIIlIlIll)] 
I/com.dropbox.sync.android.ad( 3141): Dropbox initialized for application: hizqkiq3952astb (com.dropbox.android/240408 DropboxSync/2.0.2 (Android; 5.0.2; samsung SM-A300FU armeabi-v7a; en_US))
D/OverheatReceiver( 1177): onReceive() getAction : android.intent.action.BOOT_COMPLETED
D/OverheatReceiver( 1177): into the SAFE_MODE_ACTION
D/OverheatReceiver( 1177): VZW on -> change to Global UX [safe mode]
D/OverheatReceiver( 1177): isSafeMode = false
I/ServiceManager(  315): Waiting for service AtCmdFwd...
I/ActivityManager( 1018): Killing 2429:com.sec.android.app.camera/u0a135 (adj 15): empty #31
I/DBG_DM  ( 3179): [com.wssyncmldm.XDMService(1603/IlIlllIIlIlIIIlIlIll)] m_WakeLock is acquire!!
D/BootupListener( 1449): intent.getAction() = android.intent.action.BOOT_COMPLETED
D/SettingsProvider( 1018): name = internet_call_settings_visibility
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1001
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
D/PhoneUtilsCommon( 1449): isSupportVoLTE is false.
I/ActivityManager( 1018): Killing 1607:com.google.android.partnersetup/u0a14 (adj 15): empty #31
D/AndroidRuntime( 3294): 
D/AndroidRuntime( 3294): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
D/AndroidRuntime( 3294): CheckJNI is OFF
D/AndroidRuntime( 3294): readGMSProperty: start
D/AndroidRuntime( 3294): readGMSProperty: already setted!!
D/AndroidRuntime( 3294): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 3294): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 3294): readGMSProperty: end
D/AndroidRuntime( 3294): addProductProperty: start
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/Telecom ( 1431): InCallController: Attempting to bind to InCall com.android.incallui, is dupe? false 
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
I/DBG_POLICYDM( 3243): [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.server.telecom, destAppInfo.processName = com.android.incallui
I/DBG_POLICYDM( 3243): [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 3243): [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/DBG_POLICYDM( 3243): [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
I/DBG_POLICYDM( 3243): [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
I/DBG_DM  ( 3179): [com.wssyncmldm.XDMService(1420/lllIlIlIIIllIIlIllIl)] 0
I/DBG_DM  ( 3179): [IIlIIIlllllIIlIIIlII(232/llllIllIIIIIlIIllIII)] Default - NO_ROOTING_CHECK : false
I/DBG_POLICYDM( 3243): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
I/DBG_DM  ( 3179): [com.wssyncmldm.XDMService(1463/llIlIIIIlIIIIIlIlIII)] 0
I/DBG_DM  ( 3179): [IIlIIIlllllIIlIIIlII(261/IIllIlIIIIlIIIllIllI)] Roaming Check : true
I/DBG_DM  ( 3179): [com.wssyncmldm.XDMService(1548/llIIllllIIlllIIIIlll)] 0
I/DBG_DM  ( 3179): [IIlIIIlllllIIlIIIlII(293/llIIlIlIlIlIIIIIIlIl)] validation Check On
I/DBG_DM  ( 3179): [com.wssyncmldm.XDMService(1505/IllIlIIIIlIIlIIIllIl)] 0
I/DBG_DM  ( 3179): [IIlIIIlllllIIlIIIlII(274/lllllllIlllIIlllIlIl)] SSL Check On
E/Zygote  ( 3323): MountEmulatedStorage()
E/Zygote  ( 3323): v2
I/libpersona( 3323): KNOX_SDCARD checking this for 10090
I/libpersona( 3323): KNOX_SDCARD not a persona
I/SELinux ( 3323): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3323): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3323): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DBG_POLICYDM( 3243): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
I/DBG_POLICYDM( 3243): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
I/ActivityManager( 1018): Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=3323 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 2450:com.sec.android.app.mt/1000 (adj 15): empty #31
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Tethering( 1018): No numeric data
E/Tethering( 1018): No numeric data
I/DBG_POLICYDM( 3243): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2015/11/25/15:58:24
I/DBG_POLICYDM( 3243): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
I/DBG_DM  ( 3179): [llIIlIIlIllIllIlllII(109/llllIIIllIlIIIIllllI)] 
E/Zygote  ( 3343): MountEmulatedStorage()
E/Zygote  ( 3343): v2
I/libpersona( 3343): KNOX_SDCARD checking this for 10052
I/libpersona( 3343): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.StartUpReceiver: pid=3343 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
I/SELinux ( 3343): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
E/Tethering( 1018): No numeric data
I/SELinux ( 3343): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/Tethering( 1018): No numeric data
E/SELinux ( 3343): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 3243): [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
I/DBG_POLICYDM( 3243): [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
I/DBG_POLICYDM( 3243): [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/DBG_POLICYDM( 3243): [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
E/Tethering( 1018): No numeric data
D/TimaKeyStoreProvider( 3323): TimaSignature is unavailable
D/ActivityThread( 3323): Added TimaKeyStore provider
I/DBG_DM  ( 3179): [IlIIlIIlIllllIlllIII(181/llIIIIlllllIIllIIllI)] XEVENT_OS_INITIALIZED
I/DBG_DM  ( 3179): [llIlIIIIlllIlllllIll(142/llIIIIlllllIIllIIllI)] nSync = 0
I/DBG_POLICYDM( 3243): [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
E/Tethering( 1018): No numeric data
I/DBG_POLICYDM( 3243): [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2015/11/20/12:50:04
I/DBG_DM  ( 3179): [llIIlIIlIllIllIlllII(397/llIIIIlllllIIllIIllI)] External SD Card Path : /storage/extSdCard
D/TimaKeyStoreProvider( 3343): TimaSignature is unavailable
D/ActivityThread( 3343): Added TimaKeyStore provider
I/DBG_POLICYDM( 3243): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
I/art     (  305): Explicit concurrent mark sweep GC freed 8704(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 612us total 37.439ms
I/DBG_POLICYDM( 3243): [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
I/DBG_POLICYDM( 3243): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
W/ContextImpl( 3179): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.lllIlIlIIIllIIlIllIl:72 com.wssyncmldm.ui.lIlIIlIlIlIllllllIII.llIIIIlllllIIllIIllI:112 IlIIlIIlIllllIlllIII.llIIIIlllllIIllIIllI:185 
I/DBG_POLICYDM( 3243): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
I/DBG_DM  ( 3179): [llIIlIIlIllIllIlllII(166/llllIIIllIlIIIIllllI)] bExternalStorageAvailable [true]
I/DBG_POLICYDM( 3243): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
I/DBG_DM  ( 3179): [llIIlIIlIllIllIlllII(167/llllIIIllIlIIIIllllI)] bExternalSDStorageAvailable [false]
I/DBG_DM  ( 3179): [com.wssyncmldm.XDMService(1624/IIlIlIIlIlIIlIlllIIl)] 
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 588us total 20.631ms
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
I/Telecom ( 1431): InCallController: onConnected to ComponentInfo{com.android.incallui/com.android.incallui.InCallServiceImpl}
W/libprocessgroup( 1018): failed to open /acct/uid_10135/pid_2429/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2450/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10014/pid_1607/cgroup.procs: No such file or directory
I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 589us total 16.770ms
I/DBG_POLICYDM( 3243): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
I/DBG_POLICYDM( 3243): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
I/DBG_DM  ( 3179): [com.wssyncmldm.XDMService(1629/IIlIlIIlIlIIlIlllIIl)] m_WakeLock is release!!
I/DBG_POLICYDM( 3243): [com.policydm.db.XDB(2239/xdbGetEULAAgreement)] Samsung eula Agree : true
I/DBG_DM  ( 3179): [com.wssyncmldm.XDMService(155/onStartCommand)] 
I/DBG_DM  ( 3179): [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
I/DBG_POLICYDM( 3243): [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
I/DBG_DM  ( 3179): [com.wssyncmldm.db.file.XDB(1976/llIlIIIIlIIIIIlIlIII)] xdbDMffs_Init
I/DBG_DM  ( 3179): [com.wssyncmldm.ui.IIllIllllIIlIlIIlIII(49/onServiceConnected)] 
D/[SBeam] ( 1316): SBeamEnabler.isSBeamSupported : [-1]
D/[SBeam] ( 1316): SBeamEnabler.isSBeamSupported : EXIST
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
D/elm:15121( 3323): ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
D/elm:15121( 3323): ELMEngine.ELMEngine( context ).
D/elm:15121( 3323): MDMBridge.setEnterpriseBridge()
I/System.out( 3141): Thread-409(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
I/System.out( 3141): Thread-409(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 3141): Thread-409(ApacheHTTPLog):isShipBuild true
I/System.out( 3141): Thread-409(ApacheHTTPLog):SMARTBONDING_ENABLED is false
I/System.out( 3141): Thread-409(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10088
D/elm:15121( 3323): ELMAbstractReceiver : Receive Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
I/DBG_DM  ( 3179): [IlIIlIIlIllllIlllIII(191/llIIIIlllllIIllIIllI)] XEVENT_PHONEBOOK_INITIALIZED
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
V/EmergencyMode( 1417): [EmergencyReceiver] EmergencyReceiver [android.intent.action.BOOT_COMPLETED]
D/elm:15121( 3323): ElmAgentService : onCreate()
D/elm:15121( 3323): ElmAgentService : onHandleIntent() Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
D/elm:15121( 3323): ELMEngine.ServiceHandler.handleMessage( BOOT_COMPLETED ). 
D/elm:15121( 3323): BootCompletedState : startBootCompleted() call
E/Zygote  ( 3373): MountEmulatedStorage()
I/libpersona( 3373): KNOX_SDCARD checking this for 10014
E/Zygote  ( 3373): v2
I/libpersona( 3373): KNOX_SDCARD not a persona
I/SELinux ( 3373): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.google.android.partnersetup for content provider com.google.android.partnersetup/.RlzAppProvider: pid=3373 uid=10014 gids={50014, 9997, 3003} abi=armeabi-v7a
I/SELinux ( 3373): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/elm:15121( 3323): MDMBridge.getAllLicenseInfoFromSDK()
I/DBG_DM  ( 3179): [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
I/elm:15121( 3323): Get License : 0
I/DBG_POLICYDM( 3243): [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
E/SELinux ( 3373): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Killing 2482:com.sec.tcpdumpservice/1000 (adj 15): empty #31
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3390): MountEmulatedStorage()
E/Zygote  ( 3390): v2
I/libpersona( 3390): KNOX_SDCARD checking this for 1000
I/libpersona( 3390): KNOX_SDCARD not a persona
I/SELinux ( 3390): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/TimaKeyStoreProvider( 3373): TimaSignature is unavailable
I/DBG_DM  ( 3179): [com.wssyncmldm.XDMService(1377/llllIIIllIlIIIIllllI)] wssGetUpdateReport : 0
D/ActivityThread( 3373): Added TimaKeyStore provider
I/DBG_DM  ( 3179): [IlIIlIIlIllllIlllIII(217/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT
I/SELinux ( 3390): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.fmm.dm for broadcast com.fmm.dm/.XDMBroadcastReceiver: pid=3390 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 2516:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
I/ActivityManager( 1018): Killing 2499:com.sec.android.app.sbrowser/u0a127 (adj 15): empty #32
E/SELinux ( 3390): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/elm:15121( 3323): ElmAgentService : onDestroy().
I/ActivityManager( 1018): Killing 2587:com.android.calendar/u0a131 (adj 15): empty #31
V/EmergencyMode( 1417): [EmergencyBase] setBootTime
V/EmergencyMode( 1417): [EmergencyFactory] No Recovery State, kill my self.
E/Tethering( 1018): No numeric data
D/TimaKeyStoreProvider( 3390): TimaSignature is unavailable
D/ActivityThread( 3390): Added TimaKeyStore provider
V/audio_hw_primary(  284): adev_get_parameters: enter: keys - call_forwarding
D/audio_hw_extn(  284): audio_extn_get_parameters: returns 
V/msm8974_platform(  284): platform_get_parameters: exit: returns - 
V/audio_hw_primary(  284): adev_get_parameters: exit: returns - call_forwarding=false
I/str_params(  284): key: 'call_forwarding' value: ''
V/InCall  ( 1862): ProximitySensor -  - screenonImmediately: false
V/InCall  ( 1862): ProximitySensor -  - mFromRcsShare: false
I/InCall  ( 1862): ProximitySensor -  - ProximitySensor{keybrd=0, dpad=0, offhook=0, hor=0, ui=0, aud=EARPIECE}
E/Tethering( 1018): No numeric data
E/Tethering( 1018): No numeric data
D/LocationManagerService( 1018): getProviders()=[passive]
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/ScoverManager( 1862): serviceVersion : 16908288
D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
D/InCall  ( 1862): InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
D/InCall  ( 1862): InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
I/Telecom ( 1431): ProximitySensorManager: Proximity wake lock already released
I/InCall  ( 1862): InCallPresenter -  - InCallState = NO_CALLS
E/Tethering( 1018): No numeric data
I/InCall  ( 1862): InCallPresenter -  - Phone switching state: NO_CALLS -> NO_CALLS
D/InCall  ( 1862): InCallPresenter -  - dismissCoverDialog()...
I/ContactAccountLoggerTas( 3343): canRun() : Opted Out
E/Zygote  ( 3413): MountEmulatedStorage()
I/libpersona( 3413): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3413): v2
I/libpersona( 3413): KNOX_SDCARD not a persona
I/SELinux ( 3413): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/InCall  ( 1862): CallSContextMotion - stopPutDownListening
I/DBG_POLICYDM( 3243): [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
I/ActivityManager( 1018): Start proc com.sec.factory.camera for broadcast com.sec.factory.camera/com.sec.android.app.camerafirmware.CameraFirmwareBroadCastReceiver: pid=3413 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 3413): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/InCall  ( 1862): StatusBarNotifier - updateInCallNotification(allowFullScreenIntent = false)...
E/SELinux ( 3413): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/PhoneStatusBarView( 1177): setCallBackground:0
I/ActivityManager( 1018): Waited long enough for: ServiceRecord{115fac5f u0 com.samsung.hs20settings/.WifiHs20UtilityService}
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
D/TimaKeyStoreProvider( 3413): TimaSignature is unavailable
D/ActivityThread( 3413): Added TimaKeyStore provider
D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
D/InCall  ( 1862): InCallUtils - isCoverClosed : TYPE_FLIP_COVER 
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
V/VibratorService( 1018): hasVibrator - useVibetonz: true
E/AffinityControl( 3294): AffinityControl: registerfunction enter
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2482/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10127/pid_2499/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2516/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10131/pid_2587/cgroup.procs: No such file or directory
W/NotificationAccessSettings( 1316): Skipping notification listener service com.android.settings/com.android.settings.accessibility.notificationreminder.NotificationReminderService: it does not require the permission android.permission.BIND_NOTIFICATION_LISTENER_SERVICE
V/VibratorService( 1018): hasVibrator - useVibetonz: true
V/VibratorService( 1018): hasVibrator - useVibetonz: true
W/ResourcesManager( 1316): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/DBG_FMMDM( 3390): [50.20.150420][Line:608][xdmGetCheckWifiOnlyModel] isWifiOnly : false
I/CameraApp( 3413): CameraApp.onCreate()... mFeature : null
I/testFeature( 3413): Feature.Feature(context)
I/testFeature( 3413): Feature.readInternalDefaultXml()
I/testFeature( 3413): ResetFeatureValue
I/CameraFirmware_broadcast( 3413): CameraFirmwareBroadCastReceiver...
I/CameraApp( 3413): CameraApp.getAppFeature()...
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3438): MountEmulatedStorage()
E/Zygote  ( 3438): v2
I/libpersona( 3438): KNOX_SDCARD checking this for 10095
I/SELinux ( 3438): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 3438): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.samsung.android.provider.filterprovider for broadcast com.samsung.android.provider.filterprovider/.FilterProviderReceiver: pid=3438 uid=10095 gids={50095, 9997, 1023} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 2616:com.android.keychain/1000 (adj 15): empty #31
I/SELinux ( 3438): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
D/AndroidRuntime( 3294): Calling main entry com.android.commands.am.Am
E/SELinux ( 3438): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/VideoCallManager( 1862): Instantiating VideoCallManager
I/DBG_POLICYDM( 3243): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
D/TimaKeyStoreProvider( 3438): TimaSignature is unavailable
D/ActivityThread( 3438): Added TimaKeyStore provider
E/        ( 1862): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
I/GFX construct_block_size_descriptor_2d second part( 1862): took 2.301615ms for 0*0 texture 0
E/PersonaManagerService( 1018): inState():  stateMachine is null !!
I/PersonaManagerService( 1018): PersonaId don't exist
I/ActivityManager( 1018): do not start freezing screen for locked container getKeyguardshowstate = false
I/GFX generate_partition_tables( 1862): took 5.206562ms for 0*0 texture 0
I/GFX raster( 1862): took 11.455520ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1862): Bitmap=0xb81adb38 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b0, Counterpart=0xb81ad408 counterpartCT=4 counterpartW=176 counterparth=144
I/DBG_FMMDM( 3390): [50.20.150420][Line:27][xdmInitialize] AgVOOqV7UpXFblBk29Ld3aZrOQhtHCYbjdszx6nYrjFYzeVOvvlPUzE67GnQVups
I/DBG_FMMDM( 3390): [50.20.150420][Line:28][xdmInitialize] c8aaBoNX+zCI65M7gVNTej45+K/MzxjqVpKd5x0FMtd3o63nokSujfTEanrHiU41
I/DBG_FMMDM( 3390): [50.20.150420][Line:29][xdmInitialize] X2Nl5mgTWVn0/a90MNBgtYshxOiQq2MqI4oMf2Nwz6I=
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/CustomFrequencyManagerService( 1018): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
W/ActivityManager( 1018): mDVFSHelper.acquire()
D/FocusedStackFrame( 1018): Set to : 0
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.example.hello
D/InputDispatcher( 1018): Focused application set to: xxxx
D/InputDispatcher( 1018): Focus left window: 1480
D/PhoneWindow( 1018): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 1018): *FMB* installDecor flags : 25362712
D/AndroidRuntime( 3294): Shutting down VM
D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
D/PreloadFilterInstaller( 3438): uses FILTER_DB_VER_1
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 1018): *FMB* isFloatingMenuEnabled return false
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/SurfaceFlinger(  258): id=10 createSurf (1x1),1 flag=404, iello
I/DBG_POLICYDM( 3243): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
D/Launcher.HomeView( 1480): onPause
E/        ( 1862): GFX convertToRaster() in Bitmap.cpp for bitmap size 320x240
D/Launcher( 1480): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
I/Adreno-EGL( 1862): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 1862): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 1862): Build Date: 04/06/15 Mon
I/Adreno-EGL( 1862): Local Branch: 
I/Adreno-EGL( 1862): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 1862): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 1862):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
I/libpersona( 3456): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3456): MountEmulatedStorage()
I/libpersona( 3456): KNOX_SDCARD not a persona
E/Zygote  ( 3456): v2
I/SELinux ( 3456): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/ScoverManager( 1316): serviceVersion : 16908288
I/SELinux ( 3456): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3456): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.pcw.device for content provider com.sec.pcw.device/.contentprovider.DMProvider: pid=3456 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/SQLiteLog( 3438): (284) automatic index on titles(filter_id)
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2616/cgroup.procs: No such file or directory
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/Zygote  ( 3469): MountEmulatedStorage()
I/libpersona( 3469): KNOX_SDCARD checking this for 10333
E/Zygote  ( 3469): v2
I/libpersona( 3469): KNOX_SDCARD not a persona
I/SELinux ( 3469): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3469): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3469): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.example.hello for activity com.example.hello/.MainActivity: pid=3469 uid=10333 gids={50333, 9997, 3003, 3001, 3002} abi=armeabi-v7a
I/DBG_POLICYDM( 3243): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
I/FilterProviderReceiver( 3438): onReceive in FilterProviderReceiver
I/DBG_POLICYDM( 3243): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
D/TimaKeyStoreProvider( 3456): TimaSignature is unavailable
D/ActivityThread( 3456): Added TimaKeyStore provider
I/FilterProviderReceiver( 3438): onReceive in FilterProviderReceiver when ACTION_BOOT_COMPLETED
D/TimaKeyStoreProvider( 3469): TimaSignature is unavailable
D/ActivityThread( 3469): Added TimaKeyStore provider
I/GFX GPU raster( 1862): eglCreateImageKHR: EGL_SUCCESS
I/DBG_POLICYDM( 3243): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/glCompressedTexImage2D( 1862): took 0.477552ms for 320*61440 texture 37809
I/draw setup( 1862): took 11.525417ms for 320*240 texture 37809
E/GFX GPU raster( 1862): drawn
I/GFX GPU raster ASTC( 1862): took 45.267657ms for 320*240 texture 12
I/GFX raster( 1862): took 45.339636ms for 320*240 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1862): Bitmap=0xb81adab8 bitmapCt=12 bitmapW=320 bitmapH=240 BitmapInternalFormat=93b1, Counterpart=0xb81ad620 counterpartCT=4 counterpartW=320 counterparth=240
V/ActivityThread( 1480): updateVisibility : ActivityRecord{161c73b7 token=android.os.BinderProxy@c05e641 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
E/        ( 1862): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
I/GFX GPU raster( 1862): eglCreateImageKHR: EGL_SUCCESS
I/glCompressedTexImage2D( 1862): took 0.453959ms for 480*122880 texture 37813
I/draw setup( 1862): took 0.992292ms for 480*640 texture 37813
E/GFX GPU raster( 1862): drawn
I/GFX GPU raster ASTC( 1862): took 8.799687ms for 480*640 texture 12
I/GFX raster( 1862): took 8.886562ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1862): Bitmap=0xb81ad620 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b5, Counterpart=0xb83ef078 counterpartCT=4 counterpartW=480 counterparth=640
W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1712 com.android.server.ssrm.ad.ec:-1 com.android.server.ssrm.ae.handleMessage:-1 android.os.Handler.dispatchMessage:102 android.os.Looper.loop:145 
E/Zygote  ( 3490): MountEmulatedStorage()
I/libpersona( 3490): KNOX_SDCARD checking this for 10098
E/Zygote  ( 3490): v2
I/libpersona( 3490): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=3490 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
I/SELinux ( 3490): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3490): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Killing 2725:com.android.email/u0a141 (adj 15): empty #31
E/SELinux ( 3490): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
V/WindowOrientationListener( 1018): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
V/WindowManager( 1018): rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1018): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
D/Launcher.HomeView( 1480): onStop
V/ActivityThread( 1480): updateVisibility : ActivityRecord{161c73b7 token=android.os.BinderProxy@c05e641 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
W/GAV2    ( 3343): Thread[Background Non-Blocking-1,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
D/PersonaManager( 1018): isKioskContainerExistOnDevice
D/TimaKeyStoreProvider( 3490): TimaSignature is unavailable
D/ActivityThread( 3490): Added TimaKeyStore provider
W/GAV2    ( 3343): Thread[Background Non-Blocking-1,5,main]: dispatch call queued.  Need to call GAServiceManager.getInstance().initialize().
W/art     ( 3294): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
E/USB_UICC(  298): Timeout! No signal received. Retry num = 29
D/SensorService( 1018): [SO] activate (ident=0xb8696fd0, enabled=0)
D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
E/        ( 1862): GFX convertToRaster() in Bitmap.cpp for bitmap size 440x330
,I/GFX GPU raster( 1862): eglCreateImageKHR: EGL_SUCCESS
I/glCompressedTexImage2D( 1862): took 0.368125ms for 440*116864 texture 37809
I/draw setup( 1862): took 0.960833ms for 440*330 texture 37809
E/GFX GPU raster( 1862): drawn
,D/SensorManager( 1018): unregisterListener ::   
,I/Sensors ( 1018): AccelerometerSensor(0) setDelay : 66000000(ns)
,D/SensorService( 1018): [SO] changed settle time [1]
D/SensorService( 1018): [SO] setDelay [66000000]
D/SensorService( 1018): [SO] activate (ident=0xb8696fd0, enabled=1)
D/SensorService( 1018): [SO] AR_init
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,I/GFX GPU raster ASTC( 1862): took 7.108386ms for 440*330 texture 12
I/GFX raster( 1862): took 7.210209ms for 440*330 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1862): Bitmap=0xb83ef058 bitmapCt=12 bitmapW=440 bitmapH=330 BitmapInternalFormat=93b1, Counterpart=0xb83ef428 counterpartCT=4 counterpartW=440 counterparth=330
,D/SensorManager( 1018): registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,E/YouTube MDX( 3209): Bogus value in shared preferences for key MdxServerSelection value , returning default value.
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,E/        ( 1862): GFX convertToRaster() in Bitmap.cpp for bitmap size 480x640
,I/GFX GPU raster( 1862): eglCreateImageKHR: EGL_SUCCESS
,I/glCompressedTexImage2D( 1862): took 0.430261ms for 480*163840 texture 37811
I/draw setup( 1862): took 1.132500ms for 480*640 texture 37811
E/GFX GPU raster( 1862): drawn
,I/GFX GPU raster ASTC( 1862): took 6.861615ms for 480*640 texture 12
I/GFX raster( 1862): took 6.951511ms for 480*640 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1862): Bitmap=0xb83eee98 bitmapCt=12 bitmapW=480 bitmapH=640 BitmapInternalFormat=93b3, Counterpart=0xb8401ec0 counterpartCT=4 counterpartW=480 counterparth=640
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/Launcher( 1480): onTrimMemory. Level: 20
,I/AudioService( 1018): getStreamVolume 3 index 70
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/MediaRouter( 3343): Found default route: MediaRouter.RouteInfo{ uniqueId=android/mo:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=7, volumeMax=15, presentationDisplayId=-1, extras=null, providerPackageName=android }
,I/ContactAccountLoggerTas( 3343): canRun() : Opted Out
,I/FavoriteContactNamesSup( 3343): get() : Execute runnable (UI thread)
,I/ContactLabelSupplier( 3343): get() : Execute runnable (UI thread)
,I/ContactLabelSupplier( 3343): get() : OptedIn = false
,I/PCWCLIENTTRACE_LOG( 3456): DEFAULT_LOGON : true
I/PCWCLIENTTRACE_LOG( 3456): DEFAULT_LOGLEVEL : 3
,I/PCWCLIENTTRACE_DMDBOpenHelper( 3456): new DMDBOpenHelper instance
,D/SensorService( 1018): [SO] Reset Rotation Old [100], Init [1]
,D/PackageIntentReceiver( 3490): ACTION_BOOT_COMPLETED
,D/PackageIntentReceiver( 3490): jangil::ACTION_BOOT_COMPLETED::do not need pkg remove..
,D/PCWCLIENTTRACE_DMContentProvider( 3456): [URIMatcher] - result : 2
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/        ( 1862): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/GFX construct_block_size_descriptor_2d second part( 1862): took 2.902292ms for 0*0 texture 0
,I/GFX generate_partition_tables( 1862): took 8.076042ms for 0*0 texture 0
,E/Zygote  ( 3514): MountEmulatedStorage()
I/GFX raster( 1862): took 13.431666ms for 176*144 texture 0
I/libpersona( 3514): KNOX_SDCARD checking this for 10099
E/Zygote  ( 3514): v2
I/libpersona( 3514): KNOX_SDCARD not a persona
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1862): Bitmap=0xb83defa8 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b2, Counterpart=0xb8401ee0 counterpartCT=4 counterpartW=176 counterparth=144
,I/SELinux ( 3514): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.google.android.gm for broadcast com.google.android.gm/.GoogleMailDeviceStartupReceiver: pid=3514 uid=10099 gids={50099, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 2796:com.mobeam.barcodeService/1000 (adj 15): empty #31
,I/SELinux ( 3514): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3514): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/        ( 1862): GFX convertToRaster() in Bitmap.cpp for bitmap size 176x144
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
I/GFX construct_block_size_descriptor_2d second part( 1862): took 3.284115ms for 0*0 texture 0
I/GFX generate_partition_tables( 1862): took 6.367864ms for 0*0 texture 0
I/GFX raster( 1862): took 11.830365ms for 176*144 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 1862): Bitmap=0xb83ef508 bitmapCt=12 bitmapW=176 bitmapH=144 BitmapInternalFormat=93b1, Counterpart=0xb8403bd0 counterpartCT=4 counterpartW=176 counterparth=144
I/ActivityManager( 1018): Start proc com.samsung.android.intelligenceservice for broadcast com.samsung.android.intelligenceservice/.useranalysis.UserAnalysisBroadcastReceiver: pid=3529 uid=10055 gids={50055, 9997, 3001, 3002} abi=armeabi-v7a
E/Zygote  ( 3529): MountEmulatedStorage()
E/Zygote  ( 3529): v2
I/libpersona( 3529): KNOX_SDCARD checking this for 10055
D/SensorService( 1018): [SO] currT = 35331064000, prevT = 35011279000, diff = 319785000, [-0.364 0.038 9.902]
D/SensorService( 1018): [SO] -0.364 0.038 9.902
D/SensorService( 1018): [SO] [100 -> 255]
D/ScoverManager( 1862): registerListener
I/libpersona( 3529): KNOX_SDCARD not a persona
I/SELinux ( 3529): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3529): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3529): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
,D/CoverManagerWhiteLists( 1018): isAllowedToUse : SIGNATURE_MATCH
D/CoverManager.StateNotifier( 1018): registerListenerCallback : binder = android.os.BinderProxy@c892c96, pid : 1862, uid : 1001, type : 1
D/TimaKeyStoreProvider( 3514): TimaSignature is unavailable
,D/ActivityThread( 3514): Added TimaKeyStore provider
,I/WebViewFactory( 3469): Loading com.google.android.webview version 37 (1726107-arm) (code 119201)
,I/ActivityManager( 1018): Killing 1770:com.samsung.android.securitylogagent/1000 (adj 15): empty #31
,D/InCall  ( 1862): InCallPresenter -  - Finished InCallPresenter.setUp
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/DBG_FMMDM( 3390): [50.20.150420][Line:40][onCreate] FMMApplication NOT Start !
,D/TimaKeyStoreProvider( 3529): TimaSignature is unavailable
,I/LibraryLoader( 3469): Loading: webviewchromium
,D/ActivityThread( 3529): Added TimaKeyStore provider
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/LibraryLoader( 3469): Time to load native libraries: 5 ms (timestamps 5380-5385)
I/LibraryLoader( 3469): Expected native library version number "",actual native library version number ""
,I/DBG_FMMDM( 3390): [50.20.150420][Line:67][onReceive] android.intent.action.BOOT_COMPLETED
,I/DBG_FMMDM( 3390): [50.20.150420][Line:309][onReceive] android.intent.action.BOOT_COMPLETED
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2796/cgroup.procs: No such file or directory
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3547): MountEmulatedStorage()
E/Zygote  ( 3547): v2
I/libpersona( 3547): KNOX_SDCARD checking this for 1000
I/libpersona( 3547): KNOX_SDCARD not a persona
,I/SELinux ( 3547): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3547): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1018): Start proc com.fmm.ds for broadcast com.fmm.ds/.XDSBroadcastReceiver: pid=3547 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,E/SELinux ( 3547): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Killing 2819:com.sec.knox.bridge/1000 (adj 15): empty #31
,I/ActivityManager( 1018): Killing 2832:flipboard.boxer.app/u0a97 (adj 15): empty #32
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,I/AudioService( 1018): getStreamVolume 3 index 70
,D/TimaKeyStoreProvider( 3547): TimaSignature is unavailable
,D/ActivityThread( 3547): Added TimaKeyStore provider
,D/UserAnalysis.PlaceProvider( 3529): PlaceProvider onCreate()
,I/LockPatternUtils( 1316): isSmartCardAuthenticationAvailable: false
,D/Settings_Utils( 1316): isSupportVNFestival SM-A300FU XEO
,W/libprocessgroup( 1018): failed to open /acct/uid_10141/pid_2725/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_1770/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10097/pid_2832/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2819/cgroup.procs: No such file or directory
,D/UserAnalysis.SecureDbManager( 3529): Key for secure DB is newly created
,D/UserAnalysis.SecurePlaceDbHelper( 3529): SecurePlaceDbHelper() 
D/UserAnalysis( 3529): Create SecureDbHelper
,D/IntelligenceServiceApplication( 3529): onCreate()
,D/UserAnalysis.UserAnalysisBroadcastReceiver( 3529): Intent(action: android.intent.action.BOOT_COMPLETED) is received.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/ResourceType( 1316): Failure getting entry for 0x7f0202b4 (t=1 e=692) (error -75),
,D/IntelligenceServiceApplication( 3529): no applications having user consent for prediction
,E/Zygote  ( 3562): MountEmulatedStorage()
E/Zygote  ( 3562): v2
I/libpersona( 3562): KNOX_SDCARD checking this for 10056
I/libpersona( 3562): KNOX_SDCARD not a persona
I/SELinux ( 3562): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3562): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1018): Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=3562 uid=10056 gids={50056, 9997, 1028, 1015, 3003} abi=armeabi-v7a
E/SELinux ( 3562): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Killing 2854:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #31,
,V/PlaceDetection v1.0.19 ( 3529): [PlaceDetection::stopService] Service stopped.
,I/art     (  305): Explicit concurrent mark sweep GC freed 8693(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 594us total 25.992ms
,W/ResourceType( 1316): Failure getting entry for 0x7f020510 (t=1 e=1296) (error -75)
,D/TimaKeyStoreProvider( 3562): TimaSignature is unavailable
D/ActivityThread( 3562): Added TimaKeyStore provider
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 666us total 17.655ms
,V/WebViewChromiumFactoryProvider( 3469): Binding Chromium to main looper Looper (main, tid 1) {1dfe3d93}
I/LibraryLoader( 3469): Expected native library version number "",actual native library version number ""
I/chromium( 3469): [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,I/DBG_FMMDS( 3547): [50.18.150420][Line:56][onCreate] FMMDS Application Start
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 593us total 16.929ms
,I/SurfaceFlinger(  258): id=9 Removed Mauncher (5/8)
I/SurfaceFlinger(  258): id=9 Removed Mauncher (-2/8)
I/DBG_FMMDS( 3547): [50.18.150420][Line:28][<init>] XDBHelper First Call!!!
,I/BrowserStartupController( 3469): Initializing chromium process, renderers=0
,W/art     ( 3469): Attempt to remove local handle scope entry from IRT, ignoring
E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
I/FactoryTestApp( 2572): [IPCWriterToSecPhoneService$disConnectSecPhoneService](3120)  
,W/ContextImpl( 3209): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/cache
,I/ActivityManager( 1018): Killing 2459:com.sec.modem.settings/1000 (adj 15): empty #31
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 3209): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/chromium( 3469): [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
W/ContextImpl( 3209): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
I/chromium( 3469): [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=35 off=46768 len=2953
,I/chromium( 3469): [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:36 off:229524 len:643667
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.gms
,I/Adreno-EGL( 3469): <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
I/Adreno-EGL( 3469): OpenGL ES Shader Compiler Version: E031.25.03.02
I/Adreno-EGL( 3469): Build Date: 04/06/15 Mon
I/Adreno-EGL( 3469): Local Branch: 
I/Adreno-EGL( 3469): Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
I/Adreno-EGL( 3469): Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
I/Adreno-EGL( 3469):                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,W/libprocessgroup( 1018): failed to open /acct/uid_10148/pid_2854/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2459/cgroup.procs: No such file or directory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
V/PlaceDetection v1.0.19 ( 3529): [PlaceDetectionManager::removeDetectionListener] PlaceDetectionListener removed.
,D/UserAnalysis.MyPlaceDbPreference( 3529): Constructor Preference
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/DBG_DM  ( 3179): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 0 sec
,I/System.out( 3141): pool-10-thread-1 calls detatch()
,D/PCWCLIENTTRACE_DMContentProvider( 3456): [URIMatcher] - result : 2
,E/DBG_FMMDS( 3547): Warning!!! [50.18.150420][Line:36][xdsDevAdpGetDeviceID] DeviceID read fail!!!!!!!!
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/DBG_FMMDS( 3547): [50.18.150420][Line:43][xdbDBInit] 
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/BatteryService( 1018): !@BatteryListener : batteryPropertiesChanged!
,D/BatteryService( 1018): level:100, scale:100, status:5, health:2, present:true, voltage: 4306, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
D/BatteryService( 1018): online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
D/BatteryService( 1018): Sending ACTION_BATTERY_CHANGED.
,I/MotionRecognitionService( 1018): Plugged
I/MotionRecognitionService( 1018): mGripSensorEnabled= false
,D/KeyguardUpdateMonitor( 1177): received broadcast android.intent.action.BATTERY_CHANGED
,D/KeyguardUpdateMonitor( 1177): handleBatteryUpdate
D/PowerUI ( 1177): Cable  true --> true mBootCompleted : true
D/PowerUI ( 1177): Sending cableIntent : Intent { act=com.samsung.systemui.power.action.ACTION_CABLE_CONNECTED }
,V/EmergencyMode( 1417): [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
,V/EmergencyMode( 1417): [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,V/HeadsetService( 2607): HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
D/HeadsetStateMachine( 2607): Disconnected process message: 10
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.apps.docs, destAppInfo.processName = com.google.android.gms
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,D/BatteryMeterView( 1177): ACTION_BATTERY_CHANGED : level:100 status:5 health:2
D/SViewCoverView( 1177): BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
D/SViewCoverView( 1177): level :100 plugged : 2
,I/GAV2    ( 2688): Thread[GAThread,5,main]: No campaign data found.
,W/chromium( 3469): [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/sCloudBackupApp( 3562): sCloudBackupApp Version Info : 4.04.7.KK_APP
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
W/art     ( 3469): Attempt to remove local handle scope entry from IRT, ignoring
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/AwContents( 3469): onDetachedFromWindow called when already detached. Ignoring,
,I/DBG_FMMDS( 3547): [50.18.150420][Line:63][onCreate] onCreate Db Initialized
,E/Zygote  ( 3637): MountEmulatedStorage()
E/Zygote  ( 3637): v2
I/libpersona( 3637): KNOX_SDCARD checking this for 10058
I/libpersona( 3637): KNOX_SDCARD not a persona
,I/DBG_FMMDS( 3547): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
I/DBG_FMMDS( 3547): [50.18.150420][Line:279][xdsDefaultProfileCheckServerID] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,I/SELinux ( 3637): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
D/PhoneWindow( 3469): *FMB* installDecor mIsFloating : false
D/PhoneWindow( 3469): *FMB* installDecor flags : 8456448
I/ActivityManager( 1018): Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=3637 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/DBG_FMMDS( 3547): [50.18.150420][Line:363][xdsGetAccount] UZnlD2ITkPmcCbh9srjpN/1auPpXZ1U0673eFrlr5G7ujCmOnoTUvn8Wy3q3+o8W
I/ActivityManager( 1018): Killing 2913:org.simalliance.openmobileapi.service/1101 (adj 15): empty #31
I/SELinux ( 3637): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
W/chromium( 3469): [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,I/DBG_FMMDS( 3547): [50.18.150420][Line:376][xdsCheckSamsungAccountForChina] VG44Fy9kdMk+/k3D4uP4d3do/3rw5AoymvTy0wXAnzc=
,E/SELinux ( 3637): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/DBG_FMMDS( 3547): [50.18.150420][Line:89][onReceive] Receive Intent : android.intent.action.BOOT_COMPLETED
,I/DBG_FMMDS( 3547): [50.18.150420][Line:248][onReceive] XCOMMON_INTENT_NOTI_CALLLOG_CLICK
,D/SystemWebViewEngine( 3469): CordovaWebView is running on device made by: samsung
,I/ActivityManager( 1018): Killing 2218:flipboard.app/u0a96 (adj 15): empty #31
,D/AndroidHttpClient( 3209): [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A300FU Build/LRX22G)
D/AndroidHttpClient( 3209): [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
I/System.out( 3209): Thread-473(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
D/TimaKeyStoreProvider( 3637): TimaSignature is unavailable
I/System.out( 3209): Thread-473(ApacheHTTPLog):isSBSettingEnabled false
I/System.out( 3209): Thread-473(ApacheHTTPLog):isShipBuild true
I/System.out( 3209): Thread-473(ApacheHTTPLog):SMARTBONDING_ENABLED is false
D/ActivityThread( 3637): Added TimaKeyStore provider
,I/System.out( 3209): Thread-473(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,I/FOTA_Client( 3265): [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,W/art     ( 3469): Attempt to remove local handle scope entry from IRT, ignoring
W/art     ( 3469): Attempt to remove local handle scope entry from IRT, ignoring
,I/FOTA_Client( 3265): [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10161
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
,I/FOTA_Client( 3265): [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
,W/MessageQueue( 3209): Handler (android.os.Handler) {24b9e49b} sending message to a Handler on a dead thread
W/MessageQueue( 3209): java.lang.IllegalStateException: Handler (android.os.Handler) {24b9e49b} sending message to a Handler on a dead thread
W/MessageQueue( 3209): 	at android.os.MessageQueue.enqueueMessage(MessageQueue.java:325)
W/MessageQueue( 3209): 	at android.os.Handler.enqueueMessage(Handler.java:631)
W/MessageQueue( 3209): 	at android.os.Handler.sendMessageAtTime(Handler.java:600)
W/MessageQueue( 3209): 	at android.os.Handler.sendMessageDelayed(Handler.java:570)
W/MessageQueue( 3209): 	at android.os.Handler.post(Handler.java:326)
W/MessageQueue( 3209): 	at ffw.a(SourceFile:327)
W/MessageQueue( 3209): 	at guw.a(SourceFile:120)
W/MessageQueue( 3209): 	at guf.c(SourceFile:26)
W/MessageQueue( 3209): 	at gui.run(SourceFile:297)
W/MessageQueue( 3209): 	at android.os.Handler.handleCallback(Handler.java:739)
W/MessageQueue( 3209): 	at android.os.Handler.dispatchMessage(Handler.java:95)
W/MessageQueue( 3209): 	at android.os.Looper.loop(Looper.java:145)
W/MessageQueue( 3209): 	at android.os.HandlerThread.run(HandlerThread.java:61)
,W/FOTA_Client( 3265): [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3664): MountEmulatedStorage(),
I/libpersona( 3664): KNOX_SDCARD checking this for 10013
E/Zygote  ( 3664): v2
I/libpersona( 3664): KNOX_SDCARD not a persona
I/SELinux ( 3664): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,V/VibratorService( 1018): hasVibrator - useVibetonz: true
,I/ActivityManager( 1018): Start proc com.google.android.onetimeinitializer for broadcast com.google.android.onetimeinitializer/.OneTimeInitializerReceiver: pid=3664 uid=10013 gids={50013, 9997} abi=armeabi-v7a
,I/SELinux ( 3664): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Killing 2972:com.sec.android.app.taskmanager/u0a153 (adj 15): empty #31
,E/SELinux ( 3664): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL,
,D/OpenGLRenderer( 3469): Render dirty regions requested: true
,D/TimaKeyStoreProvider( 3664): TimaSignature is unavailable
,D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
D/ActivityThread( 3664): Added TimaKeyStore provider
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
W/libprocessgroup( 1018): failed to open /acct/uid_1101/pid_2913/cgroup.procs: No such file or directory
,D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
,D/PhoneWindow( 3469): *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
D/PhoneWindow( 3469): *FMB* isFloatingMenuEnabled return false
,I/SurfaceFlinger(  258): id=11 createSurf (1x1),1 flag=404, NainActivit
,W/libprocessgroup( 1018): failed to open /acct/uid_10096/pid_2218/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10153/pid_2972/cgroup.procs: No such file or directory
,W/ContextImpl( 1847): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
,E/USB_UICC(  298): Timeout! No signal received. Retry num = 30
,I/ExternalOEMControlProvider( 3637): onCreate
,D/InputDispatcher( 1018): Focus entered window: 3469
,D/SRIB_DCS( 3469): log_dcs ThreadedRenderer::initialize entered! 
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101,
I/OpenGLRenderer( 3469): Initialized EGL, version 1.4
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
,D/OpenGLRenderer( 3469): Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
D/OpenGLRenderer( 3469): Enabling debug mode 0
,D/SecUISvc( 1847): Thread created.
,D/SecUISvc( 1847): Service started flags 0 startId 1
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/System.out( 3209): Thread-473 calls detatch()
,E/Zygote  ( 3691): MountEmulatedStorage()
E/Zygote  ( 3691): v2
I/libpersona( 3691): KNOX_SDCARD checking this for 1000
I/libpersona( 3691): KNOX_SDCARD not a persona
,I/SELinux ( 3691): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3691): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 3691): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.sec.android.app.servicemodeapp for broadcast com.sec.android.app.servicemodeapp/.ServiceModeAppBroadcastReceiver: pid=3691 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 2875:com.sec.android.app.clockpackage/u0a81 (adj 15): empty #31
,W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,W/ActivityManager( 1018): Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
,D/SettingsProvider( 1018): name = PREVIOUS_SYS_TIME
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10058
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/TimaKeyStoreProvider( 3691): TimaSignature is unavailable,
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10058
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,D/ActivityThread( 3691): Added TimaKeyStore provider
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/SettingsProvider( 1018): name = PREVIOUS_ELAPSED_TIME
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10058
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10058
,E/USB_UICC(  298): Timeout! No signal received. Reach maximum retries!
E/USB_UICC(  298): usb_uicc_init_qmi failed ! 
I/USB_UICC(  298): usb_uicc_cleanup, signal received: 0x3 
I/USB_UICC(  298): usb_uicc_cleanup, Issuing QMI deinit ... 
,I/ActivityManager( 1018): Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3710 uid=10026 gids={50026, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/Zygote  ( 3710): MountEmulatedStorage()
I/libpersona( 3710): KNOX_SDCARD checking this for 10026
E/Zygote  ( 3710): v2
I/libpersona( 3710): KNOX_SDCARD not a persona
,I/SELinux ( 3710): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/SELinux ( 3710): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3710): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,W/libprocessgroup( 1018): failed to open /acct/uid_10081/pid_2875/cgroup.procs: No such file or directory
,I/StatusBar( 1177): Icon Only
,D/PanelView( 1177): There is/are notification(s) 
,I/Timeline( 3469): Timeline: Activity_idle id: android.os.BinderProxy@1181b183 time:36328
,D/TimaKeyStoreProvider( 3710): TimaSignature is unavailable
,D/ActivityThread( 3710): Added TimaKeyStore provider
V/OneTimeInitializerReceiver( 3664): OneTimeInitializerReceiver.onReceive
,I/Gmail   ( 3514): Observing account changes for notifications
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.onetimeinitializer, destAppInfo.processName = com.google.android.onetimeinitializer
,W/ResourcesManager( 3691): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,V/OneTimeService( 3664): OneTimeService.onHandleIntent
,I/Gmail   ( 3514): getAccountsCursor
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1018): Displayed Component not be shown by security: +1s376ms
,D/CustomFrequencyManagerService( 1018): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1018): mDVFSHelper.release()
I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{35d5023f u0 com.example.hello/.MainActivity t10} time:36372
,D/CustomFrequencyManagerService( 1018): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@11
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 30397(1619KB) AllocSpace objects, 2(38KB) LOS objects, 33% free, 22MB/33MB, paused 4.635ms total 321.141ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,I/SamsungIME( 1822): getCurrentCandidateView
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,V/GLSActivity( 1627): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/ServiceMode( 3691): received = ACTION_BOOT_COMPLETED
I/ServiceMode( 3691): setReferenceIsDumpState : 0
,W/GAV2    ( 3514): Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3747): MountEmulatedStorage()
E/Zygote  ( 3747): v2
I/libpersona( 3747): KNOX_SDCARD checking this for 1000
I/libpersona( 3747): KNOX_SDCARD not a persona
,I/SELinux ( 3747): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.wssnps for broadcast com.wssnps/.smlNpsReceiverDefault: pid=3747 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 3747): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1018): Killing 2997:com.sec.usbsettings/1000 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
E/SELinux ( 3747): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1719): Starting #4
,I/Hs20UtilService( 1719): Message received 5003
,D/TimaKeyStoreProvider( 3747): TimaSignature is unavailable
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 3747): Added TimaKeyStore provider
,E/Zygote  ( 3763): MountEmulatedStorage()
E/Zygote  ( 3763): v2
I/libpersona( 3763): KNOX_SDCARD checking this for 10018
I/libpersona( 3763): KNOX_SDCARD not a persona
,I/SELinux ( 3763): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/chromium( 3469): [INFO:CONSOLE(10)] "The key "target-densitydpi" is not supported.", source: file:///android_asset/www/index.html (10)
E/AndroidProtocolHandler( 3469): Unable to open asset URL: file:///android_asset/www/jxcore.js
I/ActivityManager( 1018): Start proc com.samsung.klmsagent for broadcast com.samsung.klmsagent/.listner.MainReciver: pid=3763 uid=10018 gids={50018, 9997, 3003} abi=armeabi-v7a
,I/SELinux ( 3763): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3763): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3763): TimaSignature is unavailable
,D/ActivityThread( 3763): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_2997/cgroup.procs: No such file or directory
,I/SurfaceFlinger(  258): id=10 Removed iello (7/8)
,I/SurfaceFlinger(  258): id=10 Removed iello (-2/8)
,I/KLMS-2.5.123: ( 3763): KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Fri Nov 20 12:50:06 GMT+01:00 2015
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,I/KLMS-2.5.123: ( 3763): KLMSAbstractReciever(): onReceive().END.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/LockPatternUtils( 1316): isSmartCardAuthenticationAvailable: false
,I/KLMS-2.5.123: ( 3763): KLMSIntentService(): onCreate()
,E/Zygote  ( 3781): MountEmulatedStorage()
E/Zygote  ( 3781): v2
I/libpersona( 3781): KNOX_SDCARD checking this for 10020
I/libpersona( 3781): KNOX_SDCARD not a persona
,I/SELinux ( 3781): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3781): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
E/SELinux ( 3781): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
I/ActivityManager( 1018): Start proc com.android.managedprovisioning for broadcast com.android.managedprovisioning/.BootReminder: pid=3781 uid=10020 gids={50020, 9997, 1028, 3003} abi=armeabi-v7a
,I/KLMS-2.5.123: ( 3763): KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,I/KLMS-2.5.123: ( 3763): KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,I/KLMS-2.5.123: ( 3763): KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,D/CustomFrequencyManagerService( 1018): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@11
,D/TimaKeyStoreProvider( 3781): TimaSignature is unavailable
,D/ActivityThread( 3781): Added TimaKeyStore provider
,I/KLMS-2.5.123: ( 3763): KLMSIntentService(): BOOT_COMPLETED
,I/DBG_DM  ( 3179): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 1 sec
,D/NPS_WSSNPS( 3747): [] android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 3747): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.wssnps.smlNpsReceiverDefault.onReceive:35 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,D/NPS_WSSNPS( 3747): [] Service onCreate!!
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3801): MountEmulatedStorage(),
I/libpersona( 3801): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3801): v2
I/libpersona( 3801): KNOX_SDCARD not a persona
I/SELinux ( 3801): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.samsung.android.app.accesscontrol for broadcast com.samsung.android.app.accesscontrol/.AccessControlReceiver: pid=3801 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 3801): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/SELinux ( 3801): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/JsMessageQueue( 3469): Set native->JS mode to OnlineEventsBridgeMode,
,E/Zygote  ( 3811): MountEmulatedStorage()
I/libpersona( 3811): KNOX_SDCARD checking this for 1000
E/Zygote  ( 3811): v2
I/libpersona( 3811): KNOX_SDCARD not a persona
I/SELinux ( 3811): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3811 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/SELinux ( 3811): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 3811): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/TimaKeyStoreProvider( 3801): TimaSignature is unavailable
I/ActivityManager( 1018): Killing 2317:com.android.mms/u0a41 (adj 15): empty #31
D/ActivityThread( 3801): Added TimaKeyStore provider
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/KLMS-2.5.123: ( 3763): KLMSIntentService(): onDestroy()
D/NPS_WSSNPS( 3747): [50.150321] smlDBHelper
,D/NPS_WSSNPS( 3747): [50.150321] NpsServiceTask Start
,E/Gmail   ( 3514): Error finding the version of the Email provider.....
E/Gmail   ( 3514): android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
E/Gmail   ( 3514): 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
E/Gmail   ( 3514): 	at com.google.android.gm.EmailMigrationService.aU(SourceFile:1236)
E/Gmail   ( 3514): 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
E/Gmail   ( 3514): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/Gmail   ( 3514): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/Gmail   ( 3514): 	at android.os.Looper.loop(Looper.java:145)
E/Gmail   ( 3514): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/EmailMigration( 3514): We do not support migrating this version of the Email provider.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/TimaKeyStoreProvider( 3811): TimaSignature is unavailable
,D/ActivityThread( 3811): Added TimaKeyStore provider
,I/Gmail   ( 3514): getAccountsCursor
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
V/GLSActivity( 1627): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
,D/CountryDetector( 1018): No listener is left
,W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
,D/btif_config_util( 2607): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,D/SettingsProvider( 1018): name = access_control_enabled
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
W/libprocessgroup( 1018): failed to open /acct/uid_10041/pid_2317/cgroup.procs: No such file or directory
,E/MTPRx   ( 3811): In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,E/Zygote  ( 3841): MountEmulatedStorage()
,E/Zygote  ( 3841): v2
I/libpersona( 3841): KNOX_SDCARD checking this for 10065
I/libpersona( 3841): KNOX_SDCARD not a persona
,I/SELinux ( 3841): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1018): Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=3841 uid=10065 gids={50065, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 3025:com.sec.android.app.safetyassurance/u0a43 (adj 15): empty #31
,I/SELinux ( 3841): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,W/ActivityManager( 1018): Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
E/SELinux ( 3841): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/SecContentProvider2( 1018): uri = 14 selection = getSealedState
D/SecContentProvider2( 1018): mCursor = null
,D/SecContentProvider2( 1018): uri = 14 selection = getSealedUsbMassStorageState
,D/SecContentProvider2( 1018): mCursor = null
,V/MTPRx   ( 3811): sealedState: false
V/MTPRx   ( 3811): sealedUsbMassStorageState: false
,E/ActivityThread( 3514): Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@301c25f4 that was originally bound here
E/ActivityThread( 3514): android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.J@301c25f4 that was originally bound here
E/ActivityThread( 3514): 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
E/ActivityThread( 3514): 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
E/ActivityThread( 3514): 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
E/ActivityThread( 3514): 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
E/ActivityThread( 3514): 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
E/ActivityThread( 3514): 	at com.android.emailcommon.service.H.a(SourceFile:181)
E/ActivityThread( 3514): 	at com.android.emailcommon.service.H.mb(SourceFile:224)
E/ActivityThread( 3514): 	at com.android.email.service.n.j(SourceFile:160)
E/ActivityThread( 3514): 	at com.android.email.provider.b.a(SourceFile:171)
E/ActivityThread( 3514): 	at com.android.email.provider.b.F(SourceFile:115)
E/ActivityThread( 3514): 	at com.android.email.service.EmailBroadcastProcessorService.kD(SourceFile:305)
E/ActivityThread( 3514): 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:130)
E/ActivityThread( 3514): 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
E/ActivityThread( 3514): 	at android.os.Handler.dispatchMessage(Handler.java:102)
E/ActivityThread( 3514): 	at android.os.Looper.loop(Looper.java:145)
E/ActivityThread( 3514): 	at android.os.HandlerThread.run(HandlerThread.java:61)
W/ActivityManager( 1018): Unbind failed: could not find connection for android.os.BinderProxy@237c596d
,I/NPS_WSSNPS( 3747): [50.150321] AsyncBulkFlagCheck
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
D/SettingsProvider( 1018): name = mtp_usb_connection_status
,D/TimaKeyStoreProvider( 3841): TimaSignature is unavailable
,D/SamsungIME( 1822): Dismiss ExpandCandiate
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
D/ActivityThread( 3841): Added TimaKeyStore provider
,D/SettingsProvider( 1018): name = media_player_mode,
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,D/SettingsProvider( 1018): name = mtp_usb_conditions_met
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,E/Zygote  ( 3858): MountEmulatedStorage()
E/Zygote  ( 3858): v2
I/libpersona( 3858): KNOX_SDCARD checking this for 10102
I/libpersona( 3858): KNOX_SDCARD not a persona
,I/NPS_WSSNPS( 3747): [50.150321] IsRemain_AsyncBulkCheck
I/SELinux ( 3858): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/NPS_WSSNPS( 3747): [50.150321] IsRemain_Asyncing nothing
W/ContextImpl( 3747): Calling a method in the system process without a qualified user: android.app.ContextImpl.stopService:2069 android.content.ContextWrapper.stopService:538 com.wssnps.h.run:107 java.util.Timer$TimerImpl.run:284 <bottom of call stack> 
,I/SELinux ( 3858): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/ActivityManager( 1018): Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3858 uid=10102 gids={50102, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
E/SELinux ( 3858): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.wssnps, destAppInfo.processName = com.wssnps
,D/NPS_WSSNPS( 3747): [50.150321] Service onDestroy
,D/SettingsProvider( 1018): name = mtp_running_status
,I/NPS_WSSNPS( 3747): [50.150321] smlBRConfigurationDelete
,D/SettingsProvider( 1018): name = media_mount_count
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/art     (  305): Explicit concurrent mark sweep GC freed 8723(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 634us total 24.757ms
,I/NPS_WSSNPS( 3747): [50.150321] smlBRMessageDelete
,D/SettingsProvider( 1018): name = mtp_sync_alive
,I/NPS_WSSNPS( 3747): [50.150321] smlBREmailDelete
,I/NPS_WSSNPS( 3747): [50.150321] smlBRNetworkDelete
,I/NPS_WSSNPS( 3747): [50.150321] smlBRCallLogDelete
,I/NPS_WSSNPS( 3747): [50.150321] smlBRMiniDiaryDelete
I/NPS_WSSNPS( 3747): [50.150321] smlBRPenMemoMDelete
I/NPS_WSSNPS( 3747): [50.150321] smlBRSMemoDelete
,I/NPS_WSSNPS( 3747): [50.150321] cpuBooster release : false
,I/chromium( 3469): [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
I/chromium( 3469): 
,D/SettingsProvider( 1018): name = sdcard_launch
,D/SettingsProvider( 1018): name = boot_time_connected
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 599us total 19.584ms
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 603us total 18.687ms
,W/libprocessgroup( 1018): failed to open /acct/uid_10043/pid_3025/cgroup.procs: No such file or directory
,D/SettingsProvider( 1018): name = mtp_open_session
,D/TimaKeyStoreProvider( 3858): TimaSignature is unavailable
D/ActivityThread( 3858): Added TimaKeyStore provider
D/NPS_WSSNPS( 3747): [50.150321] dsServerSocket close
,I/ActivityManager( 1018): Killing 3038:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,V/GLSActivity( 1627): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
D/Finsky  ( 3710): [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/PCWCLIENTTRACE_PushUtil( 3456): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3456): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3456): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3456): [onReceive] - android.intent.action.BOOT_COMPLETED
D/PCWCLIENTTRACE_SYSTEMReceiver( 3456): ACTION_BOOTUP - Version: 4.82
D/PCWCLIENTTRACE_SYSTEMReceiver( 3456): ACTION_BOOTUP - Push type: [SPP, GCM]
,I/GoogleHttpClient( 1627): GMS http client unavailable, use old client
,W/ResourcesManager( 3858): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,I/SamsungIME( 1822): getDebugLevel  : 0x4f4c
,E/SQLiteLog( 3514): (283) recovered 57 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,W/PCWCLIENTTRACE_AccountUtil( 3456): [hasSamungAccount] - No Samsung Account
,D/jxcore_app_log( 3469): JniHelper::setJavaVM(0xb7e01448), pthread_self() = -1203243432
,D/JX-Cordova( 3469): jxcore cordova android initializing
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.partnersetup, destAppInfo.processName = com.google.android.partnersetup
,I/RlzPingService( 3373): Setting next ping for 1448625007276
,E/SMD     (  289): DCD OFF
,W/jxcore-log( 3469): Initializing JXcore engine
W/jxcore-log( 3469): JXcore engine is ready
,W/jxcore-log( 3469): Starting JXcore engine
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3038/cgroup.procs: No such file or directory
,I/ServiceManager(  315): Waiting for service AtCmdFwd...
,D/FileShare-Server( 3841): ServerBroadcastReceiver.onReceive - action android.intent.action.BOOT_COMPLETED // null
,I/art     ( 1627): Explicit concurrent mark sweep GC freed 5829(328KB) AllocSpace objects, 2(32KB) LOS objects, 39% free, 7MB/11MB, paused 1.424ms total 62.477ms,
,E/audit   ( 1818): type=1400 msg=audit(1448020207.403:205): avc:  denied  { ioctl } for  pid=3469 comm="m.example.hello" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2064 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,E/audit   ( 1818):  SEPF_SM-A300FU_5.0.2_0027
E/audit   ( 1818): type=1300 msg=audit(1448020207.403:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=4 a3=bee70d58 items=0 ppid=305 ppcomm=main pid=3469 auid=4294967295 uid=10333 gid=10333 euid=10333 suid=10333 fsuid=10333 egid=10333 sgid=10333 fsgid=10333 ses=4294967295 tty=(none) comm="m.example.hello" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
E/audit   ( 1818): type=1320 msg=audit(1448020207.403:205): 
,I/PCWCLIENTTRACE_SecurePreferencesJNI( 3456): [GetString-S]
,I/ReactiveServiceManager( 3456): Supported : 1
,W/ContextImpl( 1316): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:130 <bottom of call stack> 
,W/ContextImpl( 1316): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendOrderedBroadcast:1741 android.content.ContextWrapper.sendOrderedBroadcast:408 android.content.ContextWrapper.sendOrderedBroadcast:408 com.android.settings.settingssearch.SettingsSearchIntentReceiver$InitSerachDBThread.run:131 <bottom of call stack> 
,I/SettingSearch/SearchIntentReceiver( 1316): InitSerachDBThread thread end!
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/QSEECOMAPI: ( 1018): QSEECom_get_handle sb_length = 0x2040
,D/QSEECOMAPI: ( 1018): App is not loaded in QSEE
,D/Finsky  ( 3710): [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,W/jxcore-log( 3469): Platform android
W/jxcore-log( 3469): 
W/jxcore-log( 3469): Process ARCH arm
W/jxcore-log( 3469): 
,D/FactoryTestApp( 2572): [DummyFtClient$onDestroy](2572) Destroy DummyFtClient service
,D/FactoryTestApp( 2572): [Support$Values.getString](2572) id=MODEL_COMMUNICATION_MODE, value=gsm
,I/FactoryTestApp( 2572): [ModuleCommon$isConnectionModeNone](2572) mConnectionMode = gsm
I/FactoryTestApp( 2572): [ModuleCommon$isRunningFtClient](2572) RUNNING_FTCLIENT : false
D/FactoryTestApp( 2572): [DummyFtClient$onDestroy](2572) kill process
I/Process ( 2572): Sending signal. PID: 2572 SIG: 9
,W/Settings( 3710): Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,W/Settings( 3710): Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,I/jxcore-log( 3469): JXcore Cordova bridge is ready!
I/jxcore-log( 3469): 
,W/jxcore-log( 3469): JXcore engine is started
,D/Volley  ( 3710): [534] DiskBasedCache.clear: Cache cleared.
,I/ActivityManager( 1018): Killing 3013:com.sec.dsm.system/1000 (adj 15): empty #31
,I/ActivityManager( 1018): Process com.sec.factory (pid 2572)(adj 0) has died(24,647)
,D/QSEECOMAPI: ( 1018): Loaded image: APP id = 9
,I/SamsungIME( 1822): getDebugLevel  : 0x4f4c
,D/QSEECOMAPI: ( 1018): QSEECom_dealloc_memory 
D/QSEECOMAPI: ( 1018): QSEECom_shutdown_app, app_id = 9
,E/terrier ( 1018): handleString: Failed to handle string(-4)
E/terrier ( 1018): Java_com_android_server_ReactiveService_GetString: error code = [-4]
D/PCWCLIENTTRACE_SecurePreferencesJNI( 3456): getString is null
I/PCWCLIENTTRACE_SecurePreferencesJNI( 3456): [GetString-E]
,I/PCWCLIENTTRACE_PushUtil( 3456): SPPPushClient is installed : true
,I/PCWCLIENTTRACE_PushUtil( 3456): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3456): getPushTypeList : [SPP, GCM]
,E/PCWCLIENTTRACE_PCWHandler( 3456): [ensureRegistration] - No Samsung account
,D/Volley  ( 3710): [527] DiskBasedCache.clear: Cache cleared.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/Ads     ( 3710): Skipping gmscore version check
,E/Zygote  ( 3902): MountEmulatedStorage()
,I/libpersona( 3902): KNOX_SDCARD checking this for 10028
E/Zygote  ( 3902): v2
I/libpersona( 3902): KNOX_SDCARD not a persona
I/SELinux ( 3902): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3902): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/SamsungIME( 1822): KeybaordView init() : load resources
,E/SELinux ( 3902): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3902 uid=10028 gids={50028, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 2381:com.sec.android.gallery3d/u0a39 (adj 15): empty #31
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,E/File    ( 3514): fail readDirectory() errno=2
,I/Gmail   ( 3514): notifyAccountChanged
,D/TimaKeyStoreProvider( 3902): TimaSignature is unavailable
,D/ActivityThread( 3902): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/Gmail   ( 3514): getAccountsCursor
,E/jxcore-log( 3469): >> samsung-SM-A300FU
E/jxcore-log( 3469): 
,I/jxcore-log( 3469): Total memory 1451114496
I/jxcore-log( 3469): 
,I/jxcore-log( 3469): Free memory 38203392
I/jxcore-log( 3469): 
I/jxcore-log( 3469): execPath /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3469): 
I/jxcore-log( 3469): process.cwd /data/data/com.example.hello/files/www/jxcore
I/jxcore-log( 3469): 
,V/GLSActivity( 1627): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3514): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,I/jxcore-log( 3469): userPath [ 'www' ]
I/jxcore-log( 3469): 
,I/jxcore-log( 3469): Size 540 960
I/jxcore-log( 3469): 
,I/jxcore-log( 3469): Screen Brightness 255
I/jxcore-log( 3469): 
,E/jxcore-log( 3469): Dummy Error Log.
E/jxcore-log( 3469): 
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3013/cgroup.procs: No such file or directory,
,I/Gmail   ( 3514): calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,D/Finsky  ( 3710): [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,D/Finsky  ( 3710): [1] Libraries$2.run: Finished loading 1 libraries.
,I/DBG_DM  ( 3179): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
,W/libprocessgroup( 1018): failed to open /acct/uid_10039/pid_2381/cgroup.procs: No such file or directory
,I/Gmail   ( 3514): getAccountsCursor
,V/GLSActivity( 1627): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/Gmail   ( 3514): calculateUnknownSyncRationalesAndPurgeInBackground: running
I/SamsungIME( 1822): getCurrentKeyboard
,I/SamsungIME( 1822): getTextKeyboard
,I/Gmail   ( 3514): calculateUnknownSyncRationalesAndPurgeInBackground: running
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Finsky  ( 3710): [1] GmsCoreHelper.cleanupNlp: result=false type=4
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,I/System.out( 3902): Inside onCreate() of WakeupTriggerProvide
I/System.out( 3902): Inside WakeupProvider
,D/PackageManager( 1018): [MSG] MCS_UNBIND
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/ActivityManager( 1018): Killing 2665:com.android.chrome/u0a77 (adj 15): empty #31
,D/Finsky  ( 3710): [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,I/ActivityManager( 1018): Killing 3101:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
,I/Icing   ( 2053): Storage manager: low false usage 2.08MB avail 8.51GB capacity 9.90GB
,I/Babel   ( 3858): MmsConfig: mnc/mcc: 0/0
I/Babel   ( 3858): MmsConfig.loadMmsSettings
I/Babel   ( 3858): MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
I/Babel   ( 3858): MmsConfig.loadFromDatabase
,W/libprocessgroup( 1018): failed to open /acct/uid_10077/pid_2665/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3101/cgroup.procs: No such file or directory
,I/VlingoApplication( 3902): VlingoApplication appVersion ='11.7.0.1.40139', coreVersion = '2.6.1.16800', ro.csc.sales_code=XEO
,D/SamsungIME( 1822): [SwiftkeyWrapper] currentLangauge : 1701729619
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,E/Babel   ( 3858): canonicalizeMccMnc: invalid mccmnc 
I/Babel   ( 3858): MmsConfig.loadFromResources
,E/Babel   ( 3858): canonicalizeMccMnc: invalid mccmnc nullnull
,I/Babel   ( 3858): MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A300FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A300FU.xml
,W/VideoCapabilities( 3858): Unrecognized profile 2130706433 for video/avc
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/VlingoAndroidCore( 3902): AppName: SamsungTproject, Core: 2.6.1.16800, SDK: 2.0.2137, EDM:16800
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/AudioCapabilities( 3858): Unsupported mime audio/evrc
,W/AudioCapabilities( 3858): Unsupported mime audio/qcelp
,W/Settings( 3858): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,I/DBG_POLICYDM( 3243): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,W/AudioCapabilities( 3858): Unsupported mime audio/mpeg-L1
,W/AudioCapabilities( 3858): Unsupported mime audio/mpeg-L2
,W/Atfwd_Sendcmd(  315): AtCmdFwd service not published, waiting... retryCnt : 3
,W/AudioCapabilities( 3858): Unsupported mime audio/x-ms-wma
,W/AudioCapabilities( 3858): Unsupported mime audio/x-ima
,I/jxcore-log( 3469): getBuffer is called!!!!
I/jxcore-log( 3469): 
,W/AudioCapabilities( 3858): Unsupported mime audio/qcelp
,W/AudioCapabilities( 3858): Unsupported mime audio/evrc
,I/DBG_POLICYDM( 3243): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 3243): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 3243): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
I/DBG_POLICYDM( 3243): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
I/DBG_POLICYDM( 3243): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,D/WearableService( 1798): callingUid 10011, callindPid: 1798
,E/GmsWearableLS( 1798): GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,I/DBG_POLICYDM( 3243): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 3243): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,W/VideoCapabilities( 3858): Unsupported mime video/wvc1
,W/VideoCapabilities( 3858): Unsupported mime video/x-ms-wmv
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 22066(1114KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 22MB/33MB, paused 2.294ms total 154.940ms
,W/VideoCapabilities( 3858): Unrecognized profile/level 32768/2 for video/mp4v-es
,I/ActivityManager( 1018): Killing 3079:com.google.android.configupdater/u0a82 (adj 15): empty #31
,W/VideoCapabilities( 3858): Unsupported mime video/wvc1
,W/VideoCapabilities( 3858): Unsupported mime video/x-ms-wmv
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
,W/ContextImpl( 1018): Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
,W/VideoCapabilities( 3858): Unsupported mime video/x-ms-wmv7
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
W/VideoCapabilities( 3858): Unsupported mime video/x-ms-wmv8
,W/VideoCapabilities( 3858): Unsupported mime video/mp43
,V/Babel   ( 3858): babel boot account: SMS
,E/Zygote  ( 3950): MountEmulatedStorage()
E/Zygote  ( 3950): v2
I/libpersona( 3950): KNOX_SDCARD checking this for 1000
I/libpersona( 3950): KNOX_SDCARD not a persona
,I/SELinux ( 3950): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3950 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/SELinux ( 3950): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
V/Babel   ( 3858): babel boot account: thalitester@gmail.com
,E/SELinux ( 3950): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/VideoCapabilities( 3858): Unsupported mime video/sorenson
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/VideoCapabilities( 3858): Unsupported mime video/mp4v-esdp
,I/ActivityManager( 1018): Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=3962 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 3141:com.dropbox.android/u0a88 (adj 15): empty #31
E/Zygote  ( 3962): MountEmulatedStorage()
E/Zygote  ( 3962): v2
I/libpersona( 3962): KNOX_SDCARD checking this for 1000
I/libpersona( 3962): KNOX_SDCARD not a persona
,I/SELinux ( 3962): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,D/VlingoApplication( 3902): sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
D/VlingoApplication( 3902): sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,W/libprocessgroup( 1018): failed to open /acct/uid_10082/pid_3079/cgroup.procs: No such file or directory
,I/SELinux ( 3962): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3962): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 3950): TimaSignature is unavailable
,D/ActivityThread( 3950): Added TimaKeyStore provider
,D/TimaKeyStoreProvider( 3962): TimaSignature is unavailable
D/ActivityThread( 3962): Added TimaKeyStore provider
,D/DialogFlow( 3902): initQueue()
,I/VideoCapabilities( 3858): Unsupported profile 4 for video/mp4v-es
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3982): MountEmulatedStorage()
,E/Zygote  ( 3982): v2
I/libpersona( 3982): KNOX_SDCARD checking this for 10029
I/libpersona( 3982): KNOX_SDCARD not a persona
,I/SELinux ( 3982): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/ActivityManager( 1018): Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=3982 uid=10029 gids={50029, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 3156:com.sec.android.diagmonagent/1000 (adj 15): empty #31
I/SELinux ( 3982): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3982): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,V/AlarmManager( 1018): waitForAlarm result :4
,D/TimaKeyStoreProvider( 3982): TimaSignature is unavailable
,D/ActivityThread( 3982): Added TimaKeyStore provider
,V/AlarmManager( 1018): waitForAlarm result :4
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3156/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10088/pid_3141/cgroup.procs: No such file or directory
,W/ContextImpl( 3950): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 3998): MountEmulatedStorage(),
E/Zygote  ( 3998): v2
I/libpersona( 3998): KNOX_SDCARD checking this for 1000
I/libpersona( 3998): KNOX_SDCARD not a persona
I/SELinux ( 3998): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 3998): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 3998): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
I/ActivityManager( 1018): Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=3998 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,D/TimaKeyStoreProvider( 3998): TimaSignature is unavailable
,D/ActivityThread( 3998): Added TimaKeyStore provider
,W/ResourcesManager( 3998): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,W/ContextImpl( 3998): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4015): MountEmulatedStorage()
I/ActivityManager( 1018): Start proc com.sec.android.app.bluetoothtest for broadcast com.sec.android.app.bluetoothtest/.BluetoothBDAdrressReceiver: pid=4015 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 4015): v2
I/libpersona( 4015): KNOX_SDCARD checking this for 1000
I/SELinux ( 4015): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 4015): KNOX_SDCARD not a persona
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk,
,I/SELinux ( 4015): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/SELinux ( 4015): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4024 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
I/F_PHONE ( 3998): [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
I/ActivityManager( 1018): Killing 1582:com.sec.android.provider.badge/u0a68 (adj 15): empty #31
,W/ContextImpl( 3998): Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,E/Zygote  ( 4024): MountEmulatedStorage()
E/Zygote  ( 4024): v2
I/libpersona( 4024): KNOX_SDCARD checking this for 1000
I/libpersona( 4024): KNOX_SDCARD not a persona
,I/SELinux ( 4024): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4024): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,D/TimaKeyStoreProvider( 4015): TimaSignature is unavailable
E/SELinux ( 4024): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
D/ActivityThread( 4015): Added TimaKeyStore provider
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/DBG_DM  ( 3179): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,D/TimaKeyStoreProvider( 4024): TimaSignature is unavailable
,D/ActivityThread( 4024): Added TimaKeyStore provider
,E/Zygote  ( 4050): MountEmulatedStorage(),
E/Zygote  ( 4050): v2
I/libpersona( 4050): KNOX_SDCARD checking this for 10030
I/libpersona( 4050): KNOX_SDCARD not a persona
,I/SELinux ( 4050): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
W/ResourcesManager( 4015): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/ActivityManager( 1018): Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=4050 uid=10030 gids={50030, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,I/SELinux ( 4050): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
D/F_PHONE ( 3998): [[com.sec.bcservice]] onServiceConnected()
I/F_PHONE ( 3998): default registerAction()
I/F_PHONE ( 3998): [[com.sec.bcservice]] sendPendingMessage(),
E/SELinux ( 4050): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,D/TimaKeyStoreProvider( 4050): TimaSignature is unavailable
,D/ActivityThread( 4050): Added TimaKeyStore provider
,W/libprocessgroup( 1018): failed to open /acct/uid_10068/pid_1582/cgroup.procs: No such file or directory
,E/KnoxSetupWizardClient( 4024): isShipMode : 1
,I/KnoxSetupWizardClient( 4024): onReceive : android.intent.action.BOOT_COMPLETED
,D/BluetoothBDAdrressReceiver( 4015): onReceive(), action: android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 4015): Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.app.bluetoothtest.BluetoothBDAdrressReceiver.onReceive:32 android.app.ActivityThread.handleReceiver:3125 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.app.bluetoothtest, destAppInfo.processName = com.sec.android.app.bluetoothtest
,I/ActivityManager( 1018): Killing 3188:com.dropbox.android:crash_uploader/u0a88 (adj 15): empty #31
,W/ResourcesManager( 1449): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,D/BluetoothBDTestService( 1449): onCreate()
,E/BluetoothBDTestService( 1449): onStart(), extra_type: BOOT_COMPLETED
E/BluetoothBDTestService( 1449): bd_address_path: /efs/bluetooth/bt_addr
,E/BluetoothBDTestService( 1449): already exist!( /efs/bluetooth/bt_addr ), file length: 17
,W/System.err( 4024): java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
,W/System.err( 4024): 	at android.os.Parcel.readException(Parcel.java:1544)
W/System.err( 4024): 	at android.os.Parcel.readException(Parcel.java:1493)
W/System.err( 4024): 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4163)
W/System.err( 4024): 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1925)
W/System.err( 4024): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
W/System.err( 4024): 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,D/ShortcutReceiver( 4024):  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED
,W/libprocessgroup( 1018): failed to open /acct/uid_10088/pid_3188/cgroup.procs: No such file or directory
,D/KnoxShortcutUtil( 4024): getIsShortcutMigrationFor_2_3_0_Done true
,D/ShortcutReceiver( 4024):  KnoxContainerVersion 2.3.0
,D/ShortcutReceiver( 4024):  shortcut migration not required 
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/FileApkUtils( 2053): Spent 28ms computing apk sha1.
,D/FileApkUtils( 2053): Module already staged or being staged:chimera-modules/MapsModule.apk,
I/art     ( 2053): DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@chimera-module-root@module-e5b9d8f8da13e4c453d8ac4c37e56e073c51a3ad@MapsModule.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/chimera-module-root/module-e5b9d8f8da13e4c453d8ac4c37e56e073c51a3ad/MapsModule.apk': Failed to open oat filename for reading: No such file or directory
E/Zygote  ( 4070): MountEmulatedStorage()
,E/Zygote  ( 4070): v2
I/libpersona( 4070): KNOX_SDCARD checking this for 1000
I/libpersona( 4070): KNOX_SDCARD not a persona
I/ActivityManager( 1018): Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4070 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 3226:com.sec.providers.settingsearch/u0a146 (adj 15): empty #31
I/SELinux ( 4070): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4070): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4070): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/DexOptUtils( 2053): Module /data/data/com.google.android.gms/app_chimera/chimera-module-root/module-e5b9d8f8da13e4c453d8ac4c37e56e073c51a3ad/MapsModule.apk is already optimized. Bailing.
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/FileApkUtils( 2053): Keeping up-to-date module: module-e5b9d8f8da13e4c453d8ac4c37e56e073c51a3ad
,D/TimaKeyStoreProvider( 4070): TimaSignature is unavailable
,D/ActivityThread( 4070): Added TimaKeyStore provider
,W/InstanceID/Rpc( 2053): Found 10011
,W/ResourcesManager( 4050): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 4050): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4050): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/GmsModuleFndr( 2053): Beginning GMS chimera module scan
W/ResourcesManager( 4050): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4050): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4050): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/libprocessgroup( 1018): failed to open /acct/uid_10146/pid_3226/cgroup.procs: No such file or directory
,W/ResourcesManager( 4050): Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
W/ResourcesManager( 4050): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,D/StatusChecker( 4070): onReceive : android.intent.action.BOOT_COMPLETED
,I/StatusChecker( 4070): onReceive : net.mt.init : DONE
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4089): MountEmulatedStorage()
,I/libpersona( 4089): KNOX_SDCARD checking this for 10113
E/Zygote  ( 4089): v2
I/libpersona( 4089): KNOX_SDCARD not a persona
,I/SELinux ( 4089): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4089): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
I/ActivityManager( 1018): Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4089 uid=10113 gids={50113, 9997} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 3243:com.policydm/1000 (adj 15): empty #31,
,E/SELinux ( 4089): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,D/GmsModuleFndr( 2053): Module pkg com.google.android.apps.kids.kidsetup not installed, skipping
D/ChimeraCfgMgr( 2053): Beginning module configuration check
D/ChimeraCfgMgr( 2053): Module APKs unchanged, check complete
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4089): TimaSignature is unavailable
,D/ActivityThread( 4089): Added TimaKeyStore provider
,I/PageBuddyNotiSvc( 4089): Intent received : action=android.intent.action.BOOT_COMPLETED
,W/ContextImpl( 4089): Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,I/PageBuddyNotiSvc( 4089): onCreate mCpBitFlag=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4106): MountEmulatedStorage(),
E/Zygote  ( 4106): v2
I/libpersona( 4106): KNOX_SDCARD checking this for 10121
I/libpersona( 4106): KNOX_SDCARD not a persona,
I/SELinux ( 4106): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4106): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4106): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4106 uid=10121 gids={50121, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     (  305): Explicit concurrent mark sweep GC freed 8742(372KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 606us total 27.639ms
,D/TimaKeyStoreProvider( 4106): TimaSignature is unavailable
,D/ActivityThread( 4106): Added TimaKeyStore provider
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 666us total 30.314ms
,W/ResourcesManager( 4106): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4106): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4106): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3950): getResourcePackageName:assistantlist
I/AMMetaDataParserService( 3950): Resource data:2131165186
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 603us total 19.341ms
,W/ResourcesManager( 3950): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 3950): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3950): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,W/ResourcesManager( 3950): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3243/cgroup.procs: No such file or directory
,D/GCM     ( 2053): COMPAT: Multi user not supported
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3950): getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
,I/AMMetaDataParserService( 3950): getResourceTypeNamexml
,D/GCM     ( 1627): COMPAT: Multi user not supported
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/CheckinService( 2053): Checkin interval check for package: unspecified last checkin: 1447837957170 min interval config: 0 actual interval: 182252438,
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PowerManagerService( 1018): [api] release WakeLock flags=0x10000006 tag=PowerUI.Notification uid=10049 pid=1177 (0x0)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3950): Icon data: ResourceEnter URL2131755287android.intent.action.doInputURL2130837509
,I/GCoreUlr( 2053): Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/CheckinService( 2053): Disabling old GoogleServicesFramework version
,I/AMMetaDataParserService( 3950): Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/QuickConnect( 4106): PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,I/GCoreUlr( 1798): DispatchingService.onCreate()
,D/SettingsProvider( 1018): name = scon_is_running
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10121
,D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,I/System.out( 3902): INFO:Resource not found:/Common.properties Using default values
,I/AMMetaDataParserService( 3950): Icon data: ResourceNew Tab2131755457android.intent.action.doNewWindow2130837510
,W/BackupManagerService( 1018): dataChanged but no participant pkg='com.android.providers.settings' uid=10121
,D/QuickConnect( 4106): Utils.setQCRunningSetting - set : 0
,I/QuickConnect( 4106): PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
,I/SecKeyguardClockSingleView( 1177): Ignore. Because it is same clock text
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SystemUpdateService( 2053): onCreate
,I/QuickConnect( 4106): PeriphStartReceiver.onReceive - no need to start
,I/Icing   ( 2053): updateResources: need to parse f{com.google.android.gms}
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4143): MountEmulatedStorage()
E/Zygote  ( 4143): v2
I/libpersona( 4143): KNOX_SDCARD checking this for 10127
I/libpersona( 4143): KNOX_SDCARD not a persona
,I/SELinux ( 4143): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4143): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2,
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
,I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
,I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.SelectBookmarkFolderActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
E/SELinux ( 4143): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4143 uid=10127 gids={50127, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 2688:com.google.android.apps.docs/u0a87 (adj 15): empty #31
,D/SystemUpdateService( 2053): onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
W/ContextImpl( 3950): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,V/AuthZen ( 2053): Handling intent: android.intent.action.BOOT_COMPLETED
,D/AuthZenEventHandler( 2053): Handling event: android.intent.action.BOOT_COMPLETED
,D/TimaKeyStoreProvider( 4143): TimaSignature is unavailable
,D/ActivityThread( 4143): Added TimaKeyStore provider
,I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:assistant
I/AMMetaDataParserService( 3950): Resource data:2131034113
,D/GCM     ( 1627): GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 10011
,I/DBG_DM  ( 3179): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,W/ResourcesManager( 3950): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3950): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3950): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3950): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3950): getResourceTypeNamexml
,E/        ( 3950): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,W/libprocessgroup( 1018): failed to open /acct/uid_10087/pid_2688/cgroup.procs: No such file or directory
,I/GFX construct_block_size_descriptor_2d second part( 3950): took 2.475416ms for 0*0 texture 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/art     ( 1798): Explicit concurrent mark sweep GC freed 28272(1895KB) AllocSpace objects, 17(272KB) LOS objects, 39% free, 7MB/12MB, paused 1.015ms total 69.454ms
,I/GFX generate_partition_tables( 3950): took 6.527135ms for 0*0 texture 0
,I/GFX raster( 3950): took 10.210312ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3950): Bitmap=0xb81ce978 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb81ce6c0 counterpartCT=4 counterpartW=96 counterparth=96
,I/CheckinService( 2053): Checking schedule, now: 1448020209962 next: 1448404884068
,I/AMMetaDataParserService( 3950): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,W/ResourcesManager( 4143): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
W/ResourcesManager( 4143): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4143): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 4143): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
I/CheckinService( 2053): active receiver: disabled
E/        ( 3950): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3950): took 0.809427ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3950): Bitmap=0xb81ce978 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb81dc618 counterpartCT=4 counterpartW=96 counterparth=96
W/BaseAppContext( 2053): Using Auth Proxy for data requests.
,I/AMMetaDataParserService( 3950): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,I/art     ( 2053): Background partial concurrent mark sweep GC freed 13150(978KB) AllocSpace objects, 13(208KB) LOS objects, 40% free, 8MB/13MB, paused 4.739ms total 101.338ms
,I/GCM     ( 1627): GCM config loaded
,I/SystemUpdateService( 2053): cancelUpdate (empty URL)
I/SystemUpdateService( 2053): active receiver: disabled
,I/Process ( 4050): Sending signal. PID: 4050 SIG: 9
,D/SBrowserFeatureFlag( 4143): initialized in static block : loadCscFeatureValue() succeed! 
,E/        ( 3950): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX construct_block_size_descriptor_2d second part( 3950): took 2.745627ms for 0*0 texture 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/GFX generate_partition_tables( 3950): took 7.686824ms for 0*0 texture 0
,I/GFX raster( 3950): took 11.556826ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3950): Bitmap=0xb81dc248 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb81dc3a0 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3950): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
D/ManifestProvider( 4143): onCreate()
,E/        ( 3950): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3950): took 0.613959ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3950): Bitmap=0xb8388dc0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8388e88 counterpartCT=4 counterpartW=96 counterparth=96
,I/ActivityManager( 1018): Process com.sec.android.app.sns3 (pid 4050)(adj 0) has died(25,664)
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/NetworkSettingsReceiver( 4143): onReceive: android.intent.action.BOOT_COMPLETED
,I/AMMetaDataParserService( 3950): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,E/Zygote  ( 4178): MountEmulatedStorage(),
I/libpersona( 4178): KNOX_SDCARD checking this for 10031
E/Zygote  ( 4178): v2
I/libpersona( 4178): KNOX_SDCARD not a persona
,I/SELinux ( 4178): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4178): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4178): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4178 uid=10031 gids={50031, 9997, 3003} abi=armeabi-v7a
,E/        ( 3950): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3950): took 0.806823ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3950): Bitmap=0xb81dc0a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb81ce6c0 counterpartCT=4 counterpartW=96 counterparth=96
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 3950): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4178): TimaSignature is unavailable
,D/ActivityThread( 4178): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.gms
,I/GAV2    ( 3343): Thread[GAThread,5,main]: No campaign data found.
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 
D/ChimeraCfgMgr( 2053): Loading module com.google.android.gms.kids from APK com.google.android.gms
,W/System.err( 4143): java.lang.NoSuchMethodException: isEnabled []
,W/System.err( 4143): 	at java.lang.Class.getMethod(Class.java:665)
W/System.err( 4143): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.isCLipboardExsupported(SBrowserFeatureFlag.java:1217)
W/System.err( 4143): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initSupportedPkg(SBrowserFeatureFlag.java:1197)
W/System.err( 4143): 	at com.sec.android.app.sbrowser.common.SBrowserFeatureFlag.initialize(SBrowserFeatureFlag.java:1114)
I/art     ( 1627): Explicit concurrent mark sweep GC freed 8570(487KB) AllocSpace objects, 6(96KB) LOS objects, 39% free, 7MB/12MB, paused 1.168ms total 90.347ms
W/System.err( 4143): 	at com.sec.android.app.sbrowser.preferences.SbrowserSettings.<init>(SbrowserSettings.java:221)
W/System.err( 4143): 	at com.sec.android.app.sbrowser.common.SBrowserMobileApplication.getSetting(SBrowserMobileApplication.java:111)
W/System.err( 4143): 	at com.sec.android.app.sbrowser.net.NetworkSettingsReceiver.onReceive(NetworkSettingsReceiver.java:48)
W/System.err( 4143): 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
W/System.err( 4143): 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
W/System.err( 4143): 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
W/System.err( 4143): 	at android.os.Handler.dispatchMessage(Handler.java:102)
W/System.err( 4143): 	at android.os.Looper.loop(Looper.java:145)
W/System.err( 4143): 	at android.app.ActivityThread.main(ActivityThread.java:6145)
W/System.err( 4143): 	at java.lang.reflect.Method.invoke(Native Method)
W/System.err( 4143): 	at java.lang.reflect.Method.invoke(Method.java:372)
W/System.err( 4143): 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
W/System.err( 4143): 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,E/SBrowserFeatureFlag( 4143): initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@30a3fda
,W/ResourcesManager( 3982): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,E/SMD     (  289): DCD OFF
,E/        ( 3950): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3950): took 0.641406ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3950): Bitmap=0xb81da948 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb81daa30 counterpartCT=4 counterpartW=96 counterparth=96
,D/SBrowserFeatureFlag( 4143): initialize : initSupportedPkg() succeed! 
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/VerificationLog( 4143): SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,I/AMMetaDataParserService( 3950): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,D/PCWCLIENTTRACE_AccountAppFacade2_0( 3456): unregister AuthInfo UpdateReceiver v2.0
,I/AuthZen ( 2053): Fetching signing key...
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,I/AuthZen ( 2053): Signing key fetched successfully!
,E/Zygote  ( 4206): MountEmulatedStorage()
E/Zygote  ( 4206): v2
I/libpersona( 4206): KNOX_SDCARD checking this for 10131
I/libpersona( 4206): KNOX_SDCARD not a persona
,I/SELinux ( 4206): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4206 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,I/ActivityManager( 1018): Killing 3323:com.sec.esdk.elm/u0a90 (adj 15): empty #31
,I/SELinux ( 4206): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
E/SELinux ( 4206): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ResourcesManager( 3982): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3982): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3982): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,W/BaseAppContext( 2053): Using Auth Proxy for data requests.
,E/        ( 3950): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/SSRM:n  ( 1018): SIOP:: AP = 420
,I/GFX raster( 3950): took 0.750781ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3950): Bitmap=0xb853b6a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb853b750 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4216): MountEmulatedStorage()
I/ActivityManager( 1018): Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4216 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
E/Zygote  ( 4216): v2
I/ActivityManager( 1018): Killing 3390:com.fmm.dm/1000 (adj 15): empty #31
I/libpersona( 4216): KNOX_SDCARD checking this for 1000
I/SELinux ( 4216): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/libpersona( 4216): KNOX_SDCARD not a persona
,D/TimaKeyStoreProvider( 4206): TimaSignature is unavailable
D/ActivityThread( 4206): Added TimaKeyStore provider
,I/SELinux ( 4216): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4216): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/GCoreUlr( 1798): WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED,
,I/AMMetaDataParserService( 3950): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534,
D/a       ( 2053): Opening database auth.proximity.permit_store...
D/AuthZenTransactionCache( 2053): Initialized cache in: /data/data/com.google.android.gms/files
D/AuthZenTransactionCache( 2053): Clearing transaction cache
,D/TimaKeyStoreProvider( 4216): TimaSignature is unavailable,
D/ActivityThread( 4216): Added TimaKeyStore provider
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ResourcesManager( 4206): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4206): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,W/ResourcesManager( 4206): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,D/ChimeraCfgMgr( 2053): Loading module com.google.android.gms.kids from APK com.google.android.gms
,D/SystemUpdateService( 2053): onDestroy
,E/        ( 3950): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3950): took 0.538229ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3950): Bitmap=0xb7f55c78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb81b2150 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3950): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,V/GLSActivity( 1627): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/GCoreFlp( 1798): No location to return for getLastLocation()
,W/FusedLocationProvider( 2053): location=null
,I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:assistant
I/AMMetaDataParserService( 3950): Resource data:2131034113
,I/AMMetaDataParserService( 3950): getResourceName:com.android.contacts:xml/assistant_main
I/AMMetaDataParserService( 3950): getResourceTypeNamexml
,E/        ( 3950): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3950): took 0.815469ms for 96*96 texture 0,
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3950): Bitmap=0xb81bcd38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb81bc1b8 counterpartCT=4 counterpartW=96 counterparth=96
,W/Kids    ( 2053): [AbstractKidsOperation] Invalid device state 3
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3950): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,V/GLSActivity( 1627): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DBG_POLICYDM( 4216): [com.policydm.XDMApplication(554/xdmWakeLockAcquire)] 
,V/GLSActivity( 1627): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,I/DBG_POLICYDM( 4216): [com.policydm.XDMApplication(559/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,I/DBG_POLICYDM( 4216): [com.policydm.eng.core.XDMMsg(70/xdmSendMessage)] waiting for DM_TaskHandler create
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/GCoreFlp( 1798): No location to return for getLastLocation()
,W/FusedLocationProvider( 2053): location=null
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/daemonapp( 1752): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,W/Auth    ( 1627): [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,E/        ( 3950): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 34061(1996KB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 22MB/34MB, paused 2.801ms total 190.865ms
,I/GFX raster( 3950): took 0.890625ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3950): Bitmap=0xb81bcd38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb81b2150 counterpartCT=4 counterpartW=96 counterparth=96
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
V/GLSActivity( 1627): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3950): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,E/Zygote  ( 4254): MountEmulatedStorage(),
E/Zygote  ( 4254): v2
I/libpersona( 4254): KNOX_SDCARD checking this for 10037
I/libpersona( 4254): KNOX_SDCARD not a persona
,I/SELinux ( 4254): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=4254 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
,I/SELinux ( 4254): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,E/SELinux ( 4254): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,E/        ( 3950): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/GFX raster( 3950): took 0.606823ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3950): Bitmap=0xb81bc1b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb81b2150 counterpartCT=4 counterpartW=96 counterparth=96
,V/GLSActivity( 1627): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3950): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,D/TimaKeyStoreProvider( 4254): TimaSignature is unavailable
,D/ActivityThread( 4254): Added TimaKeyStore provider
,E/Zygote  ( 4271): MountEmulatedStorage()
E/Zygote  ( 4271): v2
I/libpersona( 4271): KNOX_SDCARD checking this for 10135
I/libpersona( 4271): KNOX_SDCARD not a persona
,I/SELinux ( 4271): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4271): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4271): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/ActivityManager( 1018): Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4271 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
,V/GmsCoreStatsServiceLauncher( 2053): Received broadcast intent Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher (has extras) }
,V/GLSActivity( 1627): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3390/cgroup.procs: No such file or directory
W/libprocessgroup( 1018): failed to open /acct/uid_10090/pid_3323/cgroup.procs: No such file or directory
,W/ResourcesManager( 4254): Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4271): TimaSignature is unavailable
,D/ActivityThread( 4271): Added TimaKeyStore provider
,I/Icing   ( 2053): Internal init done: storage state 0
,W/ResourcesManager( 4271): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,W/ResourcesManager( 4271): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 4271): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 4271): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 4271): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/PersistentNotificationBroadcastReceiver( 1627): Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,I/Icing   ( 2053): Post-init done
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/CalendarProvider2( 4254): CalendarProvider2.onCreate() called
,I/DBG_DM  ( 3179): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,I/ActivityManager( 1018): Killing 3413:com.sec.factory.camera/1000 (adj 15): empty #31
,E/        ( 3950): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3950): took 0.753802ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3950): Bitmap=0xb81b2150 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb81d4f48 counterpartCT=4 counterpartW=96 counterparth=96
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3950): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,E/Zygote  ( 4290): MountEmulatedStorage()
I/libpersona( 4290): KNOX_SDCARD checking this for 10141
E/Zygote  ( 4290): v2
I/libpersona( 4290): KNOX_SDCARD not a persona
,E/        ( 3950): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
I/SELinux ( 4290): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/GFX raster( 3950): took 0.850208ms for 96*96 texture 0
I/ActivityManager( 1018): Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4290 uid=10141 gids={50141, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3950): Bitmap=0xb81d4f48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb81d52c8 counterpartCT=4 counterpartW=96 counterparth=96
,I/SELinux ( 4290): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4290): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 3950): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3413/cgroup.procs: No such file or directory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/TimaKeyStoreProvider( 4290): TimaSignature is unavailable
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/ActivityThread( 4290): Added TimaKeyStore provider
,W/ResourcesManager( 4290): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,W/ResourcesManager( 4290): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 4290): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 4290): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/        ( 3950): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3950): took 0.640208ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3950): Bitmap=0xb81da948 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb81b4e10 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3950): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/        ( 3950): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3950): took 0.788228ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3950): Bitmap=0xb853b6a8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb81dc080 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3950): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,E/        ( 3950): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3950): took 0.539010ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3950): Bitmap=0xb7f55c78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb81daaa0 counterpartCT=4 counterpartW=96 counterparth=96
D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3950): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,I/AMMetaDataParserService( 3950): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
,I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
,I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.contacts.ContactShortcut
I/AMMetaDataParserService( 3950): Resource data:Loop for running activityalias.DialShortcut
I/AMMetaDataParserService( 3950): Resource data:Loop for running activityalias.MessageShortcut
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3950): getResourcePackageName:assistant
I/AMMetaDataParserService( 3950): Resource data:2131034112
,I/AMMetaDataParserService( 3950): getResourceName:com.android.contacts:xml/assistant_detail
I/AMMetaDataParserService( 3950): getResourceTypeNamexml
,E/        ( 3950): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,I/GFX raster( 3950): took 0.634479ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3950): Bitmap=0xb81b2150 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8389740 counterpartCT=4 counterpartW=96 counterparth=96
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3950): Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,I/DBG_POLICYDM( 4216): [com.policydm.adapter.XDMTargetAdapter(191/xdmInitExternalStorageState)] 
,I/DBG_POLICYDM( 4216): [com.policydm.agent.XDMTask(163/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,I/DBG_POLICYDM( 4216): [com.policydm.agent.XDMAgent(156/xdmAgentSetSyncMode)] nSync = 0
,I/DBG_POLICYDM( 4216): [com.policydm.adapter.XDMTargetAdapter(390/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,I/GCoreUlr( 1798): WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,I/DBG_POLICYDM( 4216): [com.policydm.adapter.XDMTargetAdapter(248/xdmInitExternalStorageState)] DATA_DIR_PATH [/data]
,I/DBG_POLICYDM( 4216): [com.policydm.adapter.XDMTargetAdapter(249/xdmInitExternalStorageState)] EXTERNAL_DIR_PATH [/storage/emulated/0]
,E/        ( 3950): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/DBG_POLICYDM( 4216): [com.policydm.adapter.XDMTargetAdapter(250/xdmInitExternalStorageState)] EXTERNAL_SD_DIR_PATH [/storage/extSdCard]
I/GFX raster( 3950): took 0.655520ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3950): Bitmap=0xb81b2150 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8389740 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_POLICYDM( 4216): [com.policydm.adapter.XDMTargetAdapter(251/xdmInitExternalStorageState)] POLICY_DIR_PATH [/data/data/com.policydm/cache]
,I/DBG_POLICYDM( 4216): [com.policydm.adapter.XDMTargetAdapter(253/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,I/GCoreUlr( 1798): Unbound from all location providers
,I/AMMetaDataParserService( 3950): Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,I/DBG_POLICYDM( 4216): [com.policydm.adapter.XDMTargetAdapter(254/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,I/DBG_POLICYDM( 4216): [com.policydm.XDMApplication(580/xdmWakeLockRelease)] 
,I/DBG_POLICYDM( 4216): [com.policydm.XDMApplication(585/xdmWakeLockRelease)] m_WakeLock is release!!
,I/DBG_POLICYDM( 4216): [com.policydm.XDMApplication(179/onCreate)] DMApplication Start !
,I/DBG_POLICYDM( 4216): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.intent.action.BOOT_COMPLETED
,E/        ( 3950): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3950): took 0.646458ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3950): Bitmap=0xb8389740 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb81da640 counterpartCT=4 counterpartW=96 counterparth=96
,I/DBG_POLICYDM( 4216): [com.policydm.db.XDB(2211/xdbIsAlreadyAgree)] bAgree : true
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/AMMetaDataParserService( 3950): Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,I/DBG_POLICYDM( 4216): [com.policydm.db.XDB(1531/xdbDMffs_Init)] xdbDMffs_Init
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/        ( 3950): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3950): took 0.675105ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3950): Bitmap=0xb81da948 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb81dc080 counterpartCT=4 counterpartW=96 counterparth=96
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,I/AMMetaDataParserService( 3950): Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,E/Zygote  ( 4316): MountEmulatedStorage()
I/libpersona( 4316): KNOX_SDCARD checking this for 10032
E/Zygote  ( 4316): v2
I/libpersona( 4316): KNOX_SDCARD not a persona
,I/SELinux ( 4316): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity,
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity,
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
,I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity,
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.emergency.InteractionEmergencyMessageActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity,
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
,I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:assistant
I/AMMetaDataParserService( 3950): Resource data:2131034113
I/SELinux ( 4316): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/AMMetaDataParserService( 3950): getResourceName:com.android.contacts:xml/assistant_main,
,I/AMMetaDataParserService( 3950): getResourceTypeNamexml
E/        ( 3950): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
E/SELinux ( 4316): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/GFX raster( 3950): took 0.828698ms for 96*96 texture 0,
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3950): Bitmap=0xb81bcd38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb81de828 counterpartCT=4 counterpartW=96 counterparth=96,
,I/ActivityManager( 1018): Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4316 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/AMMetaDataParserService( 3950): Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,I/ActivityManager( 1018): Killing 3438:com.samsung.android.provider.filterprovider/u0a95 (adj 15): empty #31
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/        ( 3950): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3950): took 0.821094ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3950): Bitmap=0xb81bcd38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb81c7258 counterpartCT=4 counterpartW=96 counterparth=96
,D/TimaKeyStoreProvider( 4316): TimaSignature is unavailable
,D/ActivityThread( 4316): Added TimaKeyStore provider
,I/ActivityManager( 1018): Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4330 uid=10068 gids={50068, 9997} abi=armeabi-v7a,
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,E/Zygote  ( 4330): MountEmulatedStorage()
E/Zygote  ( 4330): v2
I/libpersona( 4330): KNOX_SDCARD checking this for 10068
I/libpersona( 4330): KNOX_SDCARD not a persona
,I/SELinux ( 4330): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4330): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4330): [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,I/AMMetaDataParserService( 3950): Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/TimaKeyStoreProvider( 4330): TimaSignature is unavailable
,D/ActivityThread( 4330): Added TimaKeyStore provider
,E/        ( 3950): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3950): took 0.641666ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3950): Bitmap=0xb81bc1b8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb81de828 counterpartCT=4 counterpartW=96 counterparth=96
,E/Zygote  ( 4351): MountEmulatedStorage(),
E/Zygote  ( 4351): v2
I/libpersona( 4351): KNOX_SDCARD checking this for 10142,
I/libpersona( 4351): KNOX_SDCARD not a persona
,I/DBG_POLICYDM( 4216): [com.policydm.agent.XDMTask(171/xdmAgentTaskHandler)] XEVENT_DM_INIT
,I/SELinux ( 4351): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/DBG_POLICYDM( 4216): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/ActivityManager( 1018): Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4351 uid=10142 gids={50142, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,I/SELinux ( 4351): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
,E/SELinux ( 4351): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,I/DBG_POLICYDM( 4216): [com.policydm.XDMApplication(619/xdmGetNotibarState)] get NotibarState : 7
,I/DBG_POLICYDM( 4216): [com.policydm.ui.XUINotificationManager(48/xuiSetIndicator)] Indicator id : 7
,I/AMMetaDataParserService( 3950): Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,W/libprocessgroup( 1018): failed to open /acct/uid_10095/pid_3438/cgroup.procs: No such file or directory
,I/DBG_POLICYDM( 4216): [com.policydm.XDMApplication(611/xdmSetNotibarState)] set NotibarState : 7
I/GCoreUlr( 1798): DispatchingService.onDestroy()
I/GCoreUlr( 1798): Stopping handler for UlrDispSvcFast
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,I/ActivityManager( 1018): Killing 3529:com.samsung.android.intelligenceservice/u0a55 (adj 15): empty #31
,I/ActivityManager( 1018): Killing 3490:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #32
,D/TimaKeyStoreProvider( 4351): TimaSignature is unavailable
,D/ActivityThread( 4351): Added TimaKeyStore provider
,I/GCoreUlr( 1798): Unbound from all location providers
,I/DBG_POLICYDM( 4216): [com.policydm.db.XDBAESCrypt(217/xdbGetCryptionkey)] try read dbString
,W/ResourcesManager( 4351): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,D/BadgeProvider( 4330): onCreate,
D/BadgeProvider( 4330): DatabaseHelper
,I/DBG_POLICYDM( 4216): [com.policydm.db.XDBFumoAdp(428/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,I/DBG_POLICYDM( 4216): [com.policydm.db.XDBFumoAdp(587/xdbGetFUMOInitiatedType)] Initiated Type: 0
,I/DBG_POLICYDM( 4216): [com.policydm.polling.XPollingAgent(72/xpollingCheckVersionInfo)] 
I/DBG_POLICYDM( 4216): [com.policydm.agent.XDMUITask(191/xdmUIEvent)] XUI_DM_IDLE_STATE :true
,D/BadgeProvider( 4330): query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,I/DBG_POLICYDM( 4216): [com.policydm.polling.XPollingAgent(271/xpollingCheckTimer)] 
,I/DBG_POLICYDM( 4216): [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,I/DBG_POLICYDM( 4216): [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] savedpollingtime : 2015/11/25/15:58:24
,I/DBG_POLICYDM( 4216): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 4216): [com.policydm.polling.XPollingAgent(286/xpollingCheckTimer)] currentTime : 2015/11/20/12:50:11
I/DBG_POLICYDM( 4216): [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,I/DBG_POLICYDM( 4216): [com.policydm.polling.XPollingAgent(290/xpollingCheckTimer)] Restart Timer..
,I/DBG_POLICYDM( 4216): [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,I/DBG_POLICYDM( 4216): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 0
,I/DBG_POLICYDM( 4216): [com.policydm.noti.XNOTIAdapter(401/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,I/DBG_POLICYDM( 4216): [com.policydm.noti.XNOTIAdapter(441/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
I/DBG_POLICYDM( 4216): [com.policydm.noti.XNOTIAdapter(267/xnotiPushAdpClearSessionStatus)] 
I/DBG_POLICYDM( 4216): [com.policydm.ui.XUIAdapter(39/xuiAdpSetUiMode)] nDmUiMode : 0
,I/DBG_POLICYDM( 4216): [com.policydm.db.XDBFumoAdp(439/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,D/BadgeProvider( 4330): sendNotify entered. [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4330): sendNotify, [notify] : null
D/BadgeProvider( 4330): update, [uri] : content://com.sec.badge/apps/1
D/BadgeProvider( 4330): update, [BadgeCount] : badgecount=0
D/BadgeProvider( 4330): update, [UpdateCount] : 1
,D/Launcher.Model( 1480): reloadBadges entered.
,W/libprocessgroup( 1018): failed to open /acct/uid_10055/pid_3529/cgroup.procs: No such file or directory
,W/libprocessgroup( 1018): failed to open /acct/uid_10098/pid_3490/cgroup.procs: No such file or directory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,I/GAV2    ( 3514): Thread[GAThread,5,main]: No campaign data found.
,I/DBG_POLICYDM( 4216): [com.policydm.db.XDBFumoAdp(565/xdbSetFUMOInitiatedType)] Initiated Type: 0
,W/ActivityManager( 1018): getTasks: caller 10141 does not hold GET_TASKS; limiting output
,I/Process ( 4290): Sending signal. PID: 4290 SIG: 9
,D/RCPManagerService( 1018): exchangeData() failure , invalid userId
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4376): MountEmulatedStorage(),
E/Zygote  ( 4376): v2
I/ActivityManager( 1018): Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4376 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,I/libpersona( 4376): KNOX_SDCARD checking this for 1000
I/libpersona( 4376): KNOX_SDCARD not a persona
,I/SELinux ( 4376): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 4376): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4376): [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
E/lowmemorykiller(  255): Error writing /proc/4290/oom_score_adj; errno=22
,I/ActivityManager( 1018): Killing 3547:com.fmm.ds/1000 (adj 15): empty #31
,E/JavaBinder( 4351): !!! FAILED BINDER TRANSACTION !!!
,E/lowmemorykiller(  255): Error writing /proc/4290/oom_score_adj; errno=22
,I/art     (  305): Explicit concurrent mark sweep GC freed 8724(371KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 606us total 24.865ms
,D/TimaKeyStoreProvider( 4376): TimaSignature is unavailable
,D/ActivityThread( 4376): Added TimaKeyStore provider
,E/lowmemorykiller(  255): Error writing /proc/4290/oom_score_adj; errno=22
,W/ActivityManager( 1018): getTasks: caller 10142 does not hold GET_TASKS; limiting output
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 592us total 16.801ms
,E/        ( 3950): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3950): took 1.933229ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3950): Bitmap=0xb81b2150 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb81dc030 counterpartCT=4 counterpartW=96 counterparth=96
I/Process ( 4351): Sending signal. PID: 4351 SIG: 9
,I/AMMetaDataParserService( 3950): Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,I/art     (  305): Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 621us total 17.635ms
,I/DBG_POLICYDM( 4216): [com.policydm.db.XDB(1825/xdbSetBackUpServerUrl)] 
,I/ActivityManager( 1018): Process com.android.email (pid 4290)(adj 11) has died(35,646)
,E/        ( 3950): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3950): took 0.824219ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3950): Bitmap=0xb81d4f48 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb81dc030 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3950): Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3547/cgroup.procs: No such file or directory
,I/ActivityManager( 1018): Process com.android.exchange (pid 4351)(adj 9) has died(35,646)
,E/        ( 3950): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3950): took 0.742292ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3950): Bitmap=0xb81dab50 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb81c7220 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3950): Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,E/        ( 3950): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3950): took 0.703021ms for 96*96 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3950): Bitmap=0xb7f55c78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb81dc030 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3950): Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,E/        ( 3950): GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,I/GFX raster( 3950): took 0.691146ms for 96*96 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3950): Bitmap=0xb81bcd38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb81c7220 counterpartCT=4 counterpartW=96 counterparth=96
,I/AMMetaDataParserService( 3950): Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,E/SPPClientService( 4316): ============PushLog. commonIsShipBuild. stop!
,E/SPPClientService( 4316): [PushClientApplication] Push log off : This is Ship build version
,E/SPPClientService( 4316): [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,I/DBG_POLICYDM( 4216): [com.policydm.polling.XPollingAgent(312/xPollingReportReStartAlarm)] 
,D/SPPClientService( 4316): PushLog.txt file is not deleted.
D/SPPClientService( 4316): PushLog.txt file is not deleted.
D/SPPClientService( 4316): ============PushLog. stop!
,I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
W/ContextImpl( 3950): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
,I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
,I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
,I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.Welcome
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.DataConnection
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.Debug
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.MessageListXL
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:assistant
I/AMMetaDataParserService( 3950): Resource data:2131165203
,E/Zygote  ( 4395): MountEmulatedStorage()
E/Zygote  ( 4395): v2
,I/libpersona( 4395): KNOX_SDCARD checking this for 10036
I/libpersona( 4395): KNOX_SDCARD not a persona
,I/SELinux ( 4395): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4395 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 3562:com.samsung.android.scloud.backup/u0a56 (adj 15): empty #31
I/SELinux ( 4395): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/DBG_POLICYDM( 4216): [com.policydm.XDMApplication(626/xdmStartAlarm)] Alarm ID: 1
,E/SELinux ( 4395): [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
W/ResourcesManager( 3950): Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3950): getResourceName:com.android.email:xml/email_assistant_menu
W/ResourcesManager( 3950): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3950): getResourceTypeNamexml
,W/ResourcesManager( 3950): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
W/ResourcesManager( 3950): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,E/        ( 3950): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX construct_block_size_descriptor_2d second part( 3950): took 3.781146ms for 0*0 texture 0
I/DBG_POLICYDM( 4216): [com.policydm.agent.XDMTask(203/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,I/DBG_POLICYDM( 4216): [com.policydm.db.XDBProfileAdp(207/xdbSetChangedProtocol)] xdbSetChangedProtocol : false
,D/TimaKeyStoreProvider( 4395): TimaSignature is unavailable
,D/ActivityThread( 4395): Added TimaKeyStore provider
,I/GFX generate_partition_tables( 3950): took 17.218283ms for 0*0 texture 0
,I/GFX raster( 3950): took 21.580054ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3950): Bitmap=0xb81dc098 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b7, Counterpart=0xb81b2118 counterpartCT=4 counterpartW=80 counterparth=80
,V/AlarmManager( 1018): waitForAlarm result :8
,I/DBG_POLICYDM( 4216): [com.policydm.db.XDBProfileListAdp(258/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,I/DBG_POLICYDM( 4216): [com.policydm.db.XDBNotiAdp(38/xdbNotiExistInfo)] Noti Exist : false
,I/AMMetaDataParserService( 3950): Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,W/libprocessgroup( 1018): failed to open /acct/uid_10056/pid_3562/cgroup.procs: No such file or directory
,E/        ( 3950): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX construct_block_size_descriptor_2d second part( 3950): took 2.237708ms for 0*0 texture 0
,I/GFX generate_partition_tables( 3950): took 5.195990ms for 0*0 texture 0
,I/GFX raster( 3950): took 8.479533ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3950): Bitmap=0xb81b2118 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb7df6b30 counterpartCT=4 counterpartW=80 counterparth=80
,I/AMMetaDataParserService( 3950): Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,I/SA      ( 4395): [SSP] onCreated
,E/        ( 3950): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 3950): took 0.697916ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3950): Bitmap=0xb81b2118 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb81bb420 counterpartCT=4 counterpartW=80 counterparth=80
,I/AMMetaDataParserService( 3950): Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,E/        ( 3950): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
I/GFX raster( 3950): took 0.699738ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3950): Bitmap=0xb81b2118 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb81bb420 counterpartCT=4 counterpartW=80 counterparth=80
I/AMMetaDataParserService( 3950): Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
I/DBG_DM  ( 3179): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,I/SA      ( 4395): [TPM] There is no property file
,I/SA      ( 4395): [SCU] isHaveSA() - false
,I/SA      ( 4395): [TPM] getModelProperty : null
,I/SA      ( 4395): [TPM] getCSCProperty : null
,I/SA      ( 4395): [DM] FLOATING AMOLED FEATURE: true
,E/        ( 3950): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
I/SA      ( 4395): [DM] PRODUCT AMOLED FEATURE: false
I/SA      ( 4395): [DM] TFT FEATURE: false
I/GFX raster( 3950): took 0.624896ms for 80*80 texture 0
W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3950): Bitmap=0xb81bb420 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb7f47c08 counterpartCT=4 counterpartW=80 counterparth=80
,I/SA      ( 4395): [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
,I/SA      ( 4395): [DM] init START
,I/AMMetaDataParserService( 3950): Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,I/SA      ( 4395): [DM] This device is not a Vodafone
,E/        ( 3950): GFX convertToRaster() in Bitmap.cpp for bitmap size 80x80
,I/GFX raster( 3950): took 0.624427ms for 80*80 texture 0
,W/GFX DEBUGLOG GPUCompressionToBitmapDecoder( 3950): Bitmap=0xb81bb420 bitmapCt=12 bitmapW=80 bitmapH=80 BitmapInternalFormat=93b0, Counterpart=0xb7f47c08 counterpartCT=4 counterpartW=80 counterparth=80
,W/ResourceType( 4395): Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,W/ResourceType( 4395): Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,W/ResourceType( 4395): Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
W/ResourceType( 4395): Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,W/ResourceType( 4395): Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
W/ResourceType( 4395): Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,W/ResourceType( 4395): Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
,W/ResourceType( 4395): No package identifier when getting value for resource number 0x00000000
,I/AMMetaDataParserService( 3950): Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
W/ResourceType( 4395): Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,W/ResourceType( 4395): Failure getting entry for 0x7f060027 (t=5 e=39) (error -75)
,W/ResourceType( 4395): Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,W/ResourceType( 4395): Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
W/ResourceType( 4395): Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,W/ResourceType( 4395): Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
W/ResourceType( 4395): Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
,W/ResourceType( 4395): Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
W/ResourceType( 4395): Failure getting entry for 0x7f06002e (t=5 e=46) (error -75),
W/ResourceType( 4395): Failure getting entry for 0x7f06001d (t=5 e=29) (error -75)
,W/ResourceType( 4395): Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
W/ResourceType( 4395): Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,W/ResourceType( 4395): Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,W/ResourceType( 4395): Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
W/ResourceType( 4395): Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,W/ResourceType( 4395): Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
W/ResourceType( 4395): Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,W/ResourceType( 4395): Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,I/SA      ( 4395): [SCU] isHaveSA() - false
I/SA      ( 4395): support phone number id : false
I/SA      ( 4395): [DM] Supports Ref Jpn : true
,I/SA      ( 4395): [DM] init END
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.MessageCompose
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
W/ContextImpl( 3950): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.DebugActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.SearchActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3950): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,I/SA      ( 4395): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
I/SA      ( 4395): [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 1023, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,I/SA      ( 4395): [OR] onReceive END
,I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:android.app.spellscroll
I/AMMetaDataParserService( 3950): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3950): getResourcePackageName:assistant
I/AMMetaDataParserService( 3950): Resource data:2131099648
,I/SA      ( 4395): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,I/SA      ( 4395): [ODM] queryOpenData(key= GEO_IP )
,W/ResourcesManager( 3950): Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,W/ResourcesManager( 3950): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3950): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3950): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
W/ResourcesManager( 3950): Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3950): getResourceName:com.android.mms:xml/assistant_messaging
,I/AMMetaDataParserService( 3950): getResourceTypeNamexml
,I/SA      ( 4395): getMccForGalaxyJpn step2 GEO_IP MCC : 260
,I/SA      ( 4395): [LBE] REF_JPN : true
I/SA      ( 4395): [BDC] create
,I/splitIntent( 1018): Queue : background intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart  false.
,I/AMMetaDataParserService( 3950): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
,D/accuweather( 1701): [KK AccuPhone]>>> WCW:32 [0:0] action : widgetactionAPPWIDGET_UPDATE
,I/AMMetaDataParserService( 3950): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/daemonapp( 1752): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 2
,D/accuweather( 1701): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,I/SA      ( 4395): [DBMV2] getEmailID
,D/accuweather( 1701): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1701): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
,I/SA      ( 4395): [DBMV2] getDataV02ForItems
,I/SA      ( 4395): [SSP] query invoked
,D/accuweather( 1701): [KK AccuPhone]>>> WCW:42 [0:0] weather widget id size = 1
,D/accuweather( 1701): [KK AccuPhone]>>> UIM:312 [0:0]  action:widgetactionAPPWIDGET_UPDATE
D/accuweather( 1701): [KK AccuPhone]>>> UIM:158 [0:0] make widget 4x1 view!!! 
,D/accuweather( 1701): [KK AccuPhone]>>> UIM:160 [0:0] make widget 4x2 view!!! 
,I/SA      ( 4395): [SCU] get signed id from samsung account2.0 DB.
,D/daemonapp( 1752): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,I/AMMetaDataParserService( 3950): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,I/SA      ( 4395): [SCU] get signed id from samsung account1.0 DB.
,I/SA      ( 4395): [BDC] destroy
,I/ActivityManager( 1018): Killing 3637:com.samsung.android.scloud.sync/u0a58 (adj 15): empty #31
,D/daemonapp( 1752): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/daemonapp( 1752): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/AMMetaDataParserService( 3950): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/daemonapp( 1752): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1701): [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
,D/accuweather( 1701): [KK AccuPhone]>>> UIM:178 [0:0] get widget 4x1 view!!! wid = 2
,D/accuweather( 1701): [KK AccuPhone]>>> RU:73 [0:0] get ww = 341, wh = 60span x = 5, span y = 1
,D/accuweather( 1701): [KK AccuPhone]>>> UIM:964 [0:0]  cUI : cnt = 0
I/AMMetaDataParserService( 3950): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
D/accuweather( 1701): [KK AccuPhone]>>> UIM:983 [0:0]  composeEmptyCityUI : true
,E/accuweather( 1701): [KK AccuPhone]>>> UIM:1488 [0:0] bTM 12 50
,E/accuweather( 1701): [KK AccuPhone]>>> UIM:967 [0:0] ========>>> mRefreshManagerisRefreshCompleted() = true
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather
I/AMMetaDataParserService( 3950): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:assistant
I/AMMetaDataParserService( 3950): Resource data:2131099648
I/AMMetaDataParserService( 3950): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3950): getResourceTypeNamexml
,I/AMMetaDataParserService( 3950): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/AMMetaDataParserService( 3950): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/accuweather( 1701): [KK AccuPhone]>>> WC:30 [0:0] action : widgetactionAPPWIDGET_UPDATE
,D/accuweather( 1701): [KK AccuPhone]>>> WC:37 [0:0] oR : create UI manager : start
,D/accuweather( 1701): [KK AccuPhone]>>> UIMEM:89 [0:0] getInstance
,D/accuweather( 1701): [KK AccuPhone]>>> UIMEM:77 [0:0] UIManager : create ui manager
D/accuweather( 1701): [KK AccuPhone]>>> RM:73 [0:0] RefreshManager : create
D/accuweather( 1701): [KK AccuPhone]>>> RM:136 [0:0]  V init 
,D/daemonapp( 1752): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1701): [KK AccuPhone]>>> RM:128 [0:0] updateCityList
,D/daemonapp( 1752): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/accuweather( 1701): [KK AccuPhone]>>> DBH:3426 [0:0] gADWI : count = 0
,I/AMMetaDataParserService( 3950): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,D/daemonapp( 1752): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,D/accuweather( 1701): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/accuweather( 1701): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/BootupListener( 1449): intent.getAction() = android.intent.action.SERVICE_STATE
,D/SettingsProvider( 1018): name = internet_call_settings_visibility
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 1001
,D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,D/PhoneUtilsCommon( 1449): isSupportVoLTE is false.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
I/AMMetaDataParserService( 3950): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.sec.android.app.mt
,D/StatusChecker( 4070): onReceive : android.intent.action.SERVICE_STATE
,I/StatusChecker( 4070): onReceive : net.mt.init : DONE
,D/StatusChecker( 4070): Service state changed : 3 mSub-1
,I/AMMetaDataParserService( 3950): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.sec.android.widgetapp.ap.hero.accuweather, destAppInfo.processName = com.sec.android.daemonapp
,I/AMMetaDataParserService( 3950): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,D/daemonapp( 1752): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1752): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,D/daemonapp( 1752): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:assistant
I/AMMetaDataParserService( 3950): Resource data:2131099648
,I/AMMetaDataParserService( 3950): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3950): getResourceTypeNamexml
,D/daemonapp( 1752): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,I/AMMetaDataParserService( 3950): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,D/daemonapp( 1752): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,D/daemonapp( 1752): [MSC_Daemon]>>> WDSM:54 [0:0] Act : widgetappapaccuweatherdaemonactionCURRENT_LOCATION_WEATHER_DATA, run:true
,D/comsamsunglog( 1752): [MSC_Daemon]>>> ====================================================================================================================
,D/comsamsunglog( 1752): [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,D/comsamsunglog( 1752): [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
D/comsamsunglog( 1752): [MSC_Daemon]>>> ====================================================================================================================
D/daemonapp( 1752): [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,D/daemonapp( 1752): [MSC_Daemon]>>> WDSM:119 [0:0] start_app:true, packagename:widgetappapheroaccuweather, cp:Accuweather, aRS:false
,I/ActivityManager( 1018): Waited long enough for: ServiceRecord{208f1a4e u0 com.sec.android.daemonapp/.ap.accuweather.WeatherClockService}
,D/daemonapp( 1752): [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,D/daemonapp( 1752): [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,I/AMMetaDataParserService( 3950): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,D/daemonapp( 1752): [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,D/daemonapp( 1752): [MSC_Daemon]>>> WDSM:140 [0:0] Widget flag autoRefreshSet :  false
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
I/AMMetaDataParserService( 3950): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3950): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,I/AMMetaDataParserService( 3950): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3950): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
,I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:assistant
I/AMMetaDataParserService( 3950): Resource data:2131099648
,I/AMMetaDataParserService( 3950): getResourceName:com.android.mms:xml/assistant_messaging
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
I/AMMetaDataParserService( 3950): getResourceTypeNamexml
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3950): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3950): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/libprocessgroup( 1018): failed to open /acct/uid_10058/pid_3637/cgroup.procs: No such file or directory
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3950): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3950): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3950): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3950): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:assistant
I/AMMetaDataParserService( 3950): Resource data:2131099648
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,I/AMMetaDataParserService( 3950): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3950): getResourceTypeNamexml
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3950): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/splitIntent( 1018): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
I/splitIntent( 1018): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
I/splitIntent( 1018): other index=3, name=com.google.android.gms com.google.android.gms.photos.InitializePhotosIntentReceiver
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/CalendarProvider2( 4254): Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
I/AMMetaDataParserService( 3950): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 3950): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
I/ActivityManager( 1018): Killing 3265:com.sec.android.fotaclient/u0a8 (adj 15): empty #31
I/AMMetaDataParserService( 3950): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,E/MDM     ( 1798): [195] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null},
,I/AMMetaDataParserService( 3950): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,I/AMMetaDataParserService( 3950): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.ConversationList
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:assistant
I/AMMetaDataParserService( 3950): Resource data:2131099648
,I/AMMetaDataParserService( 3950): getResourceName:com.android.mms:xml/assistant_messaging
I/AMMetaDataParserService( 3950): getResourceTypeNamexml
,I/AMMetaDataParserService( 3950): Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,I/AMMetaDataParserService( 3950): Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,D/TP/SmsProvider( 1449): query,matched:0, calling pid = 2053
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 3950): Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
D/TP/SmsProvider( 1449): match 0:Elapsed time : 1.627 ms
,D/TP/MmsProvider( 1449): Query uri=content://mms, match=0, calling pid = 2053
,I/AMMetaDataParserService( 3950): Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,D/TP/SmsProvider( 1449): query,matched:0, calling pid = 2053
,D/TP/SmsProvider( 1449): match 0:Elapsed time : 2.838 ms
,W/libprocessgroup( 1018): failed to open /acct/uid_10008/pid_3265/cgroup.procs: No such file or directory
,I/AMMetaDataParserService( 3950): Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,D/TP/MmsProvider( 1449): Query uri=content://mms, match=0, calling pid = 2053
,I/AMMetaDataParserService( 3950): Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.PushMessageDialog
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
W/ContextImpl( 3950): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3950): Resource data:Loop for ,running activitycom.android.mms.saverestore.RestorePreviewActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.location.LocationMapActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3950): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check,
I/AMMetaDataParserService( 3950): getResourcePackageName:android.app.default_searchable
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
,I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm,
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
,I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:assistant
I/AMMetaDataParserService( 3950): Resource data:2131165197
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
W/ResourcesManager( 3950): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3950): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3950): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/ResourcesManager( 3950): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
W/ResourcesManager( 3950): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
W/ResourcesManager( 3950): Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
W/ResourcesManager( 3950): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3950): getResourceName:com.sec.android.gallery3d:xml/assistant
I/AMMetaDataParserService( 3950): getResourceTypeNamexml
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3950): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/LocationInitializer( 2053): Restart initialization of location
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3950): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623,
,I/AMMetaDataParserService( 3950): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/AMMetaDataParserService( 3950): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
,I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3950): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3950): getResourcePackageName:assistant
I/AMMetaDataParserService( 3950): Resource data:2131165197
,I/AMMetaDataParserService( 3950): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 3950): getResourceTypeNamexml
,I/AMMetaDataParserService( 3950): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/AMMetaDataParserService( 3950): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/AMMetaDataParserService( 3950): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,I/AMMetaDataParserService( 3950): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.cooliris.media.Gallery
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:assistant
I/AMMetaDataParserService( 3950): Resource data:2131165197
,I/AMMetaDataParserService( 3950): getResourceName:com.sec.android.gallery3d:xml/assistant
,I/AMMetaDataParserService( 3950): getResourceTypeNamexml
,I/AMMetaDataParserService( 3950): Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,I/AMMetaDataParserService( 3950): Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 27232(1572KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 22MB/34MB, paused 2.287ms total 145.578ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/AMMetaDataParserService( 3950): Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,D/BluetoothAdapter( 3469): disable()
,D/SettingsProvider( 1018): name = bluetooth_on
,I/AMMetaDataParserService( 3950): Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
,I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:android.wallpaper.preview
,W/ContextImpl( 3950): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:android.wallpaper.preview
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
,I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:android.app.searchable,
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler,
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
,I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.app.camera.Camera
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3950): getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
I/AMMetaDataParserService( 3950): getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.keyguard.layout
I/AMMetaDataParserService( 3950): getResourcePackageName:assistant
I/AMMetaDataParserService( 3950): Resource data:2131099648
,W/ResourcesManager( 3950): Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
W/ResourcesManager( 3950): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3950): getResourceName:com.sec.android.app.camera:xml/assistant
W/ResourcesManager( 3950): Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3950): getResourceTypeNamexml
,W/ResourcesManager( 3950): Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
W/ResourcesManager( 3950): Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,D/BluetoothAdapterState( 2607): CURRENT_STATE=ON, MSG = USER_TURN_OFF
D/BluetoothAdapterProperties( 2607): Setting state to 13
I/BluetoothAdapterState( 2607): Bluetooth adapter state changed: 12-> 13
D/BluetoothAdapterService( 2607): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2607): updateAdapterState state is 13
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/BluetoothPbapService( 2607): action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
D/BluetoothAdapterService( 2607): Autoconnection is available 
D/BluetoothAdapterService( 2607): updateAdapterState prevState = 12newState = 13
D/BluetoothAdapterService( 2607): terminating service from this receiver
,D/BluetoothSocket( 2607): close() in, this: android.bluetooth.BluetoothSocket@32277fb6, channel: 19, state: LISTENING
D/BluetoothSocket( 2607): close() this: android.bluetooth.BluetoothSocket@32277fb6, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@6cf1b51, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@207f04b7mSocket: android.net.LocalSocket@260ef424 impl:android.net.LocalSocketImpl@3a991b8d fd:FileDescriptor[76]
D/BluetoothSocket( 2607): Closing mSocket: android.net.LocalSocket@260ef424 impl:android.net.LocalSocketImpl@3a991b8d fd:FileDescriptor[76]
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,D/BluetoothAdapterProperties( 2607): onBluetoothDisable()
D/BluetoothAdapterProperties( 2607): mDiscovering is false
,D/SecContentProvider( 1018): uri = 3 selection = isDiscoverableEnabled
,I/BluetoothAdapterState( 2607): Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,W/InputMethodManagerService( 1018): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,I/InputMethodManagerService( 1018): [BT Setting State] State =13
,D/BluetoothTile( 1177):  onBluetoothStateChange:
,I/AMMetaDataParserService( 3950): Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,D/BluetoothTile( 1177):  onBluetoothPairedDevicesChanged:
,D/BluetoothTile( 1177):  handleUpdatestate:false name:null
,D/BluetoothTile( 1177):  handleUpdatestate:false name:null
,D/BluetoothTile( 1177): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1177):  getBluetoothState : 13
,D/SecContentProvider( 1018): uri = 18 selection = isWifiEnabled
D/SecContentProvider2( 1018): uri = 20 selection = isWifiStateChangeAllowed
D/SecContentProvider2( 1018): mCursor = null
,D/SettingsProvider( 1018): name = wifi_on
D/WifiService( 1018): setWifiEnabled: false pid=3469, uid=10333
,D/STATUSBAR-QSTileView( 1177): onStateChanged: Bluetooth
,I/SamsungIME( 1822): STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
D/StatusBarManagerService( 1018): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/StatusBarManagerService( 1018): setIconVisibility slot=bluetooth visible=false
,D/PhoneStatusBar( 1177): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
,D/PhoneStatusBar( 1177): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
,I/jxcore-log( 3469): ****TEST TOOK:  5123  ms ****
I/jxcore-log( 3469): 
,I/jxcore-log( 3469): ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
I/jxcore-log( 3469): 
,D/BluetoothAdapterProperties( 2607): Scan Mode:20
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
D/BluetoothAdapterState( 2607): CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
E/bt-btif ( 2607): btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
E/bt-btif ( 2607): btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
E/bt-btif ( 2607): BTA got event 0x1a1c
E/bt-btm  ( 2607): btm_ble_start_auto_conn start : 0, 0
W/bt-btif ( 2607): bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
W/bt-l2cap( 2607): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2607): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2607): L2CAP - PSM: 0x001b not found for deregistration
D/btif_config_util( 2607): btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,E/WifiStateMachine( 1018): WifiStateMachine: Leaving Connected state
,I/wpa_supplicant( 1386): reset timer : RESET_TIMER 0
I/wpa_supplicant( 1386): wlan0: Setting scan request: 0 sec 0 usec
I/wpa_supplicant( 1386): P2P: Current p2p state = IDLE
I/wpa_supplicant( 1386): Scan requested (ret=0) - scan timeout 30 seconds
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,E/WifiConfigStore( 1018): saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/BluetoothSocket( 2607): close() in, this: android.bluetooth.BluetoothSocket@35a3e142, channel: 5, state: LISTENING
D/BluetoothSocket( 2607): close() this: android.bluetooth.BluetoothSocket@35a3e142, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@15c9c878, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@753553mSocket: android.net.LocalSocket@39592e90 impl:android.net.LocalSocketImpl@2a88e389 fd:FileDescriptor[74]
D/BluetoothSocket( 2607): Closing mSocket: android.net.LocalSocket@39592e90 impl:android.net.LocalSocketImpl@2a88e389 fd:FileDescriptor[74]
,I/DBG_DM  ( 3179): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/GCM     ( 1627): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,D/AuthorizationBluetoothService( 1627): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,D/a       ( 1627): Opening database auth.proximity.permit_store...
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
I/AMMetaDataParserService( 3950): Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1627): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/WifiP2pService( 1018): InactiveState{ what=143375 },
,D/CommandListener(  279): Clearing all IP addresses on wlan0
D/WifiP2pService( 1018): P2pEnabledState{ what=143375 },
V/NativeCrypto( 1627): Read error: ssl=0xb821f5c0: I/O error during system call, Connection timed out
D/StatusBar.NetworkController( 1177): refreshViews connected={ wifi } level=?? combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:"NG700"
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/NativeCrypto( 1627): SSL shutdown failed: ssl=0xb821f5c0: I/O error during system call, Broken pipe
E/ConnectivityService( 1018): updateNetworkInfo(),
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
E/ConnectivityService( 1018): updateNetworkInfo()
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): ValidatedState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): DefaultState{ when=0 what=532488 arg1=10011 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1018): reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10011
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Forcing reevaluation
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Checking http://connectivitycheck.android.com/generate_204 on <unknown ssid>
I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
,I/qtaguid ( 1018): Tagging socket 344 with tag ffffffff00000000{4294967295,0} for uid 10011, pid: 1018, getuid(): 1000
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/qtaguid ( 1018): Untagging socket 344
,I/System.out( 1018): (HTTPLog)-Static: isSBSettingEnabled false
D/WifiP2pService( 1018): InactiveState{ what=131204 }
D/EnterpriseController(  279): mIsMarkChainAdded is 0 mIsBlockChainAdded is 0 netId is 0
D/WifiP2pService( 1018): P2pEnabledState{ what=131204 }
D/Netd    (  279): getNetworkForDns: using netid 502 for uid 1000
D/WifiNetworkAgent( 1018): NetworkAgent: NetworkAgent channel lost
,D/WifiScanningService( 1018): SCAN_AVAILABLE : 1
,D/WifiScanningService( 1018): DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
D/RttService( 1018): SCAN_AVAILABLE : 1
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.android.com": No address associated with hostname
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): Validated
D/RttService( 1018): EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/GCoreFlp( 1798): No location to return for getLastLocation()
W/FusedLocationProvider( 1627): location=null
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
,V/GmsCoreStatsServiceLauncher( 2053): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
W/ContextImpl( 3950): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/bt-l2cap( 2607): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2607): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2607): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 2607): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2607): L2CAP - PSM: 0x0017 not found for deregistration
W/bt-l2cap( 2607): L2CAP - PSM: 0x001b not found for deregistration
W/bt-l2cap( 2607): L2CAP - PSM: 0x0019 not found for deregistration
W/bt-l2cap( 2607): L2CAP - PSM: 0x0017 not found for deregistration
,W/bt-l2cap( 2607): L2CAP - PSM: 0x001b not found for deregistration
W/bt-btif ( 2607): ag scb idx 1 not allocated
W/bt-btif ( 2607): ag scb idx 2 not allocated
E/bt-btif ( 2607): BTA AG is already disabled, ignoring ...
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
I/bt_userial_mct( 2607): exiting userial_read_thread
D/bt_userial_mct( 2607): Leaving userial_evt_read_thread()
D/bt_userial_mct( 2607): userial_close_reader Joined userial reader thread: 0
,I/bt_vendor( 2607): hw_epilog_process
D/bt_userial_mct( 2607): userial_close
I/bt_vendor( 2607): bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/WifiP2pService( 1018): sending p2p connection changed broadcast: FAILED
,D/WifiDisplayController( 1018): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,D/WifiDisplayAdapter( 1018): onP2pDisconnected
,D/IpRemoteDisplayController( 1018): disconnectWfdBridgeServer
D/IpRemoteDisplayController( 1018): WfdBridgeServer is already null
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/WifiP2pService( 1018): sending p2p connection changed broadcast: DISCONNECTED
,D/WifiDisplayController( 1018): Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
D/WifiDisplayController( 1018): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayController( 1018): disconnect
D/WifiDisplayController( 1018): updateConnection
D/WifiDisplayController( 1018): updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,D/WifiP2pService( 1018): P2pDisablingState
,D/WifiP2pService( 1018): P2pDisablingState{ what=147458 }
D/WifiP2pService( 1018): p2p socket connection lost
D/WifiP2pService( 1018): P2pDisabledState
,D/WifiP2pService( 1018): P2pDisabledState{ what=143375 },
D/WifiP2pService( 1018): DefaultState{ what=143375 }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/WifiDisplayController( 1018): Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
E/WifiStateMachine( 1018): BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
D/WifiDisplayAdapter( 1018): onP2pDisconnected
W/ActivityManager( 1018): userId = 0, bbcId = -10000
D/IpRemoteDisplayController( 1018): disconnectWfdBridgeServer
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
D/IpRemoteDisplayController( 1018): WfdBridgeServer is already null
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/AllShareCastTile( 1177): action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,D/WifiDisplayAdapter( 1018): getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,D/AllShareCastTile( 1177): wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.GridSettings
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:assistant
I/AMMetaDataParserService( 3950): Resource data:2131165220
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ResourcesManager( 3950): Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.,
W/ResourcesManager( 3950): Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
W/ResourcesManager( 3950): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 3950): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 3950): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,I/AMMetaDataParserService( 3950): getResourceName:com.android.settings:xml/assistant
W/ResourcesManager( 3950): Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
I/AMMetaDataParserService( 3950): getResourceTypeNamexml
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = com.android.phone
,D/CommandListener(  279): Clearing all IP addresses on wlan0
,D/ConnectivityManager.CallbackHandler( 1177): CM callback handler got msg 524292
D/ConnectivityService( 1018): setProvNotificationVisibleIntent: E visible=false networkType=1 extraInfo=null
D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
D/ConnectivityService( 1018): notifyType LOST for NetworkAgentInfo [WIFI () - 502]
D/ConnectivityService( 1018): Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
D/WIFI_P2P( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
,I/AMMetaDataParserService( 3950): Icon data: ResourceSearch2131363517com.android.settings.Search2130837580
D/CSLegacyTypeTracker( 1018): Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.133/24,fe80::aec:a9ff:fe50:7628/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
D/CSLegacyTypeTracker( 1018): Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,D/ConnectivityManager.CallbackHandler( 2053): CM callback handler got msg 524292
D/EntConnectivity( 1018): Not allowed due to - mEnabled false - primarySimSlot false
I/WifiTrafficPoller( 1018): evaluateTrafficStatsPolling
I/wpa_supplicant( 1386): p2p0: State: DISCONNECTED -> DISCONNECTED
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth,
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/ConnectivityService( 1018): NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
V/NetworkStats( 1018): updateIfacesLocked()
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,V/NetworkStats( 1018): performPollLocked(flags=0x1)
D/ConnectivityService( 1018): nai.networkMonitor.doQuit()
,D/NetworkMonitorNetworkAgentInfo [WIFI () - null]( 1018): doQuit - quitNow()
E/ConnectivityService( 1018): updateNetworkInfo()
E/ConnectivityService( 1018): updateNetworkInfo()
D/WIFI    ( 1018): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/SecContentProvider2( 1018): uri = 20 selection = getPromptCredentialsEnabled
D/SecContentProvider2( 1018): mCursor = null
D/Tethering( 1018): Tethering got CONNECTIVITY_ACTION_IMMEDIATE
D/Tethering( 1018): MasterInitialState.processMessage what=3
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/EntConnectivity( 1018): Not allowed due to - mEnabled false - primarySimSlot false
D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
V/NetworkStats( 1018): advisePersistThreshold() given 9223372036854775, clamped to 2097152
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/StatusBar.NetworkController( 1177): EthernetConnected: false
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): 0
D/StatusBar.NetworkController( 1177): getUpdateDataNetType(): mDataTypeBrand = LTE
D/StatusBar.NetworkController( 1177): updateDataNetType()
D/StatusBar.NetworkController( 1177): NoService, mRoamingIconId = 0
E/StatusBar.NetworkController( 1177): updateLTEICONDataNetType:0
,I/AMMetaDataParserService( 3950): Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,D/StatusBar.NetworkController( 1177): updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength: hasService=false ss=null
,D/WifiCredService( 1316): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/StatusBar.NetworkController( 1177): updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020561/com.android.systemui:drawable/stat_sys_wifi_signal_0 mQSWifiIconId=0x7f020157/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=true enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false),
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/HotspotTile( 1177): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1177): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-QSTileView( 1177): onStateChanged: Wi-Fi
D/STATUSBAR-WifiQuickSettingButton( 1177): Wifi onReceive(0)
D/HotspotTile( 1177): onReceive : 0, 0
,D/TelephonyNetworkFactory( 1449): evalRequest evalRequest  = NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ] n.requested= false
D/TelephonyNetworkFactory( 1449): Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,W/ActivityManager( 1018): userId = 0, bbcId = -10000,
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.SubSettings
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.LabelName
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Password
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.wifi.WifiSecSetupActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.andr,oid.settings.wifi.WifiPickerDialog
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity
I/AMMetaDataParserServ,ice( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3950): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.TetherSettings
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.samsung.android.multiuser.install_only_owner
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.LanguageSettings
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3950): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3950): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.HomeSettings
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.DisplaySettings
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.DockSettings
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
W/ContextImpl( 3950): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3950): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3950): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.ManageApplications
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.RunningServices
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.LaunchApplication
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.applications.StorageUse
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
,I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.SecuritySettings
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.CredentialStorage
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.SetProfileOwner
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.IccLockSettings
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.ApnEditor
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.MediaFormat
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.MediaFormatSd
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.AppPicker
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.UsbSettings
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.ActivityPicker
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.BatteryInfo
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Display
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.RadioInfo
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.ProxySelector
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.BandMode
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.TestingSettings
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/ActivityManager( 1018): Killing 3691:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
V/NetworkStats( 1018): performPollLocked() took 135ms
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/Nat464Xlat( 1018): interfaceLinkStateChanged p2p0, false
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.CryptKeeper
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/wpa_supplicant( 1386): Blacklist: Clear (all) 
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
E/SMD     (  289): DCD OFF
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3950): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.SoundSettings
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.GSensorSettings
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.InkeffectPreview
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.ModePreview
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.NewModePreview
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.SViewColor
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.SViewColor2014
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.SViewStyleClock
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.sec.android.sdk.cover.MODE
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.WarrantyLegal
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
W/ActivityManager( 1018): userId = 0, bbcId = -10000
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.PenHelpActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.PhoneVibration
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.OneHandHelp
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.MagazineCard
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.SearchActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:android.app.searchable
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.activekey.AppList
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.SETTING_HEADER_ID
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
I/AMMetaDataParserService( 3950): Resource data:Inside bundle  check
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
I/AMMetaDataParserService( 3950): getResourcePackageName:com.android.settings.FRAGMENT_CLASS
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
I/AMMetaDataParserService( 3950): Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
D/SIP     ( 1449): [SipSharedPreferences] isReceivingCallsEnabled, option not set; use default value, exception: android.provider.Settings$SettingNotFoundException: sip_receive_calls
E/File    ( 1449): fail readDirectory() errno=2
D/AndroidRuntime( 4437): 
D/AndroidRuntime( 4437): >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/AndroidRuntime( 4437): CheckJNI is OFF
D/AndroidRuntime( 4437): readGMSProperty: start
D/AndroidRuntime( 4437): readGMSProperty: already setted!!
D/AndroidRuntime( 4437): propertySet: couldn't set property (it is from app)
D/AndroidRuntime( 4437): readGMSProperty: could not set the property(default)!!
D/AndroidRuntime( 4437): readGMSProperty: end
D/AndroidRuntime( 4437): addProductProperty: start
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
I/wpa_supplicant( 1386): p2p0: CTRL-EVENT-TERMINATING 
D/Tethering( 1018): interfaceLinkStateChanged p2p0, false
D/Tethering( 1018): interfaceStatusChanged p2p0, false
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
I/bt_vendor( 2607): bt-vendor : BT_VND_OP_POWER_CTRL: Off
I/bt_vendor( 2607): bluetooth satus is on
I/bt_vendor( 2607): bt-vendor : resetting BT status
I/bt_vendor( 2607): Starting hciattach daemon
I/bt_vendor( 2607): try to set false
I/bt_vendor( 2607): Starting hciattach daemon
I/bt_vendor( 2607): try to set false
I/bt_vendor( 2607): cleanup
I/GKI_LINUX( 2607): gki_task task_id=0 [BTU] terminating
I/wpa_supplicant( 1386): CTRL-EVENT-DISCONNECTED bssid=C0.AA.48 reason=3 locally_generated=1
I/wpa_supplicant( 1386): wlan0: State: COMPLETED -> DISCONNECTED
I/wpa_supplicant( 1386): Prev BSS - hexdump(len=6): c0 ff d4 d3 aa 48
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
I/wpa_supplicant( 1386): CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=C0.AA.48 SSID=4E47373030
I/wpa_supplicant( 1386): wlan0: State: DISCONNECTED -> DISCONNECTED
I/GKI_LINUX( 2607): GKI_exit_task 0 done
I/GKI_LINUX( 2607): GKI_shutdown(): task [BTU] terminated
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
D/Tethering( 1018): InitialState.processMessage what=4
D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
D/BluetoothAdapterState( 2607): CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
D/BtConfig.SecureMode( 2607): isSecureModeOn:false
D/BluetoothAdapterService( 2607): mProfilesStarted : true supportedProfileServices.length : 12
W/BluetoothAdapterService( 2607): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
D/BtSettings.ProfileConfig( 2607): getProfileSaveSetting: com.android.bluetooth.gatt.GattService
E/Tethering( 1018): No numeric data
W/BluetoothAdapterService( 2607): Not skipping com.android.bluetooth.gatt.GattService
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 2607): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
D/BtSettings.ProfileConfig( 2607): getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
D/BtGatt.DebugUtils( 2607): handleDebugAction() action=null
W/BluetoothAdapterService( 2607): Not skipping com.android.bluetooth.hfp.HeadsetService
D/Tethering( 1018): sendTetherStateChangedBroadcast 0, 0, 0
D/Tethering( 1018): clearTetheredNotification()
I/Hs20UtilService( 1719): Starting #5
D/BtGatt.GattService( 2607): Received stop request...Stopping profile...
D/BtGatt.GattService( 2607): stop()
D/BtGatt.AdvertiseManager( 2607): advertise clients cleared
I/Hs20UtilService( 1719): Message received 5007
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 2607): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
D/BtSettings.ProfileConfig( 2607): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
W/BluetoothAdapterService( 2607): Not skipping com.android.bluetooth.a2dp.A2dpService
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 2607): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
D/BtSettings.ProfileConfig( 2607): getProfileSaveSetting: com.android.bluetooth.hid.HidService
W/BluetoothAdapterService( 2607): Not skipping com.android.bluetooth.hid.HidService
D/HotspotTile( 1177): onReceive : android.net.conn.TETHER_STATE_CHANGED
D/HotspotTile( 1177): updateTetherState():false, false
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 2607): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
D/BtSettings.ProfileConfig( 2607): getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
D/BluetoothAdapterService( 2607): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21c4a4ce
W/BluetoothAdapterService( 2607): Not skipping com.android.bluetooth.hdp.HealthService
D/HeadsetService( 2607): Received stop request...Stopping profile...
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
V/NetworkStats( 1018): performPollLocked(flags=0x1)
D/NetworkStatsFactory( 1018): UpdateStatsForKnox updated
V/NetworkStats( 1018): performPollLocked() took 3ms
D/NetworkStatsFactory( 1018): UpdateStatsForKnox main else ---
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 2607): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
D/BtSettings.ProfileConfig( 2607): getProfileSaveSetting: com.android.bluetooth.pan.PanService
W/libprocessgroup( 1018): failed to open /acct/uid_1000/pid_3691/cgroup.procs: No such file or directory
,W/BluetoothAdapterService( 2607): Not skipping com.android.bluetooth.pan.PanService
,D/BluetoothAdapterService( 2607): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21c4a4ce
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
W/BluetoothAdapterService( 2607): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
D/BtSettings.ProfileConfig( 2607): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
W/BluetoothAdapterService( 2607): Not skipping com.android.bluetooth.map.BluetoothMapService
,D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
D/NtpTrustedTime( 1018): currentTimeMillis() cache hit
,D/AudioService( 1018): onServiceDisconnected: Bluetooth profile: 1
D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
,I/NearbySettings( 1316): MountReceiver.onReceive - Keep current state
W/BluetoothAdapterService( 2607): check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
D/BtSettings.ProfileConfig( 2607): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,D/A2dpService( 2607): Received stop request...Stopping profile...
D/A2dpStateMachine( 2607): Exit Disconnected: -1
W/BluetoothAdapterService( 2607): Not skipping com.broadcom.bt.service.sap.SapService
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.android.bluetooth, destAppInfo.processName = com.android.bluetooth
D/BluetoothAdapterService( 2607): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21c4a4ce
W/BluetoothAdapterService( 2607): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
D/BtSettings.ProfileConfig( 2607): getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,W/BluetoothAdapterService( 2607): Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
W/BluetoothAdapterService( 2607): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
D/BtSettings.ProfileConfig( 2607): getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,D/BluetoothA2dp( 1018): Proxy object disconnected
D/AudioService( 1018): onServiceDisconnected: Bluetooth profile: 2
D/HidService( 2607): Received stop request...Stopping profile...
D/HidService( 2607): Stopping Bluetooth HidService
W/BluetoothHidServiceJni( 2607): Cleaning up Bluetooth HID Interface...
W/bt-btif ( 2607): cleanup: HH disabling or disabled already, status = 0
W/BluetoothHidServiceJni( 2607): Cleaning up Bluetooth GID callback object
D/BluetoothAdapterService( 2607): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21c4a4ce
W/BluetoothAdapterService( 2607): Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
W/BluetoothAdapterService( 2607): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
D/BtSettings.ProfileConfig( 2607): getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,W/BluetoothAdapterService( 2607): Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
W/BluetoothAdapterService( 2607): check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
D/BtSettings.ProfileConfig( 2607): getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
W/BluetoothAdapterService( 2607): Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
D/BluetoothAdapterState( 2607): Stopping profile services that were post enabled
,E/BluetoothAdapterService(566535374)( 2607): processProfileServiceStateChanged() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,D/HealthService( 2607): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2607): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21c4a4ce
,E/BluetoothAdapterService(566535374)( 2607): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2607): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2607): Profile still running: com.android.bluetooth.hid.HidService
D/PanService( 2607): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2607): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21c4a4ce
,D/BluetoothPan( 1018): BluetoothPAN Proxy object disconnected
,E/AffinityControl( 4437): AffinityControl: registerfunction enter
,W/BluetoothHeadsetServiceJni( 2607): Cleaning up Bluetooth Handsfree Interface...
W/BluetoothHeadsetServiceJni( 2607): Cleaning up Bluetooth Handsfree callback object
D/BluetoothMapService( 2607): Received stop request...Stopping profile...
D/BluetoothAdapterService( 2607): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21c4a4ce
,D/SapService( 2607): Received stop request...Stopping profile...
D/SapService( 2607): Stopping Bluetooth SapService
D/BluetoothAdapterService( 2607): getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21c4a4ce
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/wpa_supplicant( 1386): Blacklist: Clear (all) 
,E/BluetoothAdapterService(566535374)( 2607): processProfileServiceStateChanged() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2607): getProfileSaveSetting: com.android.bluetooth.hid.HidService
D/BluetoothAdapterService( 2607): Profile still running: com.android.bluetooth.hid.HidService
D/BluetoothA2dp( 2607): Proxy object disconnected
D/BluetoothAdapterService( 2607): Bluetooth A2dp source service disconnected
I/GKI_LINUX( 2607): gki_task task_id=2 [A2DP-MEDIA] terminating
I/GKI_LINUX( 2607): GKI_exit_task 2 done
I/GKI_LINUX( 2607): GKI_shutdown(): task [A2DP-MEDIA] terminated
,E/BluetoothAdapterService(566535374)( 2607): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2607): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2607): Profile still running: com.android.bluetooth.map.BluetoothMapService
E/BluetoothAdapterService(566535374)( 2607): processProfileServiceStateChanged() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2607): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2607): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothHealthServiceJni( 2607): Cleaning up Bluetooth Health Interface...
E/SQLiteLog( 1627): (10) POSIX Error : 11 SQLite Error : 3850
W/BluetoothHealthServiceJni( 2607): Cleaning up Bluetooth Health object
E/BluetoothAdapterService(566535374)( 2607): processProfileServiceStateChanged() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2607): getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
D/BluetoothAdapterService( 2607): Profile still running: com.android.bluetooth.map.BluetoothMapService
W/BluetoothPanServiceJni( 2607): Cleaning up Bluetooth PAN Interface...
W/BluetoothPanServiceJni( 2607): Cleaning up Bluetooth PAN callback object
,E/BluetoothAdapterService(566535374)( 2607): processProfileServiceStateChanged() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
D/BtSettings.ProfileConfig( 2607): getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
D/BluetoothAdapterService( 2607): Profile still running: com.broadcom.bt.service.sap.SapService
E/BluetoothAdapterService(566535374)( 2607): processProfileServiceStateChanged() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
W/BluetoothSAPServiceJni( 2607): ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
W/BluetoothSAPServiceJni( 2607): ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,I/Hs20UtilService( 1719): Starting #6
,I/Hs20UtilService( 1719): Message received 5007
,D/BluetoothAdapterState( 2607): CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
D/BluetoothAdapterProperties( 2607): Setting state to 10
I/BluetoothAdapterState( 2607): Bluetooth adapter state changed: 13-> 10
D/BluetoothAdapterService( 2607): Bluetooth PBAP supproted is true
D/BluetoothAdapterService( 2607): updateAdapterState state is 10
,D/AndroidRuntime( 4437): Calling main entry com.android.commands.pm.Pm
D/PhoneApp( 1449): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/BluetoothAdapter( 1431): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1431): Bluetooth is turned off, stop adv and scan
D/BluetoothAdapterService( 2607): Autoconnection is available 
D/BluetoothAdapterService( 2607): updateAdapterState prevState = 13newState = 10
I/BluetoothAdapterState( 2607): Entering OffState
,D/BluetoothAdapter( 1441): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1441): Bluetooth is turned off, stop adv and scan
,D/FileWriteThread_Telephony( 1449): FileWriteThread : threadType = 3
D/PhoneApp( 1449): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1449): FileWriteThread : threadType = 3
D/PhoneApp( 1449): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
D/FileWriteThread_Telephony( 1449): FileWriteThread : threadType = 3
,D/PhoneApp( 1449): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/BluetoothAdapter( 3902): onBluetoothStateChange: up=false
D/BluetoothAdapter( 3902): Bluetooth is turned off, stop adv and scan
V/NearbySettings( 1316): DMSUtil.isNetworkConnected - flag-null, state-null
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
D/BluetoothAdapter( 1627): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1627): Bluetooth is turned off, stop adv and scan
,D/BluetoothAdapter( 1018): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1018): Bluetooth is turned off, stop adv and scan
D/BluetoothAdapter( 1798): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1798): Bluetooth is turned off, stop adv and scan
D/BluetoothA2dp( 1018): onBluetoothStateChange: up=false
D/PackageManager( 1018): START PACKAGE DELETE: observer{180969712}
D/PackageManager( 1018): pkg{<packageName>}
D/PackageManager( 1018): user{0}
D/PackageManager( 1018): caller{2000}
D/PackageManager( 1018): flags{3}
D/FileWriteThread_Telephony( 1449): FileWriteThread : threadType = 3
D/BluetoothAdapter( 1449): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1449): Bluetooth is turned off, stop adv and scan
D/PhoneApp( 1449): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/BluetoothAdapter( 2607): onBluetoothStateChange: up=false
D/BluetoothAdapter( 2607): Bluetooth is turned off, stop adv and scan
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved : true
D/PersonaManagerService( 1018): isFromApprovedUnInstaller: isApproved before exit: true
D/PackageManager( 1018): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
D/PackageManager( 1018): [MSG] DELETE_PACKAGE_AS_USER
D/PackageManager( 1018): deletePackageAsUser- pkg:com.example.hello, userId:0, flag3
,D/PackageManagerService( 1018): deletePackage- pkg:com.example.hello, edmuserId:0
D/PackageManagerService( 1018): deletePackage- pkg:com.example.hello, edmuserId:-1
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled
D/ApplicationPolicy( 1018): getApplicationUninstallationEnabled :  enabled true
D/BluetoothAdapter( 3469): onBluetoothStateChange: up=false
D/BluetoothAdapter( 3469): Bluetooth is turned off, stop adv and scan
D/BluetoothA2dp( 2607): onBluetoothStateChange: up=false
,I/NearbySettings( 1316): DMSUtil.isNetworkConnected - P2P: DISCONNECTED
I/NearbySettings( 1316): DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
I/NearbySettings( 1316): MountReceiver.onReceive - Set preference state off
D/BluetoothAdapter( 1177): onBluetoothStateChange: up=false
D/BluetoothAdapter( 1177): Bluetooth is turned off, stop adv and scan
,D/FileWriteThread_Telephony( 1449): FileWriteThread : threadType = 3
D/PackageManager( 1018): !@killApplicatoin: 10333, uninstall pkg
V/NearbySettings( 1316): MountReceiver.mPrefHandler - 7002
D/PhoneApp( 1449): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/BluetoothManagerService( 1018): Broadcasting onBluetoothServiceDown() to 10 receivers.
,D/BluetoothManagerService( 1018): Broadcasting onBluetoothServiceUp() to 0 receivers.,
,I/wpa_supplicant( 1386): wlan0: CTRL-EVENT-TERMINATING 
,D/Tethering( 1018): interfaceLinkStateChanged wlan0, false
,I/Nat464Xlat( 1018): interfaceLinkStateChanged wlan0, false
D/Tethering( 1018): interfaceStatusChanged wlan0, false
,W/PackageSettings( 1018): Skipping PackageSetting{1db949e3 com.test.thalitest/10326} due to missing metadata
,D/FileWriteThread_Telephony( 1449): FileWriteThread : threadType = 3
,D/PhoneApp( 1449): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/FileWriteThread_Telephony( 1449): FileWriteThread : threadType = 3
,D/PhoneApp( 1449): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,W/InputMethodManagerService( 1018): InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,D/FileWriteThread_Telephony( 1449): FileWriteThread : threadType = 3
I/InputMethodManagerService( 1018): [BT Setting State] State =10
D/PhoneApp( 1449): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
I/InputMethodManagerService( 1018): [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,D/FileWriteThread_Telephony( 1449): FileWriteThread : threadType = 3
,D/PhoneApp( 1449): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
,D/BluetoothAdapter( 1177): 330534121: getState() :  mService = null. Returning STATE_OFF
,D/BluetoothTile( 1177):  onBluetoothPairedDevicesChanged:
D/BluetoothAdapter( 1177): 330534121: getState() :  mService = null. Returning STATE_OFF
,D/FileWriteThread_Telephony( 1449): FileWriteThread : threadType = 3
D/BluetoothTile( 1177): onReceive : android.bluetooth.adapter.action.STATE_CHANGED
D/BluetoothTile( 1177):  getBluetoothState : 10
D/BluetoothAdapter( 1177): 330534121: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1177): 330534121: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1177): 330534121: getState() :  mService = null. Returning STATE_OFF
D/PhoneApp( 1449): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/StatusBarManagerService( 1018): setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=true num=0 )
I/SamsungIME( 1822): STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
D/StatusBarManagerService( 1018): setIconVisibility slot=bluetooth visible=false
D/FileWriteThread_Telephony( 1449): FileWriteThread : threadType = 3
D/PhoneApp( 1449): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/PhoneStatusBar( 1177): updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f020338 level=0 visible=false num=0 )
D/FileWriteThread_Telephony( 1449): FileWriteThread : threadType = 3
D/PhoneApp( 1449): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
D/BluetoothAdapter( 1798): 158670380: getState() :  mService = null. Returning STATE_OFF
D/BluetoothAdapter( 1798): 158670380: getState() :  mService = null. Returning STATE_OFF
D/FileWriteThread_Telephony( 1449): FileWriteThread : threadType = 3
I/ActivityManager( 1018): Force stopping com.example.hello appid=10333 user=0: pkg removed
D/PhoneApp( 1449): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
I/ActivityManager( 1018): Killing 3469:com.example.hello/u0a333 (adj 0): stop com.example.hello cause pkg removed
D/FileWriteThread_Telephony( 1449): FileWriteThread : threadType = 3
D/PhoneApp( 1449): PhoneAppBroadcastReceiver onReceive android.intent.action.ANY_DATA_STATE
W/ActivityManager( 1018): Force removing ActivityRecord{35d5023f u0 com.example.hello/.MainActivity t10}: app died, no saved state
,D/FileWriteThread_Telephony( 1449): FileWriteThread : threadType = 3
,D/FocusedStackFrame( 1018): Set to : 0
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.example.hello
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
D/InputDispatcher( 1018): Focused application set to: xxxx
,D/InputDispatcher( 1018): Focus left window: 3469
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,E/JavaBinder( 1018): !!! FAILED BINDER TRANSACTION !!!
,I/SurfaceFlinger(  258): id=11 Removed NainActivit (6/7)
,I/SurfaceFlinger(  258): id=11 Removed NainActivit (-2/7)
,D/ConnectivityService( 1018): sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,D/CustomFrequencyManagerService( 1018): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1018): mDVFSHelper.acquire()
,V/WindowOrientationListener( 1018): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,V/WindowManager( 1018): rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
V/WindowOrientationListener( 1018): ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,W/ActivityManager( 1018): CustomStartingWindow se packge removed so remove capture also
,I/ActivityManager( 1018): Force stopping com.example.hello appid=10333 user=-1: uninstall pkg
,D/Launcher( 1480): onRestart, Launcher: 51003354
,I/GKI_LINUX( 2607): gki_task task_id=1 [BTIF] terminating
I/GKI_LINUX( 2607): GKI_exit_task 1 done
I/GKI_LINUX( 2607): GKI_shutdown(): task [BTIF] terminated
,I/BluetoothServiceJni( 2607): cleanupNative: return from cleanup
,I/art     ( 2607): System.exit called, status: 0
I/AndroidRuntime( 2607): VM exiting with result code 0, cleanup skipped.
,E/SamsungIME( 1822): mOCRHelper is null
,I/InputReader( 1018): Reconfiguring input devices.  changes=0x00000010
,W/GeofencerStateMachine( 1798): Ignoring removeGeofence because network location is disabled.
,E/WifiStateMachine( 1018): skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,W/ResourcesManager( 1449): Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,D/WifiNative-wlan0( 1018): callSECApiBoolean - ID [21]
,W/ActivityManager( 1018): NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,I/Hs20UtilService( 1719): Starting #7
,I/Hs20UtilService( 1719): Message received 5007
,D/Launcher( 1480): onStart, Launcher: 51003354
,D/Launcher.HomeView( 1480): onStart
D/Launcher( 1480): onResume, Launcher: 51003354
,D/RCPManagerService( 1018): PackageReceiver onReceive()
,W/Settings( 3858): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,D/StatusBar.NetworkController( 1177): refreshViews connected={ } level=?? combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
D/STATUSBAR-WifiQuickSettingButton( 1177): onWifiSignalChanged enabled=false enabledDesc:null
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
D/StatusBar.NetworkController( 1177): refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,D/SettingsProvider( 1018): name = kids_home_mode
D/SettingsProvider( 1018): edmUri: content://com.sec.knox.provider/RestrictionPolicy3
D/SettingsProvider( 1018): projectionArgs: isSettingsChangesAllowed
D/SettingsProvider( 1018): selectionArgs: false
D/SettingsProvider( 1018): selectionArgs: 10006
D/SecContentProvider( 1018): uri = 17 selection = isSettingsChangesAllowed
D/SettingsProvider( 1018): ret = -1
,I/HarmonyEASService( 1018): onReceive : android.intent.action.PACKAGE_REMOVED for 0
,D/Launcher.HomeView( 1480): onResume
,D/KnoxMUMContainerPolicy( 1018): mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,D/STATUSBAR-WifiQuickSettingButton( 1177): onReceive : android.net.wifi.WIFI_STATE_CHANGED
D/STATUSBAR-WifiQuickSettingButton( 1177): Wifi onReceive(1)
D/HotspotTile( 1177): onReceive : android.net.wifi.WIFI_STATE_CHANGED
,D/STATUSBAR-QSTileView( 1177): onStateChanged: Wi-Fi
,D/WifiCredService( 1316): Action received :android.net.wifi.WIFI_STATE_CHANGED
,D/HotspotTile( 1177): onReceive : 1, 0
,D/NearbySettings( 1316): MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,I/NearbySettings( 1316): MountReceiver.onReceive - Keep current state
,I/ActivityManager( 1018): Process com.android.bluetooth (pid 2607)(adj 0) has died(69,656)
,D/Launcher( 1480): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,W/Settings( 1798): Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
I/DBG_DM  ( 3179): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 8 sec
,I/DBG_DM  ( 3179): [com.wssyncmldm.XDMService(936/lIllIlllIIllllIlIlIl)] WiFi network Connected : false
,I/DBG_DM  ( 3179): [com.wssyncmldm.XDMService(952/llIlIllllllllllllllI)] Bluetooth Data Connected : false
,D/SecContentProvider2( 1018): uri = 11 selection = getMyKnoxAdmin
,D/SecContentProvider2( 1018): mCursor = null
,D/MenuAppsGridFragment( 1480): onResume
,D/ActivityManager( 1018): handle home activity for 0
,D/RegisteredServicesCache( 1441): empty dynamic service
,I/WallpaperManagerService( 1018): switchPersonaWallpaper is called for personaId-0
D/KnoxTimeoutHandler( 1018): post home show event for user 0
D/ActivityManager( 1018): post active user change for 0 fullscreen true record.isFloatingActivity() false
D/KnoxTimeoutHandler( 1018): postActiveUserChange for user 0
I/KnoxTimeoutHandler( 1018): postActiveUserChange, showWhenLocked: false
,D/EnterpriseDeviceManagerService( 1018): Package has changed for user 0
,D/EnterpriseDeviceManagerService( 1018): Admin package name: com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/TextServicesManagerService( 1018): no available spell checker services found
,I/SurfaceFlinger(  258): id=12 createSurf (540x960),1 flag=4, Mauncher
,D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,D/StatusBarManagerService( 1018): manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,I/splitIntent( 1018): intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,I/splitIntent( 1018): base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
,I/splitIntent( 1018): other index=3, name=com.google.android.gms com.google.android.gms.photos.InitializePhotosIntentReceiver
D/InputDispatcher( 1018): Focus entered window: 1480
I/splitIntent( 1018): arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PointerIcon( 1018): setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
D/PointerIcon( 1018): setMouseCustomIcon IconType is same.101
,D/SRIB_DCS( 1480): log_dcs ThreadedRenderer::initialize entered! 
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/Launcher( 1480): Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,D/InputMethodManagerService( 1018): windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,W/InputMethodManagerService( 1018): Got RemoteException sending setActive(false) notification to pid 3469 uid 10333
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ContextImpl( 1018): Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,E/MDM     ( 1798): [196] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
D/SamsungIME( 1822): onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PersonaManager( 1018): isKioskContainerExistOnDevice
,D/BackupManagerService( 1018): Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.example.hello flg=0x4000010 (has extras) }
,D/JobSchedulerService( 1018): Receieved: android.intent.action.PACKAGE_REMOVED
,V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
V/EnterpriseBillingPolicy( 1018): uID is 10333
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
,V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.example.hello
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/ApplicationPolicy( 1018): isApplicationStateBlocked userId 0 pkgname com.example.hello
,D/WindowOrientationListener( 1018):   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
D/SSRM:aZ ( 1018): MSG_TYPE_APP_REMOVED::
D/SensorService( 1018): [SO] activate (ident=0xb8696fd0, enabled=0)
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,D/TaskPersister( 1018): removeObsoleteFile: deleting file=10_task.xml
,I/ActivityManager( 1018): Displayed Component not be shown by security: +377ms
,D/SensorManager( 1018): unregisterListener ::   
,I/Sensors ( 1018): AccelerometerSensor(0) setDelay : 200000000(ns)
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/SensorService( 1018): [SO] changed settle time [0]
D/SensorService( 1018): [SO] setDelay [200000000]
D/SensorService( 1018): [SO] activate (ident=0xb8696fd0, enabled=1)
D/SensorService( 1018): [SO] AR_init
I/Sensors ( 1018): AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,D/SensorManager( 1018): registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,I/art     ( 1018): Explicit concurrent mark sweep GC freed 50822(3MB) AllocSpace objects, 5(128KB) LOS objects, 33% free, 23MB/34MB, paused 13.583ms total 332.363ms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023,
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
,V/EnterpriseBillingPolicy( 1018): uID is 10333
V/EnterpriseBillingPolicy( 1018): Removed Packageuid is0
V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - enter
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/EnterpriseBillingPolicyStorage( 1018): getProfileForApplication - exit null : containerId = 0
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - personal application - profile null
V/EnterpriseBillingPolicy( 1018): packageModificationReceiver - onreceive - might be a vpn vendor package 
V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - start - com.example.hello
,V/EnterpriseBillingPolicyStorage( 1018): getBillingProfileForVpnEngine - end - null
,D/WallpaperManagerService( 1018):  force update = false; persona id = 0; current user =0; current persona = 0
,D/KnoxTimeoutHandler( 1018): handleHomeShow for 0 and current 0
,D/KnoxTimeoutHandler( 1018): handleActiveUserChange for user 0
D/PersonaManagerService( 1018): getPersonasForUser(): returning null!
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
I/ApplicationPolicy( 1018): updateDataUsageMap
I/StatusBar( 1177): Icon Only
D/PanelView( 1177): There is/are notification(s) 
W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/LocationInitializer( 2053): Restart initialization of location
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
D/GCM     ( 1627): GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/CustomFrequencyManagerService( 1018): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
,W/ActivityManager( 1018): mDVFSHelper.release()
,D/CustomFrequencyManagerService( 1018): acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@11
,D/Tethering( 1018): interfaceRemoved wlan0
,E/Tethering( 1018): attempting to remove unknown iface (wlan0), ignoring
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/AuthorizationBluetoothService( 1627): Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,V/GLSActivity( 1627): AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/GCoreFlp( 1798): No location to return for getLastLocation()
,W/FusedLocationProvider( 1627): location=null
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/PowerManagerService( 1018): [s] UserActivityState : 1 -> 2
,V/GmsCoreStatsServiceLauncher( 2053): Received broadcast intent Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.common.stats.GmsCoreStatsServiceLauncher }
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 15 -> 15
D/DisplayPowerController( 1018): animation target = 15, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/PowerManagerService( 1018): [s] DisplayPowerCallbacks : onStateChanged()
,D/lights  ( 1018): lcd : 254 +
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,D/SensorService( 1018): [SO] Reset Rotation Old [100], Init [1]
,D/Tethering( 1018): interfaceRemoved p2p0
E/Tethering( 1018): attempting to remove unknown iface (p2p0), ignoring
I/PCWCLIENTTRACE_PushUtil( 3456): SPPPushClient is installed : true
I/PCWCLIENTTRACE_PushUtil( 3456): sales region : global
I/PCWCLIENTTRACE_PushUtil( 3456): getPushTypeList : [SPP, GCM]
I/PCWCLIENTTRACE_SYSTEMReceiver( 3456): [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,I/splitIntent( 1018): Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=9, mSplitNum[1]=17, mSplitNum[2]=24, mBgSplitQueueNum=3 divideNum= 7 r.nextReceiver= 1 receivers.size=32
I/splitIntent( 1018): finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,D/lights  ( 1018): lcd : 254 -
,D/lights  ( 1018): lcd : 220 +
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,D/lights  ( 1018): lcd : 220 -
D/lights  ( 1018): lcd : 187 +
,E/Zygote  ( 4492): MountEmulatedStorage(),
E/Zygote  ( 4492): v2
I/libpersona( 4492): KNOX_SDCARD checking this for 10108
I/libpersona( 4492): KNOX_SDCARD not a persona
,I/SELinux ( 4492): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27,
,I/SELinux ( 4492): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.google.android.music:main for broadcast com.google.android.music/.homewidgets.IFLWidgetProvider: pid=4492 uid=10108 gids={50108, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,E/SELinux ( 4492): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4500): MountEmulatedStorage()
E/Zygote  ( 4500): v2
I/libpersona( 4500): KNOX_SDCARD checking this for 10077
,I/libpersona( 4500): KNOX_SDCARD not a persona
I/SELinux ( 4500): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/ActivityManager( 1018): Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=4500 uid=10077 gids={50077, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,I/SELinux ( 4500): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4500): [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
D/lights  ( 1018): lcd : 187 -
D/lights  ( 1018): lcd : 120 +
,D/lights  ( 1018): lcd : 120 -
D/lights  ( 1018): lcd : 87 +
,D/lights  ( 1018): lcd : 87 -
,D/lights  ( 1018): lcd : 54 +
,D/TimaKeyStoreProvider( 4492): TimaSignature is unavailable
,D/ActivityThread( 4492): Added TimaKeyStore provider
,D/lights  ( 1018): lcd : 54 -
,D/lights  ( 1018): lcd : 20 +
,I/DBG_POLICYDM( 4216): [com.policydm.XDMBroadcastReceiver(53/onReceive)] android.net.conn.CONNECTIVITY_CHANGE
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 15 -> 15
D/DisplayPowerController( 1018): animation target = 15, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,D/TimaKeyStoreProvider( 4500): TimaSignature is unavailable
,D/ActivityThread( 4500): Added TimaKeyStore provider
,D/lights  ( 1018): lcd : 20 -
D/lights  ( 1018): lcd : 15 +
,I/DBG_POLICYDM( 4216): [com.policydm.XDMApplication(463/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,I/DBG_POLICYDM( 4216): [com.policydm.XDMApplication(473/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,E/DBG_POLICYDM( 4216): [com.policydm.XDMBroadcastReceiver$2(109/run)] network is unserviceable
,E/DBG_POLICYDM( 4216): [com.policydm.XDMApplication(437/isNetworkChanged)] network not changed.... 
,D/lights  ( 1018): lcd : 15 -
,D/DisplayPowerController( 1018): getFinalBrightness : Summary is 15 -> 15
D/DisplayPowerController( 1018): animation target = 15, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,W/ResourceType( 1018): Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/SensorService( 1018): [SO] currT = 44391160000, prevT = 43961061000, diff = 430099000, [-0.364 0.038 9.902]
D/SensorService( 1018): [SO] -0.364 0.038 9.902
D/SensorService( 1018): [SO] [100 -> 255]
,E/SPPClientService( 4316): [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,I/SA      ( 4395): [OR] onReceive log=[SA = 2.1.0173 V = 21 HWD = 960X540 1.5 dpi = 240  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a3ulte P = a3ultexx I = LRX22G M = SM-A300FU OKLEFT false DIS LRX22G.A300FUXXU1BOEC PSS = 4.497050696380942  ]
,I/SA      ( 4395): [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
I/SA      ( 4395): [OR] == ACTION_CONNECTIVITY_CHANGE ==
,I/Timeline( 1018): Timeline: Activity_windows_visible id: ActivityRecord{24ac92b9 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t9} time:44408
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,I/iu.SyncManager( 2053): SYNC; picasa accounts
,D/CustomFrequencyManagerService( 1018): releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@11
,I/SA      ( 4395): [SLFUCHKMGR] constructor called
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/NetworkLogImpl( 2053): Loaded NetworkSpeedPredictor
,W/ResourcesManager( 1018): Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
W/ResourcesManager( 1018): Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/PackageManager( 1018): delete codoeFile: 
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
I/AASA_removePackage( 1018): UID=10333 Target=com.example.hello
D/AASAuninstall( 1018): userId = 0, info.removedAppID = -1, info.uid = 10333, packageName = com.example.hello
,D/PackageManager( 1018): result of delete: 1{180969712}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/AndroidRuntime( 4437): Shutting down VM
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,I/SA      ( 4395): [TPMU]  strSIMState 	:SIM_STATE_ABSENT
I/SA      ( 4395): [OR] == isSIMCardReady false ==
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,W/Resources( 1018): Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,D/UsbSettingsManager( 1018): clearDefaults: com.example.hello
I/CrashAnrDetector( 1018): onPackageRemoved : com.example.hello
,D/GpsLocationProvider( 1018): receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,D/ChimeraCfgMgr( 2053): Loading module com.google.android.gms.kids from APK com.google.android.gms
,I/SA      ( 4395): [SCU] == networkStateCheck == false
I/SA      ( 4395): [OR] onReceive END
,V/DownloadManager( 1228): onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
,W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,D/accuweather( 1701): [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4530): MountEmulatedStorage(),
E/Zygote  ( 4530): v2
I/libpersona( 4530): KNOX_SDCARD checking this for 10009
I/libpersona( 4530): KNOX_SDCARD not a persona
,I/SELinux ( 4530): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
,I/SELinux ( 4530): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027
I/ActivityManager( 1018): Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=4530 uid=10009 gids={50009, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,E/SELinux ( 4530): [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,I/Choreographer( 1480): Skipped 38 frames!  The application may be doing too much work on its main thread.
D/WallpaperManager( 1480): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/WallpaperManager( 1480): SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,D/TimaKeyStoreProvider( 4530): TimaSignature is unavailable
,D/ActivityThread( 4530): Added TimaKeyStore provider
,I/Timeline( 1480): Timeline: Activity_idle id: android.os.BinderProxy@c05e641 time:44578
,D/daemonapp( 1752): [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 54
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
E/ActivityManager( 1018): checkUser: useridlist=null, currentuser=0
,E/Zygote  ( 4546): MountEmulatedStorage()
,E/Zygote  ( 4546): v2
,I/libpersona( 4546): KNOX_SDCARD checking this for 10110
,I/libpersona( 4546): KNOX_SDCARD not a persona
,I/SELinux ( 4546): Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2 ver=27
I/ActivityManager( 1018): Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4546 uid=10110 gids={50110, 9997, 3003, 1028, 1015} abi=armeabi-v7a
I/ActivityManager( 1018): Killing 3664:com.google.android.onetimeinitializer/u0a13 (adj 15): empty #31
,D/accuweather( 1701): [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
D/accuweather( 1701): [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
D/accuweather( 1701): [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
D/accuweather( 1701): [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,I/SELinux ( 4546): Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2_0027,
,E/SELinux ( 4546): [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,D/accuweather( 1701): [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,D/accuweather( 1701): [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,D/TimaKeyStoreProvider( 4546): TimaSignature is unavailable
,D/ActivityThread( 4546): Added TimaKeyStore provider
,I/DBG_POLICYDM( 4216): [com.policydm.adapter.XDMTargetAdapter(158/xdmGetTargetCustomCode)] getSalesCode = XEO
,W/art     ( 4437): ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,I/DBG_POLICYDM( 4216): [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,I/DBG_POLICYDM( 4216): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,I/DBG_POLICYDM( 4216): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,I/DBG_POLICYDM( 4216): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,I/DBG_POLICYDM( 4216): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,I/DBG_POLICYDM( 4216): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,I/DBG_POLICYDM( 4216): [com.policydm.db.XDBFile(64/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,W/libprocessgroup( 1018): failed to open /acct/uid_10013/pid_3664/cgroup.procs: No such file or directory
,I/MusicStore( 4492): Database version: 104
,I/ActivityManager( 1018): Killing 3781:com.android.managedprovisioning/u0a20 (adj 15): empty #31
,I/DBG_DM  ( 3179): [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 9 sec
,W/ActivityManager( 1018): userId = 0, bbcId = -10000
,W/ActivityManager( 1018): NORMAL SET : dst_category = 701, src_allowCategory = 0,501-1023
W/ActivityManager( 1018): NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,E/WifiStateMachine( 1018): skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,W/libprocessgroup( 1018): failed to open /acct/uid_10020/pid_3781/cgroup.procs: No such file or directory
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4546): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4546): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4546): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,E/Vold    (  257): Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
W/Vold    (  257): Returning OperationFailed - no handler for errno 0
,W/ContextImpl( 4546): Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,W/ResourcesManager( 4492): Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,W/ResourcesManager( 4492): Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.

```
