#### Test 62947189e430ee9_thali01_samsung-SM-A500FU Logs


```
--------- beginning of main
03-15 19:11:30.164  3289  3289 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.youtube/files
--------- beginning of system
03-15 19:11:30.164   256   515 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.youtube/files/
03-15 19:11:30.164   256   515 W Vold    : Returning OperationFailed - no handler for errno 0
03-15 19:11:30.174  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:30.174  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:30.174  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
03-15 19:11:30.174  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
03-15 19:11:30.174  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
03-15 19:11:30.174  1018  1504 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
03-15 19:11:30.174  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:30.174  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:30.174  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:30.174  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:30.204  3817  3817 E Zygote  : MountEmulatedStorage()
03-15 19:11:30.204  3817  3817 E Zygote  : v2
03-15 19:11:30.204  3817  3817 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-15 19:11:30.204  3817  3817 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-15 19:11:30.204  3817  3817 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 19:11:30.204  3817  3817 I libpersona: KNOX_SDCARD checking this for 1000
03-15 19:11:30.204  3817  3817 I libpersona: KNOX_SDCARD not a persona
03-15 19:11:30.204  1018  1504 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=3817 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-15 19:11:30.214  1018  1504 I ActivityManager: Killing 3134:com.sec.android.app.factorykeystring/1000 (adj 15): empty #31
03-15 19:11:30.214  1018  1518 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-15 19:11:30.214  1018  1518 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
03-15 19:11:30.234  3817  3817 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 19:11:30.234  3817  3817 D ActivityThread: Added TimaKeyStore provider
03-15 19:11:30.244  3319  3549 I System.out: pool-10-thread-1 calls detatch()
03-15 19:11:30.264  3817  3817 E MTPRx   : In MtpReceiverandroid.intent.action.BOOT_COMPLETED
,03-15 19:11:30.264  1018  1030 D SecContentProvider2: uri = 14 selection = getSealedState
03-15 19:11:30.264  1018  1030 D SecContentProvider2: mCursor = null
03-15 19:11:30.264  1018  1337 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
03-15 19:11:30.264  1018  1337 D SecContentProvider2: mCursor = null
03-15 19:11:30.264  3817  3817 V MTPRx   : sealedState: false
03-15 19:11:30.264  3817  3817 V MTPRx   : sealedUsbMassStorageState: false
03-15 19:11:30.264  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3099/cgroup.procs: No such file or directory
03-15 19:11:30.264  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3071/cgroup.procs: No such file or directory
03-15 19:11:30.264  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3134/cgroup.procs: No such file or directory
03-15 19:11:30.264  1018  1030 D SettingsProvider: name = mtp_usb_connection_status
03-15 19:11:30.284  1018  1346 D SettingsProvider: name = media_player_mode
03-15 19:11:30.284  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-15 19:11:30.294  1018  1504 D SettingsProvider: name = mtp_usb_conditions_met
03-15 19:11:30.304  1018  1337 D SettingsProvider: name = mtp_running_status
03-15 19:11:30.304  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-15 19:11:30.314  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-15 19:11:30.314  1018  1129 D SettingsProvider: name = media_mount_count
03-15 19:11:30.324  1018  1346 D SettingsProvider: name = mtp_sync_alive
03-15 19:11:30.324  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-15 19:11:30.324  1018  1337 D SettingsProvider: name = sdcard_launch
03-15 19:11:30.334  1018  1031 D SettingsProvider: name = boot_time_connected
03-15 19:11:30.344  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-15 19:11:30.344  1018  1129 D SettingsProvider: name = mtp_open_session
03-15 19:11:30.354  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-15 19:11:30.354  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-15 19:11:30.364  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
03-15 19:11:30.374  3467  3467 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-15 19:11:30.374  3467  3467 I PCWCLIENTTRACE_PushUtil: sales region : global
03-15 19:11:30.374  3467  3467 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-15 19:11:30.374  3467  3467 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.BOOT_COMPLETED
03-15 19:11:30.374  3467  3467 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Version: 4.82
03-15 19:11:30.374  3467  3467 D PCWCLIENTTRACE_SYSTEMReceiver: ACTION_BOOTUP - Push type: [SPP, GCM]
03-15 19:11:30.374  1018  1952 D ActivityManager: startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
03-15 19:11:30.374  1018  1952 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
03-15 19:11:30.374  1018  1952 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:30.374  1018  1952 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:30.384  1018  1952 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
03-15 19:11:30.384  3178  3207 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 2 sec
03-15 19:11:30.394  3677  3858 I Gmail   : getAccountsCursor
03-15 19:11:30.394  1018  1266 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
03-15 19:11:30.394  1018  1744 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
03-15 19:11:30.394  1018  1744 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
03-15 19:11:30.404  1931  1931 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-15 19:11:30.404  3467  3467 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
03-15 19:11:30.424  3467  3467 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
03-15 19:11:30.434  3467  3467 I ReactiveServiceManager: Supported : 1
03-15 19:11:30.434  1018  1705 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x2040
03-15 19:11:30.434  3677  3677 W GAV2    : Thread[main,5,main]: Need to call initialize() and be in fallback mode to start dispatch.
03-15 19:11:30.434  1018  1705 D QSEECOMAPI: : App is not loaded in QSEE
03-15 19:11:30.454  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
03-15 19:11:30.454  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.libraries.youtube.upload.service.UploadService; callingUser = 0; userId(target) = 0
03-15 19:11:30.454  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:30.454  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:30.454  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
03-15 19:11:30.454  1018  1266 D ActivityManager: startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
03-15 19:11:30.454  1018  1266 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.app.offline.transfer.OfflineTransferService; callingUser = 0; userId(target) = 0
03-15 19:11:30.454  1018  1266 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:30.454  1018  1266 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:30.454  1018  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
03-15 19:11:30.464  1018  1705 D QSEECOMAPI: : Loaded image: APP id = 9
03-15 19:11:30.464  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
03-15 19:11:30.464  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
03-15 19:11:30.474  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:30.474  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:30.474  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
03-15 19:11:30.474  1018  1705 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-15 19:11:30.474  1018  1705 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 9
03-15 19:11:30.474  1018  1705 E terrier : handleString: Failed to handle string(-4)
03-15 19:11:30.474  1018  1705 E terrier : Java_com_android_server_ReactiveService_GetString: error code = [-4]
03-15 19:11:30.474  3467  3467 D PCWCLIENTTRACE_SecurePreferencesJNI: getString is null
03-15 19:11:30.474  3467  3467 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
03-15 19:11:30.484  3467  3467 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
03-15 19:11:30.484  3467  3467 I PCWCLIENTTRACE_PushUtil: sales region : global
03-15 19:11:30.484  3467  3467 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-15 19:11:30.484  3467  3467 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
03-15 19:11:30.484  1018  1518 D ActivityManager: startProcessLocked calleePkgName: com.vlingo.midas, hostingType: broadcast
03-15 19:11:30.484  1018  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:30.484  1018  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:30.484  1018  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:30.484  1018  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:30.504  3868  3868 E Zygote  : MountEmulatedStorage()
03-15 19:11:30.504  3868  3868 I libpersona: KNOX_SDCARD checking this for 10031
03-15 19:11:30.504  3868  3868 E Zygote  : v2
03-15 19:11:30.504  3868  3868 I libpersona: KNOX_SDCARD not a persona
03-15 19:11:30.504  3868  3868 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-15 19:11:30.504  1965  1965 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.qualcomm.qti.services.secureui.BootReceiver.onReceive:30 android.app.ActivityThread.handleReceiver:3125 
03-15 19:11:30.504  3868  3868 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-15 19:11:30.504  3868  3868 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-15 19:11:30.504  1018  1518 I ActivityManager: Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.vlingo.core.facade.lmtt.LmttReceiver: pid=3868 uid=10031 gids={50031, 9997, 1028, 1015, 3003, 3002, 3001} abi=armeabi-v7a
03-15 19:11:30.514  1018  1518 I ActivityManager: Killing 3153:com.sec.android.diagmonagent/1000 (adj 15): empty #31
03-15 19:11:30.514  1018  1346 D ActivityManager: startService callerProcessName:com.qualcomm.qti.services.secureui, calleePkgName: com.qualcomm.qti.services.secureui
03-15 19:11:30.514  1018  1346 D ActivityManager: retrieveServiceLocked(): component = com.qualcomm.qti.services.secureui/com.qualcomm.qti.services.secureui.SecureUIService; callingUser = 0; userId(target) = 0
03-15 19:11:30.514  1018  1346 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:30.514  1018  1346 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:30.514  1018  1346 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service, destAppInfo.processName = com.qualcomm.qti.services.secureui:sui_service
03-15 19:11:30.514  1965  1965 D SecUISvc: Service started flags 0 startId 1
03-15 19:11:30.514  1018  1030 D ActivityManager: startProcessLocked calleePkgName: com.android.vending, hostingType: broadcast
03-15 19:11:30.524  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:30.524  1965  3877 D SecUISvc: Thread created.
03-15 19:11:30.524  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:30.524  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:30.524  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:30.534  3868  3868 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 19:11:30.534  3868  3868 D ActivityThread: Added TimaKeyStore provider
03-15 19:11:30.534   308   308 I art     : Explicit concurrent mark sweep GC freed 8737(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 664us total 27.760ms
03-15 19:11:30.544  3853  3853 D AndroidRuntime: 
03-15 19:11:30.544  3853  3853 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-15 19:11:30.544  3853  3853 D AndroidRuntime: CheckJNI is OFF
03-15 19:11:30.544  3853  3853 D AndroidRuntime: readGMSProperty: start
03-15 19:11:30.544  3853  3853 D AndroidRuntime: readGMSProperty: already setted!!
03-15 19:11:30.544  3853  3853 D AndroidRuntime: propertySet: couldn't set property (it is from app)
03-15 19:11:30.544  3853  3853 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
03-15 19:11:30.544  3853  3853 D AndroidRuntime: readGMSProperty: end
03-15 19:11:30.544  3853  3853 D AndroidRuntime: addProductProperty: start
03-15 19:11:30.564   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 637us total 18.871ms
03-15 19:11:30.574  3289  3861 D AndroidHttpClient: [NALSECURITY] isMmsRequest() : CoreProtocolPNames.USER_AGENT = Dalvik/2.1.0 (Linux; U; Android 5.0.2; SM-A500FU Build/LRX22G)
03-15 19:11:30.574  3289  3861 D AndroidHttpClient: [NALSECURITY] checkMmsSendPermission() : isMmsRequest() = false method = GET
03-15 19:11:30.574  3289  3861 I System.out: Thread-496(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
03-15 19:11:30.574  3289  3861 I System.out: Thread-496(ApacheHTTPLog):isSBSettingEnabled false
03-15 19:11:30.574  3289  3861 I System.out: Thread-496(ApacheHTTPLog):isShipBuild true
03-15 19:11:30.574  3289  3861 I System.out: Thread-496(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-15 19:11:30.574  3289  3861 I System.out: Thread-496(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-15 19:11:30.574   277   951 D EnterpriseController: uids 10166
03-15 19:11:30.574   277   951 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-15 19:11:30.574   277   951 D Netd    : getNetworkForDns: using netid 502 for uid 10166
03-15 19:11:30.574   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 615us total 17.429ms
03-15 19:11:30.594  3890  3890 E Zygote  : MountEmulatedStorage()
03-15 19:11:30.594  3890  3890 E Zygote  : v2
03-15 19:11:30.594  3890  3890 I libpersona: KNOX_SDCARD checking this for 10028
03-15 19:11:30.594  3890  3890 I libpersona: KNOX_SDCARD not a persona
03-15 19:11:30.594  3890  3890 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-15 19:11:30.594  1018  1030 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.BootCompletedReceiver: pid=3890 uid=10028 gids={50028, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-15 19:11:30.594  3890  3890 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-15 19:11:30.604  3890  3890 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-15 19:11:30.604  1018  1504 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.AttachmentService; callingUser = 0; userId(target) = 0
03-15 19:11:30.604  1018  1504 W ActivityManager: Unable to start service Intent { cmp=com.google.android.gm/com.android.email.service.AttachmentService } U=0: not found
03-15 19:11:30.614  1018  1705 D ActivityManager: startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
03-15 19:11:30.614  1018  1705 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.EmailMigrationService; callingUser = 0; userId(target) = 0
03-15 19:11:30.614  1018  1705 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:30.614  1018  1705 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:30.614  1018  1705 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
03-15 19:11:30.624  1018  1030 I ActivityManager: Killing 1590:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
03-15 19:11:30.624  1018  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-15 19:11:30.624  1018  1031 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
03-15 19:11:30.634  1018  1018 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 com.dsi.ant.server.startup.BootCompletedReceiver.onReceive:41 
03-15 19:11:30.634  1018  1018 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.dsi.ant.server.IAntHal } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.dsi.ant.server.AntService.startService:135 
03-15 19:11:30.634  1018  1018 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-15 19:11:30.634  3890  3890 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 19:11:30.634  3890  3890 D ActivityThread: Added TimaKeyStore provider
03-15 19:11:30.634  2627  2627 D FactoryTestApp: [DummyFtClient$onDestroy](2627) Destroy DummyFtClient service
03-15 19:11:30.644  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
03-15 19:11:30.644  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:30.644  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:30.644  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:30.644  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:30.654  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3153/cgroup.procs: No such file or directory
03-15 19:11:30.654  3677  3901 I Gmail   : Observing account changes for notifications
03-15 19:11:30.654  3868  3868 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-15 19:11:30.664  3914  3914 E Zygote  : MountEmulatedStorage()
03-15 19:11:30.664  3914  3914 I libpersona: KNOX_SDCARD checking this for 1000
03-15 19:11:30.664  3914  3914 E Zygote  : v2
03-15 19:11:30.664  3914  3914 I libpersona: KNOX_SDCARD not a persona
03-15 19:11:30.664  3914  3914 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-15 19:11:30.674  3914  3914 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-15 19:11:30.674  3914  3914 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 19:11:30.674  1018  1018 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=3914 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-15 19:11:30.694  1018  1346 D ActivityManager: startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
03-15 19:11:30.694  1018  1346 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GoogleMailSwitchService; callingUser = 0; userId(target) = 0
03-15 19:11:30.694  1018  1346 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:30.694  1018  1346 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:30.694  1018  1346 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
03-15 19:11:30.694  1018  1952 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-15 19:11:30.694  1018  1952 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
03-15 19:11:30.704  2627  2627 D FactoryTestApp: [Support$Values.getString](2627) id=MODEL_COMMUNICATION_MODE, value=gsm
03-15 19:11:30.704  2627  2627 I FactoryTestApp: [ModuleCommon$isConnectionModeNone](2627) mConnectionMode = gsm
03-15 19:11:30.704  2627  2627 I FactoryTestApp: [ModuleCommon$isRunningFtClient](2627) RUNNING_FTCLIENT : false
03-15 19:11:30.704  2627  2627 D FactoryTestApp: [DummyFtClient$onDestroy](2627) kill process
03-15 19:11:30.704  2627  2627 I Process : Sending signal. PID: 2627 SIG: 9
03-15 19:11:30.704  3914  3914 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 19:11:30.704  3914  3914 D ActivityThread: Added TimaKeyStore provider
03-15 19:11:30.704  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.youtube, calleePkgName: com.google.android.youtube
03-15 19:11:30.704  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.youtube/com.google.android.apps.youtube.core.player.preload.PreloadVideosTransferService; callingUser = 0; userId(target) = 0
03-15 19:11:30.704  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:30.704  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:30.704  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.youtube, destAppInfo.processName = com.google.android.youtube
03-15 19:11:30.714  1018  1346 I ActivityManager: Killing 3169:com.sec.providers.settingsearch/u0a150 (adj 15): empty #31
03-15 19:11:30.724  3853  3853 E AffinityControl: AffinityControl: registerfunction enter
03-15 19:11:30.744  1018  1043 W libprocessgroup: failed to open /acct/uid_10072/pid_1590/cgroup.procs: No such file or directory
03-15 19:11:30.744  1018  1346 D ActivityManager: startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
03-15 19:11:30.754  1018  1346 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.google.android.gm.GmailIntentService; callingUser = 0; userId(target) = 0
03-15 19:11:30.754  1018  1346 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:30.754  1018  1346 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:30.754  1018  1346 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
03-15 19:11:30.754  3853  3853 D AndroidRuntime: Calling main entry com.android.commands.am.Am
03-15 19:11:30.764  3677  3930 E Gmail   : Error finding the version of the Email provider.....
03-15 19:11:30.764  3677  3930 E Gmail   : android.content.pm.PackageManager$NameNotFoundException: com.google.android.email
03-15 19:11:30.764  3677  3930 E Gmail   : 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:165)
03-15 19:11:30.764  3677  3930 E Gmail   : 	at com.google.android.gm.EmailMigrationService.a(SourceFile:1240)
03-15 19:11:30.764  3677  3930 E Gmail   : 	at com.google.android.gm.EmailMigrationService.onHandleIntent(SourceFile:188)
03-15 19:11:30.764  3677  3930 E Gmail   : 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-15 19:11:30.764  3677  3930 E Gmail   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 19:11:30.764  3677  3930 E Gmail   : 	at android.os.Looper.loop(Looper.java:145)
03-15 19:11:30.764  3677  3930 E Gmail   : 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-15 19:11:30.764  3677  3930 W EmailMigration: We do not support migrating this version of the Email provider.
03-15 19:11:30.764  1018  1744 E PersonaManagerService: inState():  stateMachine is null !!
03-15 19:11:30.764  1018  1744 I PersonaManagerService: PersonaId don't exist
03-15 19:11:30.764  1018  1744 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
03-15 19:11:30.774  3677  3933 I Gmail   : getAccountsCursor
03-15 19:11:30.774  1018  1744 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-15 19:11:30.794  1018  1744 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-15 19:11:30.804  1018  1744 W ActivityManager: mDVFSHelper.acquire()
03-15 19:11:30.804  1018  1744 D FocusedStackFrame: Set to : 0
03-15 19:11:30.804  1509  1509 D Launcher.HomeView: onPause
03-15 19:11:30.804  1018  1744 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-15 19:11:30.804  1018  1744 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-15 19:11:30.804  1018  1744 D InputDispatcher: Focused application set to: xxxx
03-15 19:11:30.814  1018  1744 D InputDispatcher: Focus left window: 1509
03-15 19:11:30.814  3853  3853 D AndroidRuntime: Shutting down VM
03-15 19:11:30.814  1509  1509 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
03-15 19:11:30.814  1018  1051 D PhoneWindow: *FMB* installDecor mIsFloating : false
03-15 19:11:30.814  1018  1051 D PhoneWindow: *FMB* installDecor flags : -2122120936
03-15 19:11:30.814  1018  1952 D ActivityManager: startService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gm
03-15 19:11:30.814  1018  1952 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gm/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
03-15 19:11:30.814  1018  1952 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:30.814  1018  1952 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:30.814  1018  1952 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gm
03-15 19:11:30.814  1018  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-15 19:11:30.814  1018  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
03-15 19:11:30.824  1018  1030 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
03-15 19:11:30.824  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
03-15 19:11:30.824  1018  1051 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-15 19:11:30.824  1018  1051 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
03-15 19:11:30.824   257   257 I SurfaceFlinger: id=10 createSurf (1x1),1 flag=404, uhalitest
03-15 19:11:30.834  1931  1931 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
03-15 19:11:30.834  1018  1266 I ActivityManager: Process com.sec.factory (pid 2627)(adj 0) has died(136,1114)
03-15 19:11:30.834  1018  1043 W libprocessgroup: failed to open /acct/uid_10150/pid_3169/cgroup.procs: No such file or directory
03-15 19:11:30.834  1018  1346 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
03-15 19:11:30.834  1018  1346 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
03-15 19:11:30.844  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:30.844  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:30.844  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:30.844  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:30.864  3938  3938 E Zygote  : MountEmulatedStorage()
03-15 19:11:30.864  3938  3938 I libpersona: KNOX_SDCARD checking this for 10155
03-15 19:11:30.864  3938  3938 E Zygote  : v2
03-15 19:11:30.864  3938  3938 I libpersona: KNOX_SDCARD not a persona
03-15 19:11:30.864  3938  3938 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-15 19:11:30.864  1018  1031 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=3938 uid=10155 gids={50155, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-15 19:11:30.864  3938  3938 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-15 19:11:30.864  3938  3938 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
03-15 19:11:30.874  1018  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-15 19:11:30.874  1018  1030 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
03-15 19:11:30.884  1018  1337 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.syncadapters.contacts
03-15 19:11:30.884  1018  1337 D ActivityManager: retrieveServiceLocked(): component = com.google.android.syncadapters.contacts/com.google.android.syncadapters.contacts.ContactsSyncAdapterIntentService; callingUser = 0; userId(target) = 0
03-15 19:11:30.884  1018  1337 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:30.884  1018  1337 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:30.884  1018  1337 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.process.gapps
03-15 19:11:30.894  1509  1509 V ActivityThread: updateVisibility : ActivityRecord{c4d2464 token=android.os.BinderProxy@88e805f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
03-15 19:11:30.904  1018  1518 I ActivityManager: Killing 3034:com.sec.android.app.clockpackage/u0a85 (adj 15): empty #31
03-15 19:11:30.904  1018  1518 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
03-15 19:11:30.904  1018  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:30.904  1018  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:30.904  1018  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:30.904  1018  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:30.914  1678  3951 I GoogleHttpClient: GMS http client unavailable, use old client
03-15 19:11:30.914  3938  3938 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 19:11:30.914  3938  3938 D ActivityThread: Added TimaKeyStore provider
03-15 19:11:30.924  3958  3958 E Zygote  : MountEmulatedStorage()
03-15 19:11:30.924  3958  3958 E Zygote  : v2
03-15 19:11:30.924  3958  3958 I libpersona: KNOX_SDCARD checking this for 10104
03-15 19:11:30.924  3958  3958 I libpersona: KNOX_SDCARD not a persona
03-15 19:11:30.924  3958  3958 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-15 19:11:30.924  1018  1518 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.BootReceiver: pid=3958 uid=10104 gids={50104, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
03-15 19:11:30.924  1018  1504 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
03-15 19:11:30.924  1018  1504 W ActivityManager: Unable to start service Intent { act=com.google.android.gm.email.EXCHANGE_INTENT pkg=com.google.android.gm.exchange } U=0: not found
03-15 19:11:30.924  3958  3958 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-15 19:11:30.924  3958  3958 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-15 19:11:30.934  1018  1030 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-15 19:11:30.934  1018  1030 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
03-15 19:11:30.934  1018  1030 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-15 19:11:30.944  1509  1509 D Launcher.HomeView: onStop
03-15 19:11:30.944  1018  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-15 19:11:30.954  1509  1509 V ActivityThread: updateVisibility : ActivityRecord{c4d2464 token=android.os.BinderProxy@88e805f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-15 19:11:30.954  1018  1030 D PersonaManager: isKioskContainerExistOnDevice
03-15 19:11:30.954  3958  3958 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 19:11:30.954  3958  3958 D ActivityThread: Added TimaKeyStore provider
03-15 19:11:30.954  3914  3914 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:53 android.app.ActivityThread.handleReceiver:3125 
03-15 19:11:30.974  1018  1504 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
03-15 19:11:30.974  1018  1504 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.assistantmenu/com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService; callingUser = 0; userId(target) = 0
03-15 19:11:30.984  3677  3677 E ActivityThread: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@1aeda821 that was originally bound here
03-15 19:11:30.984  3677  3677 E ActivityThread: android.app.ServiceConnectionLeaked: Service com.android.email.service.EmailBroadcastProcessorService has leaked ServiceConnection com.android.emailcommon.service.aj@1aeda821 that was originally bound here
03-15 19:11:30.984  3677  3677 E ActivityThread: 	at android.app.LoadedApk$ServiceDispatcher.<init>(LoadedApk.java:1144)
03-15 19:11:30.984  3677  3677 E ActivityThread: 	at android.app.LoadedApk.getServiceDispatcher(LoadedApk.java:1038)
03-15 19:11:30.984  3677  3677 E ActivityThread: 	at android.app.ContextImpl.bindServiceCommon(ContextImpl.java:2154)
03-15 19:11:30.984  3677  3677 E ActivityThread: 	at android.app.ContextImpl.bindService(ContextImpl.java:2137)
03-15 19:11:30.984  3677  3677 E ActivityThread: 	at android.content.ContextWrapper.bindService(ContextWrapper.java:559)
03-15 19:11:30.984  3677  3677 E ActivityThread: 	at com.android.emailcommon.service.ah.a(SourceFile:181)
03-15 19:11:30.984  3677  3677 E ActivityThread: 	at com.android.emailcommon.service.ah.e(SourceFile:224)
03-15 19:11:30.984  3677  3677 E ActivityThread: 	at com.android.email.service.n.c(SourceFile:161)
03-15 19:11:30.984  3677  3677 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:173)
03-15 19:11:30.984  3677  3677 E ActivityThread: 	at com.android.email.provider.b.a(SourceFile:117)
03-15 19:11:30.984  3677  3677 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.c(SourceFile:318)
03-15 19:11:30.984  3677  3677 E ActivityThread: 	at com.android.email.service.EmailBroadcastProcessorService.onHandleIntent(SourceFile:1308)
03-15 19:11:30.984  3677  3677 E ActivityThread: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
03-15 19:11:30.984  3677  3677 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 19:11:30.984  3677  3677 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-15 19:11:30.984  3677  3677 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
03-15 19:11:30.984  1018  1504 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:30.984  1018  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:30.984  1018  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.assistantmenu, destAppInfo.processName = com.samsung.android.app.assistantmenu
03-15 19:11:30.994  1018  1030 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.bbc.bbcagent, hostingType: broadcast
03-15 19:11:30.994  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:30.994  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:30.994  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:30.994  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:31.014  1018  1030 I ActivityManager: Start proc com.samsung.android.bbc.bbcagent for broadcast com.samsung.android.bbc.bbcagent/.bbccontroller.receiver.BootCompletedReceiver: pid=3975 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-15 19:11:31.014  1018  1518 W ActivityManager: Unbind failed: could not find connection for android.os.BinderProxy@d3afa29
03-15 19:11:31.024  3975  3975 E Zygote  : MountEmulatedStorage()
03-15 19:11:31.024  3975  3975 I libpersona: KNOX_SDCARD checking this for 1000
03-15 19:11:31.024  3975  3975 E Zygote  : v2
03-15 19:11:31.024  3975  3975 I libpersona: KNOX_SDCARD not a persona
03-15 19:11:31.024  3975  3975 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-15 19:11:31.024  3853  3853 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
03-15 19:11:31.034  3975  3975 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-15 19:11:31.034  1509  1509 D Launcher: onTrimMemory. Level: 20
,03-15 19:11:31.034  3975  3975 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 19:11:31.034  3868  3868 I VlingoApplication: VlingoApplication appVersion ='11.7.0.1.40254', coreVersion = '2.6.3.16956', ro.csc.sales_code=XEO
,03-15 19:11:31.044  3958  3958 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-15 19:11:31.064  3975  3975 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:31.064  3975  3975 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:31.064  1018  1043 W libprocessgroup: failed to open /acct/uid_10085/pid_3034/cgroup.procs: No such file or directory
,03-15 19:11:31.204  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
03-15 19:11:31.204  1018  1018 D SensorService: [SO] activate (ident=0xb94af8a8, enabled=0)
03-15 19:11:31.204  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-15 19:11:31.214  1018  1018 D SensorManager: unregisterListener ::   
,03-15 19:11:31.214  1018  1018 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
,03-15 19:11:31.214  1018  1018 D SensorService: [SO] changed settle time [1]
03-15 19:11:31.214  1018  1018 D SensorService: [SO] setDelay [66000000]
03-15 19:11:31.214  1018  1018 D SensorService: [SO] activate (ident=0xb94af8a8, enabled=1)
03-15 19:11:31.214  1018  1018 D SensorService: [SO] AR_init
03-15 19:11:31.214  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-15 19:11:31.224  3868  3868 I VlingoAndroidCore: AppName: SamsungTproject, Core: 2.6.3.16956, SDK: 2.0.2173, EDM:16956
,03-15 19:11:31.224  1018  1018 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,03-15 19:11:31.244  3677  3934 E SQLiteLog: (283) recovered 68 frames from WAL file /data/data/com.google.android.gm/databases/mailstore.thalitester@gmail.com.db-wal
,03-15 19:11:31.264  3938  3938 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,03-15 19:11:31.284  3938  3938 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 2813-2815)
03-15 19:11:31.284  3938  3938 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-15 19:11:31.294  1018  1041 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-15 19:11:31.364  1018  1041 D SensorService: [SO] 0.153 0.402 10.132
,03-15 19:11:31.364  3677  3934 E File    : fail readDirectory() errno=2
03-15 19:11:31.364  1018  1041 D SensorService: [SO] [100 -> 255]
,03-15 19:11:31.364  3677  3990 I Gmail   : notifyAccountChanged
,03-15 19:11:31.374  1018  1337 I art     : Explicit concurrent mark sweep GC freed 32681(1792KB) AllocSpace objects, 2(38KB) LOS objects, 33% free, 26MB/40MB, paused 3.044ms total 260.293ms
,03-15 19:11:31.374  1018  1337 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
03-15 19:11:31.374  1018  1337 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-15 19:11:31.384  3289  3861 I System.out: Thread-496 calls detatch()
,03-15 19:11:31.384  3178  3207 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 3 sec
,03-15 19:11:31.394   257  1795 I SurfaceFlinger: id=8 Removed Mauncher (5/8)
,03-15 19:11:31.394   257   438 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
,03-15 19:11:31.404  1931  1931 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 19:11:31.414  3938  3938 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {250481c5},
,03-15 19:11:31.414  3938  3938 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-15 19:11:31.414  3938  3938 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,03-15 19:11:31.414  3975  3975 W ResourcesManager: Asset path '/system/framework/com.samsung.bbccommon.jar' does not exist or contains no resources.
,03-15 19:11:31.434  3677  3994 I Gmail   : getAccountsCursor
,03-15 19:11:31.434  3677  3990 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-15 19:11:31.444  1018  1744 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
03-15 19:11:31.444  1018  1744 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-15 19:11:31.454  1931  1931 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 19:11:31.464  1018  1504 D ActivityManager: bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: null
,03-15 19:11:31.464  3938  3938 I BrowserStartupController: Initializing chromium process, singleProcess=true
03-15 19:11:31.464  1018  1504 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,03-15 19:11:31.464  1018  1504 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:31.464  3938  3938 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-15 19:11:31.464  1018  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:31.464  1018  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-15 19:11:31.464  3938  3938 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-15 19:11:31.474  1931  1931 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 19:11:31.474  1931  1931 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 19:11:31.484  3677  3990 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: queueing
,03-15 19:11:31.494  3938  3938 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,03-15 19:11:31.494  3938  3938 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
03-15 19:11:31.494  3938  3938 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,03-15 19:11:31.504  3938  3938 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-15 19:11:31.504  3938  3938 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-15 19:11:31.504  3938  3938 I Adreno-EGL: Build Date: 04/06/15 Mon
03-15 19:11:31.504  3938  3938 I Adreno-EGL: Local Branch: 
03-15 19:11:31.504  3938  3938 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-15 19:11:31.504  3938  3938 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-15 19:11:31.504  3938  3938 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-15 19:11:31.554  1018  1952 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 19:11:31.554  1018  1952 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:31.554  1018  1952 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-15 19:11:31.554  1018  1952 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:31.574  3868  3868 D VlingoApplication: sac sec ensureCacheEmpty() car_iux_tts_cacheing_required set to false
,03-15 19:11:31.574  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.SBrowserMainActivity
03-15 19:11:31.574  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:31.574  3914  3973 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-15 19:11:31.574  3914  3973 I AMMetaDataParserService: getResourcePackageName:assistantlist
03-15 19:11:31.574  3914  3973 I AMMetaDataParserService: Resource data:2131165186
,03-15 19:11:31.574  3868  3868 D VlingoApplication: sac sec ensureCacheEmpty() purged 0 historically cached TTS files
,03-15 19:11:31.594  3868  3868 D DialogFlow: initQueue()
,03-15 19:11:31.614  3914  3973 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-15 19:11:31.614  3914  3973 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 19:11:31.614  3914  3973 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,03-15 19:11:31.614  3914  3973 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-15 19:11:31.614  3914  3973 I AMMetaDataParserService: getResourceName:com.sec.android.app.sbrowser:xml/assistantlist
03-15 19:11:31.614  3914  3973 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 19:11:31.624  3256  3345 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
03-15 19:11:31.624  3677  3990 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
03-15 19:11:31.624  3677  3990 I Gmail   : calculateUnknownSyncRationalesAndPurgeInBackground: running
03-15 19:11:31.634  3914  3973 I AMMetaDataParserService: Icon data: ResourceEnter URL2131755289android.intent.action.doInputURL2130837509
,03-15 19:11:31.644  3256  3345 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-15 19:11:31.644  3256  3345 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,03-15 19:11:31.644  3256  3345 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-15 19:11:31.654  3256  3286 I art     : WaitForGcToComplete blocked for 99.985ms for cause HomogeneousSpaceCompact
,03-15 19:11:31.664  3938  4010 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,03-15 19:11:31.664  1018  1346 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,03-15 19:11:31.674  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:31.674  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:31.674  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:31.674  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:31.684  3256  3345 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-15 19:11:31.684  3256  3345 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-15 19:11:31.684  3256  3345 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-15 19:11:31.684  4019  4019 E Zygote  : MountEmulatedStorage(),
03-15 19:11:31.684  4019  4019 E Zygote  : v2
03-15 19:11:31.684  4019  4019 I libpersona: KNOX_SDCARD checking this for 10032
03-15 19:11:31.684  4019  4019 I libpersona: KNOX_SDCARD not a persona
,03-15 19:11:31.694  1018  1346 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder:tagService for broadcast com.samsung.android.app.galaxyfinder/.tag.TagReadyReceiver: pid=4019 uid=10032 gids={50032, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a,
03-15 19:11:31.694  4019  4019 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-15 19:11:31.694  1018  1346 I ActivityManager: Killing 3221:com.samsung.android.app.colorblind/1000 (adj 15): empty #31
,03-15 19:11:31.694  4019  4019 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-15 19:11:31.694  4019  4019 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 19:11:31.704  3914  3973 I AMMetaDataParserService: Icon data: ResourceTabs2131755155android.intent.action.doWindowManager2130837511
,03-15 19:11:31.744  4019  4019 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:31.744  4019  4019 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:31.744  3914  3973 I AMMetaDataParserService: Icon data: ResourceNew Tab2131755460android.intent.action.doNewWindow2130837510
,03-15 19:11:31.774  3938  3938 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-15 19:11:31.774  3890  3890 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,03-15 19:11:31.804  3677  3858 I Gmail   : getAccountsCursor
,03-15 19:11:31.804  1018  1952 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.accounts.AccountAuthenticator
,03-15 19:11:31.804  1018  1952 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GoogleAccountAuthenticatorService; callingUser = 0; userId(target) = 0
,03-15 19:11:31.824  3938  3938 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-15 19:11:31.834  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3221/cgroup.procs: No such file or directory
,03-15 19:11:31.834  3938  3938 D PhoneWindow: *FMB* installDecor mIsFloating : false
,03-15 19:11:31.834  3938  3938 D PhoneWindow: *FMB* installDecor flags : -2139027200
,03-15 19:11:31.844  3938  3938 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,03-15 19:11:31.854  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappManager
03-15 19:11:31.854  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity
03-15 19:11:31.854  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity0
03-15 19:11:31.854  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity1
03-15 19:11:31.854  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity2
03-15 19:11:31.854  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity3
03-15 19:11:31.854  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity4
03-15 19:11:31.854  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity5
03-15 19:11:31.854  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity6
03-15 19:11:31.854  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity7
03-15 19:11:31.854  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity8
03-15 19:11:31.854  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.webapp.WebappActivity9
03-15 19:11:31.854  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.history.ui.HistoryActivity
03-15 19:11:31.854  3914  3973 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-15 19:11:31.854  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.Settings
03-15 19:11:31.854  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.reader.ui.ReaderActivity
03-15 19:11:31.854  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.menuactivity.ui.AddWebPageMenuActivity
03-15 19:11:31.854  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.activity.ReadingListActivity
03-15 19:11:31.854  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.readinglist.controller.ReadingListSearchActivity
03-15 19:11:31.854  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.sites.SitesActivity
03-15 19:11:31.854  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.common.DataChargingDialog
03-15 19:11:31.854  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.EditBookmarkFolderActivity
03-15 19:11:31.854  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.AddBookmarkActivity
03-15 19:11:31.854  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.ShowBookmarksActivity
03-15 19:11:31.854  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.,SelectBookmarkFolderActivity
03-15 19:11:31.854  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.bookmarksDb.ui.CreateBookmarkFolderActivity
03-15 19:11:31.854  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SynctabActivity
03-15 19:11:31.854  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.SelectSyncAccountActivity
03-15 19:11:31.854  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.preferences.AutofillFormEdit
03-15 19:11:31.854  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.synctab.ui.DeleteSyncTabActivity
03-15 19:11:31.854  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountGetStartedActivity
03-15 19:11:31.854  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountActivity
03-15 19:11:31.854  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountConfirmAccountActivity
03-15 19:11:31.854  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountSignInActivity
03-15 19:11:31.854  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountVerifiedAccountActivity
03-15 19:11:31.854  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.sbrowser.firefox.FxAccountCreateAccountNotAllowedActivity
03-15 19:11:31.864  3938  3938 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-15 19:11:31.864  3938  3938 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-15 19:11:31.864  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.sns3, hostingType: broadcast
03-15 19:11:31.864  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:31.864  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:31.864  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:31.864  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:31.884  4045  4045 E Zygote  : MountEmulatedStorage()
03-15 19:11:31.884  4045  4045 I libpersona: KNOX_SDCARD checking this for 10033
03-15 19:11:31.884  4045  4045 E Zygote  : v2
03-15 19:11:31.884  4045  4045 I libpersona: KNOX_SDCARD not a persona
03-15 19:11:31.884  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.PeopleActivity
03-15 19:11:31.884  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:31.884  3914  3973 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 19:11:31.884  3914  3973 I AMMetaDataParserService: Resource data:2131034113
03-15 19:11:31.884  3914  3973 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-15 19:11:31.884  3914  3973 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-15 19:11:31.884  3914  3973 I AMMetaDataParserService: getResourceTypeNamexml
03-15 19:11:31.884  3914  3973 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 19:11:31.884  3914  3973 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
03-15 19:11:31.884  1018  1031 I ActivityManager: Start proc com.sec.android.app.sns3 for broadcast com.sec.android.app.sns3/.SnsBroadcastReceiver: pid=4045 uid=10033 gids={50033, 9997, 1028, 1015, 3003} abi=armeabi-v7a
03-15 19:11:31.884  1018  1031 I ActivityManager: Killing 3256:com.policydm/1000 (adj 15): empty #31
,03-15 19:11:31.934  4045  4045 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-15 19:11:31.934  4045  4045 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-15 19:11:31.944  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 19:11:31.944  4045  4045 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-15 19:11:31.944  3938  4055 D OpenGLRenderer: Render dirty regions requested: true
,03-15 19:11:31.944  3914  3973 I GFX construct_block_size_descriptor_2d second part: took 2.503593ms for 0*0 texture 0
,03-15 19:11:31.944  1018  1030 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-15 19:11:31.944  1018  1030 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-15 19:11:31.944  1018  1030 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,03-15 19:11:31.954  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3256/cgroup.procs: No such file or directory
,03-15 19:11:31.954  3914  3973 I GFX generate_partition_tables: took 6.216979ms for 0*0 texture 0
,03-15 19:11:31.954  3914  3973 I GFX raster: took 9.967865ms for 96*96 texture 0
03-15 19:11:31.954  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fc4818 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8fc47e0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:31.964  3914  3973 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-15 19:11:31.974  3938  3938 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
,03-15 19:11:31.974  3938  3938 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-15 19:11:31.974  1018  1504 D TimaService: TIMA: in getTimaVersion
,03-15 19:11:31.974  1018  1705 D TimaService: TIMA3: KeyStore3_init
,03-15 19:11:31.974  1018  1705 D TimaService: TIMA: in getTimaVersion
,03-15 19:11:31.974  1018  1705 E TLC_TZ_KEYSTORE: : Inside TZ_KEYSTORE_initialize(),
,03-15 19:11:31.984  1018  1705 I TLC_TZ_KEYSTORE: : creating new keystore context...
03-15 19:11:31.984  1018  1705 I TLC_TZ_KEYSTORE: : initializing ccm context...
03-15 19:11:31.984  1018  1705 I TLC_TZ_KEYSTORE: : root = /firmware/image, root_strlen = 15
,03-15 19:11:31.984  1018  1705 I TLC_TZ_KEYSTORE: : process = tima_key, process_strlen = 8
03-15 19:11:31.984  1018  1705 I TZ: qc_tlc_communication: root = /firmware/image, root_len = 15
03-15 19:11:31.984  1018  1705 I TZ: qc_tlc_communication: process = tima_key, process_strlen = 8
03-15 19:11:31.984  1018  1705 I TZ: qc_tlc_communication: aligned max_sendmsg_size = 1088 = 0x440,
03-15 19:11:31.984  1018  1705 I TZ: qc_tlc_communication: aligned max_recvmsg_size = 1088 = 0x440
03-15 19:11:31.984  1018  1705 I TZ: qc_tlc_communication: max_message_size = 2176 = 0x880
03-15 19:11:31.984  1018  1705 D QSEECOMAPI: : QSEECom_get_handle sb_length = 0x880,
03-15 19:11:31.984  1018  1705 D QSEECOMAPI: : App is not loaded in QSEE
,03-15 19:11:31.984  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-15 19:11:31.984  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,03-15 19:11:31.994  1018  1018 I ActivityManager: Killing 3266:com.google.android.configupdater/u0a86 (adj 15): empty #31
,03-15 19:11:31.994   257   257 I SurfaceFlinger: id=11 createSurf (1x1),1 flag=404, NainActivit
,03-15 19:11:32.004  4045  4045 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:32.004  4045  4045 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:32.014  1018  1337 D InputDispatcher: Focus entered window: 3938
,03-15 19:11:32.014  1018  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-15 19:11:32.014  1018  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-15 19:11:32.014  3938  3938 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-15 19:11:32.014  3938  4055 I OpenGLRenderer: Initialized EGL, version 1.4
,03-15 19:11:32.024   287   287 E SMD     : DCD OFF
,03-15 19:11:32.024  3938  4055 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-15 19:11:32.024  3938  4055 D OpenGLRenderer: Enabling debug mode 0
,03-15 19:11:32.084  1018  1346 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-15 19:11:32.084  1181  1181 D PanelView: There is/are notification(s) ,
03-15 19:11:32.094  1018  4070 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-15 19:11:32.094  1018  1051 I ActivityManager: Displayed Component not be shown by security: +1s248ms
,03-15 19:11:32.094  3938  3938 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@930d996 time:43625
03-15 19:11:32.094  1018  1051 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
,03-15 19:11:32.094  1018  1044 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-15 19:11:32.104  1018  1051 W ActivityManager: mDVFSHelper.release()
03-15 19:11:32.104  1018  1051 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{31ec2767 u0 com.test.thalitest/.MainActivity t12} time:43630
,03-15 19:11:32.104  1801  1801 I SamsungIME: getCurrentCandidateView
,03-15 19:11:32.114  1018  1043 W libprocessgroup: failed to open /acct/uid_10086/pid_3266/cgroup.procs: No such file or directory
,03-15 19:11:32.244  1018  1705 D QSEECOMAPI: : Loaded image: APP id = 10
,03-15 19:11:32.254  1018  1705 I TZ: qc_tlc_communication: TIMA: path = /firmware/image, fname = tima_key, tzapp is loaded
,03-15 19:11:32.254  1018  1705 I TLC_TZ_KEYSTORE: : ctx = 0xb946c8b8, comm = 0xb93e7448, sendmsg = 0x9d8e1000, recvmsg = 0x9d8e1440
03-15 19:11:32.254  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:32.254  1018  1705 I TZ_init: : TZ_init: sending initialization request...
,03-15 19:11:32.254  3914  3973 I GFX raster: took 0.829375ms for 96*96 texture 0
03-15 19:11:32.254  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fc4818 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8fc47e0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:32.264  1018  1705 E TZ_init: : TZ_init Process: Secure memory is not initialized!
03-15 19:11:32.264  1018  1705 E TZ_init: : trustlet initialization failed
03-15 19:11:32.264  1018  1705 I TZ_init: : TZ_init_START...
,03-15 19:11:32.264  3914  3973 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-15 19:11:32.274  1018  1705 I TZ_init: : TZ_init_with_data: sending initialization request...
,03-15 19:11:32.274  1018  1705 I TZ_init: : TZ_init: successful initialization
03-15 19:11:32.274  1018  1705 D QSEECOMAPI: : QSEECom_dealloc_memory 
03-15 19:11:32.274  1018  1705 D QSEECOMAPI: : QSEECom_shutdown_app, app_id = 10
,03-15 19:11:32.274  1018  1705 E TLC_TZ_KEYSTORE: : Count : 1, Ret : 0
,03-15 19:11:32.284  3890  3890 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,03-15 19:11:32.314   257  1795 I SurfaceFlinger: id=10 Removed uhalitest (7/8)
,03-15 19:11:32.314   257   438 I SurfaceFlinger: id=10 Removed uhalitest (-2/8)
,03-15 19:11:32.334  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,03-15 19:11:32.334  3914  3973 I GFX construct_block_size_descriptor_2d second part: took 2.175157ms for 0*0 texture 0,
,03-15 19:11:32.344  3914  3973 I GFX generate_partition_tables: took 7.583802ms for 0*0 texture 0,
03-15 19:11:32.344  3914  3973 I GFX raster: took 10.704687ms for 96*96 texture 0
,03-15 19:11:32.344  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fc47e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fc92d0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:32.364  3938  3938 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3938
,03-15 19:11:32.364  3914  3973 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-15 19:11:32.374  3890  3890 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-15 19:11:32.374  4045  4045 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-15 19:11:32.374  4045  4045 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 19:11:32.374  4045  4045 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-15 19:11:32.384  3890  3890 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,03-15 19:11:32.394  3178  3207 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 4 sec
,03-15 19:11:32.394  3958  3972 W art     : Suspending all threads took: 7.496ms
,03-15 19:11:32.394  1018  1018 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@11
,03-15 19:11:32.404  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 19:11:32.404  3975  3975 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.bbc.bbcagent.bbccontroller.BBCDataConsistency.checkDBConsistencyFromPM:220 com.samsung.android.bbc.bbcagent.bbccontroller.receiver.BootCompletedReceiver.onReceive:50 
,03-15 19:11:32.404  3914  3973 I GFX raster: took 0.618490ms for 96*96 texture 0
03-15 19:11:32.404  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fcde78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fcdfd0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:32.404  1018  1031 D ActivityManager: startService callerProcessName:com.samsung.android.bbc.bbcagent, calleePkgName: com.samsung.android.bbc.bbcagent
,03-15 19:11:32.404  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.bbc.bbcagent/com.samsung.android.bbc.bbcagent.bbccontroller.service.BBCAgentService; callingUser = 0; userId(target) = 0
,03-15 19:11:32.414  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:32.414  1018  1031 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-15 19:11:32.414  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.bbc.bbcagent, destAppInfo.processName = com.samsung.android.bbc.bbcagent
,03-15 19:11:32.424  4045  4045 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-15 19:11:32.424  4045  4045 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 19:11:32.424  4045  4045 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-15 19:11:32.424  3914  3973 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-15 19:11:32.434  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:32.434  3914  3973 I GFX raster: took 0.827552ms for 96*96 texture 0
03-15 19:11:32.434  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fca880 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fca9d8 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:32.444  1018  1346 D ActivityManager: startProcessLocked calleePkgName: com.sec.bcservice, hostingType: broadcast
,03-15 19:11:32.444  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:32.444  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:32.444  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:32.444  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:32.444  3914  3973 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-15 19:11:32.454  1801  1801 D SamsungIME: Dismiss ExpandCandiate,
,03-15 19:11:32.464  4094  4094 E Zygote  : MountEmulatedStorage(),
03-15 19:11:32.464  4094  4094 E Zygote  : v2,
03-15 19:11:32.464  4094  4094 I libpersona: KNOX_SDCARD checking this for 1000,
,03-15 19:11:32.464  4094  4094 I libpersona: KNOX_SDCARD not a persona
03-15 19:11:32.474  4094  4094 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-15 19:11:32.474  4094  4094 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-15 19:11:32.484  1018  1346 I ActivityManager: Start proc com.sec.bcservice for broadcast com.sec.bcservice/.BCServiceReceiver: pid=4094 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-15 19:11:32.484  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:32.484  3914  3973 I GFX raster: took 0.644636ms for 96*96 texture 0
03-15 19:11:32.484  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fc4c68 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fc9360 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:32.494  4094  4094 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 19:11:32.494  3914  3973 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-15 19:11:32.504  3958  4101 I Babel   : MmsConfig: mnc/mcc: 0/0
03-15 19:11:32.504  3958  4101 I Babel   : MmsConfig.loadMmsSettings
03-15 19:11:32.504  3958  4101 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
03-15 19:11:32.504  3958  4101 I Babel   : MmsConfig.loadFromDatabase
,03-15 19:11:32.504  4045  4045 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-15 19:11:32.504  4045  4045 W ResourcesManager: Asset path '/system/framework/libvtmanagerjar.jar' does not exist or contains no resources.
03-15 19:11:32.504  4045  4045 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-15 19:11:32.514  3958  4101 E Babel   : canonicalizeMccMnc: invalid mccmnc 
03-15 19:11:32.514  3958  4101 I Babel   : MmsConfig.loadFromResources
,03-15 19:11:32.514  4094  4094 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:32.514  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:32.514  3914  3973 I GFX raster: took 0.796042ms for 96*96 texture 0
03-15 19:11:32.514  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fc9360 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fcb548 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:32.514  4094  4094 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:32.524  3914  3973 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-15 19:11:32.534  3958  4101 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,03-15 19:11:32.534  3958  4101 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-A500FU, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-A500FU.xml
,03-15 19:11:32.544  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:32.544  3914  3973 I GFX raster: took 0.526927ms for 96*96 texture 0
03-15 19:11:32.544  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fc8f30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fc9840 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:32.554  3914  3973 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-15 19:11:32.554  4094  4094 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,03-15 19:11:32.574  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.dialer.DialtactsActivity
,03-15 19:11:32.574  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:32.574  3914  3973 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 19:11:32.574  3914  3973 I AMMetaDataParserService: Resource data:2131034113
,03-15 19:11:32.584  3914  3973 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-15 19:11:32.584  3914  3973 I AMMetaDataParserService: getResourceTypeNamexml
03-15 19:11:32.584  1018  1129 W SEAMService:  hashset_to_int_array returning null
,03-15 19:11:32.584  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:32.584  3914  3973 I GFX raster: took 0.836823ms for 96*96 texture 0
03-15 19:11:32.584  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fc4818 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8fc96d0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:32.584  4094  4094 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.bcservice.BCServiceReceiver.onReceive:18 android.app.ActivityThread.handleReceiver:3125 
,03-15 19:11:32.584  1018  1504 D ActivityManager: startService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.bcservice
03-15 19:11:32.584  1018  1504 D ActivityManager: retrieveServiceLocked(): component = com.sec.bcservice/com.sec.bcservice.BroadcastService; callingUser = 0; userId(target) = 0
,03-15 19:11:32.584  1018  1504 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:32.584  1018  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:32.584  1018  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.bcservice
,03-15 19:11:32.594  3914  3973 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533
,03-15 19:11:32.594  3938  3938 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-15 19:11:32.604  1018  1031 W SEAMService:  hashset_to_int_array returning null
,03-15 19:11:32.604  3890  4073 D Volley  : [573] DiskBasedCache.clear: Cache cleared.
,03-15 19:11:32.604  3975  3975 E SQLiteLog: (284) automatic index on seams_container_info(seams_container_id)
03-15 19:11:32.604  3890  4036 D Volley  : [566] DiskBasedCache.clear: Cache cleared.
,03-15 19:11:32.604  3975  3975 E SQLiteLog: (284) automatic index on seams_container_info(sp_id)
,03-15 19:11:32.614  3890  4111 D Ads     : Skipping gmscore version check
,03-15 19:11:32.614  1018  1952 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
03-15 19:11:32.614  1018  1952 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.billing.iab.PendingNotificationsService; callingUser = 0; userId(target) = 0
,03-15 19:11:32.614  1018  1952 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:32.614  1018  1952 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-15 19:11:32.614  1018  1952 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-15 19:11:32.624  1018  1266 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
03-15 19:11:32.624  1018  1266 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.CallService; callingUser = 0; userId(target) = 0
,03-15 19:11:32.624  1018  1518 W SEAMService:  hashset_to_int_array returning null
,03-15 19:11:32.624  1018  1266 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:32.624  1018  1266 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:32.624  1018  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-15 19:11:32.634  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:32.634  3914  3973 I GFX raster: took 0.832448ms for 96*96 texture 0
03-15 19:11:32.634  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fc4818 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8fca9d8 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:32.634  1018  1346 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 19:11:32.644  1018  1346 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:32.644  1018  1346 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-15 19:11:32.644  1018  1346 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:32.644  3914  3973 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-15 19:11:32.654  3958  3958 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,03-15 19:11:32.674  4094  4094 I F_PHONE : [[com.sec.bcservice]] bind SecPhone Service with FactoryPhone
,03-15 19:11:32.674  4094  4094 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2136 android.content.ContextWrapper.bindService:559 com.samsung.android.sec_platform_library.FactoryPhone.connectToRilService:95 com.samsung.android.sec_platform_library.FactoryPhone.<init>:61 com.sec.bcservice.BroadcastService.onCreate:146 
,03-15 19:11:32.674  1018  1266 D ActivityManager: bindService callerProcessName:com.sec.bcservice, calleePkgName: com.sec.phone, action: null
03-15 19:11:32.674  1018  1266 D ActivityManager: retrieveServiceLocked(): component = com.sec.phone/com.sec.phone.SecPhoneService; callingUser = 0; userId(target) = 0
,03-15 19:11:32.674  1018  1266 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:32.674  1018  1266 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:32.674  1018  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.bcservice, destAppInfo.processName = com.sec.phone
,03-15 19:11:32.714  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:32.714  3914  3973 I GFX raster: took 0.640677ms for 96*96 texture 0
03-15 19:11:32.714  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fc47e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fc4e60 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:32.714  2089  4112 D FileApkUtils: Optimizing (staging complete)
,03-15 19:11:32.714  2089  4112 D FileApkUtils: Optimizing: DynamiteModules-prod.apk [0224a548494bce36274e23f9f1b42d4fbe3d4d8de53a7872e503f8974e43c3c3]
,03-15 19:11:32.714  2089  4112 I art     : DexFile_isDexOptNeeded failed to open oat file '/data/dalvik-cache/arm/data@data@com.google.android.gms@app_chimera@m@00000000@DynamiteModules-prod.apk@classes.dex' for file location '/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk': Failed to open oat filename for reading: No such file or directory
,03-15 19:11:32.714  3914  3973 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531
,03-15 19:11:32.724  2089  4112 D DexOptUtils: Module /data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk appears to be unoptimized.
03-15 19:11:32.724  2089  4112 D DexOptUtils: Lollipop platform, using <isa> directory.
,03-15 19:11:32.724  2089  4112 D DexOptUtils: Instantiating DexClassLoader to force creation of odex.
03-15 19:11:32.724  2089  4112 D DexOptUtils: Primary ABI of odexing process is armeabi-v7a
,03-15 19:11:32.724  4094  4094 D F_PHONE : [[com.sec.bcservice]] onServiceConnected()
,03-15 19:11:32.734  4094  4094 I F_PHONE : default registerAction()
03-15 19:11:32.734  4094  4094 I F_PHONE : [[com.sec.bcservice]] sendPendingMessage()
,03-15 19:11:32.734  1018  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 19:11:32.744  1018  1031 W ActivityManager: userId = 0, bbcId = -10000,
,03-15 19:11:32.744  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-15 19:11:32.744  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.google.android.gms
,03-15 19:11:32.744  3890  3890 D Finsky  : [1] Libraries$2.run: Loaded library for account: [UVAT3FEWOLBYQGmBHvKHAcB3G_U]
,03-15 19:11:32.744  3890  3890 D Finsky  : [1] Libraries$2.run: Finished loading 1 libraries.
,03-15 19:11:32.804  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:32.804  3914  3973 I GFX raster: took 0.622448ms for 96*96 texture 0
03-15 19:11:32.804  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fcde78 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fbf2c0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:32.834  3914  3973 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-15 19:11:32.854  3938  4078 D jxcore_app_log: JniHelper::setJavaVM(0xb8bed450), pthread_self() = -1189774344
,03-15 19:11:32.864  1018  1346 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-15 19:11:32.864  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 19:11:32.864  1018  1346 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.fitness.service.recording.FitRecordingBroker; callingUser = 0; userId(target) = 0
,03-15 19:11:32.864  3914  3973 I GFX raster: took 0.824427ms for 96*96 texture 0
03-15 19:11:32.864  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fca880 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fcb768 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:32.864  1018  1346 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:32.864  1018  1346 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:32.864  1018  1346 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:32.884  3938  4078 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-15 19:11:32.884  3938  4078 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-15 19:11:32.884  3938  4078 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-15 19:11:32.884  3938  4078 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-15 19:11:32.884  3938  4078 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,03-15 19:11:32.884  3938  4078 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@255ba55d added. We now have 1 listener(s)
,03-15 19:11:32.894  3938  4078 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 7C:F9:0E:37:96:AB
,03-15 19:11:32.894  3938  4078 I org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: Identity string created: {"name":"<no peer name>","address":"7C:F9:0E:37:96:AB"}
,03-15 19:11:32.894  3938  4078 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: {"name":"<no peer name>","address":"7C:F9:0E:37:96:AB"}
,03-15 19:11:32.904  3938  4078 D org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setHandshakeRequired: true -> false
,03-15 19:11:32.904  3958  3958 I Babel_StickerModule: App launched.
,03-15 19:11:32.904  1018  1952 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 19:11:32.914  1018  1952 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:32.914  1018  1952 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-15 19:11:32.914  1018  1952 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:32.914  3914  3973 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-15 19:11:32.914  4118  4118 I dex2oat : ----------------------------------------------------
03-15 19:11:32.914  4118  4118 I dex2oat : <SS>: S T A R T I N G . . .
03-15 19:11:32.914  4118  4118 I dex2oat : <SS>: Zip is absent. Canceled.
,03-15 19:11:32.914  4118  4118 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --compiler-filter=interpret-only --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_chimera/m/00000000/DynamiteModules-prod.apk --oat-fd=40 --art-fd=-1 --oat-location=/data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,03-15 19:11:32.924  3938  4078 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setHandshakeRequired: true -> false
,03-15 19:11:32.924  3938  4078 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-15 19:11:32.924  3938  4078 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-15 19:11:32.924  3938  4078 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-15 19:11:32.924  3938  4078 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 7C:F9:0E:37:96:AB
03-15 19:11:32.924  3938  4078 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-15 19:11:32.924  3938  4078 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-15 19:11:32.924  3938  4078 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-15 19:11:32.924  3938  4078 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-15 19:11:32.924  3938  4078 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-15 19:11:32.924  3938  4078 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-15 19:11:32.924  3938  4078 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ca95ea0 added. We now have 1 listener(s)
03-15 19:11:32.924  3938  4078 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,03-15 19:11:32.954  3467  3480 D PCWCLIENTTRACE_AccountAppFacade2_0: unregister AuthInfo UpdateReceiver v2.0
,03-15 19:11:32.964  1018  1266 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-15 19:11:32.964  1018  1266 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,03-15 19:11:32.974  1018  1266 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:32.974  1018  1266 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:32.974  3938  4078 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (SUPPORTED) in persistent storage
03-15 19:11:32.974  1018  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:32.984  3938  4078 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
03-15 19:11:32.984  3938  4078 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
03-15 19:11:32.984  3938  4078 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
03-15 19:11:32.984  3938  4078 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,03-15 19:11:33.024  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:33.024  3914  3973 I GFX raster: took 0.645365ms for 96*96 texture 0
03-15 19:11:33.024  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fc4c68 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fca9d8 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:33.034  3914  3973 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528
,03-15 19:11:33.064  3890  3890 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,03-15 19:11:33.074  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:33.074  3914  3973 I GFX raster: took 0.681458ms for 96*96 texture 0
03-15 19:11:33.074  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fc9360 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fc75f8 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:33.084  3914  3973 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534,
03-15 19:11:33.094  1018  2750 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.ssrm.I.m:-1 com.android.server.ssrm.J.run:-1 android.os.Handler.handleCallback:739 android.os.Handler.dispatchMessage:95 ,
,03-15 19:11:33.094  1018  1031 D ActivityManager: startService callerProcessName:com.android.vending, calleePkgName: com.android.vending
,03-15 19:11:33.094  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.vending/com.google.android.finsky.services.RestoreService; callingUser = 0; userId(target) = 0,
,03-15 19:11:33.094  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:33.094  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-15 19:11:33.094  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.vending, destAppInfo.processName = com.android.vending
,03-15 19:11:33.114  3938  4078 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,03-15 19:11:33.134  3938  4078 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 7C:F9:0E:37:96:AB
,03-15 19:11:33.144  3938  4078 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-15 19:11:33.144  3938  4078 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-15 19:11:33.144  3938  4078 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
03-15 19:11:33.144  3938  4078 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-15 19:11:33.144  3938  4078 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-15 19:11:33.144  3938  4078 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-15 19:11:33.144  3938  4078 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-15 19:11:33.144  3938  4078 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,03-15 19:11:33.144  3938  4078 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,03-15 19:11:33.144  3938  4078 D io.jxcore.node.ConnectivityMonitor: start: OK
,03-15 19:11:33.154  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-15 19:11:33.164  3938  3938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,03-15 19:11:33.164  3958  3958 V Babel   : babel boot account: SMS
,03-15 19:11:33.174  3958  3958 W Babel   : EsDatabaseHelper.static should not be called on main thread [called on main thread]
,03-15 19:11:33.174  3958  3958 W Babel   : java.lang.Exception
03-15 19:11:33.174  3958  3958 W Babel   : 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
03-15 19:11:33.174  3958  3958 W Babel   : 	at aes.<clinit>(SourceFile:95)
03-15 19:11:33.174  3958  3958 W Babel   : 	at ckh.<init>(SourceFile:103)
03-15 19:11:33.174  3958  3958 W Babel   : 	at ckh.a(SourceFile:67)
03-15 19:11:33.174  3958  3958 W Babel   : 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
03-15 19:11:33.174  3958  3958 W Babel   : 	at bhn.a(SourceFile:301)
03-15 19:11:33.174  3958  3958 W Babel   : 	at bhn.a(SourceFile:137)
03-15 19:11:33.174  3958  3958 W Babel   : 	at bhn.a(SourceFile:126)
03-15 19:11:33.174  3958  3958 W Babel   : 	at bhn.a(SourceFile:159)
03-15 19:11:33.174  3958  3958 W Babel   : 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
03-15 19:11:33.174  3958  3958 W Babel   : 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
03-15 19:11:33.174  3958  3958 W Babel   : 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
03-15 19:11:33.174  3958  3958 W Babel   : 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
03-15 19:11:33.174  3958  3958 W Babel   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 19:11:33.174  3958  3958 W Babel   : 	at android.os.Looper.loop(Looper.java:145)
03-15 19:11:33.174  3958  3958 W Babel   : 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-15 19:11:33.174  3958  3958 W Babel   : 	at java.lang.reflect.Method.invoke(Native Method)
03-15 19:11:33.174  3958  3958 W Babel   : 	at java.lang.reflect.Method.invoke(Method.java:372)
03-15 19:11:33.174  3958  3958 W Babel   : 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-15 19:11:33.174  3958  3958 W Babel   : 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,03-15 19:11:33.174  3958  3958 W Babel   : EsDatabaseHelper.getDatabaseHelper() [called on main thread]
,03-15 19:11:33.174  3958  3958 W Babel   : java.lang.Exception
03-15 19:11:33.174  3958  3958 W Babel   : 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
03-15 19:11:33.174  3958  3958 W Babel   : 	at aes.a(SourceFile:145)
03-15 19:11:33.174  3958  3958 W Babel   : 	at ckh.<init>(SourceFile:103)
03-15 19:11:33.174  3958  3958 W Babel   : 	at ckh.a(SourceFile:67)
03-15 19:11:33.174  3958  3958 W Babel   : 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
03-15 19:11:33.174  3958  3958 W Babel   : 	at bhn.a(SourceFile:301)
03-15 19:11:33.174  3958  3958 W Babel   : 	at bhn.a(SourceFile:137)
03-15 19:11:33.174  3958  3958 W Babel   : 	at bhn.a(SourceFile:126)
03-15 19:11:33.174  3958  3958 W Babel   : 	at bhn.a(SourceFile:159)
03-15 19:11:33.174  3958  3958 W Babel   : 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
03-15 19:11:33.174  3958  3958 W Babel   : 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
03-15 19:11:33.174  3958  3958 W Babel   : 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
03-15 19:11:33.174  3958  3958 W Babel   : 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
03-15 19:11:33.174  3958  3958 W Babel   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 19:11:33.174  3958  3958 W Babel   : 	at android.os.Looper.loop(Looper.java:145)
03-15 19:11:33.174  3958  3958 W Babel   : 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-15 19:11:33.174  3958  3958 W Babel   : 	at java.lang.reflect.Method.invoke(Native Method)
03-15 19:11:33.174  3958  3958 W Babel   : 	at java.lang.reflect.Method.invoke(Method.java:372)
03-15 19:11:33.174  3958  3958 W Babel   : 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-15 19:11:33.174  3958  3958 W Babel   : 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,03-15 19:11:33.194  3890  3890 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,03-15 19:11:33.214  1931  1931 D ChimeraCfgMgr: Reading stored module config
,03-15 19:11:33.224  2089  2089 W InstanceID/Rpc: Found 10012
,03-15 19:11:33.254  1018  2750 D SSRM:n  : SIOP:: AP = 390
,03-15 19:11:33.264  1181  1181 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-15 19:11:33.264  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-15 19:11:33.264  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 19:11:33.264  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 19:11:33.264  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 19:11:33.264  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 19:11:33.264  3938  3938 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-15 19:11:33.274  1018  1266 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,03-15 19:11:33.274  1018  1266 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,03-15 19:11:33.284  1018  1266 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.284  1018  1266 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:33.284  1018  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-15 19:11:33.294  1018  1129 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
03-15 19:11:33.294  1018  1129 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,03-15 19:11:33.294  1018  1129 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.294  1018  1129 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:33.294  1018  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-15 19:11:33.294  1018  1337 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk,
03-15 19:11:33.294  1018  1337 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:33.294  1018  1337 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0,
03-15 19:11:33.294  1018  1337 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:33.294  1018  1337 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk,
03-15 19:11:33.294  3958  3958 V Babel   : babel boot account: thalitester@gmail.com
,03-15 19:11:33.304  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:33.304  3914  3973 I GFX raster: took 0.530417ms for 96*96 texture 0
,03-15 19:11:33.304  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fca4e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f8fc38 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:33.314  1931  1931 D WearableService: callingUid 10012, callindPid: 1931
,03-15 19:11:33.314  3914  3973 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
,03-15 19:11:33.314  3958  3958 W Babel   : EsDatabaseHelper.getDatabaseHelper() [called on main thread]
,03-15 19:11:33.314  3958  3958 W Babel   : java.lang.Exception
03-15 19:11:33.314  3958  3958 W Babel   : 	at com.google.android.apps.hangouts.phone.EsApplication.a(SourceFile:1133)
03-15 19:11:33.314  3958  3958 W Babel   : 	at aes.a(SourceFile:145)
03-15 19:11:33.314  3958  3958 W Babel   : 	at ckh.<init>(SourceFile:103)
03-15 19:11:33.314  3958  3958 W Babel   : 	at ckh.a(SourceFile:67)
03-15 19:11:33.314  3958  3958 W Babel   : 	at com.google.android.apps.hangouts.phone.EsApplication.c(SourceFile:733)
03-15 19:11:33.314  3958  3958 W Babel   : 	at bhn.a(SourceFile:301)
03-15 19:11:33.314  3958  3958 W Babel   : 	at bhn.a(SourceFile:137)
03-15 19:11:33.314  3958  3958 W Babel   : 	at bhn.a(SourceFile:126)
03-15 19:11:33.314  3958  3958 W Babel   : 	at bhn.a(SourceFile:159)
03-15 19:11:33.314  3958  3958 W Babel   : 	at com.google.android.apps.hangouts.service.BootReceiver.onReceive(SourceFile:72)
03-15 19:11:33.314  3958  3958 W Babel   : 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:3125)
03-15 19:11:33.314  3958  3958 W Babel   : 	at android.app.ActivityThread.access$1800(ActivityThread.java:181)
03-15 19:11:33.314  3958  3958 W Babel   : 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1559)
03-15 19:11:33.314  3958  3958 W Babel   : 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 19:11:33.314  3958  3958 W Babel   : 	at android.os.Looper.loop(Looper.java:145)
03-15 19:11:33.314  3958  3958 W Babel   : 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-15 19:11:33.314  3958  3958 W Babel   : 	at java.lang.reflect.Method.invoke(Native Method)
03-15 19:11:33.314  3958  3958 W Babel   : 	at java.lang.reflect.Method.invoke(Method.java:372)
03-15 19:11:33.314  3958  3958 W Babel   : 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-15 19:11:33.314  3958  3958 W Babel   : 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,03-15 19:11:33.334  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
,03-15 19:11:33.334  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactSelectionActivity
03-15 19:11:33.334  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionTabActivity
03-15 19:11:33.334  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionGroupSelectionActivity
03-15 19:11:33.334  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.DialtactsActivity
03-15 19:11:33.334  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.RecentCallsListActivity
03-15 19:11:33.334  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.CallLogActivity
03-15 19:11:33.334  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.ContactsListActivity
03-15 19:11:33.334  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactsFrontDoor
03-15 19:11:33.334  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.DialtactsContactsEntryActivity
03-15 19:11:33.334  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.PeopleActivity
03-15 19:11:33.334  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.JoinContactActivity
03-15 19:11:33.334  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.preference.ContactsPreferenceActivity
03-15 19:11:33.334  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.list.AccountFilterActivity
03-15 19:11:33.334  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.list.CustomContactListFilterActivity
03-15 19:11:33.334  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ShowOrCreateActivity
03-15 19:11:33.334  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.GroupDetailActivity
03-15 19:11:33.334  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.GroupEditorActivity
03-15 19:11:33.334  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.quickcontact.QuickContactActivity
03-15 19:11:33.334  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:33.334  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
03-15 19:11:33.334  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.ContactShortcut
03-15 19:11:33.334  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activityalias.DialShortcut
03-15 19:11:33.334  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activityalias.MessageShortcut
03-15 19:11:33.334  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.dialer.CallDetailActivity
03-15 19:11:33.334  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDetailDeleteActivity
03-15 19:11:33.334  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactDetailActivity
03-15 19:11:33.334  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:33.334  3914  3973 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-15 19:11:33.334  3914  3973 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 19:11:33.334  3914  3973 I AMMetaDataParserService: Resour,ce data:2131034112
03-15 19:11:33.334  1931  1931 E GmsWearableNodeHelper: GoogleApiClient connection failed: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-15 19:11:33.334  3914  3973 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_detail
03-15 19:11:33.334  3914  3973 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 19:11:33.334  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:33.344  3914  3973 I GFX raster: took 0.835937ms for 96*96 texture 0
03-15 19:11:33.344  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fc8f30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fac788 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:33.354  3914  3973 I AMMetaDataParserService: Icon data: ResourceAdd to Favourites2131690170android.intent.assistant.detail.favorite2130837530
,03-15 19:11:33.384  1801  1801 I SamsungIME: getDebugLevel  : 0x4f4c,
03-15 19:11:33.384  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:33.394  3914  3973 I GFX raster: took 0.707604ms for 96*96 texture 0
03-15 19:11:33.394  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fc8f30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8efb238 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:33.394  3938  3956 I art     : Background partial concurrent mark sweep GC freed 5383(495KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 11MB/18MB, paused 7.174ms total 43.390ms
,03-15 19:11:33.394  3178  3207 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 5 sec
,03-15 19:11:33.404  3914  3973 I AMMetaDataParserService: Icon data: ResourceRemove from Favourites2131690212android.intent.assistant.detail.favorite2130837530
,03-15 19:11:33.404  4045  4045 I Process : Sending signal. PID: 4045 SIG: 9
,03-15 19:11:33.414  1018  1346 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
03-15 19:11:33.414  1018  1346 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,03-15 19:11:33.414  1018  1346 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:33.424  1018  1346 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:33.424  1018  1346 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-15 19:11:33.424  1018  1504 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-15 19:11:33.424  1018  1504 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.BootCompletedBroadcastService; callingUser = 0; userId(target) = 0
,03-15 19:11:33.424  1018  1504 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.424  1018  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:33.424  1018  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:33.434  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
,03-15 19:11:33.434  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,03-15 19:11:33.434  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.434  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:33.434  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-15 19:11:33.454  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:33.454  3914  3973 I GFX raster: took 0.751043ms for 96*96 texture 0
03-15 19:11:33.454  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fac788 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8f8fc38 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:33.454  1018  1518 D ActivityManager: startService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk
03-15 19:11:33.454  1018  1518 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.apps.hangouts.notifications.NotificationService; callingUser = 0; userId(target) = 0
,03-15 19:11:33.464  3914  3973 I AMMetaDataParserService: Icon data: ResourceEdit2131690192android.intent.assistant.detail.edit2130837529
,03-15 19:11:33.464  1018  2822 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-15 19:11:33.474  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:33.474  3914  3973 I GFX raster: took 0.655260ms for 96*96 texture 0
03-15 19:11:33.474  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8efb238 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f8fc38 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:33.484  3914  3973 I AMMetaDataParserService: Icon data: ResourceDelete2131690186android.intent.assistant.detail.delete2130837528
,03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.SelectContactInfoActivity
03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ConfirmAddDetailActivity
03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorAccountsChangedActivity
03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.ContactEditorActivity
03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.RingtoneRecommendationHelperActivity
03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.AddAnotherFieldDialogActivity
03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.AttachPhotoActivity
03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.activities.PhotoSelectionActivity
03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.ImportVCardActivity
03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportVCardPreviewActivity
03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.NfcImportVCardActivity
03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.CancelActivity
03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.SelectAccountActivity
03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.common.vcard.ExportVCardActivity
03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.vcard.ImportFinishActivity
03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.SIMContactSelectionActivity
03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbers
03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ServiceNumbersTabActivity
03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.VerizonBackupAssistantActivity
03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.widget.PinnedHeaderListDemoActivity
03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.contacts.NonPhoneActivity
03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.favorite.FavoriteSelectionActivity
03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.SetDefaultActivity
03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.GroupChangeOrderActivity
03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.EditGroupSelectionActivity
03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.GroupMultiSelectionActivity
03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.em,ergency.InteractionEmergencyMessageActivity
03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyMessageContactCreateActivity
03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.EmergencyContactListDialogActivity
03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.group.SubGroupDetailActivity
03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.GroupListActivity
03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationActivity
03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.CallDurationTabActivity
03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.LinkedContactActivity
03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.impl.DialerTutorialActivity
03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpPeopleActivity
03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyPeopleActivity
,03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpInteractionTabActivity
03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpEasyInteractionTabActivity
03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpSpeedDialActivity
03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactEditorActivity
,03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.impl.HelpContactSelectionActivity
03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.EasyPeopleActivity
,03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check,
03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: getResourcePackageName:assistant
,03-15 19:11:33.504  3914  3973 I AMMetaDataParserService: Resource data:2131034113
,03-15 19:11:33.514  1018  1518 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.514  1018  1518 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:33.514  1018  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-15 19:11:33.524  3914  3973 I AMMetaDataParserService: getResourceName:com.android.contacts:xml/assistant_main
03-15 19:11:33.524  3914  3973 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 19:11:33.524  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:33.524  3914  3973 I GFX raster: took 0.807968ms for 96*96 texture 0
03-15 19:11:33.524  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8f8fc38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8fb8cd0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:33.534  1018  1744 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,03-15 19:11:33.534  1018  1744 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:33.534  1018  1744 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:33.534  1018  1744 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:33.534  1018  1744 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:33.544  3914  3973 I AMMetaDataParserService: Icon data: ResourceRecent2131690650android.intent.assistant.main.log2130837533,
03-15 19:11:33.544  4148  4148 I libpersona: KNOX_SDCARD checking this for 1000
03-15 19:11:33.544  4148  4148 E Zygote  : MountEmulatedStorage()
03-15 19:11:33.544  4148  4148 I libpersona: KNOX_SDCARD not a persona
03-15 19:11:33.544  4148  4148 E Zygote  : v2
03-15 19:11:33.554  1018  1744 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.BootBroadcastReceiver: pid=4148 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-15 19:11:33.544  4148  4148 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-15 19:11:33.554  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-15 19:11:33.554  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.security.verifier.InternalApkUploadService; callingUser = 0; userId(target) = 0
,03-15 19:11:33.564  4148  4148 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-15 19:11:33.564  4148  4148 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 19:11:33.564  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.564  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:33.564  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:33.594  1018  1030 I ActivityManager: Process com.sec.android.app.sns3 (pid 4045)(adj 0) has died(43,1157)
,03-15 19:11:33.604  4148  4148 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:33.604  4148  4148 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:33.604  1018  1044 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,03-15 19:11:33.614  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:33.614  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:33.614  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:33.614  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:33.614  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 19:11:33.614  3914  3973 I GFX raster: took 0.836042ms for 96*96 texture 0
03-15 19:11:33.614  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8f8fc38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8f8ece0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:33.614   282   282 W QCamera2Factory: getCameraInfo: E, camera_id = 0
,03-15 19:11:33.614   282   282 W QCamera2Factory: getCameraInfo: X
,03-15 19:11:33.614   282   705 W QCamera2Factory: getCameraInfo: E, camera_id = 1
,03-15 19:11:33.614   282   705 W QCamera2Factory: getCameraInfo: X
,03-15 19:11:33.614  3914  3973 I AMMetaDataParserService: Icon data: ResourceLogs2131690639android.intent.assistant.main.log2130837533
,03-15 19:11:33.624  1018  1044 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=4164 uid=10034 gids={50034, 9997, 3003} abi=armeabi-v7a
03-15 19:11:33.634  4164  4164 E Zygote  : MountEmulatedStorage()
03-15 19:11:33.634  4164  4164 I libpersona: KNOX_SDCARD checking this for 10034
03-15 19:11:33.634  4164  4164 E Zygote  : v2
03-15 19:11:33.634  4164  4164 I libpersona: KNOX_SDCARD not a persona
03-15 19:11:33.634  4164  4164 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-15 19:11:33.634  4164  4164 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-15 19:11:33.634  4164  4164 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 19:11:33.634  1018  1705 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-15 19:11:33.634  1018  1705 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.common.stats.GmsCoreStatsService; callingUser = 0; userId(target) = 0
,03-15 19:11:33.644  1018  1705 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.644  1018  1705 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:33.644  1018  1705 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:33.674  1801  1801 I SamsungIME: getDebugLevel  : 0x4f4c
,03-15 19:11:33.674  4164  4164 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:33.674  4164  4164 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:33.704  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-15 19:11:33.704  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncReceiverService; callingUser = 0; userId(target) = 0
,03-15 19:11:33.714  3958  3958 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,03-15 19:11:33.714  3958  3958 W AudioCapabilities: Unsupported mime audio/evrc
,03-15 19:11:33.724  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:33.724  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:33.724  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:33.724  3958  3958 W AudioCapabilities: Unsupported mime audio/qcelp
,03-15 19:11:33.724  3958  3958 W AudioCapabilities: Unsupported mime audio/mpeg-L1
03-15 19:11:33.724  1018  1129 I ActivityManager: Killing 3319:com.dropbox.android/u0a92 (adj 15): empty #31
,03-15 19:11:33.724  3958  3958 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,03-15 19:11:33.734  3958  3958 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,03-15 19:11:33.734  3958  3958 W AudioCapabilities: Unsupported mime audio/x-ima
,03-15 19:11:33.734  3958  3958 W AudioCapabilities: Unsupported mime audio/qcelp
,03-15 19:11:33.734  3958  3958 W AudioCapabilities: Unsupported mime audio/evrc
,03-15 19:11:33.754  3958  3958 W VideoCapabilities: Unsupported mime video/wvc1
,03-15 19:11:33.764  1018  1030 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.foldercontainer, hostingType: broadcast
,03-15 19:11:33.774  3958  3958 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,03-15 19:11:33.774  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:33.774  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:33.774  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:33.774  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:33.794  4180  4180 E Zygote  : MountEmulatedStorage(),
,03-15 19:11:33.794  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
03-15 19:11:33.794  3914  3973 I GFX raster: took 0.597292ms for 96*96 texture 0
03-15 19:11:33.794  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8c5d4a0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fb8cd0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:33.794  2089  2089 D ChimeraCfgMgr: Reading stored module config,
03-15 19:11:33.794  4180  4180 E Zygote  : v2
,03-15 19:11:33.794  4180  4180 I libpersona: KNOX_SDCARD checking this for 1000
03-15 19:11:33.794  4180  4180 I libpersona: KNOX_SDCARD not a persona,
,03-15 19:11:33.804  3958  3958 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es,
,03-15 19:11:33.804  4180  4180 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-15 19:11:33.804  3958  3958 W VideoCapabilities: Unsupported mime video/wvc1,
,03-15 19:11:33.814  3958  3958 W VideoCapabilities: Unsupported mime video/x-ms-wmv,
,03-15 19:11:33.814  3914  3973 I AMMetaDataParserService: Icon data: ResourceContacts2131689715android.intent.assistant.main.contact2130837531,
,03-15 19:11:33.814  3958  3958 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,03-15 19:11:33.814  1018  1030 I ActivityManager: Start proc com.sec.knox.foldercontainer for broadcast com.sec.knox.foldercontainer/.ShortcutReceiver: pid=4180 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
,03-15 19:11:33.824  1018  1030 I ActivityManager: Killing 3237:com.google.android.googlequicksearchbox:search/u0a57 (adj 15): empty #31
03-15 19:11:33.824  3958  3958 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,03-15 19:11:33.824  4180  4180 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-15 19:11:33.824  4180  4180 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 19:11:33.834  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-15 19:11:33.834  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,03-15 19:11:33.834   308   308 I art     : Explicit concurrent mark sweep GC freed 8745(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 639us total 24.991ms
,03-15 19:11:33.834  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:33.834  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:33.834  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
03-15 19:11:33.834  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:33.834  3914  3973 I GFX raster: took 0.788750ms for 96*96 texture 0
03-15 19:11:33.834  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fc8f30 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f8ece0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:33.854  4180  4180 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:33.854  4180  4180 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:33.854   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 626us total 17.054ms
,03-15 19:11:33.864  3914  3973 I AMMetaDataParserService: Icon data: ResourceFavourites2131689711android.intent.assistant.main.favorite2130837530
,03-15 19:11:33.874  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:33.874   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 612us total 16.968ms
03-15 19:11:33.874  3914  3973 I GFX raster: took 1.000364ms for 96*96 texture 0
03-15 19:11:33.874  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fb8cd0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f8ece0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:33.884  3914  3973 I AMMetaDataParserService: Icon data: ResourceKeypad2131690637android.intent.assistant.main.keypad2130837532
,03-15 19:11:33.904  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:33.904  3914  3973 I GFX raster: took 0.820834ms for 96*96 texture 0
03-15 19:11:33.904  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8efb238 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fa45b0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:33.914  3958  3958 W VideoCapabilities: Unsupported mime video/mp43
03-15 19:11:33.914  3914  3973 I AMMetaDataParserService: Icon data: ResourceDelete2131689747android.intent.assistant.main.delete2130837528,
,03-15 19:11:33.914  1801  1801 I SamsungIME: KeybaordView init() : load resources
,03-15 19:11:33.934  1018  1518 D ActivityManager: startProcessLocked calleePkgName: com.policydm, hostingType: broadcast
,03-15 19:11:33.934  1018  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0,
03-15 19:11:33.934  1018  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:33.934  1018  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:33.934  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
,03-15 19:11:33.934  1018  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:33.934  3914  3973 I GFX raster: took 0.947343ms for 96*96 texture 0
,03-15 19:11:33.934  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fc9360 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f8ece0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:33.944  1018  1518 I ActivityManager: Start proc com.policydm for broadcast com.policydm/.XDMBroadcastReceiver: pid=4198 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-15 19:11:33.954  4198  4198 E Zygote  : MountEmulatedStorage()
03-15 19:11:33.954  4198  4198 E Zygote  : v2
,03-15 19:11:33.954  4198  4198 I libpersona: KNOX_SDCARD checking this for 1000
03-15 19:11:33.954  4198  4198 I libpersona: KNOX_SDCARD not a persona
,03-15 19:11:33.954  4198  4198 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-15 19:11:33.954  4198  4198 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-15 19:11:33.964  4180  4180 D KnoxSetupWizardDbHelper: dbMigrationFlag : false
03-15 19:11:33.964  4198  4198 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 19:11:33.984  4198  4198 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 19:11:33.984  3914  3973 I AMMetaDataParserService: Icon data: ResourceSearch2131690214android.intent.assistant.main.search2130837534
,03-15 19:11:33.994  4198  4198 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:33.994  1018  1043 W libprocessgroup: failed to open /acct/uid_10092/pid_3319/cgroup.procs: No such file or directory
03-15 19:11:33.994  1018  1043 W libprocessgroup: failed to open /acct/uid_10057/pid_3237/cgroup.procs: No such file or directory
,03-15 19:11:34.004  1018  1744 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms,
03-15 19:11:34.004  1018  1744 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.update.SystemUpdateService; callingUser = 0; userId(target) = 0
03-15 19:11:34.004  1018  1744 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:34.004  1018  1744 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:34.004  1018  1744 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:34.014  3958  3958 W VideoCapabilities: Unsupported mime video/sorenson,
,03-15 19:11:34.014  4180  4180 D ShortcutReceiver:  ShortcutReceiver onReceive() intent: android.intent.action.BOOT_COMPLETED,
03-15 19:11:34.024  2089  4147 D GCM     : COMPAT: Multi user not supported
03-15 19:11:34.024  1018  1518 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-15 19:11:34.024  1018  1518 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,03-15 19:11:34.024  1018  1518 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:34.024  1018  1518 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:34.024  1018  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:34.034  3958  3958 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,03-15 19:11:34.034  1018  1705 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-15 19:11:34.034  1018  1705 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.recovery.AccountRecoveryBackgroundService; callingUser = 0; userId(target) = 0
03-15 19:11:34.034  1931  1931 D GCM     : COMPAT: Multi user not supported
03-15 19:11:34.034  1018  1705 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:34.034  1018  1705 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:34.034  1018  1705 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:34.034  4180  4180 D KnoxShortcutUtil: getIsShortcutMigrationFor_2_3_0_Done true
,03-15 19:11:34.034  4180  4180 D ShortcutReceiver:  KnoxContainerVersion 2.4.0
03-15 19:11:34.034  4180  4180 D ShortcutReceiver:  shortcut migration not required 
03-15 19:11:34.034  1018  1346 D ActivityManager: startProcessLocked calleePkgName: com.sec.knox.knoxsetupwizardclient, hostingType: broadcast
03-15 19:11:34.034  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:34.034  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:34.034  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:34.034  1018  1346 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:34.064  1018  1346 I ActivityManager: Start proc com.sec.knox.knoxsetupwizardclient for broadcast com.sec.knox.knoxsetupwizardclient/.detector.SetupWizardDetectorReceiver: pid=4215 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-15 19:11:34.064  4215  4215 E Zygote  : MountEmulatedStorage()
03-15 19:11:34.064  4215  4215 I libpersona: KNOX_SDCARD checking this for 1000
03-15 19:11:34.064  4215  4215 E Zygote  : v2
03-15 19:11:34.064  4215  4215 I libpersona: KNOX_SDCARD not a persona
03-15 19:11:34.064  1018  1346 I ActivityManager: Killing 3399:com.dropbox.android:crash_uploader/u0a92 (adj 15): empty #31
,03-15 19:11:34.064  4215  4215 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-15 19:11:34.064  4215  4215 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-15 19:11:34.064  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 19:11:34.074  3914  3973 I GFX raster: took 0.612865ms for 96*96 texture 0
03-15 19:11:34.074  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-15 19:11:34.074  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fca4e8 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fa45b0 counterpartCT=4 counterpartW=96 counterparth=96
03-15 19:11:34.074  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.authzen.GcmReceiverService; callingUser = 0; userId(target) = 0
03-15 19:11:34.074  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:34.074  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:34.074  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:34.074  4215  4215 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 19:11:34.074  4019  4039 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-15 19:11:34.074  2089  2089 D BootCompletedReceiver: Will schedule periodic tasks:android.intent.action.BOOT_COMPLETED.
03-15 19:11:34.074  2089  2089 D BootCompletedReceiver: Got an BootCompleted event.
,03-15 19:11:34.084  1018  1705 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-15 19:11:34.084  1018  1705 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,03-15 19:11:34.084  1018  1705 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:34.084  1018  1705 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:34.084  1018  1705 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:34.104  1018  1266 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
03-15 19:11:34.104  1018  1266 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4291, temperature: 265, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303736, invalid charger:0
03-15 19:11:34.104  1018  1266 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:230000, current_now:0
03-15 19:11:34.104  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,03-15 19:11:34.104  3914  3973 I AMMetaDataParserService: Icon data: ResourceCreate contact2131689734android.intent.assistant.main.create_contact2130837527
03-15 19:11:34.104  4215  4215 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:34.104  4215  4215 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:34.104  1018  1018 I MotionRecognitionService: Plugged
03-15 19:11:34.104  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,03-15 19:11:34.114  1181  1181 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
03-15 19:11:34.114  1181  1181 D KeyguardUpdateMonitor: handleBatteryUpdate
,03-15 19:11:34.124  1446  1446 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
03-15 19:11:34.124  1446  1446 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,03-15 19:11:34.124  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.EasyInteractionTabActivity
03-15 19:11:34.124  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.calllog.LogsFindoSearchResultsActivity
,03-15 19:11:34.124  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:34.124  3914  3973 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-15 19:11:34.124  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.dialpad.RegularSearchActivity
03-15 19:11:34.124  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.interaction.InteractionRecentActivity
,03-15 19:11:34.124  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.editor.SamsungAccountValidationCheckActivity
03-15 19:11:34.124  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.autolink.AutoLinkActivity
03-15 19:11:34.124  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.EmergencyPeopleActivity
03-15 19:11:34.124  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.speeddial.SpeedDialActivity
03-15 19:11:34.124  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardListActivity
03-15 19:11:34.124  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.businesscard.BusinesscardViewer
03-15 19:11:34.124  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageActivity
03-15 19:11:34.124  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.RecentCallMessageActivity
03-15 19:11:34.124  3914  3973 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-15 19:11:34.124  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesEditActivity
03-15 19:11:34.124  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.PhrasesDeleteActivity
03-15 19:11:34.124  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.dialer.callmessage.CallMessageEditActivity
03-15 19:11:34.124  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoDetailActivity
03-15 19:11:34.124  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.emergency.MyEmergencyInfoEditorActivity
03-15 19:11:34.124  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverFavoritesActivity
03-15 19:11:34.124  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:34.124  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-15 19:11:34.124  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.activities.ScoverSelectNumberActivity
03-15 19:11:34.124  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:34.124  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-15 19:11:34.124  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.detail.ShowMyProfileActivity
03-15 19:11:34.124  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.contacts.interactions.InteractionProfileWhiteListActivity
03-15 19:11:34.134  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-15 19:11:34.134  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-15 19:11:34.134  1181  1181 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
03-15 19:11:34.134  2663  2663 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
03-15 19:11:34.134  2663  2738 D HeadsetStateMachine: Disconnected process message: 10
,03-15 19:11:34.144  1018  1129 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-15 19:11:34.144  1018  1129 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.internal.GoogleLocationManagerService; callingUser = 0; userId(target) = 0
,03-15 19:11:34.144  1018  1129 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:34.144  1018  1129 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:34.144  1018  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:34.144  2089  2089 D BootCompletedReceiver: Will NOT schedule AdAttestation signal task because it's disabled.
,03-15 19:11:34.174  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.SSLCertValidationActivity
03-15 19:11:34.174  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.EmailUpgradeKeystoreActivity
03-15 19:11:34.174  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SecurityCertificates
03-15 19:11:34.174  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.Welcome
03-15 19:11:34.174  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.UpgradeAccounts
03-15 19:11:34.174  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupWizard
03-15 19:11:34.174  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.VZWSetupWizard
03-15 19:11:34.174  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreAccounts
03-15 19:11:34.174  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.SncRestoreAccounts
03-15 19:11:34.174  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncRestoreOptions
03-15 19:11:34.174  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncNames
03-15 19:11:34.174  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncExchangeAccounts
03-15 19:11:34.174  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.snc.AccountSetupSncAccountsLogin
03-15 19:11:34.174  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.LDAPClientSettings
03-15 19:11:34.174  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.LDAPAccountsList
03-15 19:11:34.174  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasics
03-15 19:11:34.174  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.DataConnection
03-15 19:11:34.174  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupAccountType
03-15 19:11:34.174  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupIncoming
03-15 19:11:34.174  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOutgoing
03-15 19:11:34.174  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupExchange
03-15 19:11:34.174  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupOptions
,03-15 19:11:34.174  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupNames
03-15 19:11:34.174  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsXL
03-15 19:11:34.174  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsAddRulesforFiltering
03-15 19:11:34.174  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AddPrioritySenderActivity
03-15 19:11:34.174  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSecurity
,03-15 19:11:34.174  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountPreSetup,
,03-15 19:11:34.174  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SaveasActivity
03-15 19:11:34.174  1018  1705 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-15 19:11:34.174  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.Debug
03-15 19:11:34.174  1018  1705 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,03-15 19:11:34.174  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageListXL
03-15 19:11:34.174  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:34.174  3914  3973 I AMMetaDataParserService: getResourcePackageName:assistant,
,03-15 19:11:34.174  3914  3973 I AMMetaDataParserService: Resource data:2131165203
03-15 19:11:34.174  1018  1705 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:34.174  1018  1705 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:34.174  1018  1705 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
03-15 19:11:34.184  3914  3973 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-15 19:11:34.184  2089  4147 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=android.intent.action.BOOT_COMPLETED}]
,03-15 19:11:34.184  1018  1337 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-15 19:11:34.184  1018  1337 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.location.reporting.service.DispatchingService; callingUser = 0; userId(target) = 0
,03-15 19:11:34.184  1018  1337 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:34.184  1018  1337 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:34.184  1018  1337 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:34.184  3958  3958 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,03-15 19:11:34.184  3914  3973 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 19:11:34.184  3914  3973 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-15 19:11:34.184  3914  3973 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 19:11:34.184  3914  3973 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-15 19:11:34.194  3914  3973 I AMMetaDataParserService: getResourceName:com.android.email:xml/email_assistant_menu
03-15 19:11:34.194  3914  3973 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 19:11:34.194  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:34.194  3914  3973 I GFX construct_block_size_descriptor_2d second part: took 2.828542ms for 0*0 texture 0
,03-15 19:11:34.234  1018  1043 W libprocessgroup: failed to open /acct/uid_10092/pid_3399/cgroup.procs: No such file or directory
,03-15 19:11:34.254  1801  1801 I SamsungIME: getCurrentKeyboard
03-15 19:11:34.254  1801  1801 I SamsungIME: getTextKeyboard
,03-15 19:11:34.264  1181  1181 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
,03-15 19:11:34.264  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,03-15 19:11:34.264  3914  3973 I GFX generate_partition_tables: took 10.349480ms for 0*0 texture 0
,03-15 19:11:34.264  3914  3973 I GFX raster: took 14.008126ms for 96*96 texture 0
03-15 19:11:34.264  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb9176ee0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8fcde18 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:34.264  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 19:11:34.264  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 19:11:34.264  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 19:11:34.264  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 19:11:34.274  4215  4215 E KnoxSetupWizardClient: isShipMode : 1
03-15 19:11:34.274  4215  4215 I KnoxSetupWizardClient: onReceive : android.intent.action.BOOT_COMPLETED
,03-15 19:11:34.294  3914  3973 I AMMetaDataParserService: Icon data: ResourceDrawer menu2131363563com.android.email.intent.messagelistfragment.drawer2130837576
,03-15 19:11:34.314  1018  1030 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,03-15 19:11:34.314  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:34.314  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:34.314  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:34.314  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:34.324  1801  1801 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-15 19:11:34.334  4236  4236 E Zygote  : MountEmulatedStorage(),
03-15 19:11:34.334  4236  4236 I libpersona: KNOX_SDCARD checking this for 10107
,03-15 19:11:34.334  4236  4236 E Zygote  : v2
03-15 19:11:34.334  4236  4236 I libpersona: KNOX_SDCARD not a persona
,03-15 19:11:34.334  4236  4236 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-15 19:11:34.334  1018  1030 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=4236 uid=10107 gids={50107, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a,
03-15 19:11:34.334  4236  4236 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-15 19:11:34.334  1018  1030 I ActivityManager: Killing 3409:com.samsung.android.intelligenceservice/u0a3 (adj 15): empty #31,
03-15 19:11:34.334  4236  4236 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-15 19:11:34.374  4236  4236 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:34.374  4236  4236 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:34.384  4198  4198 I DBG_POLICYDM: [com.policydm.XDMApplication(612/xdmWakeLockAcquire)] 
,03-15 19:11:34.384  4198  4198 I DBG_POLICYDM: [com.policydm.XDMApplication(617/xdmWakeLockAcquire)] m_WakeLock is acquire!!
,03-15 19:11:34.394  3178  3207 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 6 sec
,03-15 19:11:34.434  4198  4245 I DBG_POLICYDM: [com.policydm.agent.XDMTask(162/xdmAgentTaskHandler)] XEVENT_OS_INITIALIZED
,03-15 19:11:34.434  4198  4245 I DBG_POLICYDM: [com.policydm.agent.XDMAgent(155/xdmAgentSetSyncMode)] nSync = 0
,03-15 19:11:34.444  4198  4198 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(201/xdmInitExternalStorageState)] 
,03-15 19:11:34.454  4198  4198 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(417/xdmGetExternalSDCardPath)] External SD Card Path : /storage/extSdCard
,03-15 19:11:34.474  2089  2089 D SystemUpdateService: onCreate
,03-15 19:11:34.524  4198  4245 I DBG_POLICYDM: [com.policydm.db.XDB(1530/xdbDMffs_Init)] xdbDMffs_Init
,03-15 19:11:34.534  1018  1952 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,03-15 19:11:34.534  1018  1952 D ActivityManager: retrieveServiceLocked(): component = com.google.android.talk/com.google.android.libraries.hangouts.video.VideoChatService; callingUser = 0; userId(target) = 0
,03-15 19:11:34.534  1018  1952 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:34.534  1018  1952 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-15 19:11:34.534  1018  1952 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.talk, destAppInfo.processName = com.google.android.talk
,03-15 19:11:34.544  4198  4198 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(263/xdmInitExternalStorageState)] bExternalStorageAvailable [true]
,03-15 19:11:34.544  4198  4198 I DBG_POLICYDM: [com.policydm.adapter.XDMTargetAdapter(264/xdmInitExternalStorageState)] bExternalSDStorageAvailable [false]
,03-15 19:11:34.544  4198  4198 I DBG_POLICYDM: [com.policydm.XDMApplication(638/xdmWakeLockRelease)] 
,03-15 19:11:34.544  4198  4198 I DBG_POLICYDM: [com.policydm.XDMApplication(643/xdmWakeLockRelease)] m_WakeLock is release!!
,03-15 19:11:34.544  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:34.554  3914  3973 I GFX raster: took 0.931561ms for 96*96 texture 0
03-15 19:11:34.554  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fcde18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9324fa0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:34.554  4198  4198 I DBG_POLICYDM: [com.policydm.XDMApplication(219/onCreate)] DMApplication Start !
,03-15 19:11:34.554  3914  3973 I AMMetaDataParserService: Icon data: ResourceMessage marked as complete2131362386com.android.email.intent.messageviewfragment.favorite2130837575
,03-15 19:11:34.564  1018  1744 I art     : Explicit concurrent mark sweep GC freed 32845(2023KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 26MB/40MB, paused 2.856ms total 218.043ms
,03-15 19:11:34.574  2089  4257 I CheckinService: Disabling old GoogleServicesFramework version
,03-15 19:11:34.584  1018  1045 D SecurityLogAgent:SEDenialService: Got CLOSE_WRITE Event sk.log
,03-15 19:11:34.594  1018  1045 D SecurityLogAgent:SEDenialService: Got CLOSE_WRITE Event sk.log
,03-15 19:11:34.624  2089  2089 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,03-15 19:11:34.624  1018  1952 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,03-15 19:11:34.634  1018  1952 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:34.634  1018  1952 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:34.634  1018  1952 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:34.634  1018  1952 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:34.644  4264  4264 E Zygote  : MountEmulatedStorage()
03-15 19:11:34.644  4264  4264 E Zygote  : v2
03-15 19:11:34.644  4264  4264 I libpersona: KNOX_SDCARD checking this for 10035
03-15 19:11:34.644  4264  4264 I libpersona: KNOX_SDCARD not a persona
,03-15 19:11:34.654  1018  1952 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=4264 uid=10035 gids={50035, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 19:11:34.654  4264  4264 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-15 19:11:34.654  1018  1952 I ActivityManager: Killing 3432:com.fmm.dm/1000 (adj 15): empty #31
03-15 19:11:34.654  4264  4264 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-15 19:11:34.654  4264  4264 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-15 19:11:34.714  1931  4278 D GCM     : GcmService start Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.intent.action.BOOT_COMPLETED
,03-15 19:11:34.714  4198  4245 I DBG_POLICYDM: [com.policydm.agent.XDMTask(170/xdmAgentTaskHandler)] XEVENT_DM_INIT
,03-15 19:11:34.724  4264  4264 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:34.724  4264  4264 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:34.724  4198  4245 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-15 19:11:34.734  4198  4245 I DBG_POLICYDM: [com.policydm.XDMApplication(677/xdmGetNotibarState)] get NotibarState : 7
,03-15 19:11:34.734  4198  4245 I DBG_POLICYDM: [com.policydm.ui.XUINotificationManager(47/xuiSetIndicator)] Indicator id : 7
,03-15 19:11:34.734   277   951 D EnterpriseController: uids 10012
03-15 19:11:34.734   277   951 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-15 19:11:34.734   277   951 D Netd    : getNetworkForDns: using netid 502 for uid 10012
,03-15 19:11:34.734  4198  4245 I DBG_POLICYDM: [com.policydm.XDMApplication(669/xdmSetNotibarState)] set NotibarState : 7
,03-15 19:11:34.774  4215  4232 W System.err: java.lang.IllegalArgumentException: Unknown package: com.sec.knox.setupwizardstub
03-15 19:11:34.774  4215  4232 W System.err: 	at android.os.Parcel.readException(Parcel.java:1544)
03-15 19:11:34.774  4215  4232 W System.err: 	at android.os.Parcel.readException(Parcel.java:1493)
03-15 19:11:34.774  4215  4232 W System.err: 	at android.content.pm.IPackageManager$Stub$Proxy.setApplicationEnabledSetting(IPackageManager.java:4212)
03-15 19:11:34.774  4215  4232 W System.err: 	at android.app.ApplicationPackageManager.setApplicationEnabledSetting(ApplicationPackageManager.java:1948)
,03-15 19:11:34.784  2089  4262 V AuthZen : Handling intent: android.intent.action.BOOT_COMPLETED
,03-15 19:11:34.814  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:34.814  4215  4232 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.processInternal(StubPackageThread.java:88)
03-15 19:11:34.814  4215  4232 W System.err: 	at com.sec.knox.knoxsetupwizardclient.detector.StubPackageThread.run(StubPackageThread.java:49)
,03-15 19:11:34.814  3914  3973 I GFX raster: took 0.805416ms for 96*96 texture 0
03-15 19:11:34.814  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fcde18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9326390 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:34.834  4198  4245 I DBG_POLICYDM: [com.policydm.db.XDBAESCrypt(216/xdbGetCryptionkey)] try read dbString
,03-15 19:11:34.844  4198  4245 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(427/xdbGetFUMOStatus)] xdbGetFUMOStatus : 0
,03-15 19:11:34.854  4198  4245 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(586/xdbGetFUMOInitiatedType)] Initiated Type: 0
,03-15 19:11:34.854  4198  4246 I DBG_POLICYDM: [com.policydm.agent.XDMUITask(190/xdmUIEvent)] XUI_DM_IDLE_STATE :true
03-15 19:11:34.854  4198  4245 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(71/xpollingCheckVersionInfo)] 
,03-15 19:11:34.854  3914  3973 I AMMetaDataParserService: Icon data: ResourceFlagged message2131362384com.android.email.intent.messageviewfragment.favorite2130837575
,03-15 19:11:34.874  4198  4245 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(270/xpollingCheckTimer)] 
,03-15 19:11:34.874  4198  4245 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(284/xpollingCheckTimer)] savedpollingtime : 2016/03/18/16:12:11
,03-15 19:11:34.904  1018  1705 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-15 19:11:34.904  1018  1705 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,03-15 19:11:34.904  1018  1705 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:34.904  1018  1705 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:34.904  1018  1705 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:34.914  1931  1931 I GCoreUlr: DispatchingService.onCreate()
,03-15 19:11:34.914  4198  4246 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-15 19:11:34.924  2089  4262 D AuthZenEventHandler: Handling event: android.intent.action.BOOT_COMPLETED
,03-15 19:11:34.934  4198  4245 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(285/xpollingCheckTimer)] currentTime : 2016/03/15/19:11:34
,03-15 19:11:34.934  4198  4245 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(289/xpollingCheckTimer)] Restart Timer..
,03-15 19:11:34.944  4198  4246 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-15 19:11:35.004  1018  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
03-15 19:11:35.004  1018  1043 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.api.credentials.sync.CredentialSyncService; callingUser = 0; userId(target) = 0
,03-15 19:11:35.004  4198  4245 I DBG_POLICYDM: [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 0
,03-15 19:11:35.004  4198  4246 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(398/xnotiPushAdpExcuteResumeNoti)] nSessionSaveState:0
,03-15 19:11:35.014  4198  4246 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(399/xnotiPushAdpExcuteResumeNoti)] nNotiUiEvent:0
,03-15 19:11:35.014  4198  4246 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(400/xnotiPushAdpExcuteResumeNoti)] nNotiRetryCount:0
,03-15 19:11:35.024   287   287 E SMD     : DCD OFF,
,03-15 19:11:35.034  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:35.034  3914  3973 I GFX raster: took 0.767240ms for 96*96 texture 0
03-15 19:11:35.034  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fcde18 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9327808 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:35.034  3914  3973 I AMMetaDataParserService: Icon data: ResourceUnflagged message2131362385com.android.email.intent.messageviewfragment.favorite2130837575
,03-15 19:11:35.044  4198  4246 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(440/xnotiPushAdpExcuteResumeNoti)] Current NOTI NOT SAVED State. EXIT.
,03-15 19:11:35.044  4198  4246 I DBG_POLICYDM: [com.policydm.noti.XNOTIAdapter(266/xnotiPushAdpClearSessionStatus)] 
,03-15 19:11:35.044  3938  4139 W jxcore-log: Initializing JXcore engine
03-15 19:11:35.044  3938  4139 W jxcore-log: JXcore engine is ready
,03-15 19:11:35.044  4198  4246 I DBG_POLICYDM: [com.policydm.ui.XUIAdapter(40/xuiAdpSetUiMode)] nDmUiMode : 0
,03-15 19:11:35.044  4198  4246 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(438/xdbSetFUMOStatus)] xdbSetFUMOStatus : 0
,03-15 19:11:35.064  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:35.064  3914  3973 I GFX raster: took 0.597135ms for 96*96 texture 0
03-15 19:11:35.064  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb9328d38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9328d70 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:35.074  4198  4246 I DBG_POLICYDM: [com.policydm.db.XDBFumoAdp(564/xdbSetFUMOInitiatedType)] Initiated Type: 0
,03-15 19:11:35.084  3914  3973 I AMMetaDataParserService: Icon data: ResourceStarred message2131362389com.android.email.intent.messageviewfragment.favorite2130837577
,03-15 19:11:35.124  1928  1928 E audit   : type=1400 msg=audit(1458065495.124:205): avc:  denied  { ioctl } for  pid=4139 comm="Thread-594" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,03-15 19:11:35.124  1928  1928 E audit   :  SEPF_SM-A500FU_5.0.2-1_0038
03-15 19:11:35.124  1928  1928 E audit   : type=1300 msg=audit(1458065495.124:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=a a1=5451 a2=4 a3=9c6da8f8 items=0 ppid=308 ppcomm=main pid=4139 auid=4294967295 uid=10155 gid=10155 euid=10155 suid=10155 fsuid=10155 egid=10155 sgid=10155 fsgid=10155 ses=4294967295 tty=(none) comm="Thread-594" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
03-15 19:11:35.124  1928  1928 E audit   : type=1320 msg=audit(1458065495.124:205): 
,03-15 19:11:35.134  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:35.134  3938  4139 W jxcore-log: Starting JXcore engine
03-15 19:11:35.134  3914  3973 I GFX raster: took 0.622500ms for 96*96 texture 0
03-15 19:11:35.134  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb9328d38 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb932ae80 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:35.154  4198  4246 I DBG_POLICYDM: [com.policydm.db.XDB(1824/xdbSetBackUpServerUrl)] 
,03-15 19:11:35.154  4198  4245 I DBG_POLICYDM: [com.policydm.polling.XPollingAgent(311/xPollingReportReStartAlarm)] 
,03-15 19:11:35.164  3914  3973 I AMMetaDataParserService: Icon data: ResourceUnstarred message2131362390com.android.email.intent.messageviewfragment.favorite2130837577
,03-15 19:11:35.224  1018  1266 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-15 19:11:35.224  1018  1266 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.tron.CollectionService; callingUser = 0; userId(target) = 0
,03-15 19:11:35.224  1018  1266 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:35.224  1018  1266 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-15 19:11:35.224  1018  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:35.254  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.MailboxSettings
03-15 19:11:35.254  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SelectGroup
03-15 19:11:35.254  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.SavedEmail
03-15 19:11:35.254  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.messageview.MessageFileView
03-15 19:11:35.254  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSettingsHtmlSignature
03-15 19:11:35.254  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageCompose
03-15 19:11:35.254  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:35.254  3914  3973 I AMMetaDataParserService: getResourcePackageName:android.app.spellscroll
03-15 19:11:35.254  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SelectMapActivity
03-15 19:11:35.254  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.CustomizeDate
03-15 19:11:35.254  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.QuickReplyActivity
03-15 19:11:35.254  3914  3973 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-15 19:11:35.254  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SettingsReservationActivity
03-15 19:11:35.254  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.AttachmentChooserActivity
03-15 19:11:35.254  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.DebugActivity
03-15 19:11:35.254  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSetupBasicsChoiceProviderForKOR
03-15 19:11:35.254  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiSetup
03-15 19:11:35.254  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.setup.AccountSoundNotiGeneralPreference
03-15 19:11:35.254  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SearchActivity
03-15 19:11:35.254  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:35.254  3914  3973 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-15 19:11:35.254  3914  3973 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-15 19:11:35.254  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.MessageComposeDrawingModePopup
03-15 19:11:35.254  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.utils.airjump.EmailAirScrollTryActivity
03-15 19:11:35.254  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.email.activity.SmartStayActivity
,03-15 19:11:35.264  3938  4139 W jxcore-log: Platform android
03-15 19:11:35.264  3938  4139 W jxcore-log: 
03-15 19:11:35.264  3938  4139 W jxcore-log: Process ARCH arm
03-15 19:11:35.264  3938  4139 W jxcore-log: 
,03-15 19:11:35.294  3958  4285 E SQLiteLog: (284) automatic index on conversation_participants_view(conversation_id)
,03-15 19:11:35.344  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.rcs.RcsNewFeatureActivity
03-15 19:11:35.344  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RoamingGuardPopupActivity
03-15 19:11:35.344  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.AutoRetrievePreferenceActivity
03-15 19:11:35.344  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.AutoRetrieveTabActivity
03-15 19:11:35.344  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConversationComposer
03-15 19:11:35.344  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:35.344  3914  3973 I AMMetaDataParserService: getResourcePackageName:android.app.spellscroll
03-15 19:11:35.344  3914  3973 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-15 19:11:35.344  3914  3973 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 19:11:35.344  3914  3973 I AMMetaDataParserService: Resource data:2131099648
,03-15 19:11:35.354  2089  4261 I SystemUpdateService: cancelUpdate (empty URL)
,03-15 19:11:35.354  2089  4261 I SystemUpdateService: active receiver: disabled
,03-15 19:11:35.374  1018  1952 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
,03-15 19:11:35.374  1018  1952 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:35.374  1018  1952 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:35.374  1018  1952 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:35.384  3914  3973 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
03-15 19:11:35.384  3914  3973 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 19:11:35.384  3914  3973 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-15 19:11:35.384  3914  3973 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 19:11:35.384  3914  3973 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-15 19:11:35.384  3914  3973 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-15 19:11:35.384  3914  3973 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-15 19:11:35.384  3914  3973 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 19:11:35.384  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:35.384  3914  3973 I GFX raster: took 0.736979ms for 96*96 texture 0
03-15 19:11:35.384  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb94d1658 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb94d1930 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:35.394  4264  4298 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,03-15 19:11:35.394  4264  4298 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,03-15 19:11:35.404  4264  4264 E SPPClientService: [[SystemStateMoniter]] ACTION_BOOT_COMPLETED
,03-15 19:11:35.404  4264  4298 D SPPClientService: PushLog.txt file is not deleted.
,03-15 19:11:35.404  4264  4298 D SPPClientService: PushLog.txt file is not deleted.
03-15 19:11:35.404  4264  4298 D SPPClientService: ============PushLog. stop!
,03-15 19:11:35.424  1931  4277 I GCM     : GCM config loaded
,03-15 19:11:35.444  3958  4285 E SQLiteLog: (284) automatic index on conversation_participants_view(conversation_id)
,03-15 19:11:35.464  3178  3207 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 7 sec
,03-15 19:11:35.484  1018  1043 W libprocessgroup: failed to open /acct/uid_10003/pid_3409/cgroup.procs: No such file or directory
03-15 19:11:35.484  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3432/cgroup.procs: No such file or directory
,03-15 19:11:35.484  1018  1031 D ActivityManager: bindService callerProcessName:com.google.android.gm, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
03-15 19:11:35.484  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.analytics.service.AnalyticsService; callingUser = 0; userId(target) = 0
,03-15 19:11:35.484  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:35.484  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:35.484  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gm, destAppInfo.processName = com.google.android.gms
,03-15 19:11:35.494  1018  1266 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 19:11:35.494  1018  1266 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:35.494  1018  1266 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-15 19:11:35.504  1018  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:35.504  3677  3864 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,03-15 19:11:35.514  2089  4262 W BaseAppContext: Using Auth Proxy for data requests.
,03-15 19:11:35.544  4198  4246 I DBG_POLICYDM: [com.policydm.db.XDBProfileListAdp(257/xdbGetNotiSavedInfo)] nSessionSaveState [0], nNotiUiEvent [0]
,03-15 19:11:35.554  3914  3973 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-15 19:11:35.554  1018  1952 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,03-15 19:11:35.554  1018  1952 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:35.564  1018  1952 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:35.564  1018  1952 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:35.564  1018  1952 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:35.564  4198  4246 I DBG_POLICYDM: [com.policydm.db.XDBNotiAdp(37/xdbNotiExistInfo)] Noti Exist : false
,03-15 19:11:35.584  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:35.594  3914  3973 I GFX construct_block_size_descriptor_2d second part: took 2.570053ms for 0*0 texture 0
,03-15 19:11:35.604  4198  4245 I DBG_POLICYDM: [com.policydm.XDMApplication(684/xdmStartAlarm)] Alarm ID: 1
,03-15 19:11:35.624  3914  3973 I GFX generate_partition_tables: took 8.870000ms for 0*0 texture 0
,03-15 19:11:35.624  3914  3973 I GFX raster: took 12.429531ms for 96*96 texture 0
03-15 19:11:35.624  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fac470 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8f8ed98 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:35.624  3914  3973 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-15 19:11:35.654  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:35.654  3914  3973 I GFX raster: took 0.616718ms for 96*96 texture 0
03-15 19:11:35.654  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fab858 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8fbf320 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:35.654  3914  3973 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-15 19:11:35.694  1018  1952 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=4312 uid=10041 gids={50041, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 19:11:35.704  4312  4312 E Zygote  : MountEmulatedStorage()
03-15 19:11:35.704  4312  4312 I libpersona: KNOX_SDCARD checking this for 10041
03-15 19:11:35.704  4312  4312 E Zygote  : v2
03-15 19:11:35.704  4312  4312 I libpersona: KNOX_SDCARD not a persona
03-15 19:11:35.704  4312  4312 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-15 19:11:35.704  4312  4312 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-15 19:11:35.714  4312  4312 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-15 19:11:35.724  3868  3882 W art     : Suspending all threads took: 123.957ms
,03-15 19:11:35.754  1018  1952 I ActivityManager: Killing 3454:com.samsung.android.scloud.backup/u0a60 (adj 15): empty #31
,03-15 19:11:35.764  1018  1044 I ActivityManager: Waited long enough for: ServiceRecord{1c05dc3 u0 com.samsung.hs20settings/.WifiHs20UtilityService}
,03-15 19:11:35.764  1018  4306 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 19:11:35.764  1018  4306 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:35.764  1018  4306 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:35.764  1018  4306 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:35.774  4198  4245 I DBG_POLICYDM: [com.policydm.agent.XDMTask(195/xdmAgentTaskHandler)] XEVENT_DM_INIT : Initialized
,03-15 19:11:35.774  4312  4312 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:35.774  4312  4312 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:35.784  3958  4285 E SQLiteLog: (284) automatic index on conversation_participants_view(conversation_id)
,03-15 19:11:35.784  2089  4258 I CheckinService: Checking schedule, now: 1458065495793 next: 1458246240395
03-15 19:11:35.784  2089  4258 I CheckinService: active receiver: disabled
,03-15 19:11:35.814  2089  4262 E BaseAppContext: Tried to stop global GMSCore RequestQueue. This is likely unintended, so ignoring.
,03-15 19:11:35.844  3938  4139 I jxcore-log: JXcore Cordova bridge is ready!
03-15 19:11:35.844  3938  4139 I jxcore-log: 
,03-15 19:11:35.844  4236  4236 D StrictMode: StrictMode policy violation; ~duration=657 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-15 19:11:35.844  3938  4139 W jxcore-log: JXcore engine is started
03-15 19:11:35.844  4236  4236 D StrictMode: StrictMode policy violation; ~duration=641 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-,15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-15 19:11:35.844  4236  4236 D StrictMode: StrictMode policy violation; ~duration=480 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at java.io.File.doAccess(File.java:283)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at java.io.File.exists(File.java:363)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1331)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
,03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-15 19:11:35.844  4236  4236 D StrictMode: StrictMode policy violation; ~duration=479 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-15 19:11:35.844  4236  4236 D StrictMode: StrictMode policy violation; ~duration=478 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1332)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-15 19:11:35.844  4236  4236 D StrictMode: StrictMode policy violation; ~duration=463 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.r.k.c(PG:1187)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.r.k.a(PG:2107)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.r.v.a(PG:1206)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.r.y.a(PG:2233)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.r.e.b(PG:170)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.r.e.b(PG:13188)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-15 19:11:35.844  4236  4236 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-15 19:11:35.854  4236  4236 D StrictMode: StrictMode policy violation; ~duration=461 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-15 19:11:35.854  4236  4236 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-15 19:11:35.854  4236  4236 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
03-15 19:11:35.854  4236  4236 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
03-15 19:11:35.854  4236  4236 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
03-15 19:11:35.854  4236  4236 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
03-15 19:11:35.854  4236  4236 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
03-15 19:11:35.854  4236  4236 D StrictMode: 	at com.google.r.k.c(PG:1187)
03-15 19:11:35.854  4236  4236 D StrictMode: 	at com.google.r.k.b(PG:14147)
03-15 19:11:35.854  4236  4236 D StrictMode: 	at com.google.r.k.c(PG:583)
03-15 19:11:35.854  4236  4236 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
03-15 19:11:35.854  4236  4236 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
03-15 19:11:35.854  4236  4236 D StrictMode: 	at com.google.r.v.a(PG:1206)
03-15 19:11:35.854  4236  4236 D StrictMode: 	at com.google.r.y.a(PG:2233)
03-15 19:11:35.854  4236  4236 D StrictMode: 	at com.google.r.e.b(PG:170)
03-15 19:11:35.854  4236  4236 D StrictMode: 	at com.google.r.e.b(PG:13188)
03-15 19:11:35.854  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
03-15 19:11:35.854  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
03-15 19:11:35.854  4236  4236 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
03-15 19:11:35.854  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-15 19:11:35.854  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-15 19:11:35.854  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-15 19:11:35.854  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-15 19:11:35.854  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-15 19:11:35.854  4236  4236 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-15 19:11:35.854  4236  4236 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-15 19:11:35.854  4236  4236 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-15 19:11:35.854  4236  4236 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-15 19:11:35.854  4236  4236 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 19:11:35.854  4236  4236 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-15 19:11:35.854  4236  4236 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-15 19:11:35.854  4236  4236 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-15 19:11:35.854  4236  4236 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-15 19:11:35.854  4236  4236 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-15 19:11:35.854  4236  4236 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-15 19:11:35.854  3938  4078 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
03-15 19:11:35.864  4236  4236 D StrictMode: StrictMode policy violation; ~duration=378 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-15 19:11:35.864  4236  4236 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at java.io.File.doAccess(File.java:283)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at java.io.File.exists(File.java:363)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1366)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1389)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1497)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
03-15 19:11:35.864  4236  4236 D StrictMode: StrictMode policy violation; ~duration=377 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
03-15 19:11:35.864  4236  4236 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at java.io.File.doAccess(File.java:283)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at java.io.File.exists(File.java:363)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7692)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5256)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:181)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1543)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
03-15 19:11:35.864  4236  4236 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
,03-15 19:11:35.884  3938  4139 E jxcore  : Error!: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js
03-15 19:11:35.884  3938  4139 E jxcore  : Stack: [{"_fileName":"node.js","_functionName":"$h.require","_lineNumber":"1472","_columnNumber":"1","_msg":"    at $h.require@node.js:1472:1"},{"_fileName":"main.js.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js.js:260:5"},{"_fileName":"main.js.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"},{"_fileName":"node.js","_functionName":"unknown","_lineNumber":"1472","_columnNumber":"1","_msg":""}]
03-15 19:11:35.894  3938  3938 I chromium: [INFO:CONSOLE(54)] "App.js file failed to load : "No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\nError: No such native module /data/data/com.test.thalitest/files/www/jxcore/app.js\n    at $h.require@node.js:1472:1\n    at internal_methods.loadMainFile@main.js.js:260:5\n    at JXMobile.executeJSON@main.js.js:279:7\n    at @JX_Evaluate:1:1\n"", source: file:///android_asset/www/js/thali_main.js (54)
03-15 19:11:35.904  1018  4306 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.mt, hostingType: broadcast
03-15 19:11:35.904  1018  4306 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:35.904  1018  4306 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:35.904  1018  4306 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:35.904  1018  4306 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:35.914  4333  4333 E Zygote  : MountEmulatedStorage()
03-15 19:11:35.914  4333  4333 E Zygote  : v2
03-15 19:11:35.914  4333  4333 I libpersona: KNOX_SDCARD checking this for 1000
03-15 19:11:35.914  4333  4333 I libpersona: KNOX_SDCARD not a persona
03-15 19:11:35.914  4333  4333 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-15 19:11:35.924  4333  4333 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-15 19:11:35.924  1018  4306 I ActivityManager: Start proc com.sec.android.app.mt for broadcast com.sec.android.app.mt/.StatusChecker: pid=4333 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-15 19:11:35.924  1018  4306 I ActivityManager: Killing 3503:com.fmm.ds/1000 (adj 15): empty #31
,03-15 19:11:35.924  1018  1266 D FocusedStackFrame: Set to : 0
,03-15 19:11:35.924  1018  1266 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
03-15 19:11:35.924  1018  1266 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-15 19:11:35.924  1018  1266 D InputDispatcher: Focused application set to: xxxx
,03-15 19:11:35.924  1018  1266 D InputDispatcher: Focus left window: 3938
03-15 19:11:35.924  4333  4333 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 19:11:35.934  4236  4339 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-15 19:11:35.944   257   438 D PermissionCache: checking android.permission.READ_FRAME_BUFFER for uid=1000 => granted (7275 us)
,03-15 19:11:35.954  4333  4333 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:35.954  4333  4333 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:35.964  4236  4339 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
,03-15 19:11:35.964  4236  4339 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
03-15 19:11:35.964  4236  4339 I System.out: (HTTPLog)-Static: isShipBuild true
03-15 19:11:35.964  4236  4339 I System.out: (HTTPLog)-Thread-633-937192661: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-15 19:11:35.964  4236  4339 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,03-15 19:11:35.964  1018  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-15 19:11:35.964  1018  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-15 19:11:35.964   277   951 D EnterpriseController: uids 10107
03-15 19:11:35.964   277   951 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-15 19:11:35.964   277   951 D Netd    : getNetworkForDns: using netid 502 for uid 10107
,03-15 19:11:35.984  3938  4078 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 74ms. Plugin should use CordovaInterface.getThreadPool().
,03-15 19:11:35.994  1018  1043 W libprocessgroup: failed to open /acct/uid_10060/pid_3454/cgroup.procs: No such file or directory
03-15 19:11:35.994  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3503/cgroup.procs: No such file or directory
,03-15 19:11:36.014  1018  1518 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
,03-15 19:11:36.014  1018  1518 W ActivityManager: mDVFSHelper.acquire()
,03-15 19:11:36.014  1018  1518 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-15 19:11:36.014  1018  1518 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
03-15 19:11:36.014  1018  1518 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,03-15 19:11:36.034  1509  1509 D Launcher: onRestart, Launcher: 951088449
,03-15 19:11:36.034  1509  1509 D Launcher: onStart, Launcher: 951088449
03-15 19:11:36.034  1509  1509 D Launcher.HomeView: onStart
,03-15 19:11:36.034  1509  1509 D Launcher: onResume, Launcher: 951088449
,03-15 19:11:36.044  1018  1346 D SettingsProvider: name = kids_home_mode
03-15 19:11:36.044  1018  1346 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-15 19:11:36.044  1018  1346 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-15 19:11:36.044  1018  1346 D SettingsProvider: selectionArgs: false
03-15 19:11:36.044  1018  1346 D SettingsProvider: selectionArgs: 10007
03-15 19:11:36.044  1018  1346 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
03-15 19:11:36.044  1018  1346 D SettingsProvider: ret = -1
,03-15 19:11:36.044  1509  1509 D Launcher.HomeView: onResume
,03-15 19:11:36.044  3958  3970 W art     : Suspending all threads took: 11.975ms
,03-15 19:11:36.044  4236  4339 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,03-15 19:11:36.054  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,03-15 19:11:36.054  1018  1018 D SensorService: [SO] activate (ident=0xb94af8a8, enabled=0)
03-15 19:11:36.054  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-15 19:11:36.064  1509  1509 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-15 19:11:36.064  1018  1018 D SensorManager: unregisterListener ::   
,03-15 19:11:36.064  1018  1018 I Sensors : AccelerometerSensor(0) setDelay : 200000000(ns)
,03-15 19:11:36.064  2089  2089 D SystemUpdateService: onDestroy
,03-15 19:11:36.064  1018  1018 D SensorService: [SO] changed settle time [0]
03-15 19:11:36.064  1018  1018 D SensorService: [SO] setDelay [200000000]
,03-15 19:11:36.064  1018  1018 D SensorService: [SO] activate (ident=0xb94af8a8, enabled=1)
03-15 19:11:36.064  1018  1018 D SensorService: [SO] AR_init
,03-15 19:11:36.074  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-15 19:11:36.074  2089  4262 I AuthZen : Fetching signing key...
,03-15 19:11:36.074  1018  1018 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 200000, 0,  
,03-15 19:11:36.074  1509  1509 D MenuAppsGridFragment: onResume
,03-15 19:11:36.084  1018  1129 D ActivityManager: handle home activity for 0
,03-15 19:11:36.084  1018  1129 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
,03-15 19:11:36.084  1018  1129 D KnoxTimeoutHandler: post home show event for user 0
03-15 19:11:36.084  1018  1018 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
,03-15 19:11:36.084  1018  1129 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-15 19:11:36.084  1018  1018 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
03-15 19:11:36.084  1018  1129 D KnoxTimeoutHandler: postActiveUserChange for user 0
,03-15 19:11:36.084  1018  1129 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-15 19:11:36.084  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-15 19:11:36.084  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,03-15 19:11:36.084  4333  4333 D StatusChecker: onReceive : android.intent.action.BOOT_COMPLETED
,03-15 19:11:36.084   257   257 I SurfaceFlinger: id=12 createSurf (720x1280),1 flag=4, Mauncher
,03-15 19:11:36.094  1018  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-15 19:11:36.094  4333  4333 I StatusChecker: onReceive : net.mt.init : DONE
,03-15 19:11:36.094  4312  4312 I SA      : [SSP] onCreated
,03-15 19:11:36.104  1018  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-15 19:11:36.114  1018  1518 D InputDispatcher: Focus entered window: 1509
,03-15 19:11:36.114  2089  4262 I AuthZen : Signing key fetched successfully!
,03-15 19:11:36.114  1018  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-15 19:11:36.114  1018  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-15 19:11:36.114  1018  1705 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.pagebuddynotisvc, hostingType: broadcast
,03-15 19:11:36.124  1509  1509 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-15 19:11:36.124  1018  1705 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:36.134  1018  1705 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:36.134  1018  1705 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:36.134  1018  1705 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:36.144  4356  4356 E Zygote  : MountEmulatedStorage(),
03-15 19:11:36.144  4356  4356 E Zygote  : v2
03-15 19:11:36.144  4356  4356 I libpersona: KNOX_SDCARD checking this for 10116
03-15 19:11:36.144  4356  4356 I libpersona: KNOX_SDCARD not a persona
,03-15 19:11:36.144  4356  4356 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-15 19:11:36.154  1018  1705 I ActivityManager: Start proc com.sec.android.pagebuddynotisvc for broadcast com.sec.android.pagebuddynotisvc/.PageBuddyNotiSvcBRcvr: pid=4356 uid=10116 gids={50116, 9997} abi=armeabi-v7a,
,03-15 19:11:36.154  4356  4356 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-15 19:11:36.154  4356  4356 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 19:11:36.174  1018  1705 I ActivityManager: Killing 1404:com.android.defcontainer/u0a4 (adj 15): empty #31
03-15 19:11:36.174  1509  1509 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-15 19:11:36.174  3958  4285 E SQLiteLog: (284) automatic index on conversation_participants_view(conversation_id)
,03-15 19:11:36.174  1018  1346 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-15 19:11:36.184  1181  1181 D PanelView: There is/are notification(s) 
,03-15 19:11:36.184  3938  3938 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,03-15 19:11:36.184  1018  4369 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-15 19:11:36.194  1801  1801 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-15 19:11:36.204  4356  4356 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:36.204  4356  4356 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:36.214  3958  4285 E SQLiteLog: (284) automatic index on conversation_participants_view(conversation_id)
,03-15 19:11:36.214  4312  4312 I SA      : [TPM] There is no property file
,03-15 19:11:36.224  4312  4312 I SA      : [SCU] isHaveSA() - false
,03-15 19:11:36.224  1509  1509 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@88e805f time:47754
,03-15 19:11:36.224  4312  4312 I SA      : [TPM] getModelProperty : null
03-15 19:11:36.224  4312  4312 I SA      : [TPM] getCSCProperty : null
,03-15 19:11:36.224  4236  4295 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,03-15 19:11:36.224  1018  1051 D PersonaManager: isKioskContainerExistOnDevice
,03-15 19:11:36.234  1018  1518 I ActivityManager: Killing 3524:com.samsung.android.scloud.sync/u0a62 (adj 15): empty #31
,03-15 19:11:36.244  1018  1051 I ActivityManager: Displayed Component not be shown by security: +235ms
,03-15 19:11:36.254  4312  4312 I SA      : [DM] FLOATING AMOLED FEATURE: true
03-15 19:11:36.254  4312  4312 I SA      : [DM] PRODUCT AMOLED FEATURE: false
03-15 19:11:36.254  4312  4312 I SA      : [DM] TFT FEATURE: false
,03-15 19:11:36.264  1678  1749 I art     : Explicit concurrent mark sweep GC freed 5559(227KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 7MB/12MB, paused 842us total 53.586ms
,03-15 19:11:36.264  4356  4356 I PageBuddyNotiSvc: Intent received : action=android.intent.action.BOOT_COMPLETED
,03-15 19:11:36.264  2089  4262 W BaseAppContext: Using Auth Proxy for data requests.
,03-15 19:11:36.274  4312  4312 I SA      : [SBR] StdBroadcastReceiver received Intent of  action_BOOT_COMPLETED extra.user_handle.:0
03-15 19:11:36.274  4312  4312 I SA      : [DM] init START
,03-15 19:11:36.274  1018  1041 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-15 19:11:36.284  4118  4146 W dex2oat : Verification of void android.support.v4.app.a.run() took 122.564ms,
03-15 19:11:36.284  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 19:11:36.284  3914  3973 I GFX raster: took 0.672344ms for 96*96 texture 0,
03-15 19:11:36.284  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fcdd08 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8fcaec8 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:36.284  4356  4356 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.sec.android.pagebuddynotisvc } android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.sec.android.pagebuddynotisvc.PageBuddyNotiSvcBRcvr.onReceive:-1 
,03-15 19:11:36.284  1678  1695 W SQLiteConnectionPool: A SQLiteConnection object for database '+data+user+0+com_google_android_gsf+databases+gservices_db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,03-15 19:11:36.294  4312  4312 I SA      : [DM] This device is not a Vodafone
,03-15 19:11:36.294  3914  3973 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-15 19:11:36.294  1018  1504 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 19:11:36.304  1018  1504 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:36.304  1018  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:36.304  1018  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.pagebuddynotisvc, destAppInfo.processName = com.sec.android.pagebuddynotisvc
,03-15 19:11:36.304  4356  4356 I PageBuddyNotiSvc: onCreate mCpBitFlag=0
,03-15 19:11:36.314  1018  1952 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,03-15 19:11:36.314  3914  3973 I art     : WaitForGcToComplete blocked for 17.328ms for cause DisableMovingGc
,03-15 19:11:36.314  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:36.314  3914  3973 I GFX raster: took 0.624844ms for 96*96 texture 0
03-15 19:11:36.314  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8f68830 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f8fc38 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:36.314  1018  1952 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:36.314  1018  1952 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:36.314  1018  1952 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:36.314  1018  1952 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:36.324  3914  3973 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-15 19:11:36.324  4312  4312 W ResourceType: Failure getting entry for 0x7f060010 (t=5 e=16) (error -75)
,03-15 19:11:36.334  4312  4312 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
,03-15 19:11:36.334  4019  4039 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-15 19:11:36.334  4019  4039 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 19:11:36.334  4019  4039 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-15 19:11:36.334  4312  4312 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
,03-15 19:11:36.334  4377  4377 E Zygote  : MountEmulatedStorage()
03-15 19:11:36.334  4377  4377 E Zygote  : v2
03-15 19:11:36.334  4377  4377 I libpersona: KNOX_SDCARD checking this for 10125
03-15 19:11:36.334  4377  4377 I libpersona: KNOX_SDCARD not a persona
03-15 19:11:36.334  1018  1043 W libprocessgroup: failed to open /acct/uid_10062/pid_3524/cgroup.procs: No such file or directory
03-15 19:11:36.334  1018  1043 W libprocessgroup: failed to open /acct/uid_10004/pid_1404/cgroup.procs: No such file or directory
,03-15 19:11:36.334  4312  4312 W ResourceType: Failure getting entry for 0x7f06000c (t=5 e=12) (error -75)
,03-15 19:11:36.334  4312  4312 W ResourceType: Failure getting entry for 0x7f06000d (t=5 e=13) (error -75)
03-15 19:11:36.334  4312  4312 W ResourceType: Failure getting entry for 0x7f060002 (t=5 e=2) (error -75)
,03-15 19:11:36.334  4312  4312 W ResourceType: Failure getting entry for 0x7f060014 (t=5 e=20) (error -75)
03-15 19:11:36.334  4377  4377 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-15 19:11:36.334  1018  1952 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=4377 uid=10125 gids={50125, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,03-15 19:11:36.344  4312  4312 W ResourceType: No package identifier when getting value for resource number 0x00000000
,03-15 19:11:36.344  4312  4312 W ResourceType: Failure getting entry for 0x7f060027 (t=5 e=39) (error -75),
03-15 19:11:36.344  4312  4312 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
03-15 19:11:36.344  4312  4312 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75),
03-15 19:11:36.344  4312  4312 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
03-15 19:11:36.344  4312  4312 W ResourceType: Failure getting entry for 0x7f06002b (t=5 e=43) (error -75)
,03-15 19:11:36.344  4312  4312 W ResourceType: Failure getting entry for 0x7f06002c (t=5 e=44) (error -75)
03-15 19:11:36.344  4312  4312 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
,03-15 19:11:36.344  4312  4312 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
03-15 19:11:36.344  4312  4312 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
03-15 19:11:36.344  4377  4377 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-15 19:11:36.344  4312  4312 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
03-15 19:11:36.344  4312  4312 W ResourceType: Failure getting entry for 0x7f06001f (t=5 e=31) (error -75)
,03-15 19:11:36.344  4377  4377 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 19:11:36.344  4312  4312 W ResourceType: Failure getting entry for 0x7f060011 (t=5 e=17) (error -75)
,03-15 19:11:36.354  4312  4312 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
03-15 19:11:36.354  4312  4312 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
,03-15 19:11:36.354  4312  4312 W ResourceType: Failure getting entry for 0x7f060003 (t=5 e=3) (error -75)
03-15 19:11:36.354  4312  4312 W ResourceType: Failure getting entry for 0x7f060015 (t=5 e=21) (error -75)
,03-15 19:11:36.354  4312  4312 W ResourceType: Failure getting entry for 0x7f060016 (t=5 e=22) (error -75)
,03-15 19:11:36.374  4312  4312 I SA      : [SCU] isHaveSA() - false
03-15 19:11:36.374  4312  4312 I SA      : support phone number id : false
03-15 19:11:36.374  4312  4312 I SA      : [DM] Supports Ref Jpn : true
,03-15 19:11:36.374  4312  4312 I SA      : [DM] init END
,03-15 19:11:36.374  4312  4312 I SA      : [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
03-15 19:11:36.374  4312  4312 I SA      : [OR] onReceive Intent=[ action_BOOT_COMPLETED extra.user_handle.:0 ]
,03-15 19:11:36.384  1018  1952 D ActivityManager: startService callerProcessName:com.osp.app.signin, calleePkgName: com.osp.app.signin
,03-15 19:11:36.384  1018  1952 D ActivityManager: retrieveServiceLocked(): component = com.osp.app.signin/com.osp.app.signin.BootDbCheck; callingUser = 0; userId(target) = 0
,03-15 19:11:36.394  1018  1952 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:36.394  1018  1952 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
03-15 19:11:36.394  1018  1952 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.osp.app.signin, destAppInfo.processName = com.osp.app.signin
,03-15 19:11:36.394  1018  1346 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
03-15 19:11:36.394  1018  1346 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.GetToken; callingUser = 0; userId(target) = 0
,03-15 19:11:36.394  1018  1346 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:36.394  1018  1346 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:36.394  1018  1346 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,03-15 19:11:36.394  2089  4262 D a       : Opening database auth.proximity.permit_store...
,03-15 19:11:36.404  4312  4312 I SA      : [OR] onReceive END
,03-15 19:11:36.404  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.android.providers.calendar, hostingType: broadcast
,03-15 19:11:36.404  4377  4377 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 19:11:36.404  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:36.404  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:36.404  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:36.404  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:36.404  4377  4377 D ActivityThread: Added TimaKeyStore provider,
,03-15 19:11:36.414  4394  4394 E Zygote  : MountEmulatedStorage(),
,03-15 19:11:36.424  4394  4394 E Zygote  : v2
03-15 19:11:36.424  2089  4262 D AuthZenTransactionCache: Initialized cache in: /data/data/com.google.android.gms/files
,03-15 19:11:36.424  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 19:11:36.424  2089  4262 D AuthZenTransactionCache: Clearing transaction cache
03-15 19:11:36.424  4394  4394 I libpersona: KNOX_SDCARD checking this for 10042
,03-15 19:11:36.424  3914  3973 I GFX raster: took 0.737813ms for 96*96 texture 0
03-15 19:11:36.424  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8efb238 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9177238 counterpartCT=4 counterpartW=96 counterparth=96
03-15 19:11:36.424  4394  4394 I libpersona: KNOX_SDCARD not a persona,
03-15 19:11:36.424  1018  1031 I ActivityManager: Start proc com.android.providers.calendar for broadcast com.android.providers.calendar/.CalendarReceiver: pid=4394 uid=10042 gids={50042, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 19:11:36.424  4394  4394 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-15 19:11:36.424  3914  3973 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-15 19:11:36.434  4394  4394 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-15 19:11:36.434  4394  4394 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-15 19:11:36.444  1018  1337 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 19:11:36.454  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageActivityNoLockScreen
03-15 19:11:36.454  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessageMms
03-15 19:11:36.454  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:36.454  3914  3973 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 19:11:36.454  3914  3973 I AMMetaDataParserService: Resource data:2131099648
,03-15 19:11:36.454  1018  1337 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:36.454  1018  1337 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:36.454  1018  1337 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,03-15 19:11:36.464  3914  3973 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-15 19:11:36.464  3914  3973 I AMMetaDataParserService: getResourceTypeNamexml
03-15 19:11:36.464  3178  3207 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 8 sec
,03-15 19:11:36.464  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:36.464  3914  3973 I GFX raster: took 0.688229ms for 96*96 texture 0
03-15 19:11:36.464  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb91762e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f8fc38 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:36.474  1018  1041 D SensorService: [SO] currT = 48000110917, prevT = 47580111490, diff = 419999427, [0.134 0.402 10.132]
,03-15 19:11:36.474  1018  1041 D SensorService: [SO] 0.134 0.402 10.132
03-15 19:11:36.474  1018  1041 D SensorService: [SO] [100 -> 255]
,03-15 19:11:36.474  4394  4394 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:36.474  4394  4394 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:36.484  4377  4377 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-15 19:11:36.484  4377  4377 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-15 19:11:36.484  4377  4377 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,03-15 19:11:36.494  3914  3973 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-15 19:11:36.504  4312  4312 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,03-15 19:11:36.504  4312  4312 I SA      : [ODM] queryOpenData(key= GEO_IP )
,03-15 19:11:36.504  1018  1044 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
,03-15 19:11:36.514  1018  1044 W ActivityManager: mDVFSHelper.release()
,03-15 19:11:36.514  1018  1044 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@11
,03-15 19:11:36.524  4394  4394 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,03-15 19:11:36.534  4312  4312 I SA      : getMccForGalaxyJpn step2 GEO_IP MCC : 260
03-15 19:11:36.534  4312  4312 I SA      : [LBE] REF_JPN : true
,03-15 19:11:36.534  4312  4312 I SA      : [BDC] create
,03-15 19:11:36.534  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:36.544  3914  3973 I GFX raster: took 0.724948ms for 96*96 texture 0
03-15 19:11:36.544  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fa6178 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8c46878 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:36.554  3914  3973 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-15 19:11:36.564  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:36.564  3914  3973 I GFX raster: took 0.629219ms for 96*96 texture 0
,03-15 19:11:36.564  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fab858 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb9329a80 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:36.584  3914  3973 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-15 19:11:36.584  1018  1129 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-15 19:11:36.584  1018  1129 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.playlog.service.MonitorService; callingUser = 0; userId(target) = 0
,03-15 19:11:36.584  1018  1129 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:36.584  1018  1129 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-15 19:11:36.594  1018  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:36.594  4312  4312 I SA      : [DBMV2] getEmailID
,03-15 19:11:36.594  4312  4312 I SA      : [DBMV2] getDataV02ForItems
,03-15 19:11:36.594  4312  4312 I SA      : [SSP] query invoked
,03-15 19:11:36.604  4312  4312 I SA      : [SCU] get signed id from samsung account2.0 DB.
,03-15 19:11:36.654  4377  4377 D QuickConnect: PeriphStartReceiver.onReceive - android.intent.action.BOOT_COMPLETED
,03-15 19:11:36.654  4312  4312 I SA      : [SCU] get signed id from samsung account1.0 DB.
,03-15 19:11:36.654  4377  4377 D QuickConnect: Util.setSCRunningSetting - [value]0
,03-15 19:11:36.654  1018  1031 D SettingsProvider: name = scon_is_running
,03-15 19:11:36.654  1018  1031 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-15 19:11:36.654  1018  1031 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,03-15 19:11:36.654  1018  1031 D SettingsProvider: selectionArgs: false
03-15 19:11:36.654  1018  1031 D SettingsProvider: selectionArgs: 10125
,03-15 19:11:36.654  1018  1031 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,03-15 19:11:36.664  4312  4312 I SA      : [BDC] destroy
,03-15 19:11:36.664  1018  1952 I ActivityManager: Killing 3561:com.sec.android.app.servicemodeapp/1000 (adj 15): empty #31
,03-15 19:11:36.664  1018  1031 D SettingsProvider: ret = -1
,03-15 19:11:36.674  1018  1031 W BackupManagerService: dataChanged but no participant pkg='com.android.providers.settings' uid=10125
,03-15 19:11:36.684  1018  1051 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{11335cf1 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t11} time:48211
,03-15 19:11:36.684  4394  4394 I CalendarProvider2: CalendarProvider2.onCreate() called
,03-15 19:11:36.694  1018  1044 I ActivityManager: Killing 3552:com.sec.esdk.elm/u0a94 (adj 15): empty #31
,03-15 19:11:36.694   257   440 I SurfaceFlinger: id=11 Removed NainActivit (7/8)
,03-15 19:11:36.694  4377  4377 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care ACTION_BOOT_COMPLETED. run P service
03-15 19:11:36.694   257  1795 I SurfaceFlinger: id=11 Removed NainActivit (-2/8)
,03-15 19:11:36.694  1801  4235 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,03-15 19:11:36.704  4377  4377 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,03-15 19:11:36.704  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-15 19:11:36.704  1018  1952 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.sbrowser, hostingType: broadcast
,03-15 19:11:36.704  1018  1952 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:36.704  1018  1952 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:36.704  1018  1952 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:36.704  1018  1952 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:36.714   256   507 I SecDataIO: Write to block
,03-15 19:11:36.724  1018  1952 I ActivityManager: Start proc com.sec.android.app.sbrowser for broadcast com.sec.android.app.sbrowser/.net.NetworkSettingsReceiver: pid=4415 uid=10131 gids={50131, 9997, 1023, 3003, 1028, 1015, 1007, 3001, 3002} abi=armeabi-v7a
03-15 19:11:36.724  1018  1952 I ActivityManager: Killing 3613:com.sec.factory.camera/1000 (adj 15): empty #31
,03-15 19:11:36.734  4415  4415 E Zygote  : MountEmulatedStorage()
03-15 19:11:36.734  4415  4415 I libpersona: KNOX_SDCARD checking this for 10131
03-15 19:11:36.734  4415  4415 E Zygote  : v2
03-15 19:11:36.734  4415  4415 I libpersona: KNOX_SDCARD not a persona
03-15 19:11:36.734  4415  4415 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-15 19:11:36.734  2610  3252 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendStickyBroadcast:1865 android.content.ContextWrapper.sendStickyBroadcast:463 com.sec.android.app.sysscope.service.h.run:-1 java.lang.Thread.run:818 <bottom of call stack> 
,03-15 19:11:36.734  4415  4415 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-15 19:11:36.744  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 19:11:36.744  3914  3973 I GFX raster: took 0.659427ms for 96*96 texture 0
03-15 19:11:36.744  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fcdd08 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8f8fc38 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:36.754  1931  4289 I art     : Explicit concurrent mark sweep GC freed 29021(1892KB) AllocSpace objects, 28(448KB) LOS objects, 39% free, 12MB/21MB, paused 857.403ms total 1.517s
,03-15 19:11:36.754  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3561/cgroup.procs: No such file or directory
,03-15 19:11:36.774  4415  4415 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 19:11:36.774  3178  3178 I DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(352/onReceive)] com.sec.intent.action.SYSSCOPESTATUS
,03-15 19:11:36.774  3178  3178 I DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(356/onReceive)] status  = 1
,03-15 19:11:36.784  1931  2104 W GCoreFlp: No location to return for getLastLocation()
,03-15 19:11:36.784  3178  3178 E DBG_DM  : [com.wssyncmldm.llIlIIIIlIIIIIlIlIII(367/onReceive)] Device is ok
,03-15 19:11:36.784  2610  2610 I Process : Sending signal. PID: 2610 SIG: 9
,03-15 19:11:36.784  1931  4410 W FusedLocationProvider: location=null
,03-15 19:11:36.804  3178  3178 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,03-15 19:11:36.814  4415  4415 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:36.814  4415  4415 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:36.814  1018  1018 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@11
,03-15 19:11:36.814  1931  1931 W Auth    : [FRP,FrpUpdateIntentService] Received invalid intent action: com.google.android.gms.auth.ACTION_INVALID
,03-15 19:11:36.814  3914  3973 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-15 19:11:36.814  1931  4289 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction android.intent.action.BOOT_COMPLETED
,03-15 19:11:36.824  1018  1346 I ActivityManager: Killing 3594:com.wssnps/1000 (adj 15): empty #31
,03-15 19:11:36.854  1018  1053 D PowerManagerService: [s] UserActivityState : 1 -> 2
,03-15 19:11:36.854  1018  1053 D DisplayPowerController: getFinalBrightness : Summary is 19 -> 19
,03-15 19:11:36.854  1018  1053 D DisplayPowerController: animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-15 19:11:36.854  4415  4415 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
03-15 19:11:36.854  4415  4415 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 19:11:36.854  4415  4415 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-15 19:11:36.854  4415  4415 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-15 19:11:36.864  1018  1043 W libprocessgroup: failed to open /acct/uid_10094/pid_3552/cgroup.procs: No such file or directory
,03-15 19:11:36.864  1931  2104 W GCoreFlp: No location to return for getLastLocation()
,03-15 19:11:36.864  1931  1946 W FusedLocationProvider: location=null
,03-15 19:11:36.864  1018  1053 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,03-15 19:11:36.864  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:36.864  3914  3973 I GFX raster: took 0.635208ms for 96*96 texture 0
03-15 19:11:36.864  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8f68830 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8c3eae0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:36.874  1018  1161 D lights  : lcd : 26 +
,03-15 19:11:36.884  1018  1129 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-15 19:11:36.884  3938  3938 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3938
,03-15 19:11:36.884  1018  1129 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.change.LoginAccountsChangedIntentService; callingUser = 0; userId(target) = 0
,03-15 19:11:36.884  1018  1129 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:36.884  1018  1129 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:36.884  1018  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:36.894  3914  3973 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-15 19:11:36.894  1018  1053 D DisplayPowerController: getFinalBrightness : Summary is 19 -> 19
,03-15 19:11:36.894  1018  1053 D DisplayPowerController: animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-15 19:11:36.894  1018  1161 D lights  : lcd : 26 -
,03-15 19:11:36.894  1018  1161 D lights  : lcd : 19 +
,03-15 19:11:36.904  1018  1337 W ActivityManager: Duplicate finish request for ActivityRecord{31ec2767 u0 com.test.thalitest/.MainActivity t12 f}
,03-15 19:11:36.904  3938  3938 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@1980261e that was originally registered here. Are you missing a call to unregisterReceiver()?
03-15 19:11:36.904  3938  3938 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager$BluetoothModeBroadcastReceiver@1980261e that was originally registered here. Are you missing a call to unregisterReceiver()?
03-15 19:11:36.904  3938  3938 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-15 19:11:36.904  3938  3938 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-15 19:11:36.904  3938  3938 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-15 19:11:36.904  3938  3938 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-15 19:11:36.904  3938  3938 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-15 19:11:36.904  3938  3938 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.initialize(BluetoothManager.java:275)
03-15 19:11:36.904  3938  3938 E ActivityThread: 	at org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager.bind(BluetoothManager.java:103)
03-15 19:11:36.904  3938  3938 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:75)
03-15 19:11:36.904  3938  3938 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-15 19:11:36.904  3938  3938 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-15 19:11:36.904  3938  3938 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-15 19:11:36.904  3938  3938 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-15 19:11:36.904  3938  3938 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-15 19:11:36.904  3938  3938 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-15 19:11:36.904  3938  3938 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-15 19:11:36.904  3938  3938 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-15 19:11:36.904  3938  3938 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-15 19:11:36.904  3938  3938 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-15 19:11:36.904  3938  3938 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 19:11:36.904  3938  3938 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-15 19:11:36.904  3938  3938 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-15 19:11:36.904  1018  1161 D lights  : lcd : 19 -
,03-15 19:11:36.904  1018  1053 D DisplayPowerController: getFinalBrightness : Summary is 19 -> 19
03-15 19:11:36.904  1018  1053 D DisplayPowerController: animation target = 19, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-15 19:11:36.914  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3613/cgroup.procs: No such file or directory
,03-15 19:11:36.914  1018  1346 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 19:11:36.914  1018  1346 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:36.914  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3594/cgroup.procs: No such file or directory
,03-15 19:11:36.924  1931  1931 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 19:11:36.924  1018  1346 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-15 19:11:36.934  1018  1346 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.maps, destAppInfo.processName = com.google.android.gms
,03-15 19:11:36.934  1018  1337 I ActivityManager: Process com.sec.android.app.sysscope (pid 2610)(adj 0) has died(63,1125)
,03-15 19:11:36.944  4415  4415 D SBrowserFeatureFlag: initialized in static block : loadCscFeatureValue() succeed! 
,03-15 19:11:36.954  3938  3938 E ActivityThread: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@1eb23a59 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-15 19:11:36.954  3938  3938 E ActivityThread: android.app.IntentReceiverLeaked: Activity com.test.thalitest.MainActivity has leaked IntentReceiver io.jxcore.node.ConnectivityMonitor$WifiStateChangedAndConnectivityActionBroadcastReceiver@1eb23a59 that was originally registered here. Are you missing a call to unregisterReceiver()?
03-15 19:11:36.954  3938  3938 E ActivityThread: 	at android.app.LoadedApk$ReceiverDispatcher.<init>(LoadedApk.java:970)
03-15 19:11:36.954  3938  3938 E ActivityThread: 	at android.app.LoadedApk.getReceiverDispatcher(LoadedApk.java:771)
03-15 19:11:36.954  3938  3938 E ActivityThread: 	at android.app.ContextImpl.registerReceiverInternal(ContextImpl.java:2014)
03-15 19:11:36.954  3938  3938 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1994)
03-15 19:11:36.954  3938  3938 E ActivityThread: 	at android.app.ContextImpl.registerReceiver(ContextImpl.java:1988)
03-15 19:11:36.954  3938  3938 E ActivityThread: 	at android.content.ContextWrapper.registerReceiver(ContextWrapper.java:503)
03-15 19:11:36.954  3938  3938 E ActivityThread: 	at io.jxcore.node.ConnectivityMonitor.start(ConnectivityMonitor.java:67)
03-15 19:11:36.954  3938  3938 E ActivityThread: 	at io.jxcore.node.ConnectionHelper.<init>(ConnectionHelper.java:90)
03-15 19:11:36.954  3938  3938 E ActivityThread: 	at io.jxcore.node.JXcoreExtension.LoadExtensions(JXcoreExtension.java:84)
03-15 19:11:36.954  3938  3938 E ActivityThread: 	at io.jxcore.node.jxcore.pluginInitialize(jxcore.java:335)
03-15 19:11:36.954  3938  3938 E ActivityThread: 	at org.apache.cordova.CordovaPlugin.privateInitialize(CordovaPlugin.java:58)
03-15 19:11:36.954  3938  3938 E ActivityThread: 	at org.apache.cordova.PluginManager.getPlugin(PluginManager.java:172)
03-15 19:11:36.954  3938  3938 E ActivityThread: 	at org.apache.cordova.PluginManager.exec(PluginManager.java:123)
03-15 19:11:36.954  3938  3938 E ActivityThread: 	at org.apache.cordova.CordovaBridge.jsExec(CordovaBridge.java:59)
03-15 19:11:36.954  3938  3938 E ActivityThread: 	at org.apache.cordova.engine.SystemExposedJsApi.exec(SystemExposedJsApi.java:41)
03-15 19:11:36.954  3938  3938 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.nativeDoRunLoopOnce(Native Method)
03-15 19:11:36.954  3938  3938 E ActivityThread: 	at org.chromium.base.SystemMessageHandler.handleMessage(SystemMessageHandler.java:53)
03-15 19:11:36.954  3938  3938 E ActivityThread: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-15 19:11:36.954  3938  3938 E ActivityThread: 	at android.os.Looper.loop(Looper.java:145)
03-15 19:11:36.954  3938  3938 E ActivityThread: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,03-15 19:11:36.964  1018  4306 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 19:11:36.964  1018  4306 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:36.974  1018  4306 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:36.974  1018  4306 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:36.974  1018  1518 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 19:11:36.974  1018  1518 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:36.974  1018  1518 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:36.974  1018  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:37.004  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:37.004  3914  3973 I GFX raster: took 0.724948ms for 96*96 texture 0
03-15 19:11:37.004  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8efb238 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8c5a8b8 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:37.014  4415  4415 D ManifestProvider: onCreate()
,03-15 19:11:37.024  3914  3973 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-15 19:11:37.034  1931  1931 D PersistentNotificationBroadcastReceiver: Received intent: Intent { act=android.intent.action.BOOT_COMPLETED flg=0x8000010 cmp=com.google.android.gms/.common.notification.PersistentNotificationBroadcastReceiver (has extras) }
,03-15 19:11:37.044  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.TransferContentActivity
,03-15 19:11:37.044  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CbConfigPreferenceActivity
03-15 19:11:37.044  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CbSettingTabActivity
,03-15 19:11:37.044  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ComposeMessage
03-15 19:11:37.044  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 19:11:37.044  3914  3973 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 19:11:37.044  3914  3973 I AMMetaDataParserService: Resource data:2131099648
,03-15 19:11:37.054  3914  3973 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-15 19:11:37.054  3914  3973 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 19:11:37.054  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:37.054  3914  3973 I GFX raster: took 0.690468ms for 96*96 texture 0
03-15 19:11:37.054  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb91762e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f68320 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:37.064  1018  1744 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 19:11:37.064  1018  1744 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:37.064  1018  1744 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:37.064  1018  1744 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:37.074  3914  3973 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-15 19:11:37.074  4415  4415 E NetworkSettingsReceiver: onReceive: android.intent.action.BOOT_COMPLETED
,03-15 19:11:37.074  1018  4423 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-15 19:11:37.074  1018  4423 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.people.sync.focus.ContactsSyncIntentService; callingUser = 0; userId(target) = 0
,03-15 19:11:37.074  1018  4423 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:37.074  1018  4423 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:37.074  1018  4423 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:37.104  1931  4289 I GCoreUlr: WorldUpdater:android.intent.action.BOOT_COMPLETED: Ensuring that reporting is stopped because of reasons: {account#2#=[InactiveReason{mVersionCode=0, mIdentifier=12, mName='LocationDisabled'}, InactiveReason{mVersionCode=0, mIdentifier=6, mName='ReportingNotEnabled'}, InactiveReason{mVersionCode=0, mIdentifier=14, mName='HistoryNotEnabled'}]}
,03-15 19:11:37.114  1018  1504 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-15 19:11:37.114  1018  1504 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncReceiverService; callingUser = 0; userId(target) = 0
,03-15 19:11:37.114  1018  1504 W ActivityManager: userId = 0, bbcId = -10000,
03-15 19:11:37.124  1018  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:37.124  1018  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:37.134  1931  4289 I GCoreUlr: Unbound from all location providers
03-15 19:11:37.134  1931  4289 I GCoreUlr: Place inference reporting - stopped
,03-15 19:11:37.134  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:37.134  3914  3973 I GFX raster: took 0.664062ms for 96*96 texture 0
03-15 19:11:37.134  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fa6178 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8c5a8b8 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:37.144  2089  2089 V Herrevad: NQAS connected
,03-15 19:11:37.154  3914  3973 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-15 19:11:37.174  4415  4415 E SBrowserFeatureFlag: initSupportedPkg: checkExistService com.samsung.android.smartclip.SpenGestureManager@38b07541
,03-15 19:11:37.174  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 19:11:37.174  4415  4415 D SBrowserFeatureFlag: initialize : initSupportedPkg() succeed! 
03-15 19:11:37.174  4415  4415 I VerificationLog: SbrowserSettings- url content://com.sec.android.app.sbrowser/readinglist/pinned.mhtml
,03-15 19:11:37.174  3914  3973 I GFX raster: took 0.651564ms for 96*96 texture 0
03-15 19:11:37.174  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fab858 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8f8fc38 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:37.174  1931  1931 I GCoreUlr: DispatchingService.onDestroy()
,03-15 19:11:37.174  1931  1931 I GCoreUlr: Stopping handler for UlrDispSvcFast
,03-15 19:11:37.184  1931  1931 I GCoreUlr: Unbound from all location providers
,03-15 19:11:37.184  1931  1931 I GCoreUlr: Place inference reporting - stopped
,03-15 19:11:37.204  1018  1705 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,03-15 19:11:37.204  1018  1705 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:37.204  3914  3973 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-15 19:11:37.204  1018  1705 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:37.204  1018  1705 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:37.204  1018  1705 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:37.214  4452  4452 E Zygote  : MountEmulatedStorage()
03-15 19:11:37.214  4452  4452 E Zygote  : v2
03-15 19:11:37.214  4452  4452 I libpersona: KNOX_SDCARD checking this for 10135
03-15 19:11:37.214  4452  4452 I libpersona: KNOX_SDCARD not a persona
03-15 19:11:37.214  4452  4452 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-15 19:11:37.224  4452  4452 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-15 19:11:37.224  1018  1705 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=4452 uid=10135 gids={50135, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
03-15 19:11:37.224  1018  1705 I ActivityManager: Killing 3656:com.samsung.android.app.watchmanagerstub/u0a100 (adj 15): empty #31
,03-15 19:11:37.224  4452  4452 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-15 19:11:37.234  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:37.234  3914  3973 I GFX raster: took 0.772917ms for 96*96 texture 0
03-15 19:11:37.234  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fcdd08 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8fca4e8 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:37.244  4452  4452 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 19:11:37.244   308   308 I art     : Explicit concurrent mark sweep GC freed 8732(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 643us total 25.472ms
03-15 19:11:37.244  4452  4452 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:37.254  1018  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 19:11:37.264  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:37.264  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-15 19:11:37.264  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:37.264   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 621us total 17.448ms
,03-15 19:11:37.264  4452  4452 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,03-15 19:11:37.274  1931  1931 I ConfigService: onCreate
,03-15 19:11:37.274  4452  4452 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 19:11:37.274  4452  4452 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-15 19:11:37.274  3914  3973 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-15 19:11:37.284  1018  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.google.android.gms, action: android.content.SyncAdapter
03-15 19:11:37.284  1018  1043 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.chromesync.sync.SyncService; callingUser = 0; userId(target) = 0
,03-15 19:11:37.284   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 614us total 17.182ms
,03-15 19:11:37.294  1018  1337 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
,03-15 19:11:37.294  1018  1337 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,03-15 19:11:37.294  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:37.294  3914  3973 I GFX raster: took 0.736822ms for 96*96 texture 0
03-15 19:11:37.294  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8f68830 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fcdb98 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:37.294  3914  3973 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-15 19:11:37.314  1018  1337 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:37.314  1018  1337 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-15 19:11:37.314  1018  1337 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,03-15 19:11:37.314  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:37.314  3914  3973 I GFX raster: took 0.792187ms for 96*96 texture 0
03-15 19:11:37.314  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8efb238 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8f68320 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:37.334  1018  1043 W libprocessgroup: failed to open /acct/uid_10100/pid_3656/cgroup.procs: No such file or directory
,03-15 19:11:37.334  3914  3973 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-15 19:11:37.354  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ForwardMessageActivity
03-15 19:11:37.354  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.354  3914  3973 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 19:11:37.354  3914  3973 I AMMetaDataParserService: Resource data:2131099648
,03-15 19:11:37.364  3914  3973 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-15 19:11:37.364  3914  3973 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 19:11:37.364  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:37.364  3914  3973 I GFX raster: took 0.860522ms for 96*96 texture 0
03-15 19:11:37.364  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb91762e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fcdb98 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:37.364  1323  1747 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-15 19:11:37.384  3914  3973 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-15 19:11:37.424  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:37.424  3914  3973 I GFX raster: took 0.634375ms for 96*96 texture 0
03-15 19:11:37.424  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fa6178 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8fc4948 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:37.434  3914  3973 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-15 19:11:37.444  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:37.444  3914  3973 I GFX raster: took 0.647449ms for 96*96 texture 0
,03-15 19:11:37.444  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fab858 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8fc6300 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:37.454  3914  3973 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-15 19:11:37.464  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:37.464  3914  3973 I GFX raster: took 0.654948ms for 96*96 texture 0
,03-15 19:11:37.464  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fcdd08 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb9177238 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:37.464  3178  3207 I DBG_DM  : [IlIlllIlllllIlIllllI(412/llIIllllIIlllIIIIlll)] waits 9 sec
,03-15 19:11:37.464  3178  3207 I DBG_DM  : [llllIlIIIllllIIlIlll(88/llIIIIlllllIIllIIllI)] WiFi Network is connected
,03-15 19:11:37.464  3178  3207 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,03-15 19:11:37.464  3178  3207 I DBG_DM  : [IIlIIIlllllIIlIIIlII(91/llllIIIllIlIIIIllllI)] 
,03-15 19:11:37.484  3914  3973 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-15 19:11:37.484  3178  3207 I DBG_DM  : [com.wssyncmldm.db.file.XDB(3660/lllIIIIllIlIlllllllI)] FUMO_Status : 220
,03-15 19:11:37.484  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:37.484  3914  3973 I GFX raster: took 0.629531ms for 96*96 texture 0
03-15 19:11:37.484  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8f68830 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8c3eae0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:37.504  3178  3207 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,03-15 19:11:37.514  3914  3973 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-15 19:11:37.514  3178  3207 I DBG_DM  : [com.wssyncmldm.db.file.XDB(6236/IlIIlIIlIllllIlllIII)] Initiated Type: 2
,03-15 19:11:37.514  3178  3207 I DBG_DM  : [IlIlllIlllllIlIllllI(102/lllIlIlIIIllIIlIllIl)] nStatus [220]
,03-15 19:11:37.534  1018  1744 I art     : Explicit concurrent mark sweep GC freed 35576(1916KB) AllocSpace objects, 9(144KB) LOS objects, 33% free, 30MB/45MB, paused 2.637ms total 154.813ms
,03-15 19:11:37.534  1018  1337 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
03-15 19:11:37.534  1018  1337 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,03-15 19:11:37.534  1018  1337 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:37.534  1018  1337 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:37.534  1018  1337 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-15 19:11:37.554  3178  3207 I DBG_DM  : [IlIlllIlllllIlIllllI(251/lllIlIlIIIllIIlIllIl)] XDL_STATE_READY_TO_UPDATE
,03-15 19:11:37.554  3178  3207 I DBG_DM  : [IlIIlIIlIllllIlllIII(274/llIIIIlllllIIllIIllI)] XEVENT_DM_INIT : Initialized
03-15 19:11:37.554  3178  3208 I DBG_DM  : [llllIIIllIllIlllIIlI(772/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_START
,03-15 19:11:37.554  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:37.554  3914  3973 I GFX raster: took 0.729739ms for 96*96 texture 0
03-15 19:11:37.554  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8efb238 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fbd0d0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:37.564  3914  3973 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-15 19:11:37.574  3178  3207 I DBG_DM  : [IlIIlIIlIllllIlllIII(1901/llllIIIllIlIIIIllllI)] 
,03-15 19:11:37.574  3178  3207 I DBG_DM  : [com.wssyncmldm.DMSecBroadcastReceiver(572/llIIIIlllllIIllIIllI)] m_IsSavedNfcMode : false
,03-15 19:11:37.574  3178  3208 I DBG_DM  : [llllIlllIIIlIlIlIIII(49/llIIIIlllllIIllIIllI)] 
,03-15 19:11:37.574  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ReplyMessageActivity
03-15 19:11:37.574  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.574  3914  3973 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 19:11:37.574  3914  3973 I AMMetaDataParserService: Resource data:2131099648
,03-15 19:11:37.584  3914  3973 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-15 19:11:37.584  3914  3973 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 19:11:37.584  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:37.584  1018  1504 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
03-15 19:11:37.584  3914  3973 I GFX raster: took 0.689948ms for 96*96 texture 0
03-15 19:11:37.584  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb91762e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8c46878 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:37.584  1018  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,03-15 19:11:37.594  1018  1504 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:37.594  1018  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:37.594  1018  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-15 19:11:37.594  3914  3973 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-15 19:11:37.594  3178  3207 I DBG_DM  : [com.wssyncmldm.ui.llllIIIllIlIIIIllllI(503/lllIlIlIIIllIIlIllIl)] Get bUpdateReport = false
,03-15 19:11:37.604  1018  4423 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
,03-15 19:11:37.604  1018  4423 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:37.604  1018  4423 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:37.604  1018  4423 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:37.604  1018  4423 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:37.604  3178  3208 I DBG_DM  : [IIllIIIIlIlIlIlIllII(49/IIIlIIllIlIIllIlllII)] FirmwareObjectSize:308289685
,03-15 19:11:37.614  3178  3208 I DBG_DM  : [IIllIIIIlIlIlIlIllII(1715/llllllIllIlIlllIIlIl)] 
,03-15 19:11:37.614  4476  4476 E Zygote  : MountEmulatedStorage(),
03-15 19:11:37.614  4476  4476 E Zygote  : v2
,03-15 19:11:37.614  4476  4476 I libpersona: KNOX_SDCARD checking this for 10139
03-15 19:11:37.614  4476  4476 I libpersona: KNOX_SDCARD not a persona
,03-15 19:11:37.614  4476  4476 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-15 19:11:37.624  4476  4476 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-15 19:11:37.624  1018  4423 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.BootCamera: pid=4476 uid=10139 gids={50139, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
03-15 19:11:37.624  4476  4476 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 19:11:37.624  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:37.634  3914  3973 I GFX raster: took 0.742396ms for 96*96 texture 0
03-15 19:11:37.634  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fa6178 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb9177388 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:37.644  3914  3973 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-15 19:11:37.644  3178  3208 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5178/IIIIlIllIlllIlIIIIlI)] Data Margin : 500
,03-15 19:11:37.644  4476  4476 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:37.644  4476  4476 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:37.654  3178  3208 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5298/IlIllIIIIllllllIlIIl)] Data App Weight : 0.0
,03-15 19:11:37.654  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:37.654  3914  3973 I GFX raster: took 0.646980ms for 96*96 texture 0
03-15 19:11:37.654  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fab858 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb8c5a8b8 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:37.674  3914  3973 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-15 19:11:37.674  3178  3208 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5258/llllIIlIlIIIIllIlIIl)] Delta Weight : 0.5
03-15 19:11:37.674  4476  4476 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-15 19:11:37.674  4476  4476 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-15 19:11:37.674  4476  4476 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-15 19:11:37.674  4476  4476 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
,03-15 19:11:37.674  4476  4476 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-15 19:11:37.674  3178  3208 I DBG_DM  : [com.wssyncmldm.db.file.llllIIIllIlIIIIllllI(194/llIIIIlllllIIllIIllI)] ### Data Margin only: 678432842
,03-15 19:11:37.684  3178  3178 I DBG_DM  : [com.wssyncmldm.llIIllllIIlllIIIIlll(1125/handleMessage)] event ->220
,03-15 19:11:37.694  3178  3178 I DBG_DM  : [com.wssyncmldm.XDMService(639/llllIIIllIlIIIIllllI)] TopActivity : com.android.launcher2.Launcher
,03-15 19:11:37.694  3178  3178 I DBG_DM  : [com.wssyncmldm.XDMService(712/lllIIIIllIlIlllllllI)] 
,03-15 19:11:37.704  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5018/IIllIIllIIIlllIlIIll)] Get Autoinstall status : false
,03-15 19:11:37.704  3178  3178 I DBG_DM  : [com.wssyncmldm.XDMService(468/lIllIllllIIIlllIlllI)] 
03-15 19:11:37.704  3178  3208 I DBG_DM  : [llllIIIllIllIlllIIlI(726/llIIIIlllllIIllIIllI)] XUI_DL_UPDATE_CONFIRM
,03-15 19:11:37.704  3178  3178 E DBG_DM  : [com.wssyncmldm.XDMService(476/lIllIllllIIIlllIlllI)] didn't register
,03-15 19:11:37.714  3178  3178 E DBG_DM  : [com.wssyncmldm.XDMService(477/lIllIllllIIIlllIlllI)] java.lang.IllegalArgumentException: Receiver not registered: com.wssyncmldm.llIIIIlllllIIllIIllI@2439f8fc
,03-15 19:11:37.714  3178  3208 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,03-15 19:11:37.724  1018  1518 I ActivityManager: Killing 3339:com.sec.android.fotaclient/u0a9 (adj 15): empty #31
,03-15 19:11:37.734  3178  3178 I DBG_DM  : [com.wssyncmldm.XDMService(755/lllllIIlIIIlIlIIIllI)] UI_id:223
,03-15 19:11:37.744  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,03-15 19:11:37.744  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:37.744  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:37.744  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:37.744  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:37.744  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:37.744  3914  3973 I GFX raster: took 0.637136ms for 96*96 texture 0
03-15 19:11:37.744  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fcdd08 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8f68320 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:37.754  3178  3178 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1595 android.content.ContextWrapper.startActivity:337 com.wssyncmldm.XDMService.lllllIIlIIIlIlIIIllI:761 com.wssyncmldm.XDMService.llIIllllIIlllIIIIlll:82 com.wssyncmldm.llIIllllIIlllIIIIlll.handleMessage:1090 
,03-15 19:11:37.754  3178  3178 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startActivity:1607 android.app.ContextImpl.startActivity:1596 android.content.ContextWrapper.startActivity:337 com.wssyncmldm.XDMService.lllllIIlIIIlIlIIIllI:761 com.wssyncmldm.XDMService.llIIllllIIlllIIIIlll:82 
,03-15 19:11:37.754  3178  3178 I Timeline: Timeline: Activity_launch_request id:com.wssyncmldm time:49282
,03-15 19:11:37.754  1018  1030 E PersonaManagerService: inState():  stateMachine is null !!
,03-15 19:11:37.754  1018  1030 I PersonaManagerService: PersonaId don't exist
03-15 19:11:37.754  1018  1030 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,03-15 19:11:37.754  4496  4496 E Zygote  : MountEmulatedStorage(),
03-15 19:11:37.754  4496  4496 E Zygote  : v2
03-15 19:11:37.754  4496  4496 I libpersona: KNOX_SDCARD checking this for 10145
,03-15 19:11:37.754  4496  4496 I libpersona: KNOX_SDCARD not a persona
,03-15 19:11:37.764  1018  1031 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.service.EmailBroadcastReceiver: pid=4496 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,03-15 19:11:37.764  4496  4496 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-15 19:11:37.764  1018  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-15 19:11:37.764  4496  4496 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-15 19:11:37.764  4496  4496 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 19:11:37.764  3914  3973 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522
,03-15 19:11:37.764  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:37.774  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:37.774  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-15 19:11:37.774  1018  1030 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-15 19:11:37.774  1018  1030 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
03-15 19:11:37.774  1018  1030 W ActivityManager: mDVFSHelper.acquire()
,03-15 19:11:37.774  1018  1030 D FocusedStackFrame: Set to : 0
,03-15 19:11:37.774  1509  1509 D Launcher.HomeView: onPause
,03-15 19:11:37.774  1018  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
03-15 19:11:37.774  1018  1030 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-15 19:11:37.784  1018  1030 D InputDispatcher: Focused application set to: xxxx
03-15 19:11:37.784  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:37.784  1018  1030 D InputDispatcher: Focus left window: 1509
,03-15 19:11:37.784  1509  1509 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,03-15 19:11:37.784  3914  3973 I GFX raster: took 0.662812ms for 96*96 texture 0
03-15 19:11:37.784  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8f68830 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fc6300 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:37.784  1018  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
03-15 19:11:37.784  1018  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-15 19:11:37.794  3914  3973 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-15 19:11:37.804  4496  4496 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:37.804  4496  4496 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:37.814  1018  1043 W libprocessgroup: failed to open /acct/uid_10009/pid_3339/cgroup.procs: No such file or directory
,03-15 19:11:37.824  1018  1346 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 19:11:37.824  1018  1346 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:37.824  1018  1346 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:37.824  1018  1346 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:37.834  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:37.834  3914  3973 I GFX raster: took 0.725886ms for 96*96 texture 0
03-15 19:11:37.834  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8efb238 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb9177238 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:37.844  3914  3973 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-15 19:11:37.854  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
,03-15 19:11:37.854  1018  1018 D SensorService: [SO] activate (ident=0xb94af8a8, enabled=0)
,03-15 19:11:37.854  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 1, handle 0, en 0
,03-15 19:11:37.854  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConversationList
03-15 19:11:37.854  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:37.854  3914  3973 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 19:11:37.854  3914  3973 I AMMetaDataParserService: Resource data:2131099648
,03-15 19:11:37.854  3914  3973 I AMMetaDataParserService: getResourceName:com.android.mms:xml/assistant_messaging
03-15 19:11:37.854  3914  3973 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 19:11:37.854  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:37.864  3914  3973 I GFX raster: took 0.804844ms for 96*96 texture 0
03-15 19:11:37.864  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb91762e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8c3eae0 counterpartCT=4 counterpartW=96 counterparth=96
03-15 19:11:37.864  4496  4496 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-15 19:11:37.864  4496  4496 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 19:11:37.864  4496  4496 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-15 19:11:37.864  4496  4496 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 19:11:37.864  4496  4496 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-15 19:11:37.864  3178  3178 I DBG_DM  : [com.wssyncmldm.ui.XUIDialogActivity(2153/onResume)] 
,03-15 19:11:37.864  3178  3178 I DBG_DM  : [com.wssyncmldm.ui.XUIDialogActivity(2195/lllIlIlIIIllIIlIllIl)] id 223
,03-15 19:11:37.864  3914  3973 I AMMetaDataParserService: Icon data: ResourceSearch2131493240com.android.mms.ui.conversationlistfragment.searchmessages2130837523
,03-15 19:11:37.874  1018  1018 D SensorManager: unregisterListener ::   
,03-15 19:11:37.874  1018  1018 I Sensors : AccelerometerSensor(0) setDelay : 66000000(ns)
,03-15 19:11:37.874  1018  1018 D SensorService: [SO] changed settle time [1]
03-15 19:11:37.874  1018  1018 D SensorService: [SO] setDelay [66000000]
03-15 19:11:37.874  1018  1018 D SensorService: [SO] activate (ident=0xb94af8a8, enabled=1)
03-15 19:11:37.874  1018  1018 D SensorService: [SO] AR_init
03-15 19:11:37.874  1018  1018 I Sensors : AccelerometerSensor enable: mEnabled 0, handle 0, en 1
,03-15 19:11:37.874  1018  1018 D SensorManager: registerListener :: 1600221811, Screen Orientation Sensor, 66000, 0,  
,03-15 19:11:37.884  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-15 19:11:37.894  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 37
,03-15 19:11:37.894  1018  1129 I ActivityManager: Killing 3699:com.google.android.onetimeinitializer/u0a14 (adj 15): empty #31
,03-15 19:11:37.894  1018  1340 E Watchdog: !@Sync 1
,03-15 19:11:37.904  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,03-15 19:11:37.914  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-15 19:11:37.914  3178  3178 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,03-15 19:11:37.914  3178  3178 I Timeline: Timeline: Activity_launch_request id:com.wssyncmldm time:49445
,03-15 19:11:37.914  1018  1705 E PersonaManagerService: inState():  stateMachine is null !!
,03-15 19:11:37.914  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:37.914  3914  3973 I GFX raster: took 0.644740ms for 96*96 texture 0
03-15 19:11:37.914  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fa6178 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b3, Counterpart=0xb8fbf320 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:37.914  1018  1705 I PersonaManagerService: PersonaId don't exist
03-15 19:11:37.914  1018  1705 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
,03-15 19:11:37.924  1018  1705 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:37.924  1018  1705 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:37.924  1018  1705 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.wssyncmldm, destAppInfo.processName = com.wssyncmldm
,03-15 19:11:37.924  1018  1705 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
,03-15 19:11:37.924  1018  1705 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@7
,03-15 19:11:37.924  1018  1705 W ActivityManager: mDVFSHelper.acquire()
,03-15 19:11:37.924  3914  3973 I AMMetaDataParserService: Icon data: ResourceCompose2131492866com.android.mms.ui.conversationlistfragment.composemessage2130837519
,03-15 19:11:37.934  1018  1141 D SettingsProvider: name = audio_safe_volume_state
,03-15 19:11:37.934  1018  1705 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-15 19:11:37.934  1018  1705 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-15 19:11:37.934  1018  1705 D InputDispatcher: Focused application set to: xxxx
,03-15 19:11:37.944  1018  1041 D SensorService: [SO] Reset Rotation Old [100], Init [1]
,03-15 19:11:37.944  1018  1043 W libprocessgroup: failed to open /acct/uid_10014/pid_3699/cgroup.procs: No such file or directory
,03-15 19:11:37.944  3178  3178 I DBG_DM  : [com.wssyncmldm.ui.IIllIIIlIllIIIllIIlI(252/llllIIIllIlIIIIllllI)] 
,03-15 19:11:37.954  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:37.954  3914  3973 I GFX raster: took 0.629375ms for 96*96 texture 0
03-15 19:11:37.954  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fab858 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b4, Counterpart=0xb9329a80 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:37.954  1018  1337 D ActivityManager: post active user change for 0 fullscreen false record.isFloatingActivity() false
03-15 19:11:37.954  1018  1337 D KnoxTimeoutHandler: postActiveUserChange for user 0
,03-15 19:11:37.954  1018  1337 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-15 19:11:37.954  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,03-15 19:11:37.954  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
03-15 19:11:37.954  1018  1018 I KnoxTimeoutHandler: Target Activity is not fullscreen. We will not show this activity0
,03-15 19:11:37.954  3178  3178 I DBG_DM  : [com.wssyncmldm.ui.XUIDialogActivity(2145/onPause)] 
,03-15 19:11:37.964  1018  1030 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,03-15 19:11:37.964  1018  1030 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,03-15 19:11:37.964  1018  1030 V WindowOrientationListener: ScreenOrientationEventListenerImpl.getProposedRotationLocked, Rotation: -1
,03-15 19:11:37.964  3914  3973 I AMMetaDataParserService: Icon data: ResourceAdd from contacts2131493291com.android.mms.ui.composemessagefragment.attachcontacts2130837521
,03-15 19:11:37.984  1018  1504 D RCPManagerService: exchangeData() failure , invalid userId
,03-15 19:11:37.984  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 37
,03-15 19:11:37.994  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-15 19:11:38.014  1018  1744 D RCPManagerService: exchangeData() failure , invalid userId
,03-15 19:11:38.014  1018  1041 D SensorService: [SO] currT = 49540107792, prevT = 49200084875, diff = 340022917, [0.134 0.402 10.132]
03-15 19:11:38.014  1018  1041 D SensorService: [SO] 0.134 0.402 10.132
03-15 19:11:38.014  1018  1041 D SensorService: [SO] [100 -> 255]
,03-15 19:11:38.014  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:38.014  3914  3973 I GFX raster: took 0.642448ms for 96*96 texture 0
03-15 19:11:38.014  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8fcdd08 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b1, Counterpart=0xb8fcdb98 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:38.024  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-15 19:11:38.024  3178  3178 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(75/onCreate)] Postpone Count : 37
,03-15 19:11:38.024   287   287 E SMD     : DCD OFF
,03-15 19:11:38.024  3914  3973 I AMMetaDataParserService: Icon data: ResourceCall2131494016com.android.mms.ui.composemessagefragment.calltocontact2130837522,
,03-15 19:11:38.054  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:38.054  3914  3973 I GFX raster: took 0.629062ms for 96*96 texture 0
03-15 19:11:38.054  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8f68830 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fcaec8 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:38.054  3914  3973 I AMMetaDataParserService: Icon data: ResourceDelete2131492990com.android.mms.ui.composemessagefragment.delete2130837520
,03-15 19:11:38.054  3178  3178 D PhoneWindow: *FMB* installDecor mIsFloating : false
,03-15 19:11:38.054  3178  3178 D PhoneWindow: *FMB* installDecor flags : -2139029248
,03-15 19:11:38.074  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
,03-15 19:11:38.074  3914  3973 I GFX raster: took 0.716406ms for 96*96 texture 0
03-15 19:11:38.074  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb8efb238 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb8fcd900 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:38.084  3914  3973 I AMMetaDataParserService: Icon data: ResourceSend2131492904com.android.mms.ui.composemessagefragment.send2130837524
,03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.WarnOfStorageLimitsActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SlideshowActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsSinglePageActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ClassZeroActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RetryActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MessagingPreferenceActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.EntrancePrefActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DisplaySettings
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CMASSettings
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.TextMessagesSettings
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.MultimediamessagesSettings
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.rcs.settings.RcsMessagesSettings
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DeleteoldMessagesSettings
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.PushMessagesSettings
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.NotificationSettings
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.NotificationSettingsDS
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SignatureSettings
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SpamSettings
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SafemodeSettings
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.DelaySendingSettings
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.smishing.PackageAuthorityDialog
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.MessageSmscActivityDS
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.SignatureEditActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberSettings
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CallbackNumberEditActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.BackgroundStyle
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.BubbleStyle
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android,.mms.ui.PushMessageDialog
03-15 19:11:38.094  3914  3973 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.SaveThreadActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.SavedMsgsList
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.RestorePreviewActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.saverestore.ConversationListRestore
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ManageSimMessages
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsRetryActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ConfirmRateLimitActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SearchActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SmsViewerActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsNotificationViewerActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DrmContentsActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASPreferenceActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASDialog
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASDialog_single_top
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.PDPResetDialog
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.CMASUserPromptDialog
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.LockedMessageManager
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SpamMessageManager
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ReservationMessageManager
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DraftMessageManager
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SafeMessageManager
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.RecipientListActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.GroupMessagingRecipientListActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SelectMapActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.LocationM,apActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.FavoritePlacesList
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.location.RecentPlacesList
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.BoxListViewActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:android.app.default_searchable
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.provisioning.MmsProvisionActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.ManageSDMessages
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberList
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordList
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamNumberWriteForm
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.spam.SetupSpamKeywordWriteForm
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SettingsReservationActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.SettingsTransmitMessageActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MessageDatabaseBackupActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeThreadContactSelector
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeEditActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.NoticeDeleteActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.export.MmsPartExportDialogActivityAlien
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.DirectCallTutorialActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.FakeCallActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.MmsPartExportActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.template.TextTemplateListActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.template.TextTemplateEditActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.help.AirViewMainActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.help.AirButtonMainActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.widget.WidgetPreferenceActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.cover.MissedMsgActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.oem.AutoSendingTestActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysender.AddGlanceListActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysender.AddThreadListActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.CheckDefaultSmsAppsActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.accessory.ReadReportActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.ui.FileHistoryListActivity
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.settings.FreeMessageSettings
03-15 19:11:38.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.mms.prioritysenderpanel.CocktailPrioritySenderSettingActivity
03-15 19:11:38.114  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryOpaqueActivity
03-15 19:11:38.114  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:38.114  3914  3973 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 19:11:38.124  3914  3973 I AMMetaDataParserService: Resource data:2131165197
03-15 19:11:38.124  3914  3973 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-15 19:11:38.124  3914  3973 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 19:11:38.124  3914  3973 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-15 19:11:38.124  3914  3973 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 19:11:38.124  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
03-15 19:11:38.124  3914  3973 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-15 19:11:38.134  3178  3178 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
03-15 19:11:38.134  3914  3973 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
03-15 19:11:38.134  3914  3973 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
03-15 19:11:38.134  3914  3973 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-15 19:11:38.134  3914  3973 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-15 19:11:38.134  3914  3973 I AMMetaDataParserService: getResourceTypeNamexml
03-15 19:11:38.134  3178  3178 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,03-15 19:11:38.144  3914  3973 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
03-15 19:11:38.144  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
03-15 19:11:38.164  3868  4000 I System.out: INFO:Resource not found:/Common.properties Using default values
03-15 19:11:38.164  3914  3973 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
03-15 19:11:38.174  1018  1705 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
03-15 19:11:38.174  1018  1705 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
03-15 19:11:38.174  1018  1018 D WindowManager: showStatusBarByNotification() mOpenByNotification=false
03-15 19:11:38.184  3914  3973 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-15 19:11:38.184  1018  1018 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,03-15 19:11:38.184  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 37
,03-15 19:11:38.194  1181  1781 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-15 19:11:38.194  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,03-15 19:11:38.204  1018  1129 D RCPManagerService: exchangeData() failure , invalid userId
,03-15 19:11:38.204  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-15 19:11:38.204  3178  3178 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,03-15 19:11:38.214  3914  3973 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-15 19:11:38.224  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 37
,03-15 19:11:38.234  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,03-15 19:11:38.244  1181  1181 D KnoxNotification: ----- inflateViews : modified publicViewLocal -----
,03-15 19:11:38.244  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-15 19:11:38.244  3178  3178 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,03-15 19:11:38.254  1181  1181 D KnoxNotification: ----- inflateViews : modified KnoxViewLocal -----
,03-15 19:11:38.254  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.GalleryActivity
03-15 19:11:38.254  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 19:11:38.254  3914  3973 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-15 19:11:38.254  3914  3973 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 19:11:38.254  3914  3973 I AMMetaDataParserService: Resource data:2131165197
,03-15 19:11:38.254  1181  1181 D PersonaManager: PersonaID is invalid or persona doesn't exists. : 0
,03-15 19:11:38.254  3914  3973 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-15 19:11:38.254  1181  1181 D PersonaManager: isKioskContainerExistOnDevice
03-15 19:11:38.254  3914  3973 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 19:11:38.254  1181  1181 D PersonaManager: isKioskContainerExistOnDevice
,03-15 19:11:38.254  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 37
,03-15 19:11:38.264  1181  1181 D PanelView: There is/are notification(s) 
03-15 19:11:38.264  1181  1181 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-15 19:11:38.264  1181  1181 D PersonaManager: isKioskContainerExistOnDevice
,03-15 19:11:38.264  1181  1181 D PanelView: There is/are notification(s) 
03-15 19:11:38.264  1181  1181 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-15 19:11:38.264  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,03-15 19:11:38.274  3914  3973 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-15 19:11:38.274  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-15 19:11:38.274  3178  3178 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,03-15 19:11:38.284  1018  1030 D RCPManagerService: exchangeData() failure , invalid userId
,03-15 19:11:38.284  3178  3178 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(428/onResume)] 
,03-15 19:11:38.284  1181  1181 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f02053a/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-15 19:11:38.284  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-15 19:11:38.284  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 19:11:38.284  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 37
,03-15 19:11:38.294  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 19:11:38.294  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 19:11:38.294  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 19:11:38.294  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-15 19:11:38.304  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-15 19:11:38.304  3178  3178 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(438/onResume)] Postpone Count : 37
,03-15 19:11:38.314  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5479/llIlIIIIlllIlllllIll)] Download Postpone status : 0
,03-15 19:11:38.314  3178  3178 I DBG_DM  : [com.wssyncmldm.XDMService(649/lllIlIlIIIllIIlIllIl)] Idle Screen : true
,03-15 19:11:38.324  4394  4394 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,03-15 19:11:38.324  1018  1346 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,03-15 19:11:38.324  1018  1346 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:38.324  1018  1346 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:38.324  1018  1346 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,03-15 19:11:38.324  1018  1266 I ActivityManager: Killing 2835:com.google.android.apps.plus/u0a120 (adj 15): empty #31
,03-15 19:11:38.334  3178  3178 I DBG_DM  : [com.wssyncmldm.ui.lIlIIlIlIlIllllllIII(330/llIIIIlllllIIllIIllI)] NotificationID : 4 / Notification IndicatorState : 7
,03-15 19:11:38.334  1181  1181 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,03-15 19:11:38.334  3914  3973 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-15 19:11:38.344  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5138/lIIIIIIIlllllllIIlll)] Get Priority : 0
,03-15 19:11:38.354  1018  1031 D ApplicationPolicy: isStatusBarNotificationAllowedAsUser: packageName = com.wssyncmldm,userId = 0
,03-15 19:11:38.354  1018  1031 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.wssyncmldm
,03-15 19:11:38.354  1018  1018 W NotificationService: Pray mode not found android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,03-15 19:11:38.364  1181  1181 D StatusBar: ----- contentsUnchanged : true, bigContentsUnchanged - true, headsUpContentsUnchanged - true , publicUnchanged true
,03-15 19:11:38.364  1181  1181 D PersonaManager: isKioskContainerExistOnDevice
,03-15 19:11:38.364  1181  1181 D PersonaManager: isKioskContainerExistOnDevice
,03-15 19:11:38.364  1181  1181 D PanelView: There is/are notification(s) 
03-15 19:11:38.364  1181  1181 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-15 19:11:38.364  1181  1181 D PersonaManager: isKioskContainerExistOnDevice
,03-15 19:11:38.364  1181  1181 D PanelView: There is/are notification(s) 
03-15 19:11:38.364  1181  1181 D PanelView: kidsfalse mQsExpansionEnabled:true
,03-15 19:11:38.364  3914  3973 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-15 19:11:38.374  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5416/IlIlllIlllllIlIllllI)] Get Postpone Count : 37
,03-15 19:11:38.374  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5058/IIlllIlIIlIllIlllIll)] Get Force status : 0
,03-15 19:11:38.384  3178  3178 I DBG_DM  : [com.wssyncmldm.db.file.XDB(5438/llIIlIIlIllIllIlllII)] Get Postpone Max Count : 0
,03-15 19:11:38.384  3178  3178 I DBG_DM  : [com.wssyncmldm.ui.XUIInstallConfirmActivity(532/llIIIIlllllIIllIIllI)] Check Force Install : false
,03-15 19:11:38.384  3178  3178 I DBG_DM  : [llIIlIIlIllIllIlllII(329/IllIlIIIIlIIlIIIllIl)] 
,03-15 19:11:38.384  3178  3178 I DBG_DM  : [llIIlIIlIllIllIlllII(335/IllIlIIIIlIIlIIIllIl)] InternalEncrypted : [false]
,03-15 19:11:38.394  1018  1744 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,03-15 19:11:38.394  1018  1744 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:38.394  1018  1744 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:38.394  1018  1744 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:38.394  1018  1744 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:38.414  4521  4521 E Zygote  : MountEmulatedStorage()
03-15 19:11:38.414  4521  4521 E Zygote  : v2
,03-15 19:11:38.414  4521  4521 I libpersona: KNOX_SDCARD checking this for 10072
03-15 19:11:38.414  4521  4521 I libpersona: KNOX_SDCARD not a persona
03-15 19:11:38.414  4521  4521 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-15 19:11:38.414  4521  4521 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-15 19:11:38.414  4521  4521 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-15 19:11:38.414  1018  1744 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=4521 uid=10072 gids={50072, 9997} abi=armeabi-v7a
,03-15 19:11:38.414  3914  3973 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-15 19:11:38.424  3178  4527 D OpenGLRenderer: Render dirty regions requested: true
,03-15 19:11:38.424  1018  1346 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
03-15 19:11:38.434  1018  1346 D KnoxTimeoutHandler: postActiveUserChange for user 0
03-15 19:11:38.434  1018  1346 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
03-15 19:11:38.434  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
03-15 19:11:38.434  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,03-15 19:11:38.434  3178  3178 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
03-15 19:11:38.434  3178  3178 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,03-15 19:11:38.434  1181  1181 D PanelView: mClearAll.setVisibility - mIsFullyOpened : false isShade : true mHasNotification : true mIsUpwardFling : false mQsFullyExpanded : true isShadeLocked : false mClearAllVisible : false
,03-15 19:11:38.444  4521  4521 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:38.444  1018  1504 D RCPManagerService: exchangeData() failure , invalid userId
03-15 19:11:38.444  4521  4521 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:38.464  1018  1337 D RCPManagerService: exchangeData() failure , invalid userId
,03-15 19:11:38.464  1018  1043 W libprocessgroup: failed to open /acct/uid_10120/pid_2835/cgroup.procs: No such file or directory
,03-15 19:11:38.464  1018  1705 D ActivityManager: startService callerProcessName:com.android.email, calleePkgName: com.android.email
,03-15 19:11:38.464  1018  1705 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailBroadcastProcessorService; callingUser = 0; userId(target) = 0
,03-15 19:11:38.474  1018  1705 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:38.474  1018  1705 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:38.474  1018  1705 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.email, destAppInfo.processName = com.android.email
,03-15 19:11:38.474  4521  4521 D BadgeProvider: onCreate
,03-15 19:11:38.474  4521  4521 D BadgeProvider: DatabaseHelper
,03-15 19:11:38.484   257   257 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, YUIInstallC
,03-15 19:11:38.484  1018  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-15 19:11:38.494  1018  1518 D InputDispatcher: Focus entered window: 3178
03-15 19:11:38.494  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.cooliris.media.Gallery
03-15 19:11:38.494  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.Gallery
03-15 19:11:38.494  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:38.494  3914  3973 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 19:11:38.494  3914  3973 I AMMetaDataParserService: Resource data:2131165197
,03-15 19:11:38.494  1018  1051 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,03-15 19:11:38.504  1018  1051 D PointerIcon: setMouseCustomIcon IconType is same.101
,03-15 19:11:38.504  4521  4530 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,03-15 19:11:38.504  3914  3973 I AMMetaDataParserService: getResourceName:com.sec.android.gallery3d:xml/assistant
03-15 19:11:38.504  3914  3973 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 19:11:38.504  1018  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,03-15 19:11:38.514  3178  3178 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-15 19:11:38.514  3178  4527 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-15 19:11:38.514  3178  4527 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-15 19:11:38.514  3178  4527 I Adreno-EGL: Build Date: 04/06/15 Mon
03-15 19:11:38.514  3178  4527 I Adreno-EGL: Local Branch: 
03-15 19:11:38.514  3178  4527 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-15 19:11:38.514  3178  4527 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-15 19:11:38.514  3178  4527 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-15 19:11:38.514  3914  3973 I AMMetaDataParserService: Icon data: ResourceDrawer2131625024android.intent.action.drawer2130837625
,03-15 19:11:38.514  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.android.exchange, hostingType: broadcast
,03-15 19:11:38.524  3178  4527 I OpenGLRenderer: Initialized EGL, version 1.4
,03-15 19:11:38.524  1018  2822 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-15 19:11:38.524  4496  4514 W art     : Verification of void com.android.email.activity.MessageListItemOuterContainer.checkInnerContainer() took 221.609ms
,03-15 19:11:38.534  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:38.534  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:38.534  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:38.534  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:38.544  4543  4543 E Zygote  : MountEmulatedStorage()
03-15 19:11:38.544  4543  4543 E Zygote  : v2
03-15 19:11:38.544  4543  4543 I libpersona: KNOX_SDCARD checking this for 10146
03-15 19:11:38.544  4543  4543 I libpersona: KNOX_SDCARD not a persona
,03-15 19:11:38.544  4543  4543 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-15 19:11:38.544  1018  1031 I ActivityManager: Start proc com.android.exchange for broadcast com.android.exchange/.service.ExchangeBroadcastReceiver: pid=4543 uid=10146 gids={50146, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,03-15 19:11:38.544  3178  4527 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
03-15 19:11:38.544  3178  4527 D OpenGLRenderer: Enabling debug mode 0
,03-15 19:11:38.554  1018  1031 I ActivityManager: Killing 3748:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31,
03-15 19:11:38.554  3914  3973 I AMMetaDataParserService: Icon data: ResourceSlideshow2131624011android.intent.action.slideshow2130837623
,03-15 19:11:38.554  1018  1031 I ActivityManager: Killing 3720:com.samsung.android.app.accesscontrol/1000 (adj 15): empty #32,
,03-15 19:11:38.554  4543  4543 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-15 19:11:38.554  4543  4543 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 19:11:38.574  4543  4543 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:38.584  4543  4543 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:38.584  1509  1509 D Launcher.Model: reloadBadges entered.
,03-15 19:11:38.584  4521  4531 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
,03-15 19:11:38.584  4521  4531 D BadgeProvider: sendNotify, [notify] : null
,03-15 19:11:38.594  4521  4531 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
03-15 19:11:38.594  4521  4531 D BadgeProvider: update, [BadgeCount] : badgecount=0
03-15 19:11:38.594  4521  4531 D BadgeProvider: update, [UpdateCount] : 1
,03-15 19:11:38.594  3914  3973 I AMMetaDataParserService: Icon data: ResourceCamera2131624014android.intent.action.camera2130837622
,03-15 19:11:38.624  3914  3973 I AMMetaDataParserService: Icon data: ResourceDelete2131624002android.intent.action.delete2130837624
,03-15 19:11:38.634  1018  1129 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,03-15 19:11:38.644  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3720/cgroup.procs: No such file or directory
03-15 19:11:38.644  1018  1043 W libprocessgroup: failed to open /acct/uid_10069/pid_3748/cgroup.procs: No such file or directory
,03-15 19:11:38.644  1018  1051 D PersonaManager: isKioskContainerExistOnDevice
,03-15 19:11:38.644  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.UsbDeviceActivity
,03-15 19:11:38.644  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:38.644  3914  3973 I AMMetaDataParserService: getResourcePackageName:android.hardware.usb.action.USB_DEVICE_ATTACHED
03-15 19:11:38.644  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.Wallpaper
03-15 19:11:38.644  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:38.644  3914  3973 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-15 19:11:38.644  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.LockScreen
03-15 19:11:38.644  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:38.644  3914  3973 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-15 19:11:38.644  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.BothScreen
03-15 19:11:38.644  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:38.644  3914  3973 I AMMetaDataParserService: getResourcePackageName:android.wallpaper.preview
03-15 19:11:38.644  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.CropImage
03-15 19:11:38.644  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagSetting
03-15 19:11:38.644  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.app.ContextualTagWeatherSetting
03-15 19:11:38.644  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.gallerysearch.DeleteHistoryForGallerySearchActivity
03-15 19:11:38.644  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.usertag.AddUserTagListActivity
03-15 19:11:38.644  3914  3973 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
03-15 19:11:38.644  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.view.detailview.moreinfo.MoreInfoLocationEditActivity
03-15 19:11:38.644  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:38.644  3914  3973 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-15 19:11:38.644  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.GallerySettings
03-15 19:11:38.644  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetTypeChooser
03-15 19:11:38.644  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetClickHandler
03-15 19:11:38.644  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetConfigure
03-15 19:11:38.644  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetConfigure
03-15 19:11:38.644  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.EasyWidgetConfigure
03-15 19:11:38.644  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.WidgetPreferenceActivity
03-15 19:11:38.644  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.gadget.MagazineWidgetPreferenceActivity
03-15 19:11:38.644  3914  3973 I AMMetaDataParserService: Resource data:Loo,p for running activitycom.sec.android.gallery3d.settings.AccountSettingActivity
03-15 19:11:38.644  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.gallery3d.settings.FilterbySettingActivity
03-15 19:11:38.644  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.sec.gallery2d.viewstate.MapView2dPage
03-15 19:11:38.644  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.app.imagenote.ImageNote
03-15 19:11:38.644  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.app.photonote.PhotoNote
03-15 19:11:38.644  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.controller.StartMmsSaveCmd$CallMmsSave
03-15 19:11:38.644  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.samsung.gallery.controller.GalleryChooserActivity
03-15 19:11:38.644  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.cloud.integrator.CloudIntegratorActivity
,03-15 19:11:38.654  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.Camera
03-15 19:11:38.654  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:38.654  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.cocktail.subwindow.enable
03-15 19:11:38.654  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.sec.android.multiwindow.activity.STYLE
03-15 19:11:38.654  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.keyguard.layout
03-15 19:11:38.654  3914  3973 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 19:11:38.654  3914  3973 I AMMetaDataParserService: Resource data:2131099648
,03-15 19:11:38.654  4543  4543 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,03-15 19:11:38.664  1018  4560 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,03-15 19:11:38.664  1018  1051 I ActivityManager: Displayed Component not be shown by security: +702ms (total +871ms)
,03-15 19:11:38.664  1181  1181 D PanelView: There is/are notification(s) 
,03-15 19:11:38.664  3914  3973 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
03-15 19:11:38.664  3914  3973 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-15 19:11:38.664  3914  3973 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
03-15 19:11:38.664  3914  3973 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
03-15 19:11:38.664  3914  3973 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,03-15 19:11:38.664  3914  3973 I AMMetaDataParserService: getResourceName:com.sec.android.app.camera:xml/assistant
03-15 19:11:38.664  3914  3973 I AMMetaDataParserService: getResourceTypeNamexml
,03-15 19:11:38.684  1801  1801 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,03-15 19:11:38.684  3914  3973 I AMMetaDataParserService: Icon data: ResourceSwitch camera2131559034android.intent.action.switchcamera2130837512
,03-15 19:11:38.694  3178  3178 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@265e1c4 time:50222
,03-15 19:11:38.714  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
03-15 19:11:38.714  1018  1030 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,03-15 19:11:38.714  1018  1504 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,03-15 19:11:38.714  1018  4423 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,03-15 19:11:38.724  1018  1266 W ActivityManager: getTasks: caller 10145 does not hold GET_TASKS; limiting output
,03-15 19:11:38.724  4496  4540 I Process : Sending signal. PID: 4496 SIG: 9
,03-15 19:11:38.794  1018  4423 I ActivityManager: Process com.android.email (pid 4496)(adj 9) has died(43,1134)
,03-15 19:11:38.814  4198  4245 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-15 19:11:38.814  3914  3973 I AMMetaDataParserService: Icon data: ResourceGallery2131558741android.intent.action.switchgallery2130837511
03-15 19:11:38.814  4198  4245 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-15 19:11:38.814  4198  4245 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,03-15 19:11:38.824  4198  4245 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-15 19:11:38.824  4198  4245 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-15 19:11:38.824  4198  4245 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-15 19:11:38.824  4198  4245 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-15 19:11:38.844  4118  4118 I dex2oat : dex2oat took 5.926s (threads: 4)
,03-15 19:11:38.864  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.Camcorder
03-15 19:11:38.864  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.DummyActivity
03-15 19:11:38.864  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.camera.CropImage
03-15 19:11:38.864  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.sec.android.app.shootingmodemanager.ManageShootingModeActivity
03-15 19:11:38.864  3914  3973 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,03-15 19:11:38.864  2089  4112 D DexOptUtils: Odex created at:/data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.dex
03-15 19:11:38.874  2089  4112 D DexOptUtils: Set odex to world readable.
,03-15 19:11:38.874  2089  4112 D DexOptUtils: Renamed odex to /data/data/com.google.android.gms/app_chimera/m/00000000/arm/DynamiteModules-prod.odex
,03-15 19:11:38.884  1018  1346 D RCPManagerService: exchangeData() failure , invalid userId
,03-15 19:11:38.894  1018  1705 D ActivityManager: startService callerProcessName:com.android.exchange, calleePkgName: com.android.exchange
,03-15 19:11:38.894  1018  1705 D ActivityManager: retrieveServiceLocked(): component = com.android.exchange/com.android.exchange.service.ExchangeBroadcastProcessorService; callingUser = 0; userId(target) = 0
,03-15 19:11:38.894  1018  1705 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:38.894  1018  1705 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:38.894  1018  1705 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.exchange, destAppInfo.processName = com.android.exchange
,03-15 19:11:38.894  1018  4423 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.SecSetupWizard, hostingType: broadcast
,03-15 19:11:38.904  1018  4423 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:38.904  1018  4423 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:38.904  1018  4423 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:38.904  1018  4423 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:38.914  4563  4563 E Zygote  : MountEmulatedStorage()
03-15 19:11:38.914  4563  4563 I libpersona: KNOX_SDCARD checking this for 1000
03-15 19:11:38.914  4563  4563 E Zygote  : v2
03-15 19:11:38.914  4563  4563 I libpersona: KNOX_SDCARD not a persona
,03-15 19:11:38.914  4563  4563 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-15 19:11:38.924  4563  4563 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-15 19:11:38.924  4563  4563 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 19:11:38.924  1018  4423 I ActivityManager: Start proc com.sec.android.app.SecSetupWizard for broadcast com.sec.android.app.SecSetupWizard/.SetupIntentReceiver: pid=4563 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-15 19:11:38.924  1018  1129 I ActivityManager: Killing 3350:com.google.android.partnersetup/u0a15 (adj 15): empty #31
,03-15 19:11:38.944  4563  4563 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:38.944  4563  4563 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:38.964  1018  4423 D ActivityManager: getContentProviderImpl callerProcessName:com.android.exchange, calleePkgName: com.android.email
,03-15 19:11:38.964  1018  4423 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:38.964  1018  4423 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:38.964  1018  4423 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:38.964  1018  4423 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:38.964  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.GridSettings
03-15 19:11:38.964  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:38.964  3914  3973 I AMMetaDataParserService: getResourcePackageName:assistant
03-15 19:11:38.964  3914  3973 I AMMetaDataParserService: Resource data:2131165220
,03-15 19:11:38.974  3914  3973 I AMMetaDataParserService: getResourceName:com.android.settings:xml/assistant,
03-15 19:11:38.974  3914  3973 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
03-15 19:11:38.974  3914  3973 I AMMetaDataParserService: getResourceTypeNamexml
03-15 19:11:38.974  3914  3973 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
03-15 19:11:38.974  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96
03-15 19:11:38.974  3914  3973 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.,
03-15 19:11:38.974  3914  3973 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 19:11:38.974  3914  3973 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 19:11:38.974  3914  3973 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
03-15 19:11:38.974  3914  3973 I GFX raster: took 0.745468ms for 96*96 texture 0
03-15 19:11:38.974  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb96c8a90 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb96c87c0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:38.984  4580  4580 E Zygote  : MountEmulatedStorage(),
03-15 19:11:38.984  4580  4580 E Zygote  : v2
03-15 19:11:38.984  4580  4580 I libpersona: KNOX_SDCARD checking this for 10145
03-15 19:11:38.984  4580  4580 I libpersona: KNOX_SDCARD not a persona,
,03-15 19:11:38.984  4580  4580 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
,03-15 19:11:38.984  3914  3973 I AMMetaDataParserService: Icon data: ResourceSearch2131363521com.android.settings.Search2130837580
,03-15 19:11:38.984  4580  4580 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-15 19:11:38.994  4580  4580 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 19:11:39.004  1018  4423 I ActivityManager: Start proc com.android.email for content provider com.android.email/.provider.EmailProvider: pid=4580 uid=10145 gids={50145, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,03-15 19:11:39.004  1018  1266 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,03-15 19:11:39.004  1018  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:39.004  1018  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:39.004  1018  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:39.004  1018  1266 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:39.014  3914  3973 E         : GFX convertToRaster() in Bitmap.cpp for bitmap size 96x96,
03-15 19:11:39.014  3914  3973 I GFX raster: took 0.588177ms for 96*96 texture 0
03-15 19:11:39.014  3914  3973 W GFX DEBUGLOG GPUCompressionToBitmapDecoder: Bitmap=0xb96c88e0 bitmapCt=12 bitmapW=96 bitmapH=96 BitmapInternalFormat=93b2, Counterpart=0xb96dbad0 counterpartCT=4 counterpartW=96 counterparth=96
,03-15 19:11:39.024  4592  4592 E Zygote  : MountEmulatedStorage()
,03-15 19:11:39.024  4592  4592 E Zygote  : v2
03-15 19:11:39.024  4592  4592 I libpersona: KNOX_SDCARD checking this for 1000
03-15 19:11:39.024  4592  4592 I libpersona: KNOX_SDCARD not a persona
,03-15 19:11:39.024  4592  4592 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-15 19:11:39.024  1018  1266 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.BootReceiver: pid=4592 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-15 19:11:39.024  1018  1266 I ActivityManager: Killing 3784:com.android.managedprovisioning/u0a22 (adj 15): empty #31
,03-15 19:11:39.034  4592  4592 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-15 19:11:39.034  3914  3973 I AMMetaDataParserService: Icon data: ResourceEdit quick settings2131361852com.android.settings.Favorite2130837579
,03-15 19:11:39.034  4592  4592 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 19:11:39.044  4580  4580 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 19:11:39.044  4580  4580 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:39.054  4592  4592 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:39.054  4592  4592 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:39.064  1018  1337 I ActivityManager: Killing 3817:com.samsung.android.MtpApplication/1000 (adj 15): empty #31
,03-15 19:11:39.074  1018  1051 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@7
,03-15 19:11:39.074  1018  1051 W ActivityManager: mDVFSHelper.release()
03-15 19:11:39.074  1018  1051 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2a679e7b u0 com.wssyncmldm/.ui.XUIInstallConfirmActivity t13} time:50609
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SubSettings
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LabelName
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Password
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EthernetSettingsActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WirelessSettingsActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiSettingsActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSettings
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSecPickerActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiCaptiveActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.FreeWifiScanPickerDialog
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiOffloadDialog
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiAdvancedSecSetupActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WificmccSetupActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.,settings.wifi.WifiSecSetupActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiWarningDialog
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSetupActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accessibility.smartscroll.app.sbrowsertry.SmartScreenActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPickerDialog
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiSettingsForSetupWizardXL
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AdvancedWifiSettingsActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SavedAccessPointsSettingsActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiShareProfileActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS,
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiInfo
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiConfigInfo
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiAPITest
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiStatusTest
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApSettings,
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS,
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApWarning
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.mobileap.WifiApTestConfigure
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiPoorConnection
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApListActivity
,03-15 19:11:39.084  4580  4580 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.,
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiHiddenApDeleteActivity
03-15 19:11:39.084  4580  4580 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiDisconnectWeakApSettings,
03-15 19:11:39.084  4580  4580 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ApnSettingsActivity
03-15 19:11:39.094  4580  4580 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.,
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  4580  4580 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED,
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BluetoothSettingsActivity,
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothSettings
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothScanDialog
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothErrorActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.CheckBluetoothStateActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.DevicePickerActivity
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnableActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothEnablingActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MirrorLinkActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TetherSettingsActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.TetherSettings
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.samsung.android.multiuser.install_only_owner
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pSettingsActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pSettings
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:39.104  3914  3973 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 android.content.ContextWrapper.sendBroadcast:391 com.samsung.android.app.assistantmenu.serviceframework.AMMetaDataParserService.onHandleIntent:89 android.app.IntentService$ServiceHandler.handleMessage:65 android.os.Handler.dispatchMessage:102 
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiP2pHelpActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.p2p.WifiP2pDummyPickerActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NearbySettingsActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nearby.NearbySettings
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wfd.WfdHelpActivity
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wfd.WfdPickerDialog
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VpnSettingsActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DateTimeSettingsActivity
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DateTimeSettingsSetupWizard
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.FeatureSettingsSetupWizard
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LocalePickerActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$InputMethodAndLanguageSettingsActivity
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputSettingsActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$HandwritingLanguageActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.handwritingsearch.HandwritingLanguageTablet
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$KeyboardLayoutPickerActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LanguageSettings
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SpellCheckersSettingsActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.inputmethod.InputMethodAndSubtypeEnablerActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UserDictionarySettingsActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.inputmethod.UserDictionaryAddWordActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UserDictionarySettings
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ZenModeSettingsActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ZenModeDNDSettingsActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$HomeSettingsActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.HomeSettings
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LockScreenSettingsActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DisplaySettings
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LockscreenMenuActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BlockSettingsActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LedIndicatorSettingsActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DockSettingsActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DockSettings
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ContextualPageSettings
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ContextualPageHelpActivity
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DeviceInfoSettingsActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceNameDialog
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsLicenseActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PrivacyAlertDialogActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PrivacyAlertProceedDialogActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsSafetyLegalActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ManageApplicationsActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.ManageApplications
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ManageApplications
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RunningServices
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LaunchApplication
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.StorageUse
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetailsTop
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.ManageAccountsActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.InstalledAppDetails
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.applications.UninstallMultipleScreen
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RunningServicesActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$StorageUseActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.124  1018  1044 D CustomFrequencyManagerService: acquireDVFSLockLocked : type : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  pkgName : ACTIVITY_RESUME_BOOSTER@11
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationStationActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AppOpsDetailsActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LocationSettingsActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SecuritySettingsActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MonitoringCertInfoActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TrustedCredentialsSettingsActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SecuritySettings
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrivacySettingsActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check,
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SetFullBackupPassword
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CredentialStorage
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DeviceAdminSettingsActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceAdminSettings
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceAdminAdd
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UsageAccessSettingsActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SetProfileOwner
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.IccLockSettings
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SimPinLockSettings
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SimPersoLockSettings
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccessibilitySettingsActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccessibilityDaltonizerSettingsActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED,
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.samsung.settings.accessibility.AccessibilityWidgetDialogActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CaptioningSettingsActivity
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:39.134  1018  1346 I ActivityManager: Killing 3467:com.sec.pcw.device/1000 (adj 15): empty #31
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MagnifierSettingsActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AssistantMenuPreferenceFragmentActivity
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AccessibilitySettingsSetupWizard
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TextToSpeechSettingsActivity
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DrivingModeSettingsActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AssistiveHepticSettingsActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmDeviceCredentialActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.notification.RedactionInterstitial
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.notification.RedactionSettingsStandalone
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockEnterpriseIdentity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockEnterpriseIdentity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPattern$InternalActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ConfirmLockPassword$InternalActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BluetoothPairingWithCac
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockGeneric$InternalActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxChooseLockTwoFactor
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxChooseLockBackupPin
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockPattern
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockBLock
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockPassword
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockMotion
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockAdditionalPin
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockSignature
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.EncryptionInterstitial
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.Status
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$StorageSettingsActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.MiscFilesHandler
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.deviceinfo.DeviceInfoTabActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ApnEditor
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MediaFormat
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MediaFormatSd
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$QuickLaunchSettingsActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.quicklaunch.BookmarkPicker
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DevelopmentSettingsActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrintSettingsActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PrintJobSettingsActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DevelopmentSettings
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AppPicker
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UsbSettingsActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UsbSettings
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPairingDialog
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.WifiScanModeActivity
,03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.RequestPermissionHelperActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.bluetooth.BluetoothPermissionActivity
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ActivityPicker
03-15 19:11:39.084  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NfcSettingsActivity
03-15 19:11:39.144  1509  1509 V ActivityThread: updateVisibility : ActivityRecord{c4d2464 token=android.os.BinderProxy@88e805f {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nfc.NfcAdvancedRoutingSetting
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AndroidBeamSettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SBeamSettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WifiDisplaySettingsActivity
03-15 19:11:39.144  1018  1043 W libprocessgroup: failed to open /acct/uid_10015/pid_3350/cgroup.procs: No such file or directory
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BatteryInfo
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Display
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RadioInfo
,03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ProxySelector
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.BandMode
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.TestingSettings
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.fulllocalepickertest.FullLocalePickerTest
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AppWidgetPickActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.AllowBindAppWidgetActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.UsageStatsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerUsageSummaryActivity
,03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.fuelgauge.PowerUsageSummary
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BatterySaverSettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountMenuActivity
,03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountSettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AccountSyncSettingsActivity
,03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.AddAccountSettings
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
,03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.accounts.ChooseAccountActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeper
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeper$FadeToBlack
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptKeeperConfirm$Blank
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.CryptDecryptConfirm$Blank
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptKeeperSettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptDecryptSettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.154  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3817/cgroup.procs: No such file or directory
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CryptSDCardSettingsActivity
,03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SimChangeAlertSettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DataUsageSummaryActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DataUsageMeteredSettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
,03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DreamSettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UserSettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
,03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PaymentSettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.nfc.PaymentDefaultDialog
,03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SmsDefaultDialog
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ActiveNetworkScorerDialog
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationAccessSettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ConditionProviderSettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationSettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SoundSettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PRIMARY_PROFILE_CONTROLLED
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.sec.android.PRIMARY_KNOX_CONTROLLED
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SoundSettings
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$OtherSoundSettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationAppListActivity
,03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AppNotificationSettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS,
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SimSettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.FactoryResetDialog
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.LockScreenWallpaper
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WallpaperSettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.GSensorSettings
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingMode2014Activity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSavingModeSettings2014Activity
,03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$UltraPowerSavingModeActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreviewTablet
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreviewDialog
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.InkeffectPreview
,03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.InkeffectPreviewTablet
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ModePreview
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NewModePreview
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewColor
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewColor2014
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewStyleClock
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewMiniWallpaper
,03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SViewCoverEdgeSettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ChooseLockFaceWarning
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PowerSettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
,03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.RecommendRingtoneDialog
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SelectInfoCoverSettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SelectItemDisplay
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$WeatherSettingsFragmentActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SViewCoverPopup
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.sec.android.sdk.cover.MODE
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.WarrantyLegal
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SamsungLegalTablet
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PenDetachmentOption
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenDetachmentOptionActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NotificationPanelMenu
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationPanelMenuActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.NotificationPanelSettings
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MotionSettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirMotionSettingActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.174  1018  1705 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.BOOT_COMPLETED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SMotionGuideHub2014Activity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewSettingActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.184  1018  1705 I ActivityManager: Killing 3289:com.google.android.youtube/u0a166 (adj 15): empty #31
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FingerAirViewHelpSettingActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewHelpSettingActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirViewSettingActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MouseHoveringSettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SoftwareUpdateSettingActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PenHelpActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenHelpFragmentActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DirectPenInputSettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenAirViewSettingsMenuActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PenSettingsMenuActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PhoneVibration
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.OneHandHelp
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.OneHandAdaptiveHelp
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$OneHandSideSoftKeyFragmentActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalvibration.PersonalVibration
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalvibration.SelectPatternDialog
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.LockScreenShortcutSettings
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.AppList
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.lockscreenshortcut.ExpandAppList
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ReadingModeSettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.customizablekey.CustomizableKeySettings
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CustomizableKeySettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.customizablekey.AppList
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DualClockSettingActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsMenuActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$RecommendedAppsListActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SettingsReceiverActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SelectPenDetachNotiDialog
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SecurityWarningDialog
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PersonalPageSettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageSettings
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PersonalPageDisclaimer
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageAutoModeSwitchAlertDialogActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorial
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialDisclaimerActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAppActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageTutorialAddActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPattern
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockPassword
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageChooseLockAdditionalPin
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPattern
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.personalpage.PersonalPageConfirmLockPassword
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeSettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$EasyModeAppActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceSettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094   257   440 I SurfaceFlinger: id=12 Removed Mauncher (5/8)
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MyPlaceProfileSettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$PlaceSettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myplace.SelectMapActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$GlobalRoamingSettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$TRoamingSettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.flipfont.FontListActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.flipfont.FontListProgressActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$BackupAssistantPlusSettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myprofile.MyProfileActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MagazineCard
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ClockWidgetActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.myprofile.PersonalMessage
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$CloudSettingActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ShortCameraMenu
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenu
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.ClockMyprofileMenuTablet
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$LaunchCameraSettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartScreenSettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartBondingSettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToolboxMenuActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToolboxListActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SmartScrollAdvancedSettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$MultiWindowSettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.MultiWindowSettings
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.settingssearch.SettingsSearchActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.SearchActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:android.app.searchable
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ColorChipReportActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.PARENT_FRAGMENT_TITLE
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DirectAccessActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$NotificationReminderActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
,03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$VoiceInputControlSettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PreloadAppUpdate
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.PreloadAppUpdateList
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.activekey.ActiveKeySettings
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ActiveKeySettingsActivity
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.activekey.AppList
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$DisplaySettingsTab
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$InputAndControlSettingsTab
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$GeneralSettingsTab
03-15 19:11:39.094  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.104  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.SETTING_HEADER_ID
03-15 19:11:39.104  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.DeviceHealthActivity
03-15 19:11:39.104  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SettingsEmergencyActivity
03-15 19:11:39.104  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.104  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.104  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.104  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareSettingsActivity
03-15 19:11:39.104  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.104  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.104  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.104  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareEmergencyModeActivity
03-15 19:11:39.104  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.104  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.104  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.104  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$SafetyCareDisasterActivity
03-15 19:11:39.104  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.104  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.104  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.104  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisclaimerActivity
03-15 19:11:39.104  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareDisasterDisclaimerActivity
03-15 19:11:39.104  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.safetycare.SafetyCareCoverageDialog
03-15 19:11:39.104  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$AirplaneModeSettingsActivity
03-15 19:11:39.104  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.104  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.104  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.104  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$ToddlerModeSettingsActivity
03-15 19:11:39.104  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.104  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.104  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.104  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.favorite.FavoriteMenuList
03-15 19:11:39.104  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.Settings$FestivalEffectSettingsActivity
03-15 19:11:39.104  3914  3973 I AMMetaDataParserService: Resource data:Inside bundle  check
03-15 19:11:39.104  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.TOP_LEVEL_HEADER_ID
03-15 19:11:39.104  3914  3973 I AMMetaDataParserService: getResourcePackageName:com.android.settings.FRAGMENT_CLASS
03-15 19:11:39.104  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDialog
03-15 19:11:39.104  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.powersavingmode.PowerNotiDataDialog
03-15 19:11:39.104  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.SetupWizardWifiScreen
03-15 19:11:39.104  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.wifi.CaptivePortalWebViewActivity
03-15 19:11:39.104  3914  3973 I AMMetaDataParserService: Resource data:Loop for running activitycom.android.settings.KnoxActiveProtectionEulaActivity
03-15 19:11:39.144  1509  1509 D Launcher.HomeView: onStop
03-15 19:11:39.144  1509  1509 D Launcher: onTrimMemory. Level: 20
03-15 19:11:39.174  4592  4592 D SecurityLogAgent: KnoxConfiguration : Current State = 1
03-15 19:11:39.174  4592  4592 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-15 19:11:39.174  4592  4592 D SecurityLogAgent: StateMachine : Current State = 1
03-15 19:11:39.174  4592  4592 D SecurityLogAgent: BootReceiver : completed task. Failed to return wakelock . 
03-15 19:11:39.184  1018  1044 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:39.184  1018  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:39.184  1018  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-15 19:11:39.194  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:39.194  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:39.214  1018  1030 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
03-15 19:11:39.194  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-15 19:11:39.214  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
03-15 19:11:39.194  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:39.194  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:39.194  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-15 19:11:39.204  1018  4306 D RCPManagerService: exchangeData() failure , invalid userId
03-15 19:11:39.204  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:39.204  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:39.204  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
03-15 19:11:39.214  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:39.214  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:39.214  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
03-15 19:11:39.214  2554  2554 I Hs20UtilService: Starting #3
03-15 19:11:39.214  1018  1043 W libprocessgroup: failed to open /acct/uid_10022/pid_3784/cgroup.procs: No such file or directory
03-15 19:11:39.214  2554  2571 I Hs20UtilService: Message received 5011
03-15 19:11:39.224  1018  1134 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
03-15 19:11:39.224  1018  1134 D WifiNative-wlan0: callSECStringApiVoid - ID [215]
03-15 19:11:39.224  1018  1134 E WifiNative-wlan0: invaild command id : 215
03-15 19:11:39.224  4592  4592 D SecurityLogAgent: KnoxConfiguration : Current State = 1
03-15 19:11:39.224  4592  4592 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-15 19:11:39.224  4592  4592 D SecurityLogAgent: StateMachine : Current State = 1
03-15 19:11:39.224  4592  4592 D SecurityLogAgent: StateMachine : Changed Current State = 1
03-15 19:11:39.224  1018  4306 D ActivityManager: startProcessLocked calleePkgName: com.example.hello, hostingType: broadcast
03-15 19:11:39.234  1018  1030 D RCPManagerService: exchangeData() failure , invalid userId
03-15 19:11:39.234  1018  4306 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:39.234  1018  4306 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:39.234  1018  4306 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:39.234  1018  4306 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:39.244  4613  4613 E Zygote  : MountEmulatedStorage()
03-15 19:11:39.244  4613  4613 E Zygote  : v2
03-15 19:11:39.244  4613  4613 I libpersona: KNOX_SDCARD checking this for 10174
03-15 19:11:39.244  4613  4613 I libpersona: KNOX_SDCARD not a persona
03-15 19:11:39.244  1018  4306 I ActivityManager: Start proc com.example.hello for broadcast com.example.hello/io.jxcore.node.ConnectivityChangeListener: pid=4613 uid=10174 gids={50174, 9997, 3003, 3001, 3002} abi=armeabi-v7a
03-15 19:11:39.244  4613  4613 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-15 19:11:39.244  4613  4613 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-15 19:11:39.254  4613  4613 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,03-15 19:11:39.274  4613  4613 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:39.274  4613  4613 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:39.294  1181  1181 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-15 19:11:39.294  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-15 19:11:39.294  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 19:11:39.294  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 19:11:39.294  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 19:11:39.294  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 19:11:39.294  1018  1952 D RCPManagerService: exchangeData() failure , invalid userId
,03-15 19:11:39.314  1018  1744 W ActivityManager: getTasks: caller 10146 does not hold GET_TASKS; limiting output
,03-15 19:11:39.314  4613  4613 D jxcore_app_log: JniHelper::setJavaVM(0xb8bed450), pthread_self() = -1225015608
,03-15 19:11:39.314  4613  4613 E JX-Cordova: JXcore wasn't initialized yet
,03-15 19:11:39.314  4543  4569 I Process : Sending signal. PID: 4543 SIG: 9
03-15 19:11:39.314  1018  1705 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:39.314  1018  1705 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:39.314  1018  1705 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 19:11:39.314  1018  1952 D RCPManagerService: exchangeData() failure , invalid userId
,03-15 19:11:39.314   254   254 E lowmemorykiller: Error writing /proc/4543/oom_score_adj; errno=22
,03-15 19:11:39.324  1018  1705 I ActivityManager: Killing 3677:com.google.android.gm/u0a101 (adj 15): empty #31
,03-15 19:11:39.324  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:39.324  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:39.324  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 19:11:39.334  4521  4531 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,03-15 19:11:39.334  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,03-15 19:11:39.334  1300  1300 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,03-15 19:11:39.334  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,03-15 19:11:39.344  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
03-15 19:11:39.344  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
03-15 19:11:39.344  1300  1300 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-15 19:11:39.344  1018  1952 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareClient, hostingType: broadcast
,03-15 19:11:39.344  1018  1952 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:39.344  1018  1952 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:39.344  1018  1952 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:39.344  1018  1952 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:39.354  4633  4633 E Zygote  : MountEmulatedStorage()
,03-15 19:11:39.354  1018  1952 I ActivityManager: Start proc com.samsung.android.app.FileShareClient for broadcast com.samsung.android.app.FileShareClient/.ClientBroadcastReceiver: pid=4633 uid=10068 gids={50068, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-15 19:11:39.354  4633  4633 E Zygote  : v2
03-15 19:11:39.354  4633  4633 I libpersona: KNOX_SDCARD checking this for 10068
03-15 19:11:39.354  4633  4633 I libpersona: KNOX_SDCARD not a persona
,03-15 19:11:39.364  4633  4633 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-15 19:11:39.364  4633  4633 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-15 19:11:39.364  4633  4633 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 19:11:39.374  4521  4558 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
,03-15 19:11:39.374  4521  4558 D BadgeProvider: sendNotify, [notify] : null
03-15 19:11:39.374  4521  4558 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
03-15 19:11:39.374  4521  4558 D BadgeProvider: update, [BadgeCount] : badgecount=0
,03-15 19:11:39.374  4521  4558 D BadgeProvider: update, [UpdateCount] : 1
03-15 19:11:39.374  1509  1509 D Launcher.Model: reloadBadges entered.
,03-15 19:11:39.394  1018  1504 D RCPManagerService: exchangeData() failure , invalid userId
,03-15 19:11:39.404  4633  4633 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:39.404  4633  4633 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:39.404  1018  1129 D RCPManagerService: exchangeData() failure , invalid userId
,03-15 19:11:39.404  1018  1705 I ActivityManager: Process com.android.exchange (pid 4543)(adj 13) has died(69,1137)
,03-15 19:11:39.424  4633  4633 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,03-15 19:11:39.434  1018  1018 D CustomFrequencyManagerService: releaseDVFSLockLocked : Getting Lock type frm List : DVFS_MIN_LIMIT  frequency : 1190400  uid : 1000  pid : 1018  tag : ACTIVITY_RESUME_BOOSTER@11
,03-15 19:11:39.444  4633  4633 D FileShare-Client: ClientBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,03-15 19:11:39.454  4633  4633 D FileShare-Client: ClientBroadcastReceiver.onReceive - disconnected
,03-15 19:11:39.484  4633  4633 D FileShare-Client: Outbound.stopDelayTimer - 
,03-15 19:11:39.484  1018  1744 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.FileShareServer, hostingType: broadcast
,03-15 19:11:39.484  1018  1744 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:39.484  1018  1744 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:39.484  1018  1744 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:39.484  1018  1744 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:39.504  4650  4650 E Zygote  : MountEmulatedStorage(),
03-15 19:11:39.504  4650  4650 I libpersona: KNOX_SDCARD checking this for 10069
03-15 19:11:39.504  4650  4650 E Zygote  : v2
03-15 19:11:39.504  4650  4650 I libpersona: KNOX_SDCARD not a persona
03-15 19:11:39.504  4650  4650 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-15 19:11:39.504  1018  1744 I ActivityManager: Start proc com.samsung.android.app.FileShareServer for broadcast com.samsung.android.app.FileShareServer/.ServerBroadcastReceiver: pid=4650 uid=10069 gids={50069, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 19:11:39.504  4650  4650 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-15 19:11:39.504  4650  4650 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 19:11:39.524  4650  4650 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:39.524  4650  4650 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:39.524  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3467/cgroup.procs: No such file or directory
03-15 19:11:39.524  1018  1043 W libprocessgroup: failed to open /acct/uid_10166/pid_3289/cgroup.procs: No such file or directory
,03-15 19:11:39.524  1018  1043 W libprocessgroup: failed to open /acct/uid_10101/pid_3677/cgroup.procs: No such file or directory
,03-15 19:11:39.544  4650  4650 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,03-15 19:11:39.554  1018  1504 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:39.554  1018  1504 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-15 19:11:39.554  1018  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 19:11:39.554  1018  1504 I ActivityManager: Killing 3914:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #31
,03-15 19:11:39.554  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:39.554  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:39.554  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 19:11:39.564  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:39.564  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:39.564  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 19:11:39.564  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:39.564  1018  1018 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-15 19:11:39.564  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.phone, destAppInfo.processName = system
,03-15 19:11:39.564  1018  1018 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:39.564  1018  1018 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:39.564  1018  1018 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:39.574  1018  1705 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,03-15 19:11:39.574  1018  1705 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
03-15 19:11:39.574  1018  1705 I splitIntent: other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
,03-15 19:11:39.574  1018  1705 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
03-15 19:11:39.574  1018  1705 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:39.574  1018  1705 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:39.574  1018  1705 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:39.584  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:39.584  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:39.584  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:39.594  1018  1346 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:39.594  1018  1346 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:39.594  1018  1346 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,03-15 19:11:39.614  1018  1030 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 19:11:39.614  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:39.614  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:39.614  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:39.624  1018  1952 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:39.624  1018  1952 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-15 19:11:39.624  1018  1952 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:39.634  1018  1952 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 19:11:39.634  1018  1952 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:39.634  1018  1952 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:39.634  1018  1952 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:39.634  1931  1931 D WearableService: callingUid 10012, callindPid: 1931
,03-15 19:11:39.634  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:39.634  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:39.634  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:39.644  1018  1952 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.AttachmentDownloadService; callingUser = 0; userId(target) = 0
03-15 19:11:39.644  1018  1952 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,03-15 19:11:39.644  1018  4423 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-15 19:11:39.644  1018  4423 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
,03-15 19:11:39.644  1018  4423 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:39.644  1018  4423 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:39.644  1018  4423 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:39.644  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.service.EmailDebugService; callingUser = 0; userId(target) = 0
,03-15 19:11:39.644  1018  1337 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-15 19:11:39.644  1018  1337 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,03-15 19:11:39.654  1018  1337 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:39.654  1018  1337 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:39.654  1018  1337 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:39.654  1018  1266 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:39.654  1018  1266 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:39.654  1018  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:39.654  2089  4667 D LocationInitializer: Restart initialization of location
,03-15 19:11:39.654  1018  1266 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:39.654  1018  1266 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:39.654  1018  1266 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:39.664  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3914/cgroup.procs: No such file or directory
,03-15 19:11:39.664  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.email/com.android.email.legacypush.ImapPushService; callingUser = 0; userId(target) = 0
,03-15 19:11:39.674  1018  1518 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-15 19:11:39.674  1018  1518 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,03-15 19:11:39.684  1018  1518 W ActivityManager: userId = 0, bbcId = -10000,
03-15 19:11:39.684  1018  1518 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:39.684  1018  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms,
,03-15 19:11:39.744  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-15 19:11:39.744  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.proxy.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,03-15 19:11:39.744  1484  1498 D TP/SmsProvider: query,matched:0, calling pid = 2089
,03-15 19:11:39.744  1484  1498 D TP/SmsProvider: match 0:Elapsed time : 3.248 ms
,03-15 19:11:39.744  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:39.744  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:39.744  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:39.764  1484  1791 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2089
,03-15 19:11:39.784  1018  1744 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
03-15 19:11:39.784  1018  1744 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.location.nearby.direct.service.NearbyDirectService; callingUser = 0; userId(target) = 0
,03-15 19:11:39.784  1018  1744 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:39.784  1018  1744 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:39.784  1018  1744 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:39.784  1484  2048 D TP/SmsProvider: query,matched:0, calling pid = 2089
,03-15 19:11:39.784  1484  2048 D TP/SmsProvider: match 0:Elapsed time : 1.278 ms
,03-15 19:11:39.804  1018  1518 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.nearby.messages.service.NearbyMessagesService; callingUser = 0; userId(target) = 0
,03-15 19:11:39.804  1484  1502 D TP/MmsProvider: Query uri=content://mms, match=0, calling pid = 2089
,03-15 19:11:39.814  1931  1931 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-15 19:11:39.824  1931  1931 D a       : Opening database auth.proximity.permit_store...
,03-15 19:11:39.834  1018  1952 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:39.834  1018  1952 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:39.834  1018  1952 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:39.834  1018  4423 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 19:11:39.834  1018  4423 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:39.834  1018  4423 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:39.834  1018  4423 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:39.864  2089  4676 W IcingInternalCorpora: getNumBytesRead when not calculated.
,03-15 19:11:39.884  1018  4423 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-15 19:11:39.884  1018  4423 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.location.nearby.direct.service.NearbyDirectService; callingUser = 0; userId(target) = 0
,03-15 19:11:39.884  1018  4423 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:39.884  1018  4423 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:39.884  1018  4423 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:39.894  1018  1518 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-15 19:11:39.894  1018  1518 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,03-15 19:11:39.894  1018  1518 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:39.894  1018  1518 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:39.894  1018  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:39.894  1931  4666 E MDM     : [240] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-15 19:11:39.904  1018  4306 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:39.904  1018  4306 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:39.904  1018  4306 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:39.904  1931  1931 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 19:11:39.914  1018  1504 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:39.924  1018  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-15 19:11:39.924  1018  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:39.924  1931  2104 W GCoreFlp: No location to return for getLastLocation()
,03-15 19:11:39.924  1018  1518 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-15 19:11:39.924  1018  1518 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,03-15 19:11:39.924  1931  4680 W FusedLocationProvider: location=null
,03-15 19:11:39.934  1018  1518 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:39.934  1018  1518 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:39.934  1018  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:39.934  1018  1044 I ActivityManager: Waited long enough for: ServiceRecord{12bdbeeb u0 com.samsung.android.providers.context/.ContextService}
,03-15 19:11:39.954  1018  1705 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,03-15 19:11:39.954  1018  1705 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-15 19:11:39.954  1018  1705 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:39.954  1018  1705 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-15 19:11:39.954  1018  1705 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-15 19:11:39.954  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-15 19:11:39.954  1300  1300 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,03-15 19:11:39.964  2554  2554 I Hs20UtilService: Starting #4
,03-15 19:11:39.964  2554  2571 I Hs20UtilService: Message received 5007
,03-15 19:11:39.964  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,03-15 19:11:39.964  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
03-15 19:11:39.964  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
03-15 19:11:39.964  1300  1300 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-15 19:11:39.974  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:39.974  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-15 19:11:39.974  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:39.974  1018  1031 I splitIntent: intent=com.google.android.gms.INITIALIZE will be not split. because same process=com.google.android.gms is in other queue. index=1
,03-15 19:11:39.974  1018  1031 I splitIntent: base  index=1, name=com.google.android.gms com.google.android.gms.wearable.service.AutoStarterReceiver
,03-15 19:11:39.974  1018  1031 I splitIntent: other index=4, name=com.google.android.gms com.google.android.gms.init.InitializeGmsReceiver
03-15 19:11:39.974  1018  1031 I splitIntent: arrangeSplitReceiver return false!! intent : com.google.android.gms.INITIALIZE !! do not split it!!
,03-15 19:11:39.984  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:39.984  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:39.984  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:39.984  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:39.994  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:39.994  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:39.994  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:39.994  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:39.994  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:39.994  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:39.994  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:39.994  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:40.004  1018  1031 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 19:11:40.004  1931  4689 E MDM     : [255] b.run: Couldn't connect to Google API client: ConnectionResult{statusCode=API_UNAVAILABLE, resolution=null, message=null}
,03-15 19:11:40.004  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:40.004  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:40.004  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:40.004  1018  1337 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:40.004  1018  1337 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:40.004  1018  1337 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:40.004  1018  1518 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:40.004  1018  1518 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:40.004  1018  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:40.014  1018  1504 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-15 19:11:40.014  1018  1504 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.deviceconnection.service.DeviceConnectionServiceBroker; callingUser = 0; userId(target) = 0
,03-15 19:11:40.014  1018  1504 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:40.014  1018  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:40.014  1018  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:40.014  2089  4690 D LocationInitializer: Restart initialization of location
,03-15 19:11:40.014  1018  1346 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:40.014  1018  1346 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:40.014  1018  1346 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:40.014  1931  1931 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,03-15 19:11:40.024  1018  1346 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:40.024  1018  1346 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:40.024  1018  1346 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:40.024  1018  1504 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-15 19:11:40.024  1018  1504 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.lockbox.LockboxService; callingUser = 0; userId(target) = 0
,03-15 19:11:40.024  1018  1504 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:40.024  1018  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:40.024  1018  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:40.034  1018  1744 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-15 19:11:40.034  1018  1744 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.be.account.AccountStatusChecker$InitializeService; callingUser = 0; userId(target) = 0
,03-15 19:11:40.034  1018  1744 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:40.034  1018  1744 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:40.034  1018  1744 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:40.034  1018  1044 I ActivityManager: Waited long enough for: ServiceRecord{1fb81448 u0 com.android.settings/.wifi.WifiCredService}
,03-15 19:11:40.044  1018  1705 W ActivityManager: userId = 0, bbcId = -10000,
03-15 19:11:40.044  1018  1705 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:40.044  1018  1705 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:40.044  1931  1931 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,03-15 19:11:40.044  1018  1129 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:40.044  1018  1129 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-15 19:11:40.044  1018  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:40.054  1018  1952 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-15 19:11:40.054  1018  1952 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.auth.crypto.ChannelBindingStateService; callingUser = 0; userId(target) = 0
,03-15 19:11:40.054  1018  1952 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:40.054  1018  1952 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:40.054  1018  1952 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:40.064  1018  1705 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,03-15 19:11:40.064  1018  1705 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-15 19:11:40.064  1018  1705 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:40.064  1018  1705 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:40.064  1018  1705 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-15 19:11:40.064  2554  2554 I Hs20UtilService: Starting #5
,03-15 19:11:40.064  2554  2571 I Hs20UtilService: Message received 5007
,03-15 19:11:40.074  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-15 19:11:40.074  1300  1300 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-15 19:11:40.074  1931  2104 W GCoreFlp: No location to return for getLastLocation()
,03-15 19:11:40.074  1931  4691 W FusedLocationProvider: location=null
,03-15 19:11:40.084  1018  1346 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,03-15 19:11:40.084  1018  1346 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-15 19:11:40.084  1018  1346 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:40.084  1018  1346 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:40.084  1018  1346 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-15 19:11:40.084  2554  2554 I Hs20UtilService: Starting #6
,03-15 19:11:40.084  2554  2571 I Hs20UtilService: Message received 5007
,03-15 19:11:40.094  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-15 19:11:40.094  1300  1300 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,03-15 19:11:40.094  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: CONNECTED
,03-15 19:11:40.094  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - P2P: IDLE
,03-15 19:11:40.094  1300  1300 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-true, Hotspot-false, P2P-false, Eth-false
03-15 19:11:40.094  1300  1300 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-15 19:11:40.104  1018  1518 D ActivityManager: startService callerProcessName:com.samsung.hs20settings, calleePkgName: com.samsung.hs20settings
,03-15 19:11:40.104  1018  1518 D ActivityManager: retrieveServiceLocked(): component = com.samsung.hs20settings/com.samsung.hs20settings.WifiHs20UtilityService; callingUser = 0; userId(target) = -2
,03-15 19:11:40.104  1018  1518 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:40.104  1018  1518 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:40.104  1018  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.hs20settings, destAppInfo.processName = com.samsung.hs20settings
,03-15 19:11:40.104  1300  1300 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,03-15 19:11:40.104  1300  1300 I NearbySettings: MountReceiver.onReceive - Keep current state
,03-15 19:11:40.114  2554  2554 I Hs20UtilService: Starting #7
,03-15 19:11:40.114  1018  1041 D SensorService: [SO] 0.153 0.402 10.151
,03-15 19:11:40.114  2554  2571 I Hs20UtilService: Message received 5007
,03-15 19:11:40.114  1018  1744 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,03-15 19:11:40.124  1018  1031 D SecContentProvider2: uri = 15 selection = getToastGravityEnabledState
,03-15 19:11:40.124  1018  1031 D SecContentProvider2: mCursor = null
,03-15 19:11:40.124  1018  1337 D SecContentProvider2: uri = 15 selection = getToastGravity
,03-15 19:11:40.124  1018  1337 D SecContentProvider2: mCursor = null
,03-15 19:11:40.124  1018  1129 D SecContentProvider2: uri = 15 selection = getToastGravityXOffset
,03-15 19:11:40.124  1018  1129 D SecContentProvider2: mCursor = null
,03-15 19:11:40.124  1018  1705 D SecContentProvider2: uri = 15 selection = getToastGravityYOffset
,03-15 19:11:40.124  1018  1705 D SecContentProvider2: mCursor = null
,03-15 19:11:40.134  1018  1518 D SecContentProvider2: uri = 15 selection = getToastEnabledState
,03-15 19:11:40.134  1018  1518 D SecContentProvider2: mCursor = null
,03-15 19:11:40.134  1018  1266 D SecContentProvider2: uri = 15 selection = getToastShowPackageNameState
,03-15 19:11:40.134  1018  1266 D SecContentProvider2: mCursor = null
,03-15 19:11:40.144  1018  4306 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:40.144  1018  4306 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:40.144  1018  4306 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:40.154  1018  1705 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,03-15 19:11:40.164  1018  1705 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:40.164  1018  1705 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:40.164  1018  1705 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:40.164  1018  1705 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:40.164   257   257 I SurfaceFlinger: id=14 createSurf (1x1),1 flag=4, Uoast
,03-15 19:11:40.174  4694  4694 E Zygote  : MountEmulatedStorage(),
03-15 19:11:40.174  4694  4694 E Zygote  : v2
,03-15 19:11:40.174  4694  4694 I libpersona: KNOX_SDCARD checking this for 1000
03-15 19:11:40.174  4694  4694 I libpersona: KNOX_SDCARD not a persona,
03-15 19:11:40.174  4694  4694 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-15 19:11:40.174  1018  1266 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=1018
03-15 19:11:40.174  1018  1053 D DisplayPowerController: getFinalBrightness : Summary is 60 -> 60
03-15 19:11:40.174  1018  1053 D DisplayPowerController: animation target = 60, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-15 19:11:40.174  1018  1053 D PowerManagerService: [s] DisplayPowerCallbacks : onStateChanged()
,03-15 19:11:40.184  1018  1705 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=4694 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-15 19:11:40.184  4694  4694 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-15 19:11:40.184  1181  1181 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,03-15 19:11:40.194  4694  4694 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 19:11:40.194  1018  1161 D lights  : lcd : 48 +
,03-15 19:11:40.204   308   308 I art     : Explicit concurrent mark sweep GC freed 8721(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 664us total 21.265ms
,03-15 19:11:40.214  1018  1161 D lights  : lcd : 48 -
03-15 19:11:40.214  1018  1053 D DisplayPowerController: getFinalBrightness : Summary is 60 -> 60
03-15 19:11:40.214  1018  1161 D lights  : lcd : 60 +
03-15 19:11:40.214  1018  1053 D DisplayPowerController: animation target = 60, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-15 19:11:40.224   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 694us total 17.367ms
,03-15 19:11:40.224  4694  4694 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:40.224  1018  1161 D lights  : lcd : 60 -
03-15 19:11:40.224  4694  4694 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:40.224  1018  1053 D DisplayPowerController: getFinalBrightness : Summary is 60 -> 60
03-15 19:11:40.224  1018  1053 D DisplayPowerController: animation target = 60, rate=2000 (PSM:false, AB limit:(-1 ~ -1) MB Limit:(-1 ~ -1) MAdj:(0, (0, 255)))
,03-15 19:11:40.234   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 626us total 18.185ms,
,03-15 19:11:40.254  4694  4694 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
,03-15 19:11:40.254  4694  4694 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
03-15 19:11:40.254  4694  4694 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,03-15 19:11:40.264  4694  4694 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,03-15 19:11:40.264  4694  4694 I PCWCLIENTTRACE_PushUtil: sales region : global
03-15 19:11:40.264  4694  4694 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
03-15 19:11:40.264  4694  4694 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,03-15 19:11:40.274  1018  1129 I splitIntent: Split this intent : android.net.conn.CONNECTIVITY_CHANGE, mSplitNum[0]=10, mSplitNum[1]=17, mSplitNum[2]=26, mBgSplitQueueNum=3 divideNum= 8 r.nextReceiver= 1 receivers.size=34
,03-15 19:11:40.274  1018  1129 I splitIntent: finish to split intent : android.net.conn.CONNECTIVITY_CHANGE !! Enqueue -> schedule it!!
,03-15 19:11:40.274  1018  1129 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,03-15 19:11:40.274  1018  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:40.274  1018  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:40.274  1018  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:40.274  1018  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:40.284  4711  4711 E Zygote  : MountEmulatedStorage()
,03-15 19:11:40.284  4711  4711 E Zygote  : v2
,03-15 19:11:40.284  4711  4711 I libpersona: KNOX_SDCARD checking this for 10111
03-15 19:11:40.284  4711  4711 I libpersona: KNOX_SDCARD not a persona
,03-15 19:11:40.284  1018  1129 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=4711 uid=10111 gids={50111, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 19:11:40.294  4711  4711 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-15 19:11:40.294  4711  4711 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-15 19:11:40.294  4711  4711 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-15 19:11:40.294  1181  1181 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020535/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-15 19:11:40.294  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-15 19:11:40.294  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 19:11:40.294  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 19:11:40.294  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 19:11:40.294  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 19:11:40.304  4592  4592 D SecurityLogAgent: KnoxConfiguration : Current State = 1
03-15 19:11:40.304  4592  4592 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-15 19:11:40.304  4592  4592 D SecurityLogAgent: StateMachine : Current State = 1
,03-15 19:11:40.304  4592  4592 D SecurityLogAgent: StateMachine : Changed Current State = 1
03-15 19:11:40.304  3759  3759 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Mar 15 19:11:40 GMT+01:00 2016
03-15 19:11:40.304  1759  1759 D accuweather: [KK AccuPhone]>>> WCW:32 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,03-15 19:11:40.304  1018  1030 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,03-15 19:11:40.314  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:40.314  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:40.314  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:40.314  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:40.324  4711  4711 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 19:11:40.324  4726  4726 E Zygote  : MountEmulatedStorage()
03-15 19:11:40.324  4726  4726 E Zygote  : v2
03-15 19:11:40.324  4726  4726 I libpersona: KNOX_SDCARD checking this for 10159
03-15 19:11:40.324  4726  4726 I libpersona: KNOX_SDCARD not a persona
,03-15 19:11:40.324  4711  4711 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:40.324  4726  4726 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-15 19:11:40.334  4726  4726 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-15 19:11:40.334  4726  4726 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL,
,03-15 19:11:40.334  1018  1030 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=4726 uid=10159 gids={50159, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 19:11:40.344  1018  4423 I art     : Explicit concurrent mark sweep GC freed 37624(2MB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 30MB/45MB, paused 2.761ms total 160ms
03-15 19:11:40.344  1018  1952 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
03-15 19:11:40.344  1018  1952 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
03-15 19:11:40.344  1018  1952 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:40.344  1018  1952 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:40.344  1018  1952 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
03-15 19:11:40.344  1323  1332 D daemonapp: [MSC_Daemon]>>> WCP:1254 [0:0] cp update : count : 1, pt : 4
,03-15 19:11:40.354  1759  1759 D accuweather: [KK AccuPhone]>>> U:4088 [0:0] getPWC : surface = 0, remote = 1
,03-15 19:11:40.354  1759  1759 D accuweather: [KK AccuPhone]>>> U:4207 [0:0] Store PWC = 1
03-15 19:11:40.354  1759  1759 D accuweather: [KK AccuPhone]>>> U:4140 [0:0] addPWC = 1
03-15 19:11:40.354  1759  1759 D accuweather: [KK AccuPhone]>>> UIM:312 [0:0]  action:androidnetconnCONNECTIVITY_CHANGE
,03-15 19:11:40.354  3759  3759 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
,03-15 19:11:40.364  1759  1759 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidnetconnCONNECTIVITY_CHANGE
,03-15 19:11:40.364  3759  3759 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,03-15 19:11:40.374  1759  1759 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,03-15 19:11:40.374  1018  1952 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,03-15 19:11:40.374  3759  3759 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-15 19:11:40.374  1018  1952 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:40.374  1018  1952 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:40.374  1018  1952 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:40.374  1018  1952 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:40.384  3759  3759 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-15 19:11:40.384  3759  4735 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,03-15 19:11:40.384  3759  4735 I KLMS-2.5.183: : KLMSIntentService(): NETWORK_STATE_CHANGED_ACTION
,03-15 19:11:40.384  4742  4742 E Zygote  : MountEmulatedStorage()
,03-15 19:11:40.384  4742  4742 I libpersona: KNOX_SDCARD checking this for 10081
03-15 19:11:40.384  4742  4742 E Zygote  : v2
03-15 19:11:40.384  4742  4742 I libpersona: KNOX_SDCARD not a persona
03-15 19:11:40.384  4742  4742 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-15 19:11:40.384  1018  1952 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=4742 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 19:11:40.394  4726  4726 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 19:11:40.394  4742  4742 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-15 19:11:40.394  4726  4726 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:40.394  4742  4742 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,03-15 19:11:40.404  3759  4735 I KLMS-2.5.183: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false| ETHERNET : false
,03-15 19:11:40.404  3759  4735 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().START
,03-15 19:11:40.414  3759  4735 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().START 
,03-15 19:11:40.424  4198  4754 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-15 19:11:40.424  4198  4754 I DBG_POLICYDM: [com.policydm.XDMApplication(469/isNetworkChanged)] a previous network is 0, current network is 2
,03-15 19:11:40.424  3759  4735 I KLMS-2.5.183: : NetworkChangeOperations(): uploadRequestLog().END 
,03-15 19:11:40.424  4198  4754 E DBG_POLICYDM: [com.policydm.XDMApplication(471/isNetworkChanged)] network changed.... 
,03-15 19:11:40.434  3759  4735 I KLMS-2.5.183: : StateImplV2(): networkChangeListener().END
,03-15 19:11:40.434  3759  3759 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
03-15 19:11:40.434  4742  4742 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:40.434  4742  4742 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:40.454  4264  4264 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,03-15 19:11:40.454  4312  4312 I SA      : [OR] onReceive log=[SA = 2.1.0179 V = 21 HWD = 1280X720 2.0 dpi = 320  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = a5ulte P = a5ultexx I = LRX22G M = SM-A500FU OKLEFT false DIS LRX22G.A500FUXXU1BOH2 PSS = 4.978878039476607  ]
,03-15 19:11:40.454  4312  4312 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
03-15 19:11:40.454  4312  4312 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,03-15 19:11:40.474  4198  4754 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(258/xdmExecResumeCase)] 
,03-15 19:11:40.474  4198  4754 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,03-15 19:11:40.474  4198  4754 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,03-15 19:11:40.484  4198  4754 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,03-15 19:11:40.484  4198  4754 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,03-15 19:11:40.484  4198  4754 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,03-15 19:11:40.484  4198  4754 I DBG_POLICYDM: [com.policydm.db.XDBFile(63/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,03-15 19:11:40.484  4198  4754 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(275/xdmExecResumeCase)] Start resumecase for INIT
,03-15 19:11:40.494  4198  4754 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,03-15 19:11:40.504  4198  4754 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,03-15 19:11:40.514  4312  4312 I SA      : [SLFUCHKMGR] constructor called
,03-15 19:11:40.524  4312  4312 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,03-15 19:11:40.524  4312  4312 I SA      : [OR] == isSIMCardReady false ==
,03-15 19:11:40.634  4312  4312 I SA      : [SCU] == networkStateCheck == true
,03-15 19:11:40.634  4312  4312 I SA      : [DM] getCountryCodeFromCSC : PL
,03-15 19:11:40.634  4312  4312 I SA      : isChinaCountryCode : false
03-15 19:11:40.644  4312  4312 I SA      : [SCU] is ChinestModel Data Restricted   : false
03-15 19:11:40.644  4312  4312 I SA      : [OR] == networkStateCheck true ==
,03-15 19:11:40.694  4711  4711 I MusicStore: Database version: 108
,03-15 19:11:40.704  2089  4767 I iu.SyncManager: SYNC; picasa accounts
,03-15 19:11:40.714  4312  4312 I SA      : [OR] GetMyCountryZoneTask
,03-15 19:11:40.714  4312  4312 I SA      : [OR] onReceive END
,03-15 19:11:40.714  1018  1129 I ActivityManager: Killing 3638:com.samsung.android.sm/1000 (adj 15): empty #31
,03-15 19:11:40.724  2089  2089 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,03-15 19:11:40.724  2089  2089 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,03-15 19:11:40.724  1228  1228 V DownloadManager: onReceive intent + android.net.conn.CONNECTIVITY_CHANGE
,03-15 19:11:40.734  1018  4306 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
03-15 19:11:40.734  1018  4306 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.downloads/com.android.providers.downloads.DownloadService; callingUser = 0; userId(target) = 0
,03-15 19:11:40.734  1018  4306 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:40.734  1018  4306 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-15 19:11:40.734  1018  4306 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-15 19:11:40.744  1018  1031 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-15 19:11:40.744  1018  1031 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.GcmService; callingUser = 0; userId(target) = 0
,03-15 19:11:40.744  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:40.754  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:40.754  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:40.754  1018  4306 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
,03-15 19:11:40.754  1018  4306 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:40.754  1018  4306 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:40.754  1018  4306 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:40.754  1018  4306 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:40.754  1018  1705 D SecContentProvider2: uri = 15 selection = getAppBlockDownloadState
,03-15 19:11:40.754  1018  1705 D SecContentProvider2: mCursor = null
,03-15 19:11:40.764  2089  4767 I iu.UploadsManager: num queued entries: 0
,03-15 19:11:40.764  2089  4767 I iu.UploadsManager: num updated entries: 0
,03-15 19:11:40.764  4771  4771 E Zygote  : MountEmulatedStorage()
03-15 19:11:40.764  4771  4771 E Zygote  : v2
03-15 19:11:40.764  4771  4771 I libpersona: KNOX_SDCARD checking this for 10010
,03-15 19:11:40.764  4771  4771 I libpersona: KNOX_SDCARD not a persona
,03-15 19:11:40.764  4771  4771 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-15 19:11:40.764  1018  4306 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=4771 uid=10010 gids={50010, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,03-15 19:11:40.764  4771  4771 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-15 19:11:40.774  4771  4771 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,03-15 19:11:40.774  4312  4769 I SA      : [SRS] prepareGetMyCountryZone
03-15 19:11:40.774  1018  1030 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
03-15 19:11:40.774  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,03-15 19:11:40.774  2089  4767 I iu.SyncManager: NEXT; no task
,03-15 19:11:40.774  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:40.774  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:40.774  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-15 19:11:40.774  1018  1030 I ActivityManager: Killing 3868:com.vlingo.midas/u0a31 (adj 15): empty #31
,03-15 19:11:40.784  4312  4769 I SA      : [TPMU]  strSIMState 	:SIM_STATE_ABSENT
,03-15 19:11:40.784  4312  4769 I SA      : [SSP] query invoked
,03-15 19:11:40.794  4312  4769 I SA      : [TPMU] GetMccFromDB : null
03-15 19:11:40.794  4312  4769 I SA      : [SCU] getMccFromPreferece mcc = 260
03-15 19:11:40.794  4312  4769 I SA      : [TPM] isNoProxy(default) : true
,03-15 19:11:40.804  4771  4771 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:40.804  4771  4771 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:40.804  4312  4769 E File    : fail readDirectory() errno=2
,03-15 19:11:40.834  1018  1518 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,03-15 19:11:40.834  1018  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:40.834  1018  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:40.834  1018  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:40.834  1018  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:40.844  1018  1059 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,03-15 19:11:40.844  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3638/cgroup.procs: No such file or directory
,03-15 19:11:40.854  4787  4787 E Zygote  : MountEmulatedStorage()
,03-15 19:11:40.854  4787  4787 I libpersona: KNOX_SDCARD checking this for 10113
03-15 19:11:40.854  4787  4787 E Zygote  : v2
03-15 19:11:40.854  4787  4787 I libpersona: KNOX_SDCARD not a persona
03-15 19:11:40.854  4787  4787 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-15 19:11:40.854  1018  1518 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=4787 uid=10113 gids={50113, 9997, 3003, 1028, 1015} abi=armeabi-v7a,
03-15 19:11:40.854  1018  1518 I ActivityManager: Killing 3975:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #31
,03-15 19:11:40.854  4787  4787 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-15 19:11:40.864  4787  4787 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,03-15 19:11:40.874  4787  4787 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:40.874  4787  4787 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:40.964  1018  1043 W libprocessgroup: failed to open /acct/uid_10031/pid_3868/cgroup.procs: No such file or directory
,03-15 19:11:40.964  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_3975/cgroup.procs: No such file or directory
,03-15 19:11:41.024   287   287 E SMD     : DCD OFF
,03-15 19:11:41.034  4711  4711 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,03-15 19:11:41.034  4711  4711 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,03-15 19:11:41.054  4771  4771 D WaitQueueForNetworkActivate: notifyNetworkActivated
,03-15 19:11:41.064  4711  4711 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 254 native methods...
,03-15 19:11:41.104  4771  4771 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } android.content.ContextWrapper.bindService:559 com.sec.knox.containeragent.ContainerManager.<init>:49 com.sec.android.app.samsungapps.vlibrary2.knoxmode.KNOXAPI.<init>:20 
,03-15 19:11:41.114  1018  1266 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 19:11:41.114  1018  1266 W ActivityManager: Unable to start service Intent { act=com.sec.knox.containeragent.service.containermanager.ContainerManagerService } U=0: not found
,03-15 19:11:41.114  4711  4711 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,03-15 19:11:41.114  4711  4711 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@29496bc9: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
03-15 19:11:41.114  4711  4711 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
03-15 19:11:41.114  4711  4711 D AndroidMusic: GMSCore installation verified
,03-15 19:11:41.144  1018  1129 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,03-15 19:11:41.144  1018  1129 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.preferences.MusicPreferenceService$MusicPreferenceServiceBinder; callingUser = 0; userId(target) = 0
,03-15 19:11:41.144  1018  1129 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:41.144  1018  1129 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:41.144  1018  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-15 19:11:41.154  4711  4711 I ConfigStore: Config Database version: 1
,03-15 19:11:41.234   256   515 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-15 19:11:41.234   256   515 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 19:11:41.234  4711  4711 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-15 19:11:41.234   256   515 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
03-15 19:11:41.234   256   515 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 19:11:41.244   256   515 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-15 19:11:41.244  4787  4812 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
03-15 19:11:41.244   256   515 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 19:11:41.244  4711  4711 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-15 19:11:41.244   256   515 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
03-15 19:11:41.244   256   515 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 19:11:41.244  4787  4812 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,03-15 19:11:41.254   256   515 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
03-15 19:11:41.254   256   515 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 19:11:41.254  4711  4711 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,03-15 19:11:41.264  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,03-15 19:11:41.264  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.StorageMigrationService; callingUser = 0; userId(target) = 0
,03-15 19:11:41.264  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:41.264  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:41.264  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-15 19:11:41.264   256   515 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
03-15 19:11:41.264   256   515 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 19:11:41.274  4787  4815 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,03-15 19:11:41.274   256   515 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
03-15 19:11:41.274   256   515 W Vold    : Returning OperationFailed - no handler for errno 0
,03-15 19:11:41.274  4787  4815 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,03-15 19:11:41.284  1018  4423 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,03-15 19:11:41.284  1018  4423 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.artwork.ArtDownloadService2; callingUser = 0; userId(target) = 0
,03-15 19:11:41.284  1018  4423 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:41.284  1018  4423 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:41.284  1018  4423 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-15 19:11:41.294  1018  4306 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
03-15 19:11:41.294  1018  4306 D ActivityManager: retrieveServiceLocked(): component = com.sec.android.app.samsungapps/com.sec.android.app.samsungapps.autoupdateservice.AutoUpdateService; callingUser = 0; userId(target) = 0
,03-15 19:11:41.294  1018  4306 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:41.294  1018  4306 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
03-15 19:11:41.294  1018  4306 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.samsungapps, destAppInfo.processName = com.sec.android.app.samsungapps
,03-15 19:11:41.304  4771  4771 D hcjo    : AutoUpdateManager:IDLE:execute
,03-15 19:11:41.314  4771  4771 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,03-15 19:11:41.314  4771  4771 D InitializeManagerStateMachine: exit::IDLE
03-15 19:11:41.314  4771  4771 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,03-15 19:11:41.314  4771  4771 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
,03-15 19:11:41.314  4771  4771 D InitializeManagerStateMachine: exit::NETWORK_CHECK
03-15 19:11:41.314  4771  4771 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
03-15 19:11:41.324  4771  4771 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,03-15 19:11:41.324  4771  4771 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
03-15 19:11:41.324  4771  4771 D InitializeManagerStateMachine: entry::SUCCESS
03-15 19:11:41.324  4771  4771 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,03-15 19:11:41.324  4771  4771 D hcjo    : AutoUpdateTriggerManager:REQUEST2:requestInterval
,03-15 19:11:41.334  1018  1504 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-15 19:11:41.334  1018  1129 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-15 19:11:41.344  1018  4306 I AudioService: getStreamVolume 3 index 0
,03-15 19:11:41.344  4711  4711 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,03-15 19:11:41.354  4771  4771 I Volley  : RestApi Request Add : 2307
,03-15 19:11:41.354  4711  4711 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,03-15 19:11:41.354  4771  4771 E File    : fail readDirectory() errno=2
,03-15 19:11:41.364  4711  4711 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-15 19:11:41.394  1018  1744 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,03-15 19:11:41.394  1018  1744 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,03-15 19:11:41.404  1018  1744 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:41.404  1018  1744 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:41.404  1018  1744 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-15 19:11:41.404  1018  1030 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
03-15 19:11:41.404  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.ArtDownloadQueueService; callingUser = 0; userId(target) = 0
,03-15 19:11:41.404  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:41.404  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
,03-15 19:11:41.404  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-15 19:11:41.414  1018  1518 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
03-15 19:11:41.414  1018  1518 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.download.cache.ArtCacheService; callingUser = 0; userId(target) = 0
,03-15 19:11:41.414  1018  1518 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:41.414  1018  1518 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:41.414  1018  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-15 19:11:41.424  1018  1337 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,03-15 19:11:41.424  4711  4711 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,03-15 19:11:41.434  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,03-15 19:11:41.434  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:41.434  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:41.434  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:41.434  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:41.444  4787  4787 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,03-15 19:11:41.444  4833  4833 E Zygote  : MountEmulatedStorage()
03-15 19:11:41.444  4833  4833 E Zygote  : v2
03-15 19:11:41.444  4833  4833 I libpersona: KNOX_SDCARD checking this for 10002
03-15 19:11:41.444  4833  4833 I libpersona: KNOX_SDCARD not a persona
03-15 19:11:41.444  4833  4833 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-15 19:11:41.444  4833  4833 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-15 19:11:41.454  4833  4833 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 19:11:41.454  1018  1018 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=4833 uid=10002 gids={50002, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-15 19:11:41.454  1018  1504 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 19:11:41.454  1018  1504 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:41.454  1018  1504 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:41.454  1018  1504 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.apps.magazines, destAppInfo.processName = com.google.android.gms
,03-15 19:11:41.474  4833  4833 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:41.474  4833  4833 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:41.484  1018  1030 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,03-15 19:11:41.484  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.gcm.http.GoogleHttpService; callingUser = 0; userId(target) = 0
,03-15 19:11:41.484  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:41.484  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:41.484  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.gms
,03-15 19:11:41.494  4787  4787 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 3020-3023)
03-15 19:11:41.494  4787  4787 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-15 19:11:41.494  4711  4711 W GoogleHttpClient: Failed to load SSLCertificateSocketFactory from package
03-15 19:11:41.494  4711  4711 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,03-15 19:11:41.494  4711  4711 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,03-15 19:11:41.504  1018  4306 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,03-15 19:11:41.504  4787  4787 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2e066b94}
03-15 19:11:41.504  1018  4306 D ActivityManager: retrieveServiceLocked(): component = com.google.android.music/com.google.android.music.net.NetworkMonitor; callingUser = 0; userId(target) = 0
,03-15 19:11:41.504  4787  4787 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-15 19:11:41.504  4787  4787 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,03-15 19:11:41.504  1018  4306 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:41.504  1018  4306 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:41.504  1018  4306 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.music:main, destAppInfo.processName = com.google.android.music:main
,03-15 19:11:41.524  4787  4787 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-15 19:11:41.524  4787  4787 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-15 19:11:41.534  4787  4787 E SysUtils: ApplicationContext is null in ApplicationStatus
,03-15 19:11:41.554  4787  4787 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,03-15 19:11:41.554  4787  4787 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
,03-15 19:11:41.554  4787  4787 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,03-15 19:11:41.564  4787  4787 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
03-15 19:11:41.564  4787  4787 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
03-15 19:11:41.564  4787  4787 I Adreno-EGL: Build Date: 04/06/15 Mon
03-15 19:11:41.564  4787  4787 I Adreno-EGL: Local Branch: 
03-15 19:11:41.564  4787  4787 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
03-15 19:11:41.564  4787  4787 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
03-15 19:11:41.564  4787  4787 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,03-15 19:11:41.604  1018  1504 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,03-15 19:11:41.604  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:41.604  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:41.604  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:41.604  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:41.624  4863  4863 E Zygote  : MountEmulatedStorage(),
03-15 19:11:41.624  4863  4863 E Zygote  : v2
03-15 19:11:41.624  4863  4863 I libpersona: KNOX_SDCARD checking this for 1000
03-15 19:11:41.624  4863  4863 I libpersona: KNOX_SDCARD not a persona
,03-15 19:11:41.624  4863  4863 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-15 19:11:41.624  4863  4863 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-15 19:11:41.624  4863  4863 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-15 19:11:41.624  1018  1504 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=4863 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-15 19:11:41.644  4863  4863 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:41.644  4863  4863 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:41.664  4787  4871 W AudioManagerAndroid: Requires BLUETOOTH permission
,03-15 19:11:41.664  4787  4787 I NSApplication: Starting up...
,03-15 19:11:41.684  1018  1337 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.plus, hostingType: broadcast
,03-15 19:11:41.684  1018  1337 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:41.684  1018  1337 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:41.684  1018  1337 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:41.684  1018  1337 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:41.694  4884  4884 E Zygote  : MountEmulatedStorage()
,03-15 19:11:41.694  4884  4884 E Zygote  : v2
03-15 19:11:41.694  4884  4884 I libpersona: KNOX_SDCARD checking this for 10120
03-15 19:11:41.694  4884  4884 I libpersona: KNOX_SDCARD not a persona
,03-15 19:11:41.694  4884  4884 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-15 19:11:41.704  1018  1337 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=4884 uid=10120 gids={50120, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,03-15 19:11:41.704  4884  4884 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-15 19:11:41.704  4884  4884 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
03-15 19:11:41.704  1018  1337 I ActivityManager: Killing 4180:com.sec.knox.foldercontainer/1000 (adj 15): empty #31
,03-15 19:11:41.704  1018  1337 I ActivityManager: Killing 4148:com.samsung.helphub/1000 (adj 15): empty #32
03-15 19:11:41.704  1018  1337 I ActivityManager: Killing 3890:com.android.vending/u0a28 (adj 15): empty #33
,03-15 19:11:41.724  4884  4884 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:41.734  4884  4884 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:41.744  4863  4863 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(372/llIlIIIIlIIIIIlIlIII)] 
,03-15 19:11:41.754  4884  4884 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-15 19:11:41.774  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_4148/cgroup.procs: No such file or directory
03-15 19:11:41.774  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_4180/cgroup.procs: No such file or directory
03-15 19:11:41.774  1018  1043 W libprocessgroup: failed to open /acct/uid_10028/pid_3890/cgroup.procs: No such file or directory
,03-15 19:11:41.904  4863  4863 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(59/onCreate)] nStatus : 0
,03-15 19:11:41.924  4863  4863 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(76/onCreate)] DiagMon DM Application Start !
,03-15 19:11:41.924  4863  4863 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(39/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,03-15 19:11:41.924  4863  4863 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(40/llIIIIlllllIIllIIllI)] Receive broadcast:
03-15 19:11:41.924  4863  4863 I DIAGMON_AGENT: ./extraInfo: "NG700"
,03-15 19:11:41.924  4863  4863 I DIAGMON_AGENT: [lllIIIIlIIlIlllIlIIl(54/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,03-15 19:11:42.014  4312  4769 I SA      : [RC New] Execute method=[GET] start
,03-15 19:11:42.014  1018  1031 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,03-15 19:11:42.014  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:42.024  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:42.024  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:42.024  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:42.034  4904  4904 E Zygote  : MountEmulatedStorage()
03-15 19:11:42.034  4904  4904 I libpersona: KNOX_SDCARD checking this for 10009
03-15 19:11:42.034  4904  4904 E Zygote  : v2
03-15 19:11:42.034  4904  4904 I libpersona: KNOX_SDCARD not a persona
03-15 19:11:42.034  4771  4771 D InitializeManagerStateMachine: exit::SUCCESS
03-15 19:11:42.034  1018  1031 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=4904 uid=10009 gids={50009, 9997, 3003, 1028, 1015} abi=armeabi-v7a
03-15 19:11:42.034  4771  4771 D InitializeManagerStateMachine: entry::IDLE
03-15 19:11:42.034  4904  4904 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-15 19:11:42.034  4904  4904 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-15 19:11:42.034  4904  4904 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,03-15 19:11:42.044  4312  4769 I SA      : [RC New] Security=[true],
03-15 19:11:42.044  4312  4769 I System.out: Thread-640(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
03-15 19:11:42.044  4312  4769 I System.out: Thread-640(ApacheHTTPLog):isSBSettingEnabled false
,03-15 19:11:42.044  4312  4769 I System.out: Thread-640(ApacheHTTPLog):isShipBuild true
03-15 19:11:42.044  4312  4769 I System.out: Thread-640(ApacheHTTPLog):SMARTBONDING_ENABLED is false
03-15 19:11:42.044  4312  4769 I System.out: Thread-640(ApacheHTTPLog):SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,03-15 19:11:42.054   277   951 D EnterpriseController: uids 10041
03-15 19:11:42.054   277   951 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-15 19:11:42.054   277   951 D Netd    : getNetworkForDns: using netid 502 for uid 10041
,03-15 19:11:42.054   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-15 19:11:42.064  4771  4914 I System.out: (HTTPLog)-Static: SBServiceAPI: getService class android.os.ServiceManager
03-15 19:11:42.064  4771  4914 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
03-15 19:11:42.064  4771  4914 I System.out: (HTTPLog)-Static: isShipBuild true
03-15 19:11:42.064  4771  4914 I System.out: (HTTPLog)-Thread-748-846988468: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
03-15 19:11:42.064  4771  4914 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,03-15 19:11:42.064   277   951 D EnterpriseController: uids 10010
03-15 19:11:42.064   277   951 D EnterpriseController: mIsMarkChainAdded is 18 mIsBlockChainAdded is 252 netId is 0
03-15 19:11:42.064   277   951 D Netd    : getNetworkForDns: using netid 502 for uid 10010
,03-15 19:11:42.064  4904  4904 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 19:11:42.064  4904  4904 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:42.134  4377  4377 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,03-15 19:11:42.144  4377  4377 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
03-15 19:11:42.144  4377  4377 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,03-15 19:11:42.144  4771  4914 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,03-15 19:11:42.154  4771  4914 I qtaguid : Tagging socket 26 with tag 79a327ee00000000{2040735726,0} for uid -1, pid: 4771, getuid(): 10010
,03-15 19:11:42.154  4904  4904 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
,03-15 19:11:42.164  1018  1337 D RCPManagerService: exchangeData() failure , invalid userId
,03-15 19:11:42.164  4904  4904 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(93/onReceive)] Auto update settings is activated
,03-15 19:11:42.164  4904  4904 I FOTA_Client: [IlIlIIllllIllIIIIIll(81/llllIIIllIlIIIIllllI)] Polling time is vaild
03-15 19:11:42.164  1018  1952 D RCPManagerService: exchangeData() failure , invalid userId
,03-15 19:11:42.164  1018  1705 I ActivityManager: Killing 4215:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): empty #31
,03-15 19:11:42.164  4904  4904 W FOTA_Client: [lIllIlIIlIIlllllIIll(98/llllIIIllIlIIIIllllI)] No file exists in Directory
,03-15 19:11:42.164  1018  1031 I splitIntent: Queue : background intent android.net.conn.CONNECTIVITY_CHANGE is finished at BG and BG split queue. set mSplitStart  false.
,03-15 19:11:42.174  1018  1031 I ActivityManager: Killing 4236:com.google.android.apps.maps/u0a107 (adj 15): empty #31
,03-15 19:11:42.174  1018  1018 I splitIntent: Split this intent : android.intent.action.TIME_SET, mSplitNum[0]=7, mSplitNum[1]=13, mSplitNum[2]=18, mBgSplitQueueNum=3 divideNum= 5 r.nextReceiver= 1 receivers.size=24
03-15 19:11:42.174  1018  1018 I splitIntent: finish to split intent : android.intent.action.TIME_SET !! Enqueue -> schedule it!!
,03-15 19:11:42.174  1018  1044 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,03-15 19:11:42.184  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:42.184  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:42.184  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:42.184  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:42.194  1018  1044 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=4932 uid=10062 gids={50062, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 19:11:42.194  4932  4932 E Zygote  : MountEmulatedStorage()
03-15 19:11:42.194  4932  4932 E Zygote  : v2
03-15 19:11:42.194  4932  4932 I libpersona: KNOX_SDCARD checking this for 10062
03-15 19:11:42.194  4932  4932 I libpersona: KNOX_SDCARD not a persona
,03-15 19:11:42.204  4932  4932 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-15 19:11:42.204  4932  4932 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-15 19:11:42.204  4932  4932 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 19:11:42.204  1018  1518 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
03-15 19:11:42.204  1018  1518 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:42.204  1018  1518 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
03-15 19:11:42.204  1018  1518 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:42.204  4904  4904 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
03-15 19:11:42.204  1018  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-15 19:11:42.214  1323  1323 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,03-15 19:11:42.214  1323  1323 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,03-15 19:11:42.214  1323  1323 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-15 19:11:42.214  1323  1323 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,03-15 19:11:42.224  4904  4904 I FOTA_Client: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
03-15 19:11:42.224  1323  1323 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,03-15 19:11:42.224  1323  1323 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,03-15 19:11:42.224  1323  1323 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-15 19:11:42.224  1323  1323 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
,03-15 19:11:42.224  1323  1323 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
03-15 19:11:42.224  1323  1323 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
03-15 19:11:42.224  1323  1323 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,03-15 19:11:42.224  1323  1323 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,03-15 19:11:42.224  1323  1323 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,03-15 19:11:42.234  1018  1129 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,03-15 19:11:42.234  1323  1323 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
03-15 19:11:42.234  1323  1323 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
03-15 19:11:42.234  1018  1129 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
03-15 19:11:42.234  1323  1323 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,03-15 19:11:42.234  1018  1129 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:42.234  1018  1129 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:42.234  1018  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,03-15 19:11:42.234  4932  4932 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:42.234  1323  1323 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
03-15 19:11:42.234  4932  4932 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:42.234  3759  3759 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Tue Mar 15 19:11:42 GMT+01:00 2016
,03-15 19:11:42.244  1018  1043 W libprocessgroup: failed to open /acct/uid_10107/pid_4236/cgroup.procs: No such file or directory
,03-15 19:11:42.244  4592  4592 D SecurityLogAgent: KnoxConfiguration : Current State = 1
03-15 19:11:42.244  4592  4592 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
03-15 19:11:42.244  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_4215/cgroup.procs: No such file or directory
03-15 19:11:42.244  4592  4592 D SecurityLogAgent: StateMachine : Current State = 1
,03-15 19:11:42.244  1323  1323 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,03-15 19:11:42.244  1018  4306 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
03-15 19:11:42.244  1018  4306 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,03-15 19:11:42.254  1018  4306 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:42.254  1018  4306 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:42.254  1018  4306 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,03-15 19:11:42.254  1018  1705 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,03-15 19:11:42.254  3759  3759 I KLMS-2.5.183: : KLMSAbstractReciever(): onReceive().END.
03-15 19:11:42.254  1323  1323 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
03-15 19:11:42.254  1323  1323 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,03-15 19:11:42.254  1018  1705 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:42.254  1018  1705 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:42.254  1018  1705 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:42.254  1018  1705 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:42.264  3759  3759 I KLMS-2.5.183: : KLMSIntentService(): onCreate()
,03-15 19:11:42.264  3759  3759 I KLMS-2.5.183: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,03-15 19:11:42.264  4951  4951 E Zygote  : MountEmulatedStorage()
,03-15 19:11:42.264  4951  4951 E Zygote  : v2
03-15 19:11:42.264  4951  4951 I libpersona: KNOX_SDCARD checking this for 10157
03-15 19:11:42.264  4951  4951 I libpersona: KNOX_SDCARD not a persona
,03-15 19:11:42.274  4951  4951 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-15 19:11:42.274  3759  3759 I KLMS-2.5.183: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,03-15 19:11:42.274  4951  4951 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-15 19:11:42.274  4951  4951 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 19:11:42.284  1018  1705 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=4951 uid=10157 gids={50157, 9997} abi=armeabi-v7a
03-15 19:11:42.284  3759  4950 I KLMS-2.5.183: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
,03-15 19:11:42.284  3759  4950 I KLMS-2.5.183: : KLMSIntentService(): TIME_CHANGED
,03-15 19:11:42.294  4312  4312 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
03-15 19:11:42.294  1018  1346 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
03-15 19:11:42.294  3759  4950 I KLMS-2.5.183: : StateImplV2(): dateTimeChanged().START : Tue Mar 15 19:11:42 GMT+01:00 2016
03-15 19:11:42.294  1018  1346 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
,03-15 19:11:42.294  1018  1346 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:42.294  1018  1346 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:42.294  1018  1346 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:42.304  4932  4932 I ExternalOEMControlProvider: onCreate
03-15 19:11:42.304  1181  1181 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700" emergencyOnly=false combinedLabel="NG700" mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f02056d/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014f/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020537/com.android.systemui:drawable/stat_sys_signal_inout mBluetoothTetherIconId=0x7f02054a/com.android.systemui:drawable/stat_sys_tether_bluetooth
03-15 19:11:42.304  1181  1181 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
03-15 19:11:42.304  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 19:11:42.304  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 19:11:42.304  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
03-15 19:11:42.304  1181  1181 D StatusBar.NetworkController: refreshNwBoosterIndicator - setNWBoosterIndicators(false)
,03-15 19:11:42.304   308   308 I art     : Explicit concurrent mark sweep GC freed 8701(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 656us total 28.224ms
,03-15 19:11:42.314  3759  4950 I KLMS-2.5.183: : StateImplV2(): dateTimeChanged().END
,03-15 19:11:42.314  1018  4306 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sm, hostingType: broadcast
,03-15 19:11:42.314  1018  4306 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:42.314  1018  4306 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:42.314  1018  4306 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:42.314  1018  4306 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:42.324  4951  4951 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 19:11:42.324  4951  4951 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:42.324  3759  3759 I KLMS-2.5.183: : KLMSIntentService(): onDestroy()
,03-15 19:11:42.324   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 627us total 17.437ms
03-15 19:11:42.324  4771  4914 I qtaguid : Untagging socket 26
,03-15 19:11:42.334  1018  1097 V AlarmManager: waitForAlarm result :4
,03-15 19:11:42.344  4771  4771 D hcjo    : AutoUpdateTriggerManager:REQUEST2:setInterval:345600000
,03-15 19:11:42.344   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 605us total 16.791ms,
,03-15 19:11:42.354  4967  4967 E Zygote  : MountEmulatedStorage(),
03-15 19:11:42.354  4967  4967 E Zygote  : v2
,03-15 19:11:42.354  4967  4967 I libpersona: KNOX_SDCARD checking this for 1000
,03-15 19:11:42.354  1018  4306 I ActivityManager: Start proc com.samsung.android.sm for broadcast com.samsung.android.sm/.contextagent.ContextAgentReceiver: pid=4967 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a,
03-15 19:11:42.354  4967  4967 I libpersona: KNOX_SDCARD not a persona
03-15 19:11:42.364  4967  4967 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-15 19:11:42.364  4967  4967 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-15 19:11:42.364  4967  4967 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,03-15 19:11:42.374  4932  4966 I  Time Manager : Time Difference not stored. TIME_DIFFERENCE
,03-15 19:11:42.374  1018  4306 D ActivityManager: startProcessLocked calleePkgName: com.android.mms, hostingType: broadcast
,03-15 19:11:42.374  1018  4306 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:42.374  1018  4306 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:42.374  1018  4306 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:42.374  1018  4306 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:42.374  4771  4771 D hcjo    : AutoUpdateTriggerManager:REQUEST2:notifyTimedOutAndWriteUpdateCheckedTime
03-15 19:11:42.374  4771  4771 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onUpdateTime
03-15 19:11:42.374  4771  4771 D hcjo    : SelfUpdateManager:IDLE:execute
,03-15 19:11:42.384  4951  4951 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-15 19:11:42.384  4967  4967 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:42.394  4967  4967 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:42.394  4982  4982 E Zygote  : MountEmulatedStorage()
,03-15 19:11:42.394  4982  4982 E Zygote  : v2
03-15 19:11:42.394  4982  4982 I libpersona: KNOX_SDCARD checking this for 10046
03-15 19:11:42.394  4982  4982 I libpersona: KNOX_SDCARD not a persona
,03-15 19:11:42.394  4982  4982 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-15 19:11:42.394  4982  4982 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-15 19:11:42.394  4982  4982 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-15 19:11:42.394  1018  4306 I ActivityManager: Start proc com.android.mms for broadcast com.android.mms/.transaction.MessagingNotification: pid=4982 uid=10046 gids={50046, 9997, 3003, 1028, 1015, 1023, 1003} abi=armeabi-v7a
,03-15 19:11:42.404  4771  4771 D hcjo    : SelfUpdateManager:CONDITION_CHECK:onUpdateCondition
,03-15 19:11:42.414  1018  1504 D ActivityManager: startProcessLocked calleePkgName: com.qualcomm.timeservice, hostingType: broadcast
03-15 19:11:42.414  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:42.414  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:42.414  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:42.414  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:42.414  4967  4967 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-15 19:11:42.424  4982  4982 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:42.424  4982  4982 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:42.424  4995  4995 E Zygote  : MountEmulatedStorage()
03-15 19:11:42.424  4995  4995 I libpersona: KNOX_SDCARD checking this for 1000
03-15 19:11:42.424  4995  4995 E Zygote  : v2
03-15 19:11:42.424  4995  4995 I libpersona: KNOX_SDCARD not a persona
,03-15 19:11:42.434  4995  4995 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-15 19:11:42.434  4995  4995 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-15 19:11:42.434  4995  4995 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
03-15 19:11:42.434  1018  1504 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=4995 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
03-15 19:11:42.434  4771  4771 I Volley  : RestApi Request Add : 2346
03-15 19:11:42.434  4771  4912 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
03-15 19:11:42.434  4771  4912 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
03-15 19:11:42.434  4771  4912 I qtaguid : Tagging socket 28 with tag 79a327ee00000000{2040735726,0} for uid -1, pid: 4771, getuid(): 10010,
,03-15 19:11:42.454  1018  1705 I ActivityManager: Killing 4333:com.sec.android.app.mt/1000 (adj 15): empty #31
,03-15 19:11:42.454  1018  1518 I ActivityManager: Killing 3938:com.test.thalitest/u0a155 (adj 15): empty #31
,03-15 19:11:42.454  1018  4423 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,03-15 19:11:42.454  1018  4423 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
,03-15 19:11:42.464  1018  4423 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:42.464  1018  4423 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:42.464  1018  4423 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:42.474  4995  4995 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:42.474  4995  4995 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:42.474  4982  4982 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
03-15 19:11:42.474  4982  4982 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 19:11:42.474  4982  4982 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-15 19:11:42.474  4982  4982 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-15 19:11:42.474  4982  4982 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
03-15 19:11:42.474  4982  4982 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,03-15 19:11:42.504  1759  1759 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,03-15 19:11:42.504  1759  1759 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,03-15 19:11:42.504  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,03-15 19:11:42.504  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:42.504  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:42.504  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:42.504  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:42.524  4995  4995 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1458065502534
03-15 19:11:42.524  4995  4995 D         : TimeServiceNative: User Time to be set is 1458065502535
03-15 19:11:42.524  4995  4995 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
03-15 19:11:42.524  4995  4995 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
03-15 19:11:42.524  4995  4995 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1458065502535
03-15 19:11:42.524  5013  5013 E Zygote  : MountEmulatedStorage()
03-15 19:11:42.524  5013  5013 E Zygote  : v2
03-15 19:11:42.524  5013  5013 I libpersona: KNOX_SDCARD checking this for 10085
03-15 19:11:42.524  4995  4995 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
03-15 19:11:42.524  5013  5013 I libpersona: KNOX_SDCARD not a persona
03-15 19:11:42.524   318   557 D QC-time-services: Daemon: Connection accepted:time_genoff
03-15 19:11:42.524  5013  5013 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38,
03-15 19:11:42.524   318  5018 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1458065502535
03-15 19:11:42.524   318  5018 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1458065502535, operation = 0
03-15 19:11:42.524   318  5018 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS8/14/70 16:16:58
03-15 19:11:42.524   318  5018 D QC-time-services: Daemon:Value read from RTC seconds = 22177018000
03-15 19:11:42.524   318  5018 D QC-time-services: Daemon:new time 1458065502535 ,
03-15 19:11:42.524   318  5018 D QC-time-services: Daemon: delta 1435888484535 genoff 1435888484535 
03-15 19:11:42.524   318  5018 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1435888484535 to memory
03-15 19:11:42.524   318  5018 D QC-time-services: Daemon:Opening File: /data/time/ats_2,
03-15 19:11:42.524   318  5018 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
03-15 19:11:42.524  1018  1031 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=5013 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,03-15 19:11:42.534  5013  5013 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
,03-15 19:11:42.534  4982  4982 D Mms/MmsApp: [start]    onCreate() consume time = 0.0
03-15 19:11:42.534  5013  5013 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 19:11:42.554   318  5018 D QC-time-services: Updating the TOD offset
03-15 19:11:42.554   318  5018 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1435888484535 to memory
03-15 19:11:42.554   318  5018 D QC-time-services: Daemon:Opening File: /data/time/ats_1
03-15 19:11:42.554   318  5018 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,03-15 19:11:42.554  5013  5013 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:42.554   318  5018 E QC-time-services: Daemon:Update to modem bit set
03-15 19:11:42.554   318  5018 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
03-15 19:11:42.554   318  5018 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1119923684535
,03-15 19:11:42.554  4995  4995 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
03-15 19:11:42.554  5013  5013 D ActivityThread: Added TimaKeyStore provider
03-15 19:11:42.554  1018  1744 I ActivityManager: Killing 4415:com.sec.android.app.sbrowser/u0a131 (adj 15): empty #31
,03-15 19:11:42.564   318   555 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,03-15 19:11:42.564   318   557 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,03-15 19:11:42.564  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_4333/cgroup.procs: No such file or directory
,03-15 19:11:42.574  1018  1043 W libprocessgroup: failed to open /acct/uid_10155/pid_3938/cgroup.procs: No such file or directory
,03-15 19:11:42.574  1018  1518 I ActivityManager: Killing 4476:com.sec.android.app.camera/u0a139 (adj 15): empty #31
,03-15 19:11:42.574  1931  1931 I ConfigService: onDestroy
,03-15 19:11:42.584  5013  5013 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.,
03-15 19:11:42.584  5013  5013 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
03-15 19:11:42.584  5013  5013 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-15 19:11:42.584  5013  5013 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
03-15 19:11:42.584  5013  5013 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
03-15 19:11:42.584  5013  5013 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.,
,03-15 19:11:42.644  1018  4306 D SettingsProvider: name = next_alarm_formatted
,03-15 19:11:42.644  1018  4306 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
03-15 19:11:42.644  1018  4306 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
03-15 19:11:42.644  1018  4306 D SettingsProvider: selectionArgs: false
03-15 19:11:42.644  1018  4306 D SettingsProvider: selectionArgs: 10085
,03-15 19:11:42.644  1018  4306 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,03-15 19:11:42.644  1018  4306 D SettingsProvider: ret = -1
,03-15 19:11:42.644  1018  1266 I art     : Explicit concurrent mark sweep GC freed 19308(1101KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 29MB/44MB, paused 2.622ms total 158.172ms
,03-15 19:11:42.664  1018  1031 I ActivityManager: Killing 4521:com.sec.android.provider.badge/u0a72 (adj 15): empty #31
,03-15 19:11:42.694  1018  1043 W libprocessgroup: failed to open /acct/uid_10131/pid_4415/cgroup.procs: No such file or directory
03-15 19:11:42.694  1018  1043 W libprocessgroup: failed to open /acct/uid_10139/pid_4476/cgroup.procs: No such file or directory
,03-15 19:11:42.704  4982  4982 W art     : Verification of com.android.mms.ui.MsgSweepActionListView com.android.mms.ArtClassLoader.createMsgSweepActionList(android.content.Context) took 115.540ms
,03-15 19:11:42.744  1018  1043 W libprocessgroup: failed to open /acct/uid_10072/pid_4521/cgroup.procs: No such file or directory
,03-15 19:11:42.754  5013  5013 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 102.815ms
,03-15 19:11:42.774  4982  5029 D Mms/ArtClassLoader: init before art
,03-15 19:11:42.774  4982  4982 D Mms/TelephonyPermission: start operation mode monitor
,03-15 19:11:42.784  4982  4982 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,03-15 19:11:42.784  4982  4982 D Mms/TelephonyPermission: DefaultSmsApp is com.android.mms
03-15 19:11:42.784  4982  4982 D Mms/TelephonyPermission: isDefault true
,03-15 19:11:42.784  4982  4982 D Mms/MmsApp: onCreate() com.android.mms
,03-15 19:11:42.844  1018  1129 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,03-15 19:11:42.844  1018  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:42.844  1018  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:42.854  1018  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:42.854  1018  1129 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:42.854  1018  1053 D PowerManagerService: [s] UserActivityState : 2 -> 4
,03-15 19:11:42.854  1018  1053 I PowerManagerService: [PWL] On : 0 (54382 ms ago)
,03-15 19:11:42.854  1018  1053 I PowerManagerService: [PWL]  mStayOn: false  mWakeLockSummary & WAKE_LOCK_STAY_AWAKE: 20  mUserActivitySummary: 0x4
,03-15 19:11:42.854  1018  1053 I PowerManagerService: [PWL]  SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=1018, ws=WorkSource{10054}) (elapsedTime=2677)
,03-15 19:11:42.864  5030  5030 E Zygote  : MountEmulatedStorage()
,03-15 19:11:42.864  5030  5030 E Zygote  : v2
03-15 19:11:42.864  5030  5030 I libpersona: KNOX_SDCARD checking this for 10094
03-15 19:11:42.864  5030  5030 I libpersona: KNOX_SDCARD not a persona
,03-15 19:11:42.864  5030  5030 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-15 19:11:42.864  1018  1129 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=5030 uid=10094 gids={50094, 9997, 3003} abi=armeabi-v7a
,03-15 19:11:42.874  1018  1129 I ActivityManager: Killing 4563:com.sec.android.app.SecSetupWizard/1000 (adj 15): empty #31
03-15 19:11:42.874  5030  5030 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-15 19:11:42.874  5030  5030 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 19:11:42.894  5030  5030 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:42.894  5030  5030 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:42.904  4312  4769 I SA      : [RC New] [v2liruge] api execute + 857
,03-15 19:11:42.904  4312  4769 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,03-15 19:11:42.904  4312  4769 I System.out: AsyncTask #1 calls detatch()
,03-15 19:11:42.914  4312  4769 I SA      : [ODM] saveOpenData( GEO_IP, PL )
,03-15 19:11:42.914  5030  5030 D elm:15183: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,03-15 19:11:42.914  5030  5030 D elm:15183: ELMEngine.ELMEngine( context ).
,03-15 19:11:42.914  5030  5030 D elm:15183: MDMBridge.setEnterpriseBridge()
,03-15 19:11:42.914  4312  4769 I SA      : [OCP] update openData : PL
,03-15 19:11:42.924  1018  4306 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
03-15 19:11:42.924  1018  4306 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
03-15 19:11:42.924  1018  4306 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:42.924  1018  4306 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,03-15 19:11:42.924  1018  4306 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
,03-15 19:11:42.924  5030  5030 D elm:15183: ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,03-15 19:11:42.924  4312  4769 I SA      : [TPMU] getNetworkMcc : 
,03-15 19:11:42.924  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
03-15 19:11:42.924  4312  4769 I SA      : [SCU] saveMccToPreferece Start
03-15 19:11:42.924  4312  4769 I SA      : [SCU] RegionMCC : 260
03-15 19:11:42.924  4312  4769 I SA      : [SSP] query invoked
,03-15 19:11:42.924  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:42.924  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:42.924  4312  4769 I SA      : [TPMU] GetMccFromDB : null
03-15 19:11:42.924  4312  4769 I SA      : [SCU] getMccFromPreferece mcc = 260
,03-15 19:11:42.924  4312  4769 I SA      : [SCU] saveMccToPreferece End
03-15 19:11:42.924  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:42.924  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:42.924  4312  4769 I SA      : [RC New] executeRequest [v2liruge] end. 919
03-15 19:11:42.924  4312  4769 I SA      : [RC New] Execute end
03-15 19:11:42.924  4312  4312 I SA      : [OR] GetMyCountryZoneTask mcc = 260
03-15 19:11:42.924  4312  4312 I SA      : [OR] GetMyCountryZoneTask Success
,03-15 19:11:42.934  5030  5030 D elm:15183: ElmAgentService : onCreate()
,03-15 19:11:42.934  5030  5045 D elm:15183: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,03-15 19:11:42.944  5030  5045 D elm:15183: ELMAgentService.listeningToTimeDateChanges( context, intent ).
03-15 19:11:42.944  5047  5047 I libpersona: KNOX_SDCARD checking this for 10134
03-15 19:11:42.944  5047  5047 E Zygote  : MountEmulatedStorage()
03-15 19:11:42.944  5047  5047 I libpersona: KNOX_SDCARD not a persona
03-15 19:11:42.944  5047  5047 E Zygote  : v2
03-15 19:11:42.944  1018  1031 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=5047 uid=10134 gids={50134, 9997} abi=armeabi-v7a
03-15 19:11:42.944  5030  5030 D elm:15183: ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
03-15 19:11:42.944  1018  1744 I ActivityManager: Killing 4633:com.samsung.android.app.FileShareClient/u0a68 (adj 15): empty #31
03-15 19:11:42.944  5030  5030 D elm:15183: ModuleBase.ModifySetAlarm()
03-15 19:11:42.944  5030  5030 D elm:15183: MDMBridge.getInstance()
03-15 19:11:42.944  5030  5030 D elm:15183: MDMBridge.getAllLicenseInfoFromSDK()
03-15 19:11:42.944  5047  5047 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
03-15 19:11:42.944  5047  5047 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-15 19:11:42.944  5030  5030 D elm:15183: ElmAgentService : onDestroy().
03-15 19:11:42.944  5047  5047 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,03-15 19:11:42.964  5047  5047 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:42.964  5047  5047 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:42.974  5047  5047 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,03-15 19:11:42.974  5047  5047 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,03-15 19:11:42.994  1018  4423 I ActivityManager: Killing 4650:com.samsung.android.app.FileShareServer/u0a69 (adj 15): empty #31
,03-15 19:11:43.034  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_4563/cgroup.procs: No such file or directory
,03-15 19:11:43.054   316   316 I ServiceManager: Waiting for service AtCmdFwd...
,03-15 19:11:43.084  4982  4982 D Mms/MmsApp: [start]    initCountryIso consume time = 556.394426
,03-15 19:11:43.094  1018  1030 D CountryDetector: The first listener is added
,03-15 19:11:43.094  4982  4982 D Mms/MmsApp: [end]    initCountryIso consume time = 6.700417
,03-15 19:11:43.094  4982  4982 D Mms/MmsConfig: [start]    MmsConfig.init() consume time = 0.646667
,03-15 19:11:43.094  1018  1043 W libprocessgroup: failed to open /acct/uid_10068/pid_4633/cgroup.procs: No such file or directory
03-15 19:11:43.094  1018  1043 W libprocessgroup: failed to open /acct/uid_10069/pid_4650/cgroup.procs: No such file or directory
,03-15 19:11:43.104  4982  4982 D Mms/MmsConfig: before partial update
,03-15 19:11:43.124  4982  4982 D Mms/MmsConfig: Load Resize quality : 80
,03-15 19:11:43.124  4982  4982 D EasySignUpManager_1.0.1: serviceId : 1, features : -1
,03-15 19:11:43.124  4982  4982 D EasySignUpManager_1.0.1: isAuth is false
03-15 19:11:43.124  4982  4982 D Mms/MmsConfig: setFreeMessageEnabled, getSupportedFeatures = -1 isAuth = false
,03-15 19:11:43.134  1484  1498 D TP/MmsSmsProvider: query,matched:2117, calling pid = 4982
,03-15 19:11:43.134  1484  1498 D TP/MmsSmsProvider: match 2117:Elapsed time : 1.715 ms
,03-15 19:11:43.134  4982  4982 D EasySignUpManager_1.0.1: isAuth is false
,03-15 19:11:43.154  4982  4982 D EasySignUpManager_1.0.1: getServiceStatus : serviceId (1) is OFF
03-15 19:11:43.154  4982  4982 E CscParser: mps_code.dat does not exist
03-15 19:11:43.154  4982  4982 E CscParser: customer_path =/system/csc/customer.xml
03-15 19:11:43.154  4982  4982 E CscParser: fileName + /system/csc/customer.xml
03-15 19:11:43.154  4982  4982 E CscParser: mps_code.dat does not exist
03-15 19:11:43.154  4982  4982 E CscParser: customer_path =/system/csc/customer.xml
03-15 19:11:43.154  4982  4982 E CscParser: fileName + /system/csc/customer.xml
,03-15 19:11:43.174  4982  4982 D CscParser: getInstance fileName =/system/csc/customer.xml
,03-15 19:11:43.174  4982  4982 D Mms/MmsConfig:  enable multiwindow = true
,03-15 19:11:43.174  4982  4982 E Mms/MessageUtils: setCountryDetector : update country detector info 
03-15 19:11:43.174  4982  4982 E Mms/MessageUtils: updateCountryIso : update country iso info 
,03-15 19:11:43.184  4982  4982 D Mms/MmsConfig: [end]    init() consume time = 86.629218
,03-15 19:11:43.184  4982  4982 D Mms/Contact: [start]    init() consume time = 0.77073
,03-15 19:11:43.194  1484  1502 D TP/MmsSmsProvider: query,matched:13, calling pid = 4982
,03-15 19:11:43.194  1484  1502 D TP/MmsSmsProvider: match 13:Elapsed time : 2.326 ms
,03-15 19:11:43.194  4982  4982 D Mms/Contact: [end]    init consume time = 13.778698
,03-15 19:11:43.204  4771  4912 I qtaguid : Untagging socket -1
,03-15 19:11:43.204  4771  4912 I qtaguid : Failed write_ctrl(u -1) res=-1 errno=9
03-15 19:11:43.204  4771  4912 I qtaguid : Untagging socket -1 failed errno=-9
03-15 19:11:43.204  4771  4912 W NetworkManagementSocketTagger: untagSocket(-1) failed with errno -9
,03-15 19:11:43.204  4771  4771 D hcjo    : SelfUpdateManager:REQUEST_UPD_CHECK:onUpdateCheckSuccessAndNoNeedUpdate
,03-15 19:11:43.204  4771  4771 D hcjo    : AutoUpdateManager:CHECK_SELF_UPD:onSelfUpdateResult:T
,03-15 19:11:43.204  4771  4771 D hcjo    : SellerAppAutoUpdate:clearFlag
,03-15 19:11:43.214  4771  4771 D SellerAppAutoUpdateManagerStateMachine: execute::IDLE:EXECUTE
,03-15 19:11:43.214  4771  4771 D SellerAppAutoUpdateManagerStateMachine: exit::IDLE
03-15 19:11:43.214  4771  4771 D SellerAppAutoUpdateManagerStateMachine: entry::TOKENCHECK
,03-15 19:11:43.214  4982  5068 D Mms/DraftCache: [start]    rebuildCache consume time = 17.54052
,03-15 19:11:43.214  4982  5029 D Mms/ArtClassLoader: init [DONE] art
03-15 19:11:43.214  4982  4982 D Mms/MethodReflector: getSubId is called
03-15 19:11:43.214  4982  4982 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,03-15 19:11:43.214  1484  1498 D TP/MmsSmsProvider: query,matched:12, calling pid = 4982
,03-15 19:11:43.214  4982  4982 D Mms/MethodReflector: getTelephonyProperty is called
03-15 19:11:43.214  1484  1498 D TP/MmsSmsProvider: match 12:Elapsed time : 1.499 ms
03-15 19:11:43.214  4982  4982 D Mms/DownloadManager: roaming -> false (slotId = 0)
03-15 19:11:43.214  4982  4982 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
03-15 19:11:43.224  4982  4982 D Mms/DownloadManager: auto download without roaming -> true
03-15 19:11:43.224  4982  4982 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
03-15 19:11:43.224  4982  4982 D Mms/MethodReflector: getSubId is called
,03-15 19:11:43.224  4982  4982 D Mms/MethodReflector: getDefaultSmsSubId is called
03-15 19:11:43.224  4982  4982 E Mms/TelephonyUtils: subID is null or 0 length, so get DefaultSubId!!
03-15 19:11:43.224  4982  4982 D Mms/TelephonyUtils: getLongSubId from simSlot 1, return Value = -1000
03-15 19:11:43.224  4982  4982 D Mms/MethodReflector: getTelephonyProperty is called
03-15 19:11:43.224  4982  4982 D Mms/DownloadManager: roaming -> false (slotId = 1)
03-15 19:11:43.224  4982  4982 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 1
03-15 19:11:43.224  4982  4982 D Mms/DownloadManager: auto download without roaming -> true
03-15 19:11:43.224  4982  4982 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAutoSecondary : false, roaming : false
03-15 19:11:43.224  4982  4982 D Mms/DownloadManager: auto download during roaming secondary -> false
03-15 19:11:43.224  4982  4982 D Mms/DownloadManager: mAutoDownload ------> true
,03-15 19:11:43.224  4771  4771 D SellerAppAutoUpdateManagerStateMachine: execute::TOKENCHECK:TOKEN_RECEIVED
,03-15 19:11:43.224  4771  4771 D SellerAppAutoUpdateManagerStateMachine: exit::TOKENCHECK
03-15 19:11:43.224  4771  4771 D SellerAppAutoUpdateManagerStateMachine: entry::FAILED
03-15 19:11:43.224  4771  4771 D hcjo    : AutoUpdateManager:SELLER_UPD:onSellerAutoUpdateFailed
03-15 19:11:43.224  4771  4771 D SellerAppAutoUpdateManagerStateMachine: exit::FAILED
,03-15 19:11:43.224  4771  4771 D SellerAppAutoUpdateManagerStateMachine: entry::IDLE
03-15 19:11:43.224  4982  5068 D Mms/DraftCache: [end]    rebuildCache consume time = 10.86875
,03-15 19:11:43.234  1018  1744 I ActivityManager: Killing 4694:com.sec.pcw.device/1000 (adj 15): empty #31
,03-15 19:11:43.254  4982  4982 D ComposerPerformance: 1458065503268 ms / [DONE] Composer constructor
,03-15 19:11:43.254  4982  4982 E CII     : CommonIMSInterface: VoLTE CSC feature disabled.
,03-15 19:11:43.254  4982  4982 I Mms/ReservationManager: ReservationManager()
,03-15 19:11:43.254  4982  4982 I Mms/ReservationManager: resetAfterConnected()
,03-15 19:11:43.264  4982  5069 D Mms/Conversation: [start]    init() consume time = 34.213907
,03-15 19:11:43.264  1484  1791 D TP/MmsSmsProvider: query,matched:7, calling pid = 4982
,03-15 19:11:43.264  1484  1498 D TP/MmsSmsProvider: deleteConversation threadId: 9223372036854775807
,03-15 19:11:43.264  1484  1498 D TP/MmsSmsProvider: delete URI_CONVERSATIONS_MESSAGES affectedRows=0 isIntegrated=false
,03-15 19:11:43.264  1484  1498 V TP/MmsSmsDatabaseHelper: updateThread(), thread_id = 9223372036854775807
,03-15 19:11:43.264  1484  1791 D TP/MmsSmsProvider: match 7:Elapsed time : 6.109 ms
,03-15 19:11:43.274  1484  1498 V TP/MmsSmsDatabaseHelper: sUpgradeVersion = 0, db.getVersion() = 81
,03-15 19:11:43.274  1484  1498 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-15 19:11:43.274  1484  1498 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-15 19:11:43.274  1484  1498 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-15 19:11:43.274  1484  1498 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-15 19:11:43.274  1484  1498 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
03-15 19:11:43.274  1484  1498 E SQLiteLog: (284) automatic index on im_threads(normal_thread_id)
,03-15 19:11:43.284  4982  4982 I Mms/ReservationManager: getReservedSendMessageCount(): retMessageCount=0
,03-15 19:11:43.284  4982  4982 D Mms/MmsApp: [end]    onCreate() consume time = 25.155104
,03-15 19:11:43.284  1484  1498 D TP/MmsSmsProvider: delete threadId: 9223372036854775807
03-15 19:11:43.284  1484  1498 D TP/MmsSmsProvider: need read changed broadcast:false
,03-15 19:11:43.284  4982  5069 D Mms/Conversation: [end]    init consume time = 3.102187
,03-15 19:11:43.294  4982  5069 D Mms/MessagingNotification: [start]    init() consume time = 1.613698
,03-15 19:11:43.294  1018  1744 I splitIntent: Queue : background intent android.intent.action.TIME_SET is finished at BG and BG split queue. set mSplitStart  false.
,03-15 19:11:43.294  4982  4982 D Mms/DownloadManager: Service state changed: Bundle[mParcelledData.dataSize=744]
,03-15 19:11:43.294  4982  4982 D Mms/DownloadManager: roaming ------> false, mSimSlot = 0
,03-15 19:11:43.294  1018  1744 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:43.294  1018  1744 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:43.294  1018  1744 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,03-15 19:11:43.294  1018  1744 I ActivityManager: Killing 4019:com.samsung.android.app.galaxyfinder:tagService/u0a32 (adj 15): empty #31
,03-15 19:11:43.294  4982  4982 D Mms/MethodReflector: getSubId is called
03-15 19:11:43.294  4982  4982 D Mms/TelephonyUtils: getLongSubId from simSlot 0, return Value = -1
,03-15 19:11:43.294  4982  5069 D Mms/MessagingNotification: [end]    init consume time = 7.909063
,03-15 19:11:43.304  1484  1502 D TP/MmsSmsProvider: query,matched:0, calling pid = 4982
03-15 19:11:43.304  1484  1502 V TP/MmsSmsProvider: getSimpleConversations entered.
03-15 19:11:43.304  4982  4982 D Mms/MethodReflector: getTelephonyProperty is called
03-15 19:11:43.304  4982  4982 D Mms/DownloadManager: roaming -> false (slotId = 0)
03-15 19:11:43.304  4982  4982 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState simSlot : 0
03-15 19:11:43.304  4982  4982 D Mms/DownloadManager: auto download without roaming -> true
03-15 19:11:43.304  4982  4982 D Mms/DownloadManager: [NotificationTransaction] getAutoDownloadState alwaysAuto : false, roaming : false
03-15 19:11:43.304  4982  4982 D Mms/DownloadManager: mAutoDownload ------> true
,03-15 19:11:43.304  4982  5070 D Mms/SpamFilter: [start]    SpamFilter fill() begin consume time = 7.008698
03-15 19:11:43.304  1484  1502 D TP/MmsSmsProvider: match 0:Elapsed time : 1.100 ms
,03-15 19:11:43.304  1018  1346 D ActivityManager: startService callerProcessName:com.android.contacts, calleePkgName: com.android.contacts
03-15 19:11:43.304  1484  1498 D TP/MmsSmsProvider: query,matched:400, calling pid = 4982
,03-15 19:11:43.304  1018  1346 D ActivityManager: retrieveServiceLocked(): component = com.android.contacts/com.samsung.contacts.sim.MakeSimDBService; callingUser = 0; userId(target) = 0
,03-15 19:11:43.304  4982  5071 D Mms/Synchronizer: [start]    doSync consume time = 4.067343
03-15 19:11:43.314  1018  1346 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:43.314  1018  1346 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:43.314  1018  1346 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.contacts, destAppInfo.processName = com.android.contacts
,03-15 19:11:43.314  1484  1791 D TP/MmsSmsProvider: update, matched:300, calling pid = 4982
,03-15 19:11:43.314  1484  1791 V TP/MmsSmsProvider: syncDBData start
,03-15 19:11:43.314  1484  1791 V TP/MmsSmsProvider: syncDBData sms end
03-15 19:11:43.314  1018  1504 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.MtpApplication, hostingType: broadcast
,03-15 19:11:43.314  1484  1791 V TP/MmsSmsProvider: syncDBData mms end
,03-15 19:11:43.314  1484  1791 V TP/MmsSmsProvider: syncDBData end
,03-15 19:11:43.314  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:43.314  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:43.314  1018  2750 D SSRM:n  : SIOP:: AP = 400
03-15 19:11:43.314  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:43.314  1018  1504 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:43.334  5073  5073 E Zygote  : MountEmulatedStorage()
,03-15 19:11:43.334  5073  5073 E Zygote  : v2
03-15 19:11:43.334  5073  5073 I libpersona: KNOX_SDCARD checking this for 1000
03-15 19:11:43.334  5073  5073 I libpersona: KNOX_SDCARD not a persona
,03-15 19:11:43.334  5073  5073 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-15 19:11:43.334  1018  1504 I ActivityManager: Start proc com.samsung.android.MtpApplication for broadcast com.samsung.android.MtpApplication/.MtpReceiver: pid=5073 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001, 1021, 3004, 3005, 1000, 3009, 1010} abi=armeabi-v7a
,03-15 19:11:43.334  4982  5071 D Mms/Synchronizer: [end]    doSync consume time = 27.55625
03-15 19:11:43.334  1018  1030 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.sec.android.provider.badge
,03-15 19:11:43.334  5073  5073 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
03-15 19:11:43.334  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:43.334  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:43.334  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:43.334  1018  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:43.334  5073  5073 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,03-15 19:11:43.354  5087  5087 E Zygote  : MountEmulatedStorage(),
03-15 19:11:43.354  5087  5087 I libpersona: KNOX_SDCARD checking this for 10072
03-15 19:11:43.354  5087  5087 E Zygote  : v2
03-15 19:11:43.354  5087  5087 I libpersona: KNOX_SDCARD not a persona
03-15 19:11:43.354  5087  5087 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-15 19:11:43.354  5087  5087 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038,
03-15 19:11:43.354  5073  5073 D TimaKeyStoreProvider: TimaSignature is unavailable
03-15 19:11:43.354  5087  5087 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
03-15 19:11:43.354  5073  5073 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:43.354  1018  1030 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=5087 uid=10072 gids={50072, 9997} abi=armeabi-v7a
,03-15 19:11:43.364  4982  5070 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 23.721927
,03-15 19:11:43.374  5087  5087 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:43.374  5087  5087 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:43.384  1018  1043 W libprocessgroup: failed to open /acct/uid_1000/pid_4694/cgroup.procs: No such file or directory
03-15 19:11:43.384  1018  1043 W libprocessgroup: failed to open /acct/uid_10032/pid_4019/cgroup.procs: No such file or directory
03-15 19:11:43.384  1018  1744 I ActivityManager: Killing 4164:com.sec.android.soagent/u0a34 (adj 15): empty #31
,03-15 19:11:43.394  5073  5073 E MTPRx   : In MtpReceiverandroid.hardware.usb.action.USB_STATE
,03-15 19:11:43.394  1018  1518 D SecContentProvider2: uri = 14 selection = getSealedState
03-15 19:11:43.394  1018  1518 D SecContentProvider2: mCursor = null
,03-15 19:11:43.404  1018  4423 D SecContentProvider2: uri = 14 selection = getSealedUsbMassStorageState
,03-15 19:11:43.404  1018  4423 D SecContentProvider2: mCursor = null
,03-15 19:11:43.404  5087  5087 D BadgeProvider: onCreate
,03-15 19:11:43.404  5087  5087 D BadgeProvider: DatabaseHelper
03-15 19:11:43.404  5073  5073 V MTPRx   : sealedState: false
,03-15 19:11:43.404  5073  5073 V MTPRx   : sealedUsbMassStorageState: false
03-15 19:11:43.404  5073  5073 E MTPRx   : check value of boot_completed is1
03-15 19:11:43.404  5073  5073 E MTPRx   : check booting is completed_sys.boot_completed
,03-15 19:11:43.404  5073  5073 E MTPRx   : Sd-Card path/storage/extSdCard
,03-15 19:11:43.404  5073  5073 E MTPRx   : Status for mount/Unmount :removed
03-15 19:11:43.404  5073  5073 E MTPRx   : SDcard is not available
,03-15 19:11:43.404  5073  5073 W MTPRx   : value of connected istrue
03-15 19:11:43.404  5073  5073 W MTPRx   : value of configured istrue
03-15 19:11:43.404  5073  5073 W MTPRx   : value of mtpEnabled istrue
03-15 19:11:43.404  5073  5073 W MTPRx   : value of ptpEnabled isfalse
,03-15 19:11:43.404  5073  5073 E MTPRx   : Received USB_STATE with sdCardLaunch = 0
,03-15 19:11:43.414  5073  5073 E MTPRx   : mFirstTime: false
,03-15 19:11:43.414  5073  5073 D         : MTP: reading debug level property
,03-15 19:11:43.424  5073  5073 E MTPJNIInterface: Getting CryptionKey from JAVA
,03-15 19:11:43.424  5073  5073 E MTPRx   : currentUserId is 0
,03-15 19:11:43.424  4982  5069 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
,03-15 19:11:43.424  5073  5073 E MTPRx   : Start observing USB_STATE_MATCH 
,03-15 19:11:43.424  5073  5073 E MTPRx   : cannot open file : /sys/class/android_usb/android0/bcdUSB
03-15 19:11:43.424  5073  5073 E MTPRx   : is_Privatemode is NOT 1
,03-15 19:11:43.434  1018  1518 D SettingsProvider: name = boot_time_connected
,03-15 19:11:43.434  1484  1700 D TP/SmsProvider: query,matched:26, calling pid = 4982
,03-15 19:11:43.434  1484  1700 D TP/SmsProvider: match 26:Elapsed time : 1.168 ms
,03-15 19:11:43.434  5073  5073 E MTPRx   : Sending NORMAL_BOOT to stack
03-15 19:11:43.434  5073  5073 E MTPJNIInterface: noti = 17
,03-15 19:11:43.434  1018  1129 D SettingsProvider: name = mtp_usb_conditions_met
,03-15 19:11:43.444  1018  1952 D SecContentProvider: uri = 18 selection = isUsbMediaPlayerAvailable
,03-15 19:11:43.444  5073  5073 E MTPRx   : sending MTP_ICON_ENABLED to stack
,03-15 19:11:43.444  1018  4306 D ActivityManager: startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
03-15 19:11:43.444  1018  4306 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,03-15 19:11:43.444  1018  4306 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:43.444  1018  4306 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:43.444  1018  4306 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
,03-15 19:11:43.454  1484  1502 D TP/MmsSmsProvider: query,matched:6, calling pid = 4982
03-15 19:11:43.454  1018  1031 D SettingsProvider: name = mtp_running_status
,03-15 19:11:43.454  1484  1502 D TP/MmsSmsProvider: match 6:Elapsed time : 1.493 ms
,03-15 19:11:43.454  1018  1030 D SettingsProvider: name = mtp_usb_conditions_met
,03-15 19:11:43.454  5073  5073 E MTPRx   : else part ... so first time!!!
,03-15 19:11:43.454  5073  5073 E MTPPlaObsrvr: inside setContext()
03-15 19:11:43.454  1018  1129 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
03-15 19:11:43.454  5073  5073 E MTPPlaObsrvr:  inside createplafiles
03-15 19:11:43.454  1018  1129 D ActivityManager: retrieveServiceLocked(): component = com.sec.spp.push/com.sec.spp.push.monitor.SystemStateMonitorService; callingUser = 0; userId(target) = 0
,03-15 19:11:43.454  1018  1129 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:43.464  1018  1129 W ActivityManager: NORMAL SET : dst_category = 1023, src_allowCategory = 0,701-1023
03-15 19:11:43.464  1018  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.spp.push, destAppInfo.processName = com.sec.spp.push
,03-15 19:11:43.464  1181  1181 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
,03-15 19:11:43.474  5073  5073 E MTPPlaObsrvr: playlist count is0
,03-15 19:11:43.474  5073  5073 E MTPPlaObsrvr:  inside try branch createplafiles
,03-15 19:11:43.474  5073  5073 E MTPPlaObsrvr:  inside deleteing plas createplafiles
,03-15 19:11:43.474  5073  5073 E MTPPlaObsrvr: Inside registerContentObserver
,03-15 19:11:43.474  1018  4306 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
,03-15 19:11:43.474  5073  5073 E MtpAdbObserver: inside setContext()
03-15 19:11:43.474  5073  5073 E MtpAdbObserver: Inside registerContentObserver
03-15 19:11:43.474  5073  5073 W Settings: Setting adb_enabled has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only global URI.
,03-15 19:11:43.474  1018  4306 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:43.474  1018  4306 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:43.474  1018  4306 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:43.474  1018  4306 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:43.484  5073  5107 V MtpMediaDBManager: inside deleteAllDB,
,03-15 19:11:43.484  1018  1043 W libprocessgroup: failed to open /acct/uid_10034/pid_4164/cgroup.procs: No such file or directory
,03-15 19:11:43.494  1018  1018 I ValidateNoPeople: mEvictionCount: 0
,03-15 19:11:43.494  4982  4982 D Mms/Contact: sContactsObserver.onChange(),selfUpdate=false
,03-15 19:11:43.494  4982  4982 D Mms/Contact: performUpdate:widgetCount=0
,03-15 19:11:43.494  5109  5109 E Zygote  : MountEmulatedStorage()
03-15 19:11:43.494  5109  5109 E Zygote  : v2
03-15 19:11:43.494  5109  5109 I libpersona: KNOX_SDCARD checking this for 10025
03-15 19:11:43.494  5109  5109 I libpersona: KNOX_SDCARD not a persona
,03-15 19:11:43.494  5109  5109 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A500FU_5.0.2-1 ver=38
,03-15 19:11:43.494  5109  5109 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A500FU_5.0.2-1_0038
,03-15 19:11:43.494  4982  5110 D Mms/ContactsCache: [start]    invalidate() consume time = 138.302084
03-15 19:11:43.494  1018  4306 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=5109 uid=10025 gids={50025, 9997} abi=armeabi-v7a
03-15 19:11:43.494  5109  5109 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
03-15 19:11:43.494  1018  1030 D ActivityManager: startService callerProcessName:com.samsung.android.MtpApplication, calleePkgName: com.samsung.android.MtpApplication
03-15 19:11:43.494  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.MtpApplication/com.samsung.android.MtpApplication.MtpService; callingUser = 0; userId(target) = 0
,03-15 19:11:43.504  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:43.504  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:43.504  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.MtpApplication, destAppInfo.processName = com.samsung.android.MtpApplication
03-15 19:11:43.504  4982  5110 D Mms/ContactsCache: [end]    invalidate() consume time = 1.308177
,03-15 19:11:43.504  1018  1952 D SettingsProvider: name = mtp_running_status
,03-15 19:11:43.504  1018  4423 D SettingsProvider: name = mtp_usb_conditions_met
,03-15 19:11:43.504  5073  5073 E MtpService: onCreate.
,03-15 19:11:43.504  1018  1337 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.media
03-15 19:11:43.504  1018  1337 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.media/com.android.providers.media.MtpService; callingUser = 0; userId(target) = 0
,03-15 19:11:43.504  1018  1337 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:43.504  1018  1337 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:43.504  1018  1337 W ActivityManager: NORMAL SET : srcAppInfo.processName = android.process.media, destAppInfo.processName = android.process.media
,03-15 19:11:43.504  5073  5107 V MtpMediaDBManager: inside Thread updateDB
,03-15 19:11:43.514  5073  5073 E MtpService: < MTP > Registering BroadCast receiver :::::
,03-15 19:11:43.514  5073  5107 E MtpMediaDBManager: count : 27
,03-15 19:11:43.514  1228  1228 D MtpService: updating state; isCurrentUser=true, mMtpLocked=false
,03-15 19:11:43.514  1018  1744 W ActivityManager: userId = 0, bbcId = -10000
,03-15 19:11:43.524  1018  1744 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
03-15 19:11:43.524  1018  1744 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.android.settings
,03-15 19:11:43.524  5109  5109 D TimaKeyStoreProvider: TimaSignature is unavailable
,03-15 19:11:43.524  5109  5109 D ActivityThread: Added TimaKeyStore provider
,03-15 19:11:43.524  5073  5073 E MtpService: < MTP > Registering BroadCast registerBroadCastPolicyRec :::::
03-15 19:11:43.524  5073  5073 E MtpService: < MTP > Registering BroadCast registerBroadCastEmergencyRec :::::
,03-15 19:11:43.534  1018  1346 I ActivityManager: Killing 4726:com.samsung.android.service.travel/u0a159 (adj 15): empty #31
,03-15 19:11:43.534  5073  5073 E MtpService: onStartCommand.
,03-15 19:11:43.534  5073  5073 W MTPRx   : calling native method
03-15 19:11:43.534  5073  5073 E MTPJNIInterface: < MTP > Registering BroadCast receiver :::::
,03-15 19:11:43.534  5073  5119 E MtpService: handleMessage. msg= { when=-1ms what=0 arg1=1 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
,03-15 19:11:43.544  1018  1952 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:43.544  1018  1952 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
03-15 19:11:43.544  1018  1952 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,03-15 19:11:43.544  5073  5107 W MtpMediaDBManager: sending db update complete noti to stack
03-15 19:11:43.544  5073  5107 E MTPJNIInterface: noti = 29
,03-15 19:11:43.544  5073  5073 E MTPJNIInterface: < MTP > Registering BroadCast receiver :::::::
,03-15 19:11:43.544  1018  1744 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:43.544  1018  1744 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
03-15 19:11:43.544  1018  1744 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
,03-15 19:11:43.544  5109  5109 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,03-15 19:11:43.554  1018  2822 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
03-15 19:11:43.554  1931  1931 V UserPresentBroadcastReceiver: Received Intent { act=android.intent.action.USER_PRESENT flg=0x24000010 cmp=com.google.android.gms/.auth.trustagent.UserPresentBroadcastReceiver }.
,03-15 19:11:43.554  5073  5073 E MTPJNIInterface: noti = 10,
03-15 19:11:43.554  5073  5073 E MtpService: onStartCommand.
03-15 19:11:43.554  5073  5073 W MTPRx   : calling native method
03-15 19:11:43.554  5073  5119 E MtpService: handleMessage. msg= { when=0 what=0 arg1=2 obj=Intent { cmp=com.samsung.android.MtpApplication/.MtpService } target=com.samsung.android.MtpApplication.MtpService$ServiceHandler }
03-15 19:11:43.554  5073  5073 E MTPRx   : Checking the driver time out
,03-15 19:11:43.554  5073  5073 E MTPJNIInterface: noti = 2
,03-15 19:11:43.554  5073  5073 D         : deleting sockets before message queue initialization
03-15 19:11:43.554  5073  5073 D         : event handler thread is created, so set the flag
03-15 19:11:43.554  1018  1031 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:43.554  1018  1031 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,2-1023
03-15 19:11:43.554  1018  1031 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.systemui, destAppInfo.processName = com.google.android.gms
03-15 19:11:43.554  5073  5073 E MTPRx   : called native method
,03-15 19:11:43.554  5073  5073 E MTPJNIInterface: setting Media scanner status0
03-15 19:11:43.554  5073  5073 E MTPJNIInterface: After setting Media scanner status0
03-15 19:11:43.554  5073  5126 E         : Unable to get Object Class and clearing cls 2 [int check_media_scanner_status() 594]
03-15 19:11:43.554  5073  5126 E MTPJNIInterface: Getting media scanner status0
,03-15 19:11:43.554  5073  5126 E MTPJNIInterface: DeviceName is A5-1
,03-15 19:11:43.564  1018  1129 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,03-15 19:11:43.564  5073  5073 W MTPRx   : notification from stack 1
,03-15 19:11:43.564  1018  1129 W ActivityManager: userId = 0, bbcId = -10000
03-15 19:11:43.564  1018  1129 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
03-15 19:11:43.564  1018  1129 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,03-15 19:11:43.574  5073  5126 E MTPJNIInterface: Status for mount/Unmount :removed
03-15 19:11:43.574  5073  5126 E MTPJNIInterface: SDcard is not available
,03-15 19:11:43.584  5073  5126 E         : lstat failed! errno [13] [Permission denied] [mtp_ifind_next 452]
,03-15 19:11:43.584  5109  5109 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
,03-15 19:11:43.594  5073  5126 E         : [mtp_hidden_system_volume 189] Error opening file [error = Read-only file system] 
,03-15 19:11:43.594  1300  1300 D BluetoothNotiBroadcastReceiver: onReceive
,03-15 19:11:43.594  5073  5126 E MTPJNIInterface: Status for mount/Unmount :removed
03-15 19:11:43.594  5073  5126 E MTPJNIInterface: SDcard is not available
03-15 19:11:43.594  5073  5126 E SQLiteLog: (21) API call with NULL database connection pointer
03-15 19:11:43.594  5073  5126 E SQLiteLog: (21) misuse at line 106108 of [9491ba7d73]
03-15 19:11:43.594  5073  5126 E SQLiteLog: (21) API call with NULL database connection pointer
03-15 19:11:43.594  5073  5126 E SQLiteLog: (21) misuse at line 100726 of [9491ba7d73]
03-15 19:11:43.594  5073  5126 E SQLiteLog: (21) API call with NULL database connection pointer
03-15 19:11:43.594  5073  5126 E SQLiteLog: (21) misuse at line 100726 of [9491ba7d73]
03-15 19:11:43.594  5073  5126 E SQLiteLog: (21) API call with NULL database connection pointer
03-15 19:11:43.594  5073  5126 E SQLiteLog: (21) misuse at line 106108 of [9491ba7d73]
,03-15 19:11:43.604  1181  1181 V BluetoothStatusReceiver: Received android.bluetooth.adapter.action.STATE_CHANGED
03-15 19:11:43.604  1181  1181 D BluetoothStatusReceiver: AdapterStateChanged :: BluetoothAdapter.ACTION_STATE_CHANGED, state = 11
03-15 19:11:43.604  5073  5073 W MTPRx   : notification from stack 2
,03-15 19:11:43.604  5073  5128 D         : [mtp_init_device] Library open with 32 bits.
03-15 19:11:43.604  5073  5128 D         : [mtp_init_device] Going to open(): /dev/usb_mtp_gadget
03-15 19:11:43.604  5073  5128 E         : [mtp_init_device 702]  After open the MTP fd = 33 and line = 702...
03-15 19:11:43.604  5073  5128 D         : [mtp_init_device] IOCTL SET_MTP_USER_PID Sucesss 
,03-15 19:11:43.604  1018  1705 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.intelligenceservice, hostingType: broadcast
03-15 19:11:43.604  5073  5128 E         :  [sua_support_present:1287] returning false 
03-15 19:11:43.604  5073  5128 D         : [mtp_init_device] b4 calling MTP_ONLY_ENABLE  ioctl coneect to host
,03-15 19:11:43.604  1018  1705 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:43.604  1018  1705 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:43.604  1018  1705 E ActivityManager: checkUser: useridlist=null, currentuser=0
03-15 19:11:43.604  1018  1705 E ActivityManager: checkUser: useridlist=null, currentuser=0
,03-15 19:11:43.604  4982  5069 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0

```
