#### Test 82337235c8e499b_thali03_samsung-SM-A300FU Logs


```
--------- beginning of main
08-23 13:40:29.756  1483  1507 D TP/MmsSmsProvider: query,matched:400, calling pid = 6514
08-23 13:40:29.756  1483  2017 D TP/MmsSmsProvider: update, matched:300, calling pid = 6514
08-23 13:40:29.756  1483  2017 V TP/MmsSmsProvider: syncDBData start
08-23 13:40:29.756  1483  2017 V TP/MmsSmsProvider: syncDBData sms end
08-23 13:40:29.756  1483  2017 V TP/MmsSmsProvider: syncDBData mms end
08-23 13:40:29.756  1483  2017 V TP/MmsSmsProvider: syncDBData end
08-23 13:40:29.756  6514  6687 D Mms/Synchronizer: [end]    doSync consume time = 37.43099
08-23 13:40:29.766  1018  1522 E EdmStorageProvider: Admin not in database, something went wrong
08-23 13:40:29.766  6514  6514 D Mms/FreeMessageStatusReceiver: onReceive, action : android.intent.action.PACKAGE_ADDED
08-23 13:40:29.766  1900  6576 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
08-23 13:40:29.766  6514  6686 D Mms/SpamFilter: [end]    SpamFilter fill() finished consume time = 5.356979
08-23 13:40:29.766  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-23 13:40:29.766  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 13:40:29.766  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.mms, destAppInfo.processName = com.android.mms
08-23 13:40:29.766  1900  6576 I qtaguid : Tagging socket 101 with tag 1000040b00000000{268436491,0} for uid -1, pid: 1900, getuid(): 10011
08-23 13:40:29.766  6688  6688 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:40:29.766  6688  6688 D ActivityThread: Added TimaKeyStore provider
--------- beginning of system
08-23 13:40:29.766  1018  1030 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
08-23 13:40:29.766  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.mms/com.android.mms.freemessage.FreeMessageReceiverService; callingUser = 0; userId(target) = 0
08-23 13:40:29.776  1018  1330 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.myfiles, hostingType: broadcast
08-23 13:40:29.776  1018  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:29.776  1018  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:29.776  1018  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:29.776  1018  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:29.786  6705  6705 E Zygote  : MountEmulatedStorage()
08-23 13:40:29.786  6705  6705 E Zygote  : v2
08-23 13:40:29.786  6705  6705 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 13:40:29.786  6705  6705 I libpersona: KNOX_SDCARD checking this for 10042
08-23 13:40:29.786  6705  6705 I libpersona: KNOX_SDCARD not a persona
08-23 13:40:29.786  1018  1330 I ActivityManager: Start proc com.sec.android.app.myfiles for broadcast com.sec.android.app.myfiles/.receiver.MyFilesReceiver: pid=6705 uid=10042 gids={50042, 9997, 1028, 1015, 3003, 3002, 3001, 1023} abi=armeabi-v7a
08-23 13:40:29.796  6705  6705 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 13:40:29.796  6705  6705 E SELinux : [DEBUG] get_category: variable seinfo: media sensitivity: NULL, cateogry: NULL
08-23 13:40:29.836  6705  6705 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:40:29.836  6688  6688 D BadgeProvider: onCreate
08-23 13:40:29.836  6688  6688 D BadgeProvider: DatabaseHelper
08-23 13:40:29.846  6514  6722 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_ADDED
08-23 13:40:29.846  6514  6722 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_ADDED
08-23 13:40:29.846  6705  6705 D ActivityThread: Added TimaKeyStore provider
08-23 13:40:29.856  1900  6576 I qtaguid : Tagging socket 105 with tag 1000040b00000000{268436491,0} for uid -1, pid: 1900, getuid(): 10011
08-23 13:40:29.856  1018  4442 I ActivityManager: Killing 6353:com.android.defcontainer/u0a3 (adj 15): empty #21
08-23 13:40:29.856  1018  4442 I ActivityManager: Killing 6271:com.android.calendar/u0a131 (adj 15): empty #22
08-23 13:40:29.866  6514  6685 D Mms/MessagingNotification: checkBadgeCount unreadCount=0 badgeCount=0
08-23 13:40:29.876  1483  1503 D TP/SmsProvider: query,matched:26, calling pid = 6514
08-23 13:40:29.876  6705  6705 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-23 13:40:29.876  6705  6705 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-23 13:40:29.876  6705  6705 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-23 13:40:29.876  1483  1503 D TP/SmsProvider: match 26:Elapsed time : 4.439 ms
08-23 13:40:29.886  1483  2017 D TP/MmsSmsProvider: query,matched:6, calling pid = 6514
08-23 13:40:29.896  1483  2017 D TP/MmsSmsProvider: match 6:Elapsed time : 1.492 ms
08-23 13:40:29.906  1018  1466 D ActivityManager: getContentProviderImpl callerProcessName:com.android.mms, calleePkgName: com.wsomacp
08-23 13:40:29.906  1018  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:29.906  1018  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:29.906  1018  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:29.906  1018  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:29.936  6725  6725 E Zygote  : MountEmulatedStorage()
08-23 13:40:29.936  6725  6725 E Zygote  : v2
08-23 13:40:29.936  6725  6725 I libpersona: KNOX_SDCARD checking this for 10023
08-23 13:40:29.936  6725  6725 I libpersona: KNOX_SDCARD not a persona
08-23 13:40:29.946  6725  6725 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 13:40:29.946  1018  1466 I ActivityManager: Start proc com.wsomacp for content provider com.wsomacp/.db.XCPDBSqlProvider: pid=6725 uid=10023 gids={50023, 9997} abi=armeabi-v7a
08-23 13:40:29.946  6725  6725 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 13:40:29.946  6725  6725 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-23 13:40:29.976  6725  6725 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:40:29.976  6725  6725 D ActivityThread: Added TimaKeyStore provider
08-23 13:40:29.976  1018  3269 I ActivityManager: Killing 6100:com.samsung.android.app.galaxyfinder/u0a29 (adj 15): empty #21
08-23 13:40:30.006  6705  6705 D MyFiles : MyFilesReceiver::Received the android.intent.action.PACKAGE_ADDED
08-23 13:40:30.006  1018  1522 I ActivityManager: Killing 6401:com.samsung.android.app.watchmanagerstub/u0a98 (adj 15): empty #21
08-23 13:40:30.016  1018  1059 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.defcontainer, action: null
08-23 13:40:30.016  1018  1059 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
08-23 13:40:30.016  1018  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:30.016  1018  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:30.016  1018  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:30.016  1018  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:30.026  1018  1059 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6740 uid=10003 gids={50003, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-23 13:40:30.026  6740  6740 E Zygote  : MountEmulatedStorage()
08-23 13:40:30.036  6740  6740 E Zygote  : v2
08-23 13:40:30.036  6740  6740 I libpersona: KNOX_SDCARD checking this for 10003
08-23 13:40:30.036  1900  6576 I qtaguid : Untagging socket 101
08-23 13:40:30.036  6740  6740 I libpersona: KNOX_SDCARD not a persona
08-23 13:40:30.036  1900  1900 I ConfigFetchService: fetch service done; releasing wakelock
08-23 13:40:30.036  1900  1900 I ConfigFetchService: stopping self
08-23 13:40:30.046  6740  6740 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 13:40:30.046  6740  6740 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 13:40:30.046  6740  6740 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-23 13:40:30.066  6740  6740 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:40:30.066  6740  6740 D ActivityThread: Added TimaKeyStore provider
08-23 13:40:30.086  6725  6725 I OMACP   : [com.wsomacp.XCPApplication(50/onCreate)] CPApplication Start !
08-23 13:40:30.086  6514  6685 D Mms/Omacp: checkOmacp()  old OmacpCount 0 current OmacpCount = 0
08-23 13:40:30.106   285   285 E installd: system dir 0 : /system/app/
08-23 13:40:30.106   285   285 E installd: system dir 1 : /system/priv-app/
08-23 13:40:30.106   285   285 E installd: system dir 2 : /vendor/app/
08-23 13:40:30.106   285   285 E installd: system dir 3 : /oem/app/
08-23 13:40:30.116  1018  4437 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-23 13:40:30.116  6725  6725 I OMACP   : [com.wsomacp.agent.XCPSystem(120/xcpSystemSetCPFeature)] XCP_FEATURE_MAC_CHECK: false
08-23 13:40:30.116  6725  6725 I OMACP   : [com.wsomacp.agent.XCPSystem(121/xcpSystemSetCPFeature)] XCP_FEATURE_SECURITY: 4369
08-23 13:40:30.116  6725  6725 I OMACP   : [com.wsomacp.agent.XCPSystem(122/xcpSystemSetCPFeature)] XCP_FEATURE_NETWPIN_CHECK: false
08-23 13:40:30.116  6725  6725 I OMACP   : [com.wsomacp.agent.XCPSystem(123/xcpSystemSetCPFeature)] XCP_FEATURE_MULTI_APN: true
08-23 13:40:30.126  6725  6725 I OMACP   : [com.wsomacp.agent.XCPSystem(124/xcpSystemSetCPFeature)] XCP_FEATURE_OVERWRITE_BY_APN: false
08-23 13:40:30.126  6725  6725 I OMACP   : [com.wsomacp.agent.XCPSystem(125/xcpSystemSetCPFeature)] XCP_FEATURE_DELETE_CP_MESSAGE: false
08-23 13:40:30.126  6725  6725 I OMACP   : [com.wsomacp.agent.XCPSystem(126/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_MYPHONEBOOK: false
08-23 13:40:30.126  6725  6725 I OMACP   : [com.wsomacp.agent.XCPSystem(127/xcpSystemSetCPFeature)] XCP_FEATURE_SUPPORT_OMADM_BOOTSTRAP: false
08-23 13:40:30.126  6725  6725 I OMACP   : [com.wsomacp.agent.XCPSystem(128/xcpSystemSetCPFeature)] XCP_FEATURE_BG_INTSATLL_DM_BOOTSTRAP: false
08-23 13:40:30.126  6725  6725 I OMACP   : [com.wsomacp.agent.XCPSystem(129/xcpSystemSetCPFeature)] XCP_DEVICETYPE_FEATURE_TABLET : false
08-23 13:40:30.136  6725  6725 I OMACP   : [com.wsomacp.agent.XCPSystem(130/xcpSystemSetCPFeature)] XCP_SUPPORT_DUAL_SIM : false
08-23 13:40:30.136  6725  6725 I OMACP   : [com.wsomacp.agent.XCPSystem(131/xcpSystemSetCPFeature)] XCP_SUPPORT_USA_ATT : false
08-23 13:40:30.136  6725  6725 I OMACP   : [com.wsomacp.agent.XCPSystem(132/xcpSystemSetCPFeature)] XCP_SUPPORT_SAME_APN : false
08-23 13:40:30.166  1018  1059 D PackageManager: remove MCS_UNBIND message and Posting MCS_UNBIND 10 secs later
08-23 13:40:30.296  6544  6597 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
08-23 13:40:30.296  6544  6597 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
08-23 13:40:30.296  6544  6597 I GAv4    :   adb logcat -s GAv4
08-23 13:40:30.326  1900  4233 I Icing   : Indexing D0AE1F45F393341DA3213A207506F1C2E721F1A9 from com.google.android.googlequicksearchbox
08-23 13:40:30.336  1018  1518 I art     : Explicit concurrent mark sweep GC freed 139919(7MB) AllocSpace objects, 3(1847KB) LOS objects, 33% free, 22MB/34MB, paused 2.465ms total 177.389ms
08-23 13:40:30.366  6544  6597 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
08-23 13:40:30.366  1018  1522 W ActivityManager: getRunningAppProcesses: caller 10087 does not hold REAL_GET_TASKS; limiting output
08-23 13:40:30.386  1684  2500 I art     : Explicit concurrent mark sweep GC freed 11663(563KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 8MB/13MB, paused 1.023ms total 44.162ms
08-23 13:40:30.396  1900  4233 D Icing   : Loaded CLD2 Version V2.0 - 20141016
08-23 13:40:30.406  6544  6597 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
08-23 13:40:30.426  6544  6597 W AnalyticsTrackerProxyImpl: Analytics setup for ID UA-21125203-2, app name Drive, version 2.3.357.23.33
08-23 13:40:30.436  6544  6764 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
08-23 13:40:30.456   289   289 E SMD     : DCD OFF
08-23 13:40:30.466  1900  4233 I Icing   : Indexing done D0AE1F45F393341DA3213A207506F1C2E721F1A9
08-23 13:40:30.486  1018  1518 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.filterinstaller, hostingType: broadcast
08-23 13:40:30.486  1018  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:30.486  1018  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:30.486  1018  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:30.486  1018  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:30.496  6768  6768 E Zygote  : MountEmulatedStorage()
08-23 13:40:30.496  6768  6768 E Zygote  : v2
08-23 13:40:30.496  6768  6768 I libpersona: KNOX_SDCARD checking this for 1000
08-23 13:40:30.496  6768  6768 I libpersona: KNOX_SDCARD not a persona
08-23 13:40:30.496  6768  6768 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 13:40:30.506  1018  1518 I ActivityManager: Start proc com.samsung.android.app.filterinstaller for broadcast com.samsung.android.app.filterinstaller/.PackageIntentReceiver: pid=6768 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-23 13:40:30.506  1018  1518 I ActivityManager: Killing 6416:com.sec.spp.push/u0a32 (adj 15): empty #21
08-23 13:40:30.506  6768  6768 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 13:40:30.506  6768  6768 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-23 13:40:30.506  1018  1466 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.icing.service.IndexWorkerService; callingUser = 0; userId(target) = 0
08-23 13:40:30.506  1018  1466 W ActivityManager: userId = 0, bbcId = -10000
08-23 13:40:30.506  1018  1466 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 13:40:30.506  1018  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-23 13:40:30.526  6768  6768 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:40:30.526  6768  6768 D ActivityThread: Added TimaKeyStore provider
08-23 13:40:30.556  6768  6768 D FilterInstaller: onReceive:android.intent.action.PACKAGE_ADDED, package:com.test.thalitest
08-23 13:40:30.556  6768  6768 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2063 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:44 android.app.ActivityThread.handleReceiver:3125 
08-23 13:40:30.556  1018  1030 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
08-23 13:40:30.556  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.samsung.android.app.filterinstaller/com.samsung.android.app.filterinstaller.FilterPackageService; callingUser = 0; userId(target) = 0
08-23 13:40:30.576  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-23 13:40:30.576  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 13:40:30.576  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.android.app.filterinstaller, destAppInfo.processName = com.samsung.android.app.filterinstaller
08-23 13:40:30.576  1018  4437 I splitIntent: Queue : backgroundsplit_1 intent android.intent.action.PACKAGE_ADDED is finished at BG and BG split queue. set mSplitStart and mBgSplitQueueOnlyRun false.
08-23 13:40:30.576  6768  6768 I FilterInstaller: FilterPackageService : ACTION_CHANGED
08-23 13:40:30.596  6544  6766 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-23 13:40:30.596  6544  6766 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
08-23 13:40:30.606  1018  1018 D ActivityManager: bindService callerProcessName:android, calleePkgName: android, action: null
08-23 13:40:30.606  1018  1018 D ActivityManager: retrieveServiceLocked(): component = android/com.android.server.os.BackgroundCompactionService; callingUser = 0; userId(target) = 0
08-23 13:40:30.616  1018  1395 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 13:40:30.616  6768  6786 E FilterInstaller: installFilters
08-23 13:40:30.616  1018  1395 D AlarmManagerService: Setting time of day to sec=1471952431
08-23 13:40:30.616  1018  1395 D AlarmManagerService: Trying to open a file
08-23 13:40:30.616  1018  1395 D AlarmManagerService: File Open Success
08-23 13:40:30.616  1018  1395 D AlarmManagerService: File Close Success
08-23 13:40:30.616  1018  1395 I AlarmManagerService: DRM_TIME_PATH CHMOD 666 for resetState done 
08-23 13:40:31.157  1018  1395 W AlarmManagerService: Unable to set rtc to 1471952431: Invalid argument
08-23 13:40:31.157  1018  1098 V AlarmManager: waitForAlarm result :65536
08-23 13:40:31.157  1018  1018 I BackgroundCompactionService: onStart. jobID=801
08-23 13:40:31.157  6768  6786 E FilterInstaller: There is no requred permission
08-23 13:40:31.157  1018  1018 I BackgroundCompactionService: onStart done. jobID=801
08-23 13:40:31.157  1018  1098 V AlarmManager: No more alarm at this time.nowELAPSED=95095 batch.start=108623
08-23 13:40:31.157  1018  6787 I BackgroundCompactionService: Execute BGCompaction (type1). (0 times)
08-23 13:40:31.157  1018  6787 I BackgroundCompactionService: compact_memory command done
08-23 13:40:31.206  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_SET
08-23 13:40:31.206  1179  1179 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_SET
08-23 13:40:31.206  1179  1179 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 13:40:31.216  1018  1018 D OTPFW   : OTPTimeChangeLogger :: TimeChangeListener$onReceive | Device Time Changed. Current time = 1471952431222
08-23 13:40:31.216  1018  1018 D WifiStateMachine: android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
08-23 13:40:31.216  1018  1018 I DowntimeConditions: android.intent.action.TIME_SET ignored because schedule turned off.
08-23 13:40:31.216  1018  1018 W Settings: Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-23 13:40:31.236  1018  1031 I ActivityManager: Killing 5060:com.google.android.gms.wearable/u0a11 (adj 15): empty #21
08-23 13:40:31.236  1179  1179 D SecKeyguardClockView: onTimeChanged() : mShouldShowDualClock - false, isDualClockSet() -false
08-23 13:40:31.246  1179  1179 D SecKeyguardClockView: HomeTimezone(): 1
08-23 13:40:31.256  1179  1179 D SecKeyguardStatusUtils: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
08-23 13:40:31.256  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
08-23 13:40:31.256  1018  1508 D SettingsProvider: name = lockscreen_zoom_panning_effect
08-23 13:40:31.256  1018  1508 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 13:40:31.256  1018  1508 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 13:40:31.256  1018  1508 D SettingsProvider: selectionArgs: false
08-23 13:40:31.256  1018  1508 D SettingsProvider: selectionArgs: 10049
08-23 13:40:31.256  1018  1508 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 13:40:31.256  1018  1508 D SettingsProvider: ret = -1
08-23 13:40:31.266  1018  1018 I DrmEventService:  no response from SecureClock 
08-23 13:40:31.266  1018  1018 I splitIntent: intent=android.intent.action.TIME_SET will be not split. because same process=com.google.android.gms is in other queue. index=4
08-23 13:40:31.266  1018  1018 I splitIntent: base  index=4, name=com.google.android.gms com.google.android.gms.checkin.CheckinService$Receiver
08-23 13:40:31.266  1018  1018 I splitIntent: other index=7, name=com.google.android.gms com.google.android.gms.reminders.notification.NotificationReceiver
08-23 13:40:31.266  1018  1018 I splitIntent: arrangeSplitReceiver return false!! intent : android.intent.action.TIME_SET !! do not split it!!
08-23 13:40:31.266  1179  1179 D KeyguardEffectViewUtil: isStrongPowerSavingMode() :false
08-23 13:40:31.266  1018  1018 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
08-23 13:40:31.266  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:31.266  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:31.266  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:31.266  1018  1018 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:31.276  1179  1179 D KeyguardEffectViewController: isPreloadedWallpaper=true
08-23 13:40:31.276  1179  1179 I GeometricMosaic_Keyguard: update
08-23 13:40:31.286  1179  1179 D KeyguardEffectViewUtil: getCurrentWallpaper() mWallpaperPath :null
08-23 13:40:31.286  6789  6789 E Zygote  : MountEmulatedStorage()
08-23 13:40:31.296  1018  1018 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=6789 uid=10008 gids={50008, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-23 13:40:31.296  6789  6789 E Zygote  : v2
08-23 13:40:31.296  6789  6789 I libpersona: KNOX_SDCARD checking this for 10008
08-23 13:40:31.296  6789  6789 I libpersona: KNOX_SDCARD not a persona
08-23 13:40:31.296  6789  6789 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 13:40:31.296  6789  6789 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 13:40:31.306  6789  6789 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-23 13:40:31.316  6784  6784 D AndroidRuntime: 
08-23 13:40:31.316  6784  6784 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-23 13:40:31.326  6784  6784 D AndroidRuntime: CheckJNI is OFF
08-23 13:40:31.326  6784  6784 D AndroidRuntime: readGMSProperty: start
08-23 13:40:31.326  6784  6784 D AndroidRuntime: readGMSProperty: already setted!!
08-23 13:40:31.326  6784  6784 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-23 13:40:31.326  6784  6784 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-23 13:40:31.326  6784  6784 D AndroidRuntime: readGMSProperty: end
08-23 13:40:31.326  6784  6784 D AndroidRuntime: addProductProperty: start
08-23 13:40:31.326  6789  6789 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:40:31.326  6789  6789 D ActivityThread: Added TimaKeyStore provider
08-23 13:40:31.376  6544  6766 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 240 native methods...
08-23 13:40:31.426  6544  6766 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-23 13:40:31.436  6544  6766 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@ed50a1: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-23 13:40:31.436  6544  6766 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-23 13:40:31.466  6789  6789 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(102/onReceive)] Already device registered...
08-23 13:40:31.466  1179  1179 I KeyguardEffectViewUtil: set current wallpaper info
08-23 13:40:31.466  1018  3269 D SettingsProvider: name = keyguard_current_wallpaper_type
08-23 13:40:31.466  1018  3269 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 13:40:31.466  1018  3269 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 13:40:31.466  1018  3269 D SettingsProvider: selectionArgs: false
08-23 13:40:31.466  1018  3269 D SettingsProvider: selectionArgs: 10049
08-23 13:40:31.466  1018  3269 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 13:40:31.466  1018  3269 D SettingsProvider: ret = -1
08-23 13:40:31.466  1018  1466 D SettingsProvider: name = keyguard_current_wallpaper_file_path
08-23 13:40:31.466  1018  1466 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 13:40:31.466  1018  1466 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 13:40:31.466  1018  1466 D SettingsProvider: selectionArgs: false
08-23 13:40:31.466  1018  1466 D SettingsProvider: selectionArgs: 10049
08-23 13:40:31.466  1018  1466 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 13:40:31.466  1018  1466 D SettingsProvider: ret = -1
08-23 13:40:31.476  1018  4439 D SettingsProvider: name = keyguard_current_wallpaper_res_id
08-23 13:40:31.476  1018  4439 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 13:40:31.476  1018  4439 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 13:40:31.476  1018  4439 D SettingsProvider: selectionArgs: false
08-23 13:40:31.476  1018  4439 D SettingsProvider: selectionArgs: 10049
08-23 13:40:31.476  1018  4439 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 13:40:31.476  1018  4439 D SettingsProvider: ret = -1
08-23 13:40:31.496  6789  6789 I FOTA_Client: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
08-23 13:40:31.496  1018  1222 I ActivityManager: Killing 6446:com.samsung.helphub/1000 (adj 15): empty #21
08-23 13:40:31.526  1018  1505 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-23 13:40:31.526  1018  1505 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.CheckinService; callingUser = 0; userId(target) = 0
08-23 13:40:31.526  1018  1505 W ActivityManager: userId = 0, bbcId = -10000
08-23 13:40:31.526  1018  1505 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 13:40:31.526  1018  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-23 13:40:31.536  6784  6784 E AffinityControl: AffinityControl: registerfunction enter
08-23 13:40:31.546  1018  1080 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-23 13:40:31.546  1018  1080 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.checkin.EventLogService; callingUser = 0; userId(target) = 0
08-23 13:40:31.546  1018  1080 W ActivityManager: userId = 0, bbcId = -10000
08-23 13:40:31.546  1018  1080 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 13:40:31.546  1018  1080 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-23 13:40:31.556  1179  1668 D TEST    : run!!!
08-23 13:40:31.556  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
08-23 13:40:31.556  1179  1179 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
08-23 13:40:31.556  1179  1179 D SViewCoverWidget: initClock() : TimeZone =libcore.util.ZoneInfo[id="Europe/Warsaw",mRawOffset=3600000,mEarliestRawOffset=3600000,mUseDst=true,mDstSavings=3600000,transitions=167]
08-23 13:40:31.556  6784  6784 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-23 13:40:31.566  1179  1179 I SecKeyguardClockSingleView: Ignore. Because it is same clock text
08-23 13:40:31.576  1179  1668 I GeometricMosaic_Renderer: setBackgroundBitmap
08-23 13:40:31.576  1018  1518 E PersonaManagerService: inState():  stateMachine is null !!
08-23 13:40:31.576  1018  1518 I PersonaManagerService: PersonaId don't exist
08-23 13:40:31.576  1018  1518 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-23 13:40:31.576  1018  1505 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-23 13:40:31.576  1018  1505 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.reminders.notification.NotificationService; callingUser = 0; userId(target) = 0
08-23 13:40:31.586  1018  1505 W ActivityManager: userId = 0, bbcId = -10000
08-23 13:40:31.586  1018  1505 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 13:40:31.586  1018  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-23 13:40:31.586  1018  1518 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-23 13:40:31.596  1018  1518 W ActivityManager: mDVFSHelper.acquire()
08-23 13:40:31.606  1018  1518 D FocusedStackFrame: Set to : 0
08-23 13:40:31.616  1018  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:31.616  1018  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:31.616  1018  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:31.616  1018  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:31.626  1018  1049 D PhoneWindow: *FMB* installDecor mIsFloating : false
08-23 13:40:31.626  1018  1049 D PhoneWindow: *FMB* installDecor flags : -2122120936
08-23 13:40:31.626  6817  6817 E Zygote  : MountEmulatedStorage()
08-23 13:40:31.626  6817  6817 E Zygote  : v2
08-23 13:40:31.626  6817  6817 I libpersona: KNOX_SDCARD checking this for 10170
08-23 13:40:31.626  6817  6817 I libpersona: KNOX_SDCARD not a persona
08-23 13:40:31.626  6817  6817 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 13:40:31.626  1018  1518 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6817 uid=10170 gids={50170, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-23 13:40:31.626  1018  1518 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-23 13:40:31.626  1018  1518 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-23 13:40:31.626  1018  1518 D InputDispatcher: Focused application set to: xxxx
08-23 13:40:31.626  1018  1518 D InputDispatcher: Focus left window: 1509
08-23 13:40:31.636  6784  6784 D AndroidRuntime: Shutting down VM
08-23 13:40:31.636  1018  1080 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
08-23 13:40:31.636  6817  6817 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 13:40:31.636  1018  1080 W ActivityManager: userId = 0, bbcId = -10000
08-23 13:40:31.636  1018  1080 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 13:40:31.636  1018  1080 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-23 13:40:31.636  6817  6817 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-23 13:40:31.646  1018  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-23 13:40:31.646  1018  1049 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
08-23 13:40:31.646   259   259 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, uhalitest
08-23 13:40:31.646  2812  2812 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.listner.MainReciver } | timestamp: Tue Aug 23 13:40:31 GMT+02:00 2016
08-23 13:40:31.656  1018  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-23 13:40:31.656  1018  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
08-23 13:40:31.656  1018  1330 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-23 13:40:31.656  1018  1330 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
08-23 13:40:31.656  1018  1330 W ActivityManager: userId = 0, bbcId = -10000
08-23 13:40:31.666  1018  1330 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 13:40:31.666  1018  1330 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
08-23 13:40:31.666  6817  6817 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:40:31.666  6817  6817 D ActivityThread: Added TimaKeyStore provider
08-23 13:40:31.666  2812  2812 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
08-23 13:40:31.666  1018  1522 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-23 13:40:31.676  1018  1018 V ActivityManager: Display changed displayId=0
08-23 13:40:31.676  2812  2812 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
08-23 13:40:31.676  1018  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-23 13:40:31.686  2812  2812 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
08-23 13:40:31.696  2812  2812 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
08-23 13:40:31.696  2812  6832 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService }
08-23 13:40:31.696  1018  1522 D PersonaManager: isKioskContainerExistOnDevice
08-23 13:40:31.696  2812  6832 I KLMS-2.5.123: : KLMSIntentService(): TIME_CHANGED
08-23 13:40:31.706  1018  3269 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
08-23 13:40:31.706  1018  3269 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:31.706  1018  3269 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:31.706  1018  3269 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:31.706  1018  3269 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:31.706  2812  6832 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().START : Tue Aug 23 13:40:31 GMT+02:00 2016
08-23 13:40:31.716  6834  6834 E Zygote  : MountEmulatedStorage()
08-23 13:40:31.716  6834  6834 E Zygote  : v2
08-23 13:40:31.716  6834  6834 I libpersona: KNOX_SDCARD checking this for 10036
08-23 13:40:31.716  6834  6834 I libpersona: KNOX_SDCARD not a persona
08-23 13:40:31.716  6834  6834 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 13:40:31.726  6834  6834 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 13:40:31.726  6834  6834 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-23 13:40:31.726  1018  3269 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/com.osp.broadcastreceiver.StdBroadcastReceiver: pid=6834 uid=10036 gids={50036, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-23 13:40:31.726  2812  6832 I KLMS-2.5.123: : StateImplV2(): dateTimeChanged().END
08-23 13:40:31.736  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 66
08-23 13:40:31.736  2812  2812 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
08-23 13:40:31.756   259  1157 I SurfaceFlinger: id=8 Removed Mauncher (5/9)
08-23 13:40:31.756   259  1164 I SurfaceFlinger: id=8 Removed Mauncher (-2/9)
08-23 13:40:31.756  6834  6834 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:40:31.756  6834  6834 D ActivityThread: Added TimaKeyStore provider
08-23 13:40:31.766  1509  1509 V ActivityThread: updateVisibility : ActivityRecord{40546bf token=android.os.BinderProxy@2bb42ee6 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-23 13:40:31.766  1509  1509 D Launcher: onTrimMemory. Level: 20
08-23 13:40:31.766  1900  6814 I EventLogService: Aggregate from 1471950622914 (log), 1471950622914 (data)
08-23 13:40:31.806  6834  6834 I SA      : [[OCP] ] Database Name : openData.db, DATABASE_VERSION : 2, context : com.osp.app.signin.SamsungService@17f7511b
08-23 13:40:31.816  6834  6834 I SA      : [SSP] onCreated
08-23 13:40:31.826  6834  6834 I SA      : [TPM] There is no property file
08-23 13:40:31.836  6834  6834 I SA      : [SCU] isHaveSA() - false
08-23 13:40:31.836  6817  6817 I WebViewFactory: Loading com.google.android.webview version 45.0.2454.95 (code 246109500)
08-23 13:40:31.836  6834  6834 I SA      : [TPM] getModelProperty : null
08-23 13:40:31.836  6834  6834 I SA      : [TPM] getCSCProperty : null
08-23 13:40:31.836  6834  6834 I SA      : [DM] FLOATING AMOLED FEATURE: true
08-23 13:40:31.836  6834  6834 I SA      : [DM] PRODUCT AMOLED FEATURE: false
08-23 13:40:31.836  6834  6834 I SA      : [DM] TFT FEATURE: false
08-23 13:40:31.836  6784  6784 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
,08-23 13:40:31.866  6817  6817 I cr.library_loader: Time to load native libraries: 3 ms (timestamps 5799-5802)
08-23 13:40:31.866  6817  6817 I cr.library_loader: Expected native library version number "", actual native library version number ""
,08-23 13:40:31.876  6834  6834 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,08-23 13:40:31.876  6834  6834 I SA      : [DM] init START
,08-23 13:40:31.876  6834  6834 I SA      : [DM] This device is not a Vodafone
,08-23 13:40:31.886  6834  6834 W ResourceType: Failure getting entry for 0x7f060005 (t=5 e=5) (error -75)
08-23 13:40:31.886  6834  6834 W ResourceType: Failure getting entry for 0x7f060006 (t=5 e=6) (error -75)
08-23 13:40:31.886  6834  6834 W ResourceType: Failure getting entry for 0x7f060007 (t=5 e=7) (error -75)
08-23 13:40:31.886  6834  6834 W ResourceType: Failure getting entry for 0x7f060008 (t=5 e=8) (error -75)
08-23 13:40:31.886  6834  6834 W ResourceType: Failure getting entry for 0x7f060009 (t=5 e=9) (error -75)
08-23 13:40:31.886  6834  6834 W ResourceType: Failure getting entry for 0x7f06000a (t=5 e=10) (error -75)
08-23 13:40:31.886  6834  6834 W ResourceType: Failure getting entry for 0x7f06000b (t=5 e=11) (error -75)
08-23 13:40:31.886  6834  6834 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 13:40:31.886  6834  6834 W ResourceType: Failure getting entry for 0x7f060017 (t=5 e=23) (error -75)
08-23 13:40:31.886  6834  6834 W ResourceType: Failure getting entry for 0x7f060018 (t=5 e=24) (error -75)
08-23 13:40:31.886  6834  6834 W ResourceType: Failure getting entry for 0x7f06001a (t=5 e=26) (error -75)
08-23 13:40:31.896  6834  6834 W ResourceType: Failure getting entry for 0x7f06001c (t=5 e=28) (error -75)
,08-23 13:40:31.896  6834  6834 W ResourceType: Failure getting entry for 0x7f06001e (t=5 e=30) (error -75)
08-23 13:40:31.896  6834  6834 W ResourceType: Failure getting entry for 0x7f060020 (t=5 e=32) (error -75)
,08-23 13:40:31.896  6834  6834 W ResourceType: Failure getting entry for 0x7f060021 (t=5 e=33) (error -75)
08-23 13:40:31.896  6834  6834 W ResourceType: Failure getting entry for 0x7f060022 (t=5 e=34) (error -75)
,08-23 13:40:31.896  6834  6834 W ResourceType: Failure getting entry for 0x7f060023 (t=5 e=35) (error -75)
,08-23 13:40:31.896  6834  6834 W ResourceType: Failure getting entry for 0x7f060025 (t=5 e=37) (error -75)
08-23 13:40:31.896  6834  6834 W ResourceType: Failure getting entry for 0x7f060026 (t=5 e=38) (error -75)
,08-23 13:40:31.896  6834  6834 W ResourceType: Failure getting entry for 0x7f060028 (t=5 e=40) (error -75)
,08-23 13:40:31.896  6834  6834 W ResourceType: Failure getting entry for 0x7f060029 (t=5 e=41) (error -75)
08-23 13:40:31.896  6834  6834 W ResourceType: Failure getting entry for 0x7f06002a (t=5 e=42) (error -75)
,08-23 13:40:31.896  6834  6834 W ResourceType: Failure getting entry for 0x7f06002d (t=5 e=45) (error -75)
08-23 13:40:31.896  6834  6834 W ResourceType: Failure getting entry for 0x7f06002f (t=5 e=47) (error -75)
,08-23 13:40:31.896  6834  6834 W ResourceType: Failure getting entry for 0x7f06002e (t=5 e=46) (error -75)
08-23 13:40:31.896  6834  6834 W ResourceType: Failure getting entry for 0x7f060030 (t=5 e=48) (error -75)
08-23 13:40:31.896  6834  6834 W ResourceType: Failure getting entry for 0x7f060032 (t=5 e=50) (error -75),
08-23 13:40:31.896  6834  6834 W ResourceType: Failure getting entry for 0x7f060031 (t=5 e=49) (error -75)
,08-23 13:40:31.906  6834  6834 I SA      : [SCU] isHaveSA() - false
08-23 13:40:31.906  6834  6834 I SA      : support phone number id : false,
08-23 13:40:31.906  6834  6834 I SA      : [DM] Supports Ref Jpn : true
08-23 13:40:31.906  1018  1044 W ProcessCpuTracker: Skipping unknown process pid 6784
08-23 13:40:31.906  6834  6834 I SA      : [DM] init END
08-23 13:40:31.906  6817  6817 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2cf4c893}
08-23 13:40:31.906  6817  6817 I cr.library_loader: Expected native library version number "", actual native library version number ""
08-23 13:40:31.906  6817  6817 I chromium: [INFO:library_loader_hooks.cc(121)] Chromium logging enabled: level = 0, default verbosity = 0
,08-23 13:40:31.946  6817  6817 I cr.BrowserStartup: Initializing chromium process, singleProcess=true
,08-23 13:40:31.946  6817  6817 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 13:40:31.946  1018  1508 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-23 13:40:31.956  1018  1508 D BatteryService: level:100, scale:100, status:2, health:2, present:true, voltage: 4191, temperature: 273, technology: Li-ion, AC powered:false, USB powered:true, POGO powered:false, Wireless powered:false, icon:17303737, invalid charger:0
,08-23 13:40:31.956  1018  1508 D BatteryService: online:4, current avg:0, charge type:1, power sharing:false, high voltage charger:false, capacity:190000, current_now:0
,08-23 13:40:31.956  1018  1018 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-23 13:40:31.956  1018  1508 D BatteryService: stay LED for charging
,08-23 13:40:31.956  1018  4439 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,08-23 13:40:31.956  1018  4439 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:31.956  6817  6817 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-23 13:40:31.956  1018  4439 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:31.956  1018  4439 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 13:40:31.956  1018  4439 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 13:40:31.966  6857  6857 E Zygote  : MountEmulatedStorage()
08-23 13:40:31.976  6857  6857 E Zygote  : v2
08-23 13:40:31.976  6857  6857 I libpersona: KNOX_SDCARD checking this for 10058
08-23 13:40:31.976  6857  6857 I libpersona: KNOX_SDCARD not a persona
,08-23 13:40:31.976  6857  6857 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 13:40:31.976  6857  6857 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-23 13:40:31.976  6857  6857 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL,
,08-23 13:40:31.976  1018  4439 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=6857 uid=10058 gids={50058, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-23 13:40:31.976  1018  4439 I ActivityManager: Killing 6428:com.sec.android.app.soundalive/u0a48 (adj 15): empty #21
,08-23 13:40:31.986  6817  6817 I Adreno-EGL: <qeglDrvAPI_eglInitialize:379>: EGL 1.4 QUALCOMM build: SKARAJGA_AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018+PATCH[ES]_msm8916_32_refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018__release_ENGG (I856e09677e)
08-23 13:40:31.986  6817  6817 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.02
08-23 13:40:31.986  6817  6817 I Adreno-EGL: Build Date: 04/06/15 Mon
08-23 13:40:31.986  6817  6817 I Adreno-EGL: Local Branch: 
08-23 13:40:31.986  6817  6817 I Adreno-EGL: Remote Branch: refs/tags/AU_LINUX_ANDROID_LA.BR.1.1.2_RB1.05.00.02.031.018
08-23 13:40:31.986  6817  6817 I Adreno-EGL: Local Patches: 112c106f3772623daa7b4181c6cf23491044ead1 Revert "Disable ASTC on A405"
08-23 13:40:31.986  6817  6817 I Adreno-EGL:                  58a118cb818fdc906095a49a90977c15f9d3b223 Remove ASTC
,08-23 13:40:31.986  1018  1018 I MotionRecognitionService: Plugged
,08-23 13:40:31.986  1018  1018 I MotionRecognitionService: mGripSensorEnabled= false
,08-23 13:40:31.996  1179  1179 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-23 13:40:31.996  1179  1179 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-23 13:40:31.996  1425  1425 V EmergencyMode: [EmergencyStateReceiver] onReceive : android.intent.action.BATTERY_CHANGED
08-23 13:40:31.996  1425  1425 V EmergencyMode: [EmergencyStateReceiver] ACTION_BATTERY_CHANGED mBatteryLevelForLogging = 100
,08-23 13:40:32.006  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-23 13:40:32.006  3203  3203 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-23 13:40:32.016  3203  3343 D HeadsetStateMachine: Disconnected process message: 10
,08-23 13:40:32.016  6857  6857 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 13:40:32.016  6857  6857 D ActivityThread: Added TimaKeyStore provider
,08-23 13:40:32.016  1018  1031 I ActivityManager: Killing 5937:com.google.android.googlequicksearchbox:search/u0a52 (adj 15): empty #21
,08-23 13:40:32.026  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-23 13:40:32.026  1179  1179 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:2 health:2
,08-23 13:40:32.026  1179  1179 D SViewCoverView: BroadcastReceiver onReceive() : action : android.intent.action.BATTERY_CHANGED
08-23 13:40:32.026  1179  1179 D SViewCoverView: level :100 plugged : 2
,08-23 13:40:32.066  6817  6817 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,08-23 13:40:32.076  6857  6857 I ExternalOEMControlProvider: onCreate
,08-23 13:40:32.086  6817  6817 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-23 13:40:32.086  6817  6817 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.FloatingSelectActionModeCallback>
,08-23 13:40:32.096  6817  6817 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-23 13:40:32.096  6817  6817 I art     : Rejecting re-init on previously-failed class java.lang.Class<com.android.webview.chromium.WebViewContentsClientAdapter$WebResourceErrorImpl>
,08-23 13:40:32.106  1018  3269 I ActivityManager: Killing 6128:com.sec.android.gallery3d/u0a39 (adj 15): empty #21,
,08-23 13:40:32.106  1781  1781 D accuweather: [KK AccuPhone]>>> WC:30 [0:0] action : androidintentactionTIME_SET
,08-23 13:40:32.116  1781  1781 D accuweather: [KK AccuPhone]>>> UIMEM:105 [0:0] The widget does not exist in idle!!
,08-23 13:40:32.116  1018  4439 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,08-23 13:40:32.116  1018  4439 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 13:40:32.116  1018  4439 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:32.116  1018  4439 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:32.116  1018  4439 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 13:40:32.116  6857  6886 I  Time Manager : Time Difference not stored. TIME_DIFFERENCE
,08-23 13:40:32.126  6887  6887 E Zygote  : MountEmulatedStorage()
08-23 13:40:32.126  6887  6887 E Zygote  : v2
08-23 13:40:32.126  6887  6887 I libpersona: KNOX_SDCARD checking this for 10081
08-23 13:40:32.126  6887  6887 I libpersona: KNOX_SDCARD not a persona
,08-23 13:40:32.126  6887  6887 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 13:40:32.136  1018  4439 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=6887 uid=10081 gids={50081, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-23 13:40:32.136  6887  6887 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-23 13:40:32.136  6887  6887 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 13:40:32.156  6887  6887 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 13:40:32.156  6887  6887 D ActivityThread: Added TimaKeyStore provider
,08-23 13:40:32.166  6887  6887 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,08-23 13:40:32.166  6887  6887 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-23 13:40:32.166  6887  6887 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 13:40:32.166  6887  6887 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-23 13:40:32.166  6887  6887 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,08-23 13:40:32.196  1018  1044 W ActivityManager: Activity pause timeout for ActivityRecord{196fb3d u0 com.test.thalitest/.MainActivity t163}
,08-23 13:40:32.216  1018  1522 D SettingsProvider: name = next_alarm_formatted
,08-23 13:40:32.216  1018  1522 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 13:40:32.216  1018  1522 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-23 13:40:32.216  1018  1522 D SettingsProvider: selectionArgs: false
08-23 13:40:32.216  1018  1522 D SettingsProvider: selectionArgs: 10081
08-23 13:40:32.216  1018  1522 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 13:40:32.216  1018  1522 D SettingsProvider: ret = -1
,08-23 13:40:32.216  6514  6514 I Mms/MmsApp:  start initViewCache mms
,08-23 13:40:32.226  6514  6514 D Mms/ComposeMessageFragment: [start]    fillCache consume time = 1926.890259
08-23 13:40:32.226  6514  6514 D Mms/ComposeMessageFragment: fillCache, easy = false
,08-23 13:40:32.236  6817  6817 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 13:40:32.256  6817  6817 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-23 13:40:32.266  6817  6817 D PhoneWindow: *FMB* installDecor mIsFloating : false
,08-23 13:40:32.266  6817  6817 D PhoneWindow: *FMB* installDecor flags : -2139027200
,08-23 13:40:32.276  6817  6817 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-23 13:40:32.276  6817  6817 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 13:40:32.276  6817  6817 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 13:40:32.346  6887  6887 W art     : Verification of void com.sec.android.app.clockpackage.alarm.Alarm.InitAlarmList() took 117.235ms
,08-23 13:40:32.356  6514  6514 D AbsListView: Get MotionRecognitionManager
,08-23 13:40:32.366  1018  1505 D MotionRecognitionService:  ssp status : false
,08-23 13:40:32.366  6514  6514 D Mms/ComposeMessageFragment: [end]    fillCache consume time = 145.797969
,08-23 13:40:32.406  6817  6910 D OpenGLRenderer: Render dirty regions requested: true
,08-23 13:40:32.416  1018  1222 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-23 13:40:32.416  1018  1222 D KnoxTimeoutHandler: postActiveUserChange for user 0
,08-23 13:40:32.416  1018  1222 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-23 13:40:32.416  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-23 13:40:32.416  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
,08-23 13:40:32.416  6817  6880 W chromium: [WARNING:data_reduction_proxy_config.cc(630)] SPDY proxy OFF at startup
,08-23 13:40:32.426  6817  6817 V ActivityThread: updateVisibility : ActivityRecord{69a0c73 token=android.os.BinderProxy@337802c4 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-23 13:40:32.426  6817  6817 D PhoneWindow: *FMB* isFloatingMenuEnabled mFloatingMenuBtn : null
08-23 13:40:32.426  6817  6817 D PhoneWindow: *FMB* isFloatingMenuEnabled return false
,08-23 13:40:32.446   259   259 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=404, NainActivit
,08-23 13:40:32.456  1018  1080 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-23 13:40:32.466  1018  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 13:40:32.466  1018  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:32.466  1018  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:32.466  1018  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 13:40:32.476  1018  1505 D InputDispatcher: Focus entered window: 6817
,08-23 13:40:32.476  6514  6514 D Mms/BubbleViewCache: fillCache bubble = 1
,08-23 13:40:32.476  6913  6913 E Zygote  : MountEmulatedStorage()
08-23 13:40:32.476  6913  6913 E Zygote  : v2
08-23 13:40:32.476  6913  6913 I libpersona: KNOX_SDCARD checking this for 10090
08-23 13:40:32.476  6913  6913 I libpersona: KNOX_SDCARD not a persona
,08-23 13:40:32.476  6913  6913 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 13:40:32.476  6913  6913 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 13:40:32.476  6913  6913 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 13:40:32.486  6817  6817 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-23 13:40:32.486  6817  6910 I OpenGLRenderer: Initialized EGL, version 1.4
,08-23 13:40:32.486  1018  1080 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=6913 uid=10090 gids={50090, 9997, 3003} abi=armeabi-v7a
08-23 13:40:32.486  1018  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-23 13:40:32.486  1018  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-23 13:40:32.486  1018  1080 I ActivityManager: Killing 6031:com.google.android.apps.plus/u0a117 (adj 15): empty #21,
,08-23 13:40:32.496  6817  6910 D OpenGLRenderer: Get maximum texture size. GL_MAX_TEXTURE_SIZE is 4096
,08-23 13:40:32.496  6817  6910 D OpenGLRenderer: Enabling debug mode 0
,08-23 13:40:32.506  6913  6913 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:40:32.506   321   321 I art     : Explicit concurrent mark sweep GC freed 8679(369KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 612us total 21.761ms
,08-23 13:40:32.516  6913  6913 D ActivityThread: Added TimaKeyStore provider
,08-23 13:40:32.526   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 599us total 17.084ms
,08-23 13:40:32.526  1018  1470 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-23 13:40:32.536  1018  6931 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 13:40:32.536  1179  1179 D PanelView: There is/are notification(s) 
,08-23 13:40:32.536   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 584us total 16.526ms
,08-23 13:40:32.546  1018  1049 I ActivityManager: Displayed Component not be shown by security: +846ms (total +934ms)
,08-23 13:40:32.546  1018  1049 W ActivityManager: mDVFSHelper.release()
,08-23 13:40:32.546  1018  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{196fb3d u0 com.test.thalitest/.MainActivity t163} time:96488
,08-23 13:40:32.556   259  1157 I SurfaceFlinger: id=12 Removed uhalitest (7/9)
,08-23 13:40:32.556   259   447 I SurfaceFlinger: id=12 Removed uhalitest (-2/9)
,08-23 13:40:32.566  6913  6913 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,08-23 13:40:32.566  6817  6817 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-23 13:40:32.566  6817  6817 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@337802c4 time:96504
,08-23 13:40:32.566  6913  6913 D elm:15121: ELMEngine.ELMEngine( context ).
,08-23 13:40:32.566  6913  6913 D elm:15121: MDMBridge.setEnterpriseBridge()
,08-23 13:40:32.566  1018  1030 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-23 13:40:32.576  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
08-23 13:40:32.576  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-23 13:40:32.586  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 13:40:32.586  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
08-23 13:40:32.586  6913  6913 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,08-23 13:40:32.586  1018  1470 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,08-23 13:40:32.596  1018  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:32.596  1018  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:32.596  1018  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:32.596  1018  1470 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 13:40:32.596  6817  6817 W cr.BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6817
,08-23 13:40:32.606  6913  6913 D elm:15121: ElmAgentService : onCreate()
,08-23 13:40:32.606  6913  6935 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.sec.esdk.elm/.service.ElmAgentService },
,08-23 13:40:32.606  6913  6935 D elm:15121: ELMAgentService.listeningToTimeDateChanges( context, intent ).,
,08-23 13:40:32.606  6937  6937 E Zygote  : MountEmulatedStorage()
,08-23 13:40:32.616  6937  6937 E Zygote  : v2
,08-23 13:40:32.616  6937  6937 I libpersona: KNOX_SDCARD checking this for 10130
08-23 13:40:32.616  6937  6937 I libpersona: KNOX_SDCARD not a persona,
,08-23 13:40:32.616  6937  6937 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 13:40:32.616  6937  6937 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-23 13:40:32.616  1018  1470 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=6937 uid=10130 gids={50130, 9997} abi=armeabi-v7a
08-23 13:40:32.616  6937  6937 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
08-23 13:40:32.616  6913  6913 D elm:15121: ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
08-23 13:40:32.616  6913  6913 D elm:15121: ModuleBase.ModifySetAlarm()
08-23 13:40:32.616  6913  6913 D elm:15121: MDMBridge.getInstance()
08-23 13:40:32.616  6913  6913 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-23 13:40:32.626  6913  6913 D elm:15121: ElmAgentService : onDestroy().
,08-23 13:40:32.626  1018  4442 I ActivityManager: Killing 6492:com.samsung.android.app.assistantmenu/1000 (adj 15): empty #21
,08-23 13:40:32.636  1880  1880 I SamsungIME: getCurrentCandidateView
,08-23 13:40:32.646  6937  6937 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 13:40:32.646  6937  6937 D ActivityThread: Added TimaKeyStore provider
,08-23 13:40:32.666  6937  6937 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-23 13:40:32.666  6937  6937 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,08-23 13:40:32.686  1018  1505 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,08-23 13:40:32.686  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 13:40:32.686  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:32.686  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 13:40:32.686  1018  1505 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 13:40:32.696  6954  6954 E Zygote  : MountEmulatedStorage(),
08-23 13:40:32.696  6954  6954 E Zygote  : v2
08-23 13:40:32.696  6954  6954 I libpersona: KNOX_SDCARD checking this for 10131
08-23 13:40:32.696  6954  6954 I libpersona: KNOX_SDCARD not a persona
,08-23 13:40:32.696  6954  6954 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 13:40:32.706  1018  1505 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=6954 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a,
,08-23 13:40:32.706  1018  1505 I ActivityManager: Killing 6533:com.samsung.android.provider.shootingmodeprovider/u0a148 (adj 15): empty #21
08-23 13:40:32.706  6954  6954 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 13:40:32.706  6954  6954 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 13:40:32.726  6954  6954 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:40:32.726  6954  6954 D ActivityThread: Added TimaKeyStore provider
,08-23 13:40:32.756  6954  6954 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-23 13:40:32.756  6954  6954 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 13:40:32.756  6954  6954 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-23 13:40:32.766  1880  1880 D SamsungIME: Dismiss ExpandCandiate
,08-23 13:40:32.796  1018  1522 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
08-23 13:40:32.796  1018  1522 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
,08-23 13:40:32.806  1018  1522 W ActivityManager: userId = 0, bbcId = -10000
,08-23 13:40:32.806  1018  1522 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 13:40:32.806  1018  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-23 13:40:32.806  2540  6372 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-23 13:40:32.826  1018  1466 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-23 13:40:32.826  1018  1466 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,08-23 13:40:32.826  1018  1466 W ActivityManager: userId = 0, bbcId = -10000
08-23 13:40:32.826  1018  1466 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 13:40:32.826  1018  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-23 13:40:32.836  1018  1080 D ActivityManager: getContentProviderImpl callerProcessName:com.android.calendar, calleePkgName: com.android.providers.calendar
,08-23 13:40:32.836  1018  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 13:40:32.836  1018  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:32.836  1018  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 13:40:32.836  1018  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 13:40:32.846  6817  6817 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-23 13:40:32.856  6977  6977 E Zygote  : MountEmulatedStorage()
,08-23 13:40:32.856  6977  6977 E Zygote  : v2
08-23 13:40:32.856  6977  6977 I libpersona: KNOX_SDCARD checking this for 10037
08-23 13:40:32.856  6977  6977 I libpersona: KNOX_SDCARD not a persona
,08-23 13:40:32.856  6977  6977 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 13:40:32.856  6977  6977 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 13:40:32.856  1018  1080 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=6977 uid=10037 gids={50037, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-23 13:40:32.856  6977  6977 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-23 13:40:32.856  1018  4439 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
08-23 13:40:32.856  1018  4439 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:32.856  1018  4439 E ActivityManager: checkUser: useridlist=null, currentuser=0,
08-23 13:40:32.856  1018  4439 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:32.856  1018  4439 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 13:40:32.876  6987  6987 E Zygote  : MountEmulatedStorage(),
08-23 13:40:32.876  6987  6987 E Zygote  : v2
08-23 13:40:32.876  6987  6987 I libpersona: KNOX_SDCARD checking this for 1000
08-23 13:40:32.876  6987  6987 I libpersona: KNOX_SDCARD not a persona
,08-23 13:40:32.876  6987  6987 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
,08-23 13:40:32.886  1018  4439 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.DateTimeChangedReceiver: pid=6987 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a,
,08-23 13:40:32.886  6987  6987 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-23 13:40:32.886  6987  6987 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 13:40:32.896  6977  6977 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:40:32.896  6977  6977 D ActivityThread: Added TimaKeyStore provider
,08-23 13:40:32.926  6987  6987 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 13:40:32.926  6987  6987 D ActivityThread: Added TimaKeyStore provider
,08-23 13:40:32.936  6977  6977 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,08-23 13:40:32.966  6977  6977 I CalendarProvider2: CalendarProvider2.onCreate() called
,08-23 13:40:32.976  6817  6929 D jxcore_app_log: JniHelper::setJavaVM(0xb82602b0), pthread_self() = -1199627616
,08-23 13:40:32.976  6987  6987 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-23 13:40:32.976  6987  6987 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-23 13:40:32.976  6987  6987 D SecurityLogAgent: StateMachine : Current State = 1
,08-23 13:40:32.986  6817  6929 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-23 13:40:32.986  6817  6929 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-23 13:40:32.986  6817  6929 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-23 13:40:32.986  6817  6929 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-23 13:40:32.986  6817  6929 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-23 13:40:32.986  6817  6929 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33715ae1 added. We now have 1 listener(s)
,08-23 13:40:32.986  1018  1222 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.taskmanager, hostingType: broadcast
,08-23 13:40:32.986  1018  1222 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:32.986  1018  1222 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:32.986  1018  1222 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:32.986  1018  1222 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 13:40:32.996  1880  1880 I SamsungIME: getDebugLevel  : 0x4f4c
,08-23 13:40:33.006  1018  1222 I ActivityManager: Start proc com.sec.android.app.taskmanager for broadcast com.sec.android.app.taskmanager/.UnusedAppsIntentReceiver: pid=7010 uid=10153 gids={50153, 9997} abi=armeabi-v7a,
,08-23 13:40:33.006  1018  1222 I ActivityManager: Killing 6544:com.google.android.apps.docs/u0a87 (adj 15): empty #21
,08-23 13:40:33.016  6817  6929 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 08:EC:A9:50:75:41
,08-23 13:40:33.016  6817  6929 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "08:EC:A9:50:75:41"
08-23 13:40:33.016  6817  6929 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 13:40:33.016  6472  6504 D AcmsKeyStoreHelper:  getKeyStoreForApplication Enter
08-23 13:40:33.016  6817  6929 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 13:40:33.016  7010  7010 E Zygote  : MountEmulatedStorage()
08-23 13:40:33.016  7010  7010 E Zygote  : v2
08-23 13:40:33.016  7010  7010 I libpersona: KNOX_SDCARD checking this for 10153
08-23 13:40:33.016  7010  7010 I libpersona: KNOX_SDCARD not a persona
08-23 13:40:33.026  6817  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-23 13:40:33.026  6817  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-23 13:40:33.026  6817  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-23 13:40:33.026  6817  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 08:EC:A9:50:75:41
08-23 13:40:33.026  6817  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-23 13:40:33.026  6817  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-23 13:40:33.026  6817  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-23 13:40:33.026  6817  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-23 13:40:33.026  6817  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-23 13:40:33.026  6817  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-23 13:40:33.026  6817  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-23 13:40:33.026  6817  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-23 13:40:33.026  6817  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-23 13:40:33.026  6817  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-23 13:40:33.026  6817  6929 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3a4f4 added. We now have 1 listener(s)
08-23 13:40:33.026  6817  6929 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 13:40:33.026  6817  6929 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 13:40:33.026  6817  6929 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413,
08-23 13:40:33.026  6817  6929 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-23 13:40:33.026  6817  6929 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-23 13:40:33.026  6817  6929 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-23 13:40:33.026  6472  6504 I AcmsKeyStoreHelper: Key Store exist
08-23 13:40:33.026  6472  6504 I AcmsKeyStoreHelper: Hence loading the keystore file
,08-23 13:40:33.036  6817  6929 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 13:40:33.036  6817  6929 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 08:EC:A9:50:75:41,
,08-23 13:40:33.036  6817  6929 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-23 13:40:33.036  6817  6929 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 13:40:33.036  6817  6929 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 13:40:33.036  6817  6929 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-23 13:40:33.036  6817  6929 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 13:40:33.036  6817  6929 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 13:40:33.036  6817  6929 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 13:40:33.036  6817  6929 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 13:40:33.036  6817  6929 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 13:40:33.036  6817  6929 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-23 13:40:33.036  6817  6929 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 13:40:33.046  6817  6929 I io.jxcore.node.LifeCycleMonitor: start: OK
08-23 13:40:33.046  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 13:40:33.046  6817  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 13:40:33.056  7010  7010 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 13:40:33.056  7010  7010 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-23 13:40:33.056  7010  7010 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 13:40:33.076  6817  6817 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-23 13:40:33.086  7010  7010 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 13:40:33.086  7010  7010 D ActivityThread: Added TimaKeyStore provider
,08-23 13:40:33.126  6472  6504 D AcmsKeyStoreHelper:  getKeyStoreForApplication Exit
08-23 13:40:33.126  6472  6504 I AcmsCertificateMngr: getKeyStoreForApplication success 
08-23 13:40:33.126  6472  6504 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>1
08-23 13:40:33.126  6472  6504 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-23 13:40:33.126  6472  6504 D AcmsServiceMonitor: Decrementing - Counter value: 1
08-23 13:40:33.126  6472  6504 D AcmsCore: AcmsCore: ACMS_APP_INSTALLED
,08-23 13:40:33.136  6472  6504 D AcmsCore: This is NOT a valid MirrorLink app
08-23 13:40:33.136  6472  6504 D AcmsCore: Decremented Counter Value : AcmsCoreHandler.handleMessage=>2
08-23 13:40:33.136  6472  6504 D AcmsServiceMonitor: AcmsServiceMonitor.getAcmsSvcMonitor() - Enter
08-23 13:40:33.136  6472  6504 D AcmsServiceMonitor: Decrementing - Counter value: 0
08-23 13:40:33.136  6472  6504 D AcmsServiceMonitor: Counter value is 0: Stopping ACMS service
,08-23 13:40:33.136  6472  6472 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
,08-23 13:40:33.136  6472  6472 D AcmsService: Enter onDestroy
08-23 13:40:33.136  6472  6472 I AcmsService: cleanUp(): inside service clean up
,08-23 13:40:33.136  6472  6472 D AcmsCore: AcmsCore: inside DeInit
08-23 13:40:33.136  6472  6472 D AcmsCore: AcmsCore: mLooperHandler is not null and making it null
,08-23 13:40:33.136  7010  7010 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-23 13:40:33.136  6472  6472 D AcmsCertificateMngr: AcmsCertificateMngr: inside cleanup
,08-23 13:40:33.136  6472  6472 D AcmsRevocationMngr: AcmsRevocationMngr: inside cleanup
08-23 13:40:33.136  6472  6472 D AcmsKeyStoreHelper: KeyStoreHelper: inside cleanup
,08-23 13:40:33.136  6472  6472 D AcmsAppEntryInterface: AppEntryInterface: Inside CleanUp
,08-23 13:40:33.146  6472  6472 D AcmsServiceMonitor: getSvcCounter - Counter value: 0
08-23 13:40:33.146  6472  6472 D AcmsService: killing acms process
08-23 13:40:33.146  6472  6472 I Process : Sending signal. PID: 6472 SIG: 9
,08-23 13:40:33.146  1018  4439 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
08-23 13:40:33.146  1018  4439 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,08-23 13:40:33.146  1018  4439 W ActivityManager: userId = 0, bbcId = -10000
,08-23 13:40:33.146  1018  4439 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 13:40:33.146  1018  4439 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,08-23 13:40:33.156  1018  1031 D ActivityManager: startProcessLocked calleePkgName: com.qualcomm.timeservice, hostingType: broadcast
,08-23 13:40:33.156  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:33.156  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:33.156  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:33.156  1018  1031 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 13:40:33.176  7031  7031 E Zygote  : MountEmulatedStorage(),
08-23 13:40:33.176  7031  7031 E Zygote  : v2
08-23 13:40:33.176  7031  7031 I libpersona: KNOX_SDCARD checking this for 1000
08-23 13:40:33.176  7031  7031 I libpersona: KNOX_SDCARD not a persona
,08-23 13:40:33.176  1018  1031 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=7031 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-23 13:40:33.176  7031  7031 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 13:40:33.176  1018  1031 I ActivityManager: Killing 6570:com.samsung.android.bbc.bbcagent/1000 (adj 15): empty #21
08-23 13:40:33.176  7031  7031 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 13:40:33.186  1880  1880 I SamsungIME: getDebugLevel  : 0x4f4c
,08-23 13:40:33.186  7031  7031 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 13:40:33.196  1880  1880 I SamsungIME: KeybaordView init() : load resources
,08-23 13:40:33.216   274   274 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb81447c8
08-23 13:40:33.216  7031  7031 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:40:33.216   274   274 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
08-23 13:40:33.216   274   274 I rmt_storage: wakelock acquired: 1, error no: 42
08-23 13:40:33.216   274   309 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1206631112)
08-23 13:40:33.216  7031  7031 D ActivityThread: Added TimaKeyStore provider
,08-23 13:40:33.226  1018  1470 I ActivityManager: Process ACMS.Process (pid 6472)(adj 0) has died(32,783)
,08-23 13:40:33.236  1880  1880 I SamsungIME: getCurrentKeyboard
08-23 13:40:33.236  1880  1880 I SamsungIME: getTextKeyboard
,08-23 13:40:33.276   274   309 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 917504
08-23 13:40:33.276   274   309 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
08-23 13:40:33.276   274   309 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1206631112) wakelock released: 1, error no: 0
08-23 13:40:33.276   274   309 I rmt_storage: 
,08-23 13:40:33.276  1018  1222 I ActivityManager: Killing 6592:com.sec.android.widgetapp.tapandpay/u0a152 (adj 15): empty #21
,08-23 13:40:33.276   274   274 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x5 conn_h=0xb81447c8
08-23 13:40:33.286  7031  7031 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1471952433297
08-23 13:40:33.286  7031  7031 D         : TimeServiceNative: User Time to be set is 1471952433298
08-23 13:40:33.286  7031  7031 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
08-23 13:40:33.286  7031  7031 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
08-23 13:40:33.286  7031  7031 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1471952433298
08-23 13:40:33.286  7031  7031 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
08-23 13:40:33.286   333   426 D QC-time-services: Daemon: Connection accepted:time_genoff
08-23 13:40:33.296   333  7047 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1471952433298
08-23 13:40:33.296   333  7047 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1471952433298, operation = 0
08-23 13:40:33.296   333  7047 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS1/18/71 5:23:26
08-23 13:40:33.296   333  7047 D QC-time-services: Daemon:Value read from RTC seconds = 35702606000
08-23 13:40:33.296   333  7047 D QC-time-services: Daemon:new time 1471952433298 
08-23 13:40:33.296   333  7047 D QC-time-services: Daemon: delta 1436249827298 genoff 1436249827298 
08-23 13:40:33.296   333  7047 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436249827298 to memory
08-23 13:40:33.296   333  7047 D QC-time-services: Daemon:Opening File: /data/time/ats_2
08-23 13:40:33.296   333  7047 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
08-23 13:40:33.296  1880  1880 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-23 13:40:33.336   333  7047 D QC-time-services: Updating the TOD offset
08-23 13:40:33.336   333  7047 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1436249827298 to memory
08-23 13:40:33.336   333  7047 D QC-time-services: Daemon:Opening File: /data/time/ats_1
08-23 13:40:33.336   333  7047 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,08-23 13:40:33.336   333  7047 E QC-time-services: Daemon:Update to modem bit set
08-23 13:40:33.336   333  7047 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
08-23 13:40:33.336   333  7047 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1120285027298
,08-23 13:40:33.336  7031  7031 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
08-23 13:40:33.336   333   421 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
08-23 13:40:33.336   333   426 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,08-23 13:40:33.336  1018  4442 I ActivityManager: Killing 6625:com.sec.android.app.samsungapps/u0a9 (adj 15): empty #21
,08-23 13:40:33.346  2540  2540 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
08-23 13:40:33.346  2540  2540 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
,08-23 13:40:33.346  2540  2540 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-23 13:40:33.356  2540  2540 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-23 13:40:33.356  2540  2540 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/weatherinfo
,08-23 13:40:33.366  2540  2540 D daemonapp: [MSC_Daemon]>>> WDSM:54 [0:0] Act : androidintentactionTIME_SET, run:true
,08-23 13:40:33.366  2540  2540 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
08-23 13:40:33.366  2540  2540 D comsamsunglog: [MSC_Daemon]>>> daemonapp [Version : 1504231781758 ] [ 3 ] 
08-23 13:40:33.366  2540  2540 D comsamsunglog: [MSC_Daemon]>>> Header set to : ===> "daemonapp" <===
08-23 13:40:33.366  2540  2540 D comsamsunglog: [MSC_Daemon]>>> ====================================================================================================================
,08-23 13:40:33.366  2540  2540 D daemonapp: [MSC_Daemon]>>> WDSM:95 [0:0] c:null, r:3, slted:null
,08-23 13:40:33.366  2540  2540 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,08-23 13:40:33.366  2540  2540 D daemonapp: [MSC_Daemon]>>> WU:1730 [0:0] PakNme size = 5
,08-23 13:40:33.376  2540  2540 D daemonapp: [MSC_Daemon]>>> WU:264 [0:0] regintype : EUR
,08-23 13:40:33.376  2540  2540 D daemonapp: [MSC_Daemon]>>> WU:320 [0:0] cp type is : cp_eng
08-23 13:40:33.376  2540  2540 D daemonapp: [MSC_Daemon]>>> WU:1734 [0:0] CP Name cp_eng
,08-23 13:40:33.376  2540  2540 D daemonapp: [MSC_Daemon]>>> WCP:1142 [0:0] Provider query : content://apaccuweatherprovider/packagename
,08-23 13:40:33.376  2540  2540 E daemonapp: [MSC_Daemon]>>> WU:1714 [0:0] [NameNotFoundException] !!
,08-23 13:40:33.386  2540  2540 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:61 [0:0] onReceive: androidintentactionTIME_SET
,08-23 13:40:33.386  2540  2540 D comdaemonstockapp: [Daemon_Stock]>>> StockclockDaemonService.java:62 [0:0] appServiceStatus: 0
,08-23 13:40:33.676  6817  7018 W jxcore-log: Initializing JXcore engine
08-23 13:40:33.676  6817  7018 W jxcore-log: JXcore engine is ready
,08-23 13:40:33.736  2035  2035 E audit   : type=1400 msg=audit(1471952433.736:205): avc:  denied  { ioctl } for  pid=7018 comm="Thread-1277" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2061 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-23 13:40:33.736  2035  2035 E audit   :  SEPF_SM-A300FU_5.0.2-1_0051
08-23 13:40:33.736  2035  2035 E audit   : type=1300 msg=audit(1471952433.736:205): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=3 a3=9e8fb8f8 items=0 ppid=321 ppcomm=main pid=7018 auid=4294967295 uid=10170 gid=10170 euid=10170 suid=10170 fsuid=10170 egid=10170 sgid=10170 fsgid=10170 ses=4294967295 tty=(none) comm="Thread-1277" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-23 13:40:33.736  2035  2035 E audit   : type=1320 msg=audit(1471952433.736:205): 
,08-23 13:40:33.756  6817  7018 W jxcore-log: Starting JXcore engine
,08-23 13:40:33.856  1018  3363 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.absolute.android.persistservice.a.run:1065 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 13:40:33.866  6817  7018 W jxcore-log: Platform android
08-23 13:40:33.866  6817  7018 W jxcore-log: 
08-23 13:40:33.866  6817  7018 W jxcore-log: Process ARCH arm
08-23 13:40:33.866  6817  7018 W jxcore-log: 
,08-23 13:40:33.986   289   289 E SMD     : DCD OFF
,08-23 13:40:34.076  6817  7018 I jxcore-log: JXcore Cordova bridge is ready!
08-23 13:40:34.076  6817  7018 I jxcore-log: 
,08-23 13:40:34.076  6817  7018 W jxcore-log: JXcore engine is started
,08-23 13:40:34.076  6817  6929 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-23 13:40:34.076  6817  6817 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-23 13:40:34.096  6817  7018 E jxcore  : Error!: missing name after . operator
08-23 13:40:34.096  6817  7018 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"591","_columnNumber":"9","_msg":"    at $w.prototype._compile@module.js:591:9"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"407","_columnNumber":"1","_msg":"    at $w._load@module.js:407:1"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:260:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,08-23 13:40:34.106  6817  6817 I chromium: [INFO:CONSOLE(56)] "app.js file failed to load : "missing name after . operator\nSyntaxError: missing name after . operator\n    at $w.prototype._compile@module.js:591:9\n    at $w._extensions[\".js\"]@module.js:651:1\n    at $w.prototype.load@module.js:442:1\n    at $w._load@module.js:407:1\n    at $w.prototype.require@module.js:477:8\n    at require@module.js:495:8\n    at internal_methods.loadMainFile@main.js:260:5\n    at JXMobile.executeJSON@main.js:279:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (56)
,08-23 13:40:34.106  6817  6817 I chromium: [INFO:CONSOLE(72)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (72)
,08-23 13:40:34.116  1018  4437 D FocusedStackFrame: Set to : 0
08-23 13:40:34.116  1018  4437 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-23 13:40:34.116  1018  4437 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.launcher
08-23 13:40:34.116  1018  4437 D InputDispatcher: Focused application set to: xxxx
08-23 13:40:34.116  1018  4437 D InputDispatcher: Focus left window: 6817
,08-23 13:40:34.126  1018  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-23 13:40:34.126  1018  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-23 13:40:34.126  1018  4437 I ActivityManager: Killing 6608:com.google.android.partnersetup/u0a14 (adj 15): empty #21
,08-23 13:40:34.136  6817  6929 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 25ms. Plugin should use CordovaInterface.getThreadPool().
,08-23 13:40:34.136  6817  6817 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-23 13:40:34.136  6817  6817 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
,08-23 13:40:34.146  6817  6817 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 13:40:34.146  6817  6817 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 13:40:34.146  6817  6817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 13:40:34.146  6817  6817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 13:40:34.146  6817  6817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33715ae1 removed from the list
08-23 13:40:34.146  6817  6817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 13:40:34.146  6817  6817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24c3a4f4 removed from the list
08-23 13:40:34.146  6817  6817 D io.jxcore.node.ConnectivityMonitor: stop
08-23 13:40:34.146  6817  6817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,08-23 13:40:34.146  6817  6817 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-23 13:40:34.156  6977  6977 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar },
,08-23 13:40:34.166  1018  1044 W ActivityManager: userId = 0, bbcId = -10000
08-23 13:40:34.166  1018  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 13:40:34.166  1018  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.sec.android.widgetapp.SPlannerAppWidget
,08-23 13:40:34.166   259  1040 I SurfaceFlinger: id=13 Removed NainActivit (6/8)
,08-23 13:40:34.166   259  1164 I SurfaceFlinger: id=13 Removed NainActivit (-2/8)
,08-23 13:40:34.166  1018  1330 D ActivityManager: retrieveServiceLocked(): component = com.android.providers.calendar/com.android.providers.calendar.EmptyService; callingUser = 0; userId(target) = 0
,08-23 13:40:34.166  1018  1330 W ActivityManager: userId = 0, bbcId = -10000
08-23 13:40:34.166  1018  1330 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 13:40:34.166  1018  1330 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.providers.calendar
,08-23 13:40:34.176  1018  1518 W ActivityManager: userId = 0, bbcId = -10000
08-23 13:40:34.176  1018  1518 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 13:40:34.176  1018  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,08-23 13:40:34.186  1018  4442 W ActivityManager: mDVFSHelper.acquire()
,08-23 13:40:34.186  1018  1466 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-23 13:40:34.196  1509  1509 D Launcher: onRestart, Launcher: 589884366
,08-23 13:40:34.196  1018  1030 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-23 13:40:34.196  1509  1509 D Launcher: onStart, Launcher: 589884366
,08-23 13:40:34.196  1509  1509 D Launcher.HomeView: onStart
,08-23 13:40:34.206  1509  1509 D Launcher: onResume, Launcher: 589884366
,08-23 13:40:34.206  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.AlertService; callingUser = 0; userId(target) = 0
08-23 13:40:34.206  1018  1470 D SettingsProvider: name = kids_home_mode
,08-23 13:40:34.206  1018  1470 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-23 13:40:34.206  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-23 13:40:34.206  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 13:40:34.206  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
08-23 13:40:34.206  1018  1470 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-23 13:40:34.206  1018  1470 D SettingsProvider: selectionArgs: false
,08-23 13:40:34.206  1018  1470 D SettingsProvider: selectionArgs: 10006
08-23 13:40:34.206  1018  1470 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-23 13:40:34.206  1018  1470 D SettingsProvider: ret = -1
,08-23 13:40:34.206  1509  1509 D Launcher.HomeView: onResume
,08-23 13:40:34.206  1509  1509 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
,08-23 13:40:34.206  1018  3269 W ActivityManager: userId = 0, bbcId = -10000
08-23 13:40:34.216  1018  3269 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 13:40:34.216  1018  3269 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.providers.calendar, destAppInfo.processName = com.android.calendar
,08-23 13:40:34.216  1509  1509 D MenuAppsGridFragment: onResume
,08-23 13:40:34.216  1509  1509 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-23 13:40:34.216  1509  1509 D WallpaperManager: SEC_PRODUCT_FEATURE_COMMON_SUPPORT_TEXTURE_COMPRESSION is true
,08-23 13:40:34.226  1018  4442 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
08-23 13:40:34.226  1018  4442 D ActivityManager: retrieveServiceLocked(): component = com.android.calendar/com.android.calendar.alerts.TaskAlertService; callingUser = 0; userId(target) = 0
,08-23 13:40:34.226  1018  4442 W ActivityManager: userId = 0, bbcId = -10000
08-23 13:40:34.226  1018  4442 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 13:40:34.226  1018  4442 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.android.calendar, destAppInfo.processName = com.android.calendar
,08-23 13:40:34.226  1018  1080 W ActivityManager: userId = 0, bbcId = -10000
08-23 13:40:34.226  1018  1080 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 13:40:34.226  1018  1080 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.contacts
,08-23 13:40:34.236  1018  4437 I splitIntent: Split this intent : com.sec.android.intent.action.HOME_RESUME, mSplitNum[0]=3, mSplitNum[1]=7, mSplitNum[2]=9, mBgSplitQueueNum=3 divideNum= 2 r.nextReceiver= 1 receivers.size=11
08-23 13:40:34.236  1018  4437 I splitIntent: finish to split intent : com.sec.android.intent.action.HOME_RESUME !! Enqueue -> schedule it!!
,08-23 13:40:34.236  1018  4437 W ActivityManager: userId = 0, bbcId = -10000
,08-23 13:40:34.236  1018  4437 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 13:40:34.236  1018  4437 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.gallery3d
,08-23 13:40:34.236  1018  4437 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,08-23 13:40:34.236  1018  4437 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 13:40:34.236  1018  4437 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:34.236  1018  4437 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:34.236  1018  4437 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 13:40:34.256  7053  7053 E Zygote  : MountEmulatedStorage()
,08-23 13:40:34.256  7053  7053 E Zygote  : v2
08-23 13:40:34.256  7053  7053 I libpersona: KNOX_SDCARD checking this for 10039
08-23 13:40:34.256  7053  7053 I libpersona: KNOX_SDCARD not a persona
,08-23 13:40:34.256  7053  7053 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 13:40:34.256  7053  7053 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 13:40:34.256  1018  4437 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.MediaScannerReceiver: pid=7053 uid=10039 gids={50039, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
08-23 13:40:34.256  7053  7053 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-23 13:40:34.256  1018  1518 D ActivityManager: handle home activity for 0
08-23 13:40:34.256  1018  1518 I WallpaperManagerService: switchPersonaWallpaper is called for personaId-0
08-23 13:40:34.256  1018  1518 D KnoxTimeoutHandler: post home show event for user 0
08-23 13:40:34.256  1018  1518 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-23 13:40:34.256  1018  1518 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-23 13:40:34.256  1018  1518 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-23 13:40:34.256  1018  1018 D WallpaperManagerService:  force update = false; persona id = 0; current user =0; current persona = 0
08-23 13:40:34.256  1018  1018 D PersonaManagerService: getPersonasForUser(): returning null!
08-23 13:40:34.256  1018  1018 D KnoxTimeoutHandler: handleHomeShow for 0 and current 0
08-23 13:40:34.256  1018  1018 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-23 13:40:34.256  1509  1509 D Launcher.HomeView: onPause
08-23 13:40:34.266  1509  1509 D Launcher: Launcher::setSystemUiTransparency(): getSystemUiVisibility() after setting  = 0
08-23 13:40:34.266  1018  1044 W ActivityManager: userId = 0, bbcId = -10000
08-23 13:40:34.266  1018  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 13:40:34.266  1018  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings,
,08-23 13:40:34.266  1018  1044 W ActivityManager: userId = 0, bbcId = -10000
08-23 13:40:34.266  1018  1044 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.dualclockdigital, hostingType: broadcast
08-23 13:40:34.266  1018  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 13:40:34.266  1018  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.dualclockdigital
,08-23 13:40:34.266  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:34.266  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:34.266  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:34.266  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 13:40:34.286  7053  7053 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 13:40:34.286  7053  7053 D ActivityThread: Added TimaKeyStore provider
,08-23 13:40:34.286  7066  7066 E Zygote  : MountEmulatedStorage()
08-23 13:40:34.286  7066  7066 E Zygote  : v2
08-23 13:40:34.286  7066  7066 I libpersona: KNOX_SDCARD checking this for 10089
08-23 13:40:34.286  7066  7066 I libpersona: KNOX_SDCARD not a persona
,08-23 13:40:34.286  7066  7066 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 13:40:34.286  1018  1044 I ActivityManager: Start proc com.sec.android.widgetapp.dualclockdigital for broadcast com.sec.android.widgetapp.dualclockdigital/.DigitalDualClockWidgetProvider: pid=7066 uid=10089 gids={50089, 9997, 3003} abi=armeabi-v7a
,08-23 13:40:34.286  1018  1044 W ActivityManager: userId = 0, bbcId = -10000
08-23 13:40:34.286  7066  7066 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
08-23 13:40:34.286  1018  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 13:40:34.286  1018  1044 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.activeapplicationwidget, hostingType: broadcast
,08-23 13:40:34.286  1018  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
08-23 13:40:34.286  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 13:40:34.286  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:34.286  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:34.286  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0,
,08-23 13:40:34.296  7066  7066 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,08-23 13:40:34.306  7080  7080 E Zygote  : MountEmulatedStorage()
08-23 13:40:34.306  7080  7080 E Zygote  : v2
08-23 13:40:34.306  7080  7080 I libpersona: KNOX_SDCARD checking this for 10139
08-23 13:40:34.306  7080  7080 I libpersona: KNOX_SDCARD not a persona
,08-23 13:40:34.306  7080  7080 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 13:40:34.306  7080  7080 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 13:40:34.306  1018  1044 I ActivityManager: Start proc com.sec.android.widgetapp.activeapplicationwidget for broadcast com.sec.android.widgetapp.activeapplicationwidget/.ProgramMonitorProvider: pid=7080 uid=10139 gids={50139, 9997, 1028, 1015} abi=armeabi-v7a
08-23 13:40:34.306  7080  7080 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 13:40:34.316  1018  4437 I ActivityManager: Killing 6668:com.sec.pcw.device/1000 (adj 15): empty #21
,08-23 13:40:34.336  7066  7066 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-23 13:40:34.336  7066  7066 D ActivityThread: Added TimaKeyStore provider
,08-23 13:40:34.346   259   259 I SurfaceFlinger: id=14 createSurf (540x960),1 flag=4, Mauncher
08-23 13:40:34.346  1018  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-23 13:40:34.346  1018  4439 D InputDispatcher: Focus entered window: 1509
08-23 13:40:34.346  7053  7053 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-23 13:40:34.346  7053  7053 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 13:40:34.346  7053  7053 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-23 13:40:34.346  7053  7053 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-23 13:40:34.346  7053  7053 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-23 13:40:34.346  7053  7053 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-23 13:40:34.346  7053  7053 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-23 13:40:34.346  1018  1049 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-23 13:40:34.346  1018  1049 D PointerIcon: setMouseCustomIcon IconType is same.101
,08-23 13:40:34.346  1509  1509 D SRIB_DCS: log_dcs ThreadedRenderer::initialize entered! 
,08-23 13:40:34.356  1018  1047 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-23 13:40:34.366  7080  7080 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 13:40:34.366  7080  7080 D ActivityThread: Added TimaKeyStore provider
,08-23 13:40:34.386  1509  1509 V ActivityThread: updateVisibility : ActivityRecord{40546bf token=android.os.BinderProxy@2bb42ee6 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,08-23 13:40:34.386  7066  7066 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-23 13:40:34.386  1509  1509 D Launcher.HomeView: onStop
08-23 13:40:34.386  7066  7066 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
,08-23 13:40:34.386  1018  4437 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-23 13:40:34.386  6817  6817 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-23 13:40:34.396  1018  7099 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1698 com.android.server.InputMethodManagerService$6.run:2762 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-23 13:40:34.396  1880  1880 D SamsungIME: onStartInput: No inputType, No imeOption, isInputViewShown = false, isExtractViewShown = false, isShowInputRequested = false, isConfigChanged = false
,08-23 13:40:34.396  7048  7048 D AndroidRuntime: 
08-23 13:40:34.396  7048  7048 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-23 13:40:34.396  7048  7048 D AndroidRuntime: CheckJNI is OFF
,08-23 13:40:34.396  7048  7048 D AndroidRuntime: readGMSProperty: start
08-23 13:40:34.396  7048  7048 D AndroidRuntime: readGMSProperty: already setted!!
08-23 13:40:34.396  7048  7048 D AndroidRuntime: propertySet: couldn't set property (it is from app)
08-23 13:40:34.396  7048  7048 D AndroidRuntime: readGMSProperty: could not set the property(default)!!
08-23 13:40:34.396  7048  7048 D AndroidRuntime: readGMSProperty: end
08-23 13:40:34.396  7048  7048 D AndroidRuntime: addProductProperty: start
,08-23 13:40:34.396  1179  1179 D PanelView: There is/are notification(s) ,
,08-23 13:40:34.406  1018  1522 W ActivityManager: userId = 0, bbcId = -10000
,08-23 13:40:34.406  1018  1522 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 13:40:34.406  1018  1522 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.settings
,08-23 13:40:34.406  1018  1522 W BroadcastQueue: Permission Denial: broadcasting Intent { act=com.sec.android.intent.action.HOME_RESUME flg=0x10 } from com.sec.android.app.launcher (pid=1509, uid=10006) is not exported from uid 1000 due to receiver com.android.settings/.accessibilitywidget.AccessibilityEasyWidgetProviderAssistiveLight
,08-23 13:40:34.416  1018  1044 W ActivityManager: userId = 0, bbcId = -10000
08-23 13:40:34.416  1018  1044 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 13:40:34.416  1018  1044 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.systemui
,08-23 13:40:34.416  2638  2638 D Recents_RecreateReceiver: onReceive by home
,08-23 13:40:34.416  1018  1080 W ActivityManager: userId = 0, bbcId = -10000
,08-23 13:40:34.416  1018  1080 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 13:40:34.416  1018  1080 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.digitalclock
,08-23 13:40:34.416  1018  1080 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.digitalclock, hostingType: broadcast
,08-23 13:40:34.426  7080  7080 V TaskCloserActivity: TaskCloserActivity enter()
,08-23 13:40:34.426  1018  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:34.426  1018  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:34.426  1018  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:34.426  1018  1080 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 13:40:34.446  7101  7101 E Zygote  : MountEmulatedStorage(),
08-23 13:40:34.446  7101  7101 E Zygote  : v2
08-23 13:40:34.446  7101  7101 I libpersona: KNOX_SDCARD checking this for 10084,
08-23 13:40:34.446  7101  7101 I libpersona: KNOX_SDCARD not a persona
,08-23 13:40:34.446  7101  7101 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51,
08-23 13:40:34.446  1018  1080 I ActivityManager: Start proc com.sec.android.widgetapp.digitalclock for broadcast com.sec.android.widgetapp.digitalclock/.DigitalClockWidgetProvider: pid=7101 uid=10084 gids={50084, 9997} abi=armeabi-v7a
,08-23 13:40:34.456  7101  7101 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
08-23 13:40:34.456  7101  7101 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL,
08-23 13:40:34.456  1018  1508 D PersonaManager: isKioskContainerExistOnDevice
08-23 13:40:34.456  7080  7080 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_RESUME
,08-23 13:40:34.476  1509  1509 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2bb42ee6 time:98409
08-23 13:40:34.476  1018  1018 D WindowOrientationListener:   mReceiver.onReceive :com.samsung.intent.action.AUTOROTATION,  delay = 200
,08-23 13:40:34.476  1018  4442 W ActivityManager: userId = 0, bbcId = -10000
08-23 13:40:34.476  1018  4442 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 13:40:34.476  1018  4442 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.phone
,08-23 13:40:34.476  1018  4442 I ActivityManager: Killing 5990:com.android.vending/u0a26 (adj 15): empty #21
,08-23 13:40:34.496  1018  1049 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2d822e77 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t162} time:98432
08-23 13:40:34.496  1018  1049 W ActivityManager: mDVFSHelper.release()
,08-23 13:40:34.506  7101  7101 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:40:34.506  7101  7101 D ActivityThread: Added TimaKeyStore provider,
,08-23 13:40:34.516  1018  1466 W ActivityManager: userId = 0, bbcId = -10000
08-23 13:40:34.516  1018  1466 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.camera, hostingType: broadcast
08-23 13:40:34.516  1018  1466 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 13:40:34.516  1018  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.app.camera
,08-23 13:40:34.516  1018  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:34.516  1018  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:34.516  1018  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:34.516  1018  1466 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 13:40:34.516  7101  7101 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-23 13:40:34.536  7126  7126 E Zygote  : MountEmulatedStorage(),
,08-23 13:40:34.536  7126  7126 E Zygote  : v2,
08-23 13:40:34.536  7126  7126 I libpersona: KNOX_SDCARD checking this for 10135
08-23 13:40:34.536  7126  7126 I libpersona: KNOX_SDCARD not a persona
,08-23 13:40:34.536  7126  7126 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 13:40:34.546  7126  7126 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-23 13:40:34.546  1018  1466 I ActivityManager: Start proc com.sec.android.app.camera for broadcast com.sec.android.app.camera/.HomeResumeCamera: pid=7126 uid=10135 gids={50135, 9997, 1028, 1015, 3003, 1023} abi=armeabi-v7a
08-23 13:40:34.546  1018  1466 I ActivityManager: Killing 6688:com.sec.android.provider.badge/u0a68 (adj 15): empty #21
08-23 13:40:34.546  7126  7126 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-23 13:40:34.546  1018  1466 I ActivityManager: Killing 6705:com.sec.android.app.myfiles/u0a42 (adj 15): empty #21
,08-23 13:40:34.576  7048  7048 E AffinityControl: AffinityControl: registerfunction enter
08-23 13:40:34.576   321   321 I art     : Explicit concurrent mark sweep GC freed 8680(370KB) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 616us total 29.856ms
,08-23 13:40:34.576  7053  7053 D NearbySource: Nearby Source Create!
,08-23 13:40:34.576  7053  7053 D NearbyContext: Nearby Context Create!
,08-23 13:40:34.586  7126  7126 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:40:34.586  7126  7126 D ActivityThread: Added TimaKeyStore provider
,08-23 13:40:34.596   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 586us total 16.413ms,
,08-23 13:40:34.596  7126  7126 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
08-23 13:40:34.596  7126  7126 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-23 13:40:34.596  7126  7126 W ResourcesManager: Asset path '/system/framework/secimaging.jar' does not exist or contains no resources.
08-23 13:40:34.596  7126  7126 W ResourcesManager: Asset path '/system/framework/seccamera.jar' does not exist or contains no resources.
08-23 13:40:34.596  7126  7126 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-23 13:40:34.606  7048  7048 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-23 13:40:34.616   321   321 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 51% free, 3MB/7MB, paused 591us total 16.542ms,
,08-23 13:40:34.626   258   519 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache/
08-23 13:40:34.626   258   519 W Vold    : Returning OperationFailed - no handler for errno 0
,08-23 13:40:34.626  7053  7053 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.sec.android.gallery3d/cache
,08-23 13:40:34.626  7053  7053 D SLinkSource: Samsung link source created
,08-23 13:40:34.646  1018  1080 I ActivityManager: Killing 6725:com.wsomacp/u0a23 (adj 15): empty #21
,08-23 13:40:34.646  1018  1466 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-23 13:40:34.646  1018  1466 D PackageManager: START PACKAGE DELETE: observer{461904889}
08-23 13:40:34.646  1018  1466 D PackageManager: pkg{<packageName>}
08-23 13:40:34.646  1018  1466 D PackageManager: user{0}
08-23 13:40:34.646  1018  1466 D PackageManager: caller{2000}
08-23 13:40:34.646  1018  1466 D PackageManager: flags{2}
08-23 13:40:34.646  1018  1466 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-23 13:40:34.646  1018  1466 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-23 13:40:34.646  1018  1466 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-23 13:40:34.646  1018  1466 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-23 13:40:34.646  1018  1059 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-23 13:40:34.646  1018  1059 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-23 13:40:34.646  1018  1059 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-23 13:40:34.646  1018  1059 D ApplicationPolicy: getApplicationUninstallationEnabled
08-23 13:40:34.646  1018  1059 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-23 13:40:34.656  1018  1059 D PackageManager: !@killApplicatoin: 10170, uninstall pkg
,08-23 13:40:34.656  1018  1044 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=-1: uninstall pkg
,08-23 13:40:34.656  1018  1044 I ActivityManager: Killing 6817:com.test.thalitest/u0a170 (adj 15): stop com.test.thalitest cause uninstall pkg
,08-23 13:40:34.766  1018  1031 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-23 13:40:34.776  7053  7143 D ContactProvider: getAllContactInfoList Start
,08-23 13:40:34.776  1018  1330 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-23 13:40:34.776  7053  7053 D GalleryCacheReady: Receive : home resume
,08-23 13:40:34.786  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
,08-23 13:40:34.786  1018  1030 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 13:40:34.786  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.android.mms
,08-23 13:40:34.786  6514  6514 D Mms/UIEventReceiver: ui event
,08-23 13:40:34.786  1018  1059 I ActivityManager: Force stopping com.test.thalitest appid=10170 user=0: pkg removed
,08-23 13:40:34.806  1018  1059 W ActivityManager: CustomStartingWindow se packge removed so remove capture also
,08-23 13:40:34.826  6154  6154 I art     : Explicit concurrent mark sweep GC freed 13226(727KB) AllocSpace objects, 0(0B) LOS objects, 32% free, 4MB/6MB, paused 712us total 33.429ms
,08-23 13:40:34.846  2828  2828 I art     : Explicit concurrent mark sweep GC freed 16517(986KB) AllocSpace objects, 4(64KB) LOS objects, 49% free, 4MB/8MB, paused 941us total 42.853ms
,08-23 13:40:34.846  1018  1101 I InputReader: Reconfiguring input devices.  changes=0x00000010,
,08-23 13:40:34.866  1880  1880 E SamsungIME: mOCRHelper is null
,08-23 13:40:34.886  1018  1125 V NetworkStats: removeUidsLocked() for UIDs [10170]
08-23 13:40:34.886  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 13:40:34.886  1018  1125 V NetworkStats: performPollLocked(flags=0x3)
,08-23 13:40:34.896  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox updated
08-23 13:40:34.896  1018  1125 D NetworkStatsFactory: UpdateStatsForKnox main else ---
,08-23 13:40:34.896  1018  1125 V NetworkStats: performPollLocked() took 6ms
08-23 13:40:34.896  1018  1125 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 13:40:34.906  1018  1466 I splitIntent: Queue : background intent com.sec.android.intent.action.HOME_RESUME is finished at BG and BG split queue. set mSplitStart  false.
,08-23 13:40:34.906  1018  1466 W ActivityManager: userId = 0, bbcId = -10000
08-23 13:40:34.906  1018  1466 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 13:40:34.906  1018  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.android.app.launcher, destAppInfo.processName = com.sec.android.widgetapp.activeapplicationwidget
,08-23 13:40:34.916  7080  7080 V TaskCloserActivity: TaskCloserActivity onReceive() - com.sec.android.intent.action.HOME_PAUSE
08-23 13:40:34.916  1018  1018 D RCPManagerService: PackageReceiver onReceive()
,08-23 13:40:34.916  1018  1018 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-23 13:40:34.926  1018  1018 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,08-23 13:40:34.926  1018  1018 I OTPFW   : PackageRemovalReceiver::onReceive Enter
,08-23 13:40:34.926  1018  1018 D OTPFW   : PackageRemovalReceiver::onReceive deleting token for Pkg = com.test.thalitest uid = 10170 container id = 0
,08-23 13:40:34.936  1468  1468 D PersonaManager: isKioskContainerExistOnDevice
,08-23 13:40:34.936  1468  1468 D RegisteredServicesCache: empty dynamic service
,08-23 13:40:34.956  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
08-23 13:40:34.956  1018  1126 D NtpTrustedTime: currentTimeMillis() cache hit
,08-23 13:40:34.966  1018  1018 I OTPFW   : ProvisionData::getAllEntries Enter
,08-23 13:40:34.966  1468  1468 D RegisteredComponentCache: Collect Tech packages for Knox
,08-23 13:40:34.966  1018  1018 E OTPFW   : ProvisionData::getAllEntries Table is empty
,08-23 13:40:34.966  1468  1468 D PersonaManager: isKioskContainerExistOnDevice
,08-23 13:40:35.056  1018  1059 I art     : Explicit concurrent mark sweep GC freed 46546(3MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 23MB/34MB, paused 2.995ms total 240.207ms
,08-23 13:40:35.056  1018  1508 I art     : WaitForGcToComplete blocked for 191.524ms for cause Explicit
,08-23 13:40:35.086  1018  1059 D PackageManager: delete codoeFile: 
,08-23 13:40:35.096  1018  1018 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-23 13:40:35.096  1018  1018 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-23 13:40:35.096  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-23 13:40:35.096  1018  1018 V EnterpriseBillingPolicy: uID is 10170
08-23 13:40:35.096  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
08-23 13:40:35.096  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-23 13:40:35.096  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
,08-23 13:40:35.106  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-23 13:40:35.106  1018  1059 D AASAuninstall: userId = 0, info.removedAppID = 10170, info.uid = 10170, packageName = com.test.thalitest
08-23 13:40:35.106  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-23 13:40:35.106  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-23 13:40:35.106  1018  1059 I AASA_removePackage: UID=10170 Target=com.test.thalitest
08-23 13:40:35.106  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-23 13:40:35.106  1018  1059 D PackageManager: result of delete: 1{461904889}
,08-23 13:40:35.106  1018  1018 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
,08-23 13:40:35.106  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_FULLY_REMOVED
08-23 13:40:35.106  1018  1018 V EnterpriseBillingPolicy: uID is 10170
08-23 13:40:35.106  1018  1018 V EnterpriseBillingPolicy: Removed Packageuid is0
08-23 13:40:35.106  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
08-23 13:40:35.106  1018  1165 D TaskPersister: removeObsoleteFile: deleting file=163_task.xml
,08-23 13:40:35.106  1018  1018 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null : containerId = 0
08-23 13:40:35.106  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-23 13:40:35.106  1018  1018 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-23 13:40:35.106  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
08-23 13:40:35.106  1018  1018 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-23 13:40:35.106  1018  3342 D SSRM:bc : MSG_TYPE_APP_REMOVED::
,08-23 13:40:35.106  1018  1018 V AlarmManagerEXT: com.test.thalitest(10170) is removed.
,08-23 13:40:35.106  7048  7048 D AndroidRuntime: Shutting down VM
,08-23 13:40:35.116  1018  1059 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-23 13:40:35.116  1018  1059 D PackageManager: userId{-1}
08-23 13:40:35.116  1018  1059 D PackageManager: andCode{true}
,08-23 13:40:35.116  1018  1059 D ActivityManager: retrieveServiceLocked(): component = com.android.defcontainer/com.android.defcontainer.DefaultContainerService; callingUser = 0; userId(target) = 0
,08-23 13:40:35.216  1018  1508 I art     : Explicit concurrent mark sweep GC freed 12794(727KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 22MB/34MB, paused 3.575ms total 160.724ms
,08-23 13:40:35.216  1736  1980 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-23 13:40:35.216  1018  4442 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-23 13:40:35.216  1018  4442 D SecContentProvider2: mCursor = null
,08-23 13:40:35.216  1018  1043 D EnterpriseDeviceManagerService: Package has changed for user 0
08-23 13:40:35.216  1018  1043 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
08-23 13:40:35.216  1018  1043 W TextServicesManagerService: no available spell checker services found
,08-23 13:40:35.226  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 13:40:35.236  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 13:40:35.236  2812  2812 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive(): Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.listner.MainReciver (has extras) } | timestamp: Tue Aug 23 13:40:35 GMT+02:00 2016
,08-23 13:40:35.236  1018  1505 D ActivityManager: startService callerProcessName:com.samsung.klmsagent, calleePkgName: com.samsung.klmsagent
08-23 13:40:35.236  1018  1505 D ActivityManager: retrieveServiceLocked(): component = com.samsung.klmsagent/com.samsung.klmsagent.services.KLMSIntentService; callingUser = 0; userId(target) = 0
,08-23 13:40:35.236  1018  1505 W ActivityManager: userId = 0, bbcId = -10000
,08-23 13:40:35.236  1018  1505 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
,08-23 13:40:35.236  1018  1505 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.samsung.klmsagent, destAppInfo.processName = com.samsung.klmsagent
,08-23 13:40:35.246  2812  2812 I KLMS-2.5.123: : KLMSAbstractReciever(): onReceive().END.
,08-23 13:40:35.246  1018  1031 I splitIntent: Split this intent : android.intent.action.PACKAGE_REMOVED, mSplitNum[0]=12, mSplitNum[1]=22, mSplitNum[2]=32, mBgSplitQueueNum=3 divideNum= 10 r.nextReceiver= 1 receivers.size=42
08-23 13:40:35.246  1018  1031 I splitIntent: finish to split intent : android.intent.action.PACKAGE_REMOVED !! Enqueue -> schedule it!!
,08-23 13:40:35.256  1018  1044 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-23 13:40:35.256  2812  2812 I KLMS-2.5.123: : KLMSIntentService(): onCreate()
,08-23 13:40:35.256  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 13:40:35.256  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:35.256  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:35.256  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 13:40:35.256  2812  2812 I KLMS-2.5.123: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-23 13:40:35.256  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 13:40:35.256  6913  6913 D elm:15121: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-23 13:40:35.256  2812  2812 I KLMS-2.5.123: : KLMSUtility(): isTestMode(): product_ship: true | testApk: false
,08-23 13:40:35.256  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 13:40:35.266  2812  7145 I KLMS-2.5.123: : KLMSIntentService(): onHandleIntent().START: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.samsung.klmsagent/.services.KLMSIntentService (has extras) }
,08-23 13:40:35.266  2812  7145 I KLMS-2.5.123: : KLMSIntentService(): PACKAGE_REMOVED
,08-23 13:40:35.266  2812  7145 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().START
,08-23 13:40:35.266  7146  7146 E Zygote  : MountEmulatedStorage()
08-23 13:40:35.266  7146  7146 E Zygote  : v2
08-23 13:40:35.266  7146  7146 I libpersona: KNOX_SDCARD checking this for 10032
08-23 13:40:35.266  7146  7146 I libpersona: KNOX_SDCARD not a persona
08-23 13:40:35.266  7146  7146 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 13:40:35.276  1018  1044 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.receiver.PackageInfoChangeReceiver: pid=7146 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-23 13:40:35.276  2812  7145 I KLMS-2.5.123: : KLMSIntentService(): REPLACING: false | pkgName: com.test.thalitest
,08-23 13:40:35.276  7146  7146 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051,
,08-23 13:40:35.276  1018  1044 D ActivityManager: startProcessLocked calleePkgName: com.google.android.googlequicksearchbox, hostingType: broadcast
,08-23 13:40:35.276  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:35.276  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:35.276  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:35.276  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 13:40:35.276  7146  7146 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-23 13:40:35.296  7160  7160 E Zygote  : MountEmulatedStorage(),
08-23 13:40:35.296  7160  7160 E Zygote  : v2
08-23 13:40:35.296  7160  7160 I libpersona: KNOX_SDCARD checking this for 10052
08-23 13:40:35.296  7160  7160 I libpersona: KNOX_SDCARD not a persona
,08-23 13:40:35.296  7160  7160 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
,08-23 13:40:35.306  7160  7160 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 13:40:35.306  7160  7160 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-23 13:40:35.306  1018  1044 I ActivityManager: Start proc com.google.android.googlequicksearchbox:search for broadcast com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.IcingCorporaChangedReceiver: pid=7160 uid=10052 gids={50052, 9997, 3003, 3001, 1028, 3002, 1015} abi=armeabi-v7a
,08-23 13:40:35.306  1018  1044 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.watchmanagerstub, hostingType: broadcast,
,08-23 13:40:35.306  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:35.316  7146  7146 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:40:35.306  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:35.316  7146  7146 D ActivityThread: Added TimaKeyStore provider
08-23 13:40:35.306  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:35.316  7048  7048 W art     : ConditionVariable::~ConditionVariable for GC request condition variable called with 1 waiters.
08-23 13:40:35.306  1018  1044 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 13:40:35.336  1018  1044 I ActivityManager: Start proc com.samsung.android.app.watchmanagerstub for broadcast com.samsung.android.app.watchmanagerstub/com.sec.android.applicationmgr.PackageIntentReceiver: pid=7170 uid=10098 gids={50098, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-23 13:40:35.336  1018  1470 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-23 13:40:35.336  1018  1470 D ActivityManager: retrieveServiceLocked(): component = com.sec.esdk.elm/com.sec.esdk.elm.service.ElmAgentService; callingUser = 0; userId(target) = 0
,08-23 13:40:35.336  1018  1470 W ActivityManager: userId = 0, bbcId = -10000,
08-23 13:40:35.336  1018  1470 W ActivityManager: NORMAL SET : dst_category = 0, src_allowCategory = 0,2-1023
08-23 13:40:35.336  1018  1470 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.sec.esdk.elm, destAppInfo.processName = com.sec.esdk.elm
08-23 13:40:35.336  6913  6913 D elm:15121: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-23 13:40:35.346  7170  7170 E Zygote  : MountEmulatedStorage()
,08-23 13:40:35.346  7170  7170 I libpersona: KNOX_SDCARD checking this for 10098
08-23 13:40:35.346  7170  7170 E Zygote  : v2
08-23 13:40:35.346  7170  7170 I libpersona: KNOX_SDCARD not a persona
08-23 13:40:35.346  7170  7170 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 13:40:35.346  6913  6913 D elm:15121: ElmAgentService : onCreate()
08-23 13:40:35.346  6913  7177 D elm:15121: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
08-23 13:40:35.346  6913  7177 D elm:15121: MainReceiver.listeningToPackageRemoved()
08-23 13:40:35.346  6913  7177 D elm:15121: MDMBridge.getInstance()
08-23 13:40:35.346  6913  7177 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-23 13:40:35.346  7170  7170 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 13:40:35.346  7170  7170 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-23 13:40:35.356  2812  7145 I KLMS-2.5.123: : KLMSIntentService(): Notification App List is Null. Remove Notification.
,08-23 13:40:35.356  6913  7177 D elm:15121: MDMBridge.getAllLicenseInfoFromSDK()
,08-23 13:40:35.356  7160  7160 D TimaKeyStoreProvider: TimaSignature is unavailable,
08-23 13:40:35.356  7160  7160 D ActivityThread: Added TimaKeyStore provider
,08-23 13:40:35.366  1018  1043 W ResourceType: Failure getting entry for 0x7f07007b (t=6 e=123) (error -75)
,08-23 13:40:35.366  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 13:40:35.376  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 13:40:35.376  2812  7145 I KLMS-2.5.123: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-23 13:40:35.376  7170  7170 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 13:40:35.376  7170  7170 D ActivityThread: Added TimaKeyStore provider
,08-23 13:40:35.386  7053  7143 D ContactProvider: getAllContactInfoList End
,08-23 13:40:35.386  7053  7143 I syncContacts: thread: 1308, sync time = 713
,08-23 13:40:35.386  2812  7145 I KLMS-2.5.123: : KLMSIntentService(): listeningToPackageRemoved().END
08-23 13:40:35.386  6913  6913 D elm:15121: ElmAgentService : onDestroy().
,08-23 13:40:35.396  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 13:40:35.396  2812  2812 I KLMS-2.5.123: : KLMSIntentService(): onDestroy()
,08-23 13:40:35.406  1684  1684 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,08-23 13:40:35.406  1684  1684 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,08-23 13:40:35.406  1018  1043 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-23 13:40:35.406  1018  1043 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 13:40:35.406  1018  1043 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-23 13:40:35.406  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 13:40:35.416  1018  4442 D ActivityManager: startService callerProcessName:com.google.android.gsf, calleePkgName: com.google.android.gms
,08-23 13:40:35.416  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 13:40:35.416  1018  4442 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.app.service.PackageBroadcastService; callingUser = 0; userId(target) = 0
08-23 13:40:35.416  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 13:40:35.426  1018  4442 W ActivityManager: userId = 0, bbcId = -10000
08-23 13:40:35.426  1018  4442 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 13:40:35.426  1018  4442 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.process.gapps, destAppInfo.processName = com.google.android.gms
,08-23 13:40:35.426  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 13:40:35.426  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-23 13:40:35.426  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 13:40:35.426  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 13:40:35.426  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-23 13:40:35.436  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-23 13:40:35.436  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-23 13:40:35.436  1018  1043 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-23 13:40:35.436  1900  7195 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-23 13:40:35.436  1900  7195 D AccountUtils: Clearing selected account for com.test.thalitest
,08-23 13:40:35.446  7146  7194 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
08-23 13:40:35.446  7146  7194 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-23 13:40:35.446  1018  1518 D ActivityManager: startProcessLocked calleePkgName: com.samsung.helphub, hostingType: broadcast
,08-23 13:40:35.446  1018  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:35.446  1018  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:35.446  1018  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:35.446  1018  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 13:40:35.456  7198  7198 E Zygote  : MountEmulatedStorage()
08-23 13:40:35.456  7198  7198 I libpersona: KNOX_SDCARD checking this for 1000
08-23 13:40:35.456  7198  7198 E Zygote  : v2
08-23 13:40:35.456  7198  7198 I libpersona: KNOX_SDCARD not a persona
08-23 13:40:35.456  1018  1518 I ActivityManager: Start proc com.samsung.helphub for broadcast com.samsung.helphub/.broadcast.HelpHubBroadcastReceiver: pid=7198 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1028, 1015, 1007, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-23 13:40:35.466  7198  7198 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 13:40:35.466  1018  1043 D UsbSettingsManager: clearDefaults: com.test.thalitest
08-23 13:40:35.466  1018  1043 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
08-23 13:40:35.466  1018  1518 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
08-23 13:40:35.466  7198  7198 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 13:40:35.466  1018  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:35.466  7198  7198 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-23 13:40:35.466  1018  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:35.466  1018  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-23 13:40:35.466  1018  1518 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-23 13:40:35.476  7146  7146 E SQLiteLog: (28) failed to open "/data/data/com.sec.spp.push/databases/registration_db" with flag (131138) and mode_t (0) due to error (30)
,08-23 13:40:35.476  7146  7194 D SPPClientService: PushLog.txt file is not deleted.
08-23 13:40:35.476  7146  7194 D SPPClientService: PushLog.txt file is not deleted.
08-23 13:40:35.476  7146  7194 D SPPClientService: ============PushLog. stop!
,08-23 13:40:35.476  7146  7146 E SQLiteDatabase: Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.
08-23 13:40:35.476  7146  7146 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-23 13:40:35.476  7146  7146 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-23 13:40:35.476  7146  7146 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-23 13:40:35.476  7146  7146 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-23 13:40:35.476  7146  7146 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-23 13:40:35.476  7146  7146 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-23 13:40:35.476  7146  7146 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-23 13:40:35.476  7146  7146 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:908)
08-23 13:40:35.476  7146  7146 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:878)
08-23 13:40:35.476  7146  7146 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-23 13:40:35.476  7146  7146 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1519)
08-23 13:40:35.476  7146  7146 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-23 13:40:35.476  7146  7146 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-23 13:40:35.476  7146  7146 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-23 13:40:35.476  7146  7146 E SQLiteDatabase: 	at com.sec.spp.push.i.a.a(Unknown Source)
08-23 13:40:35.476  7146  7146 E SQLiteDatabase: 	at com.sec.spp.push.i.c.d(Unknown Source)
08-23 13:40:35.476  7146  7146 E SQLiteDatabase: 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
08-23 13:40:35.476  7146  7146 E SQLiteDatabase: 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
08-23 13:40:35.476  7146  7146 E SQLiteDatabase: 	at com.sec.spp.push.receiver.a.handleMessage(Unknown Source)
08-23 13:40:35.476  7146  7146 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 13:40:35.476  7146  7146 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-23 13:40:35.476  7146  7146 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:6145)
08-23 13:40:35.476  7146  7146 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 13:40:35.476  7146  7146 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 13:40:35.476  7146  7146 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1399)
08-23 13:40:35.476  7146  7146 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1194)
08-23 13:40:35.476  7146  7146 E SPPClientService: [c] [getAppId()] SQLiteException with message =not an error (code 0): Could not open the database in read/write mode.
,08-23 13:40:35.486  7213  7213 E Zygote  : MountEmulatedStorage(),
,08-23 13:40:35.486  7213  7213 E Zygote  : v2
08-23 13:40:35.486  7213  7213 I libpersona: KNOX_SDCARD checking this for 10032
08-23 13:40:35.486  7213  7213 I libpersona: KNOX_SDCARD not a persona
08-23 13:40:35.496  7213  7213 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-A300FU_5.0.2-1 ver=51
08-23 13:40:35.486  1018  1518 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7213 uid=10032 gids={50032, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-23 13:40:35.496  1018  1518 I ActivityManager: Killing 6768:com.samsung.android.app.filterinstaller/1000 (adj 15): empty #21
,08-23 13:40:35.496  7213  7213 I SELinux : Function: selinux_compare_spd_ram , priority [1] , priority version is VE=SEPF_SM-A300FU_5.0.2-1_0051
,08-23 13:40:35.496  7213  7213 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-23 13:40:35.496  1018  1508 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 13:40:35.506  1018  1508 W ActivityManager: userId = 0, bbcId = -10000
08-23 13:40:35.506  1018  1508 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 13:40:35.506  1018  1508 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 13:40:35.506  7198  7198 D TimaKeyStoreProvider: TimaSignature is unavailable
08-23 13:40:35.506  7198  7198 D ActivityThread: Added TimaKeyStore provider
,08-23 13:40:35.516  7213  7213 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-23 13:40:35.516  7213  7213 D ActivityThread: Added TimaKeyStore provider
,08-23 13:40:35.516  1018  1466 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-23 13:40:35.516  1018  1466 D ActivityManager: retrieveServiceLocked(): component = com.google.android.gms/com.google.android.gms.googlehelp.service.ClearHelpHistoryIntentService; callingUser = 0; userId(target) = 0
,08-23 13:40:35.516  1018  1466 W ActivityManager: userId = 0, bbcId = -10000
08-23 13:40:35.516  1018  1466 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 13:40:35.516  1018  1466 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
,08-23 13:40:35.526  1018  1518 D ActivityManager: retrieveServiceLocked(): component = null; callingUser = 0; userId(target) = 0
,08-23 13:40:35.526  1018  1518 W ActivityManager: userId = 0, bbcId = -10000
08-23 13:40:35.526  1018  1518 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 13:40:35.526  1018  1518 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.gms, destAppInfo.processName = com.google.android.gms
08-23 13:40:35.526  1018  1030 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-23 13:40:35.526  1018  1030 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0
,08-23 13:40:35.526  1018  1030 W ActivityManager: userId = 0, bbcId = -10000
08-23 13:40:35.526  1018  1030 W ActivityManager: NORMAL SET : dst_category = 701, src_allowCategory = 0,701-1023
08-23 13:40:35.526  1018  1030 W ActivityManager: NORMAL SET : srcAppInfo.processName = com.google.android.googlequicksearchbox, destAppInfo.processName = com.google.android.googlequicksearchbox
,08-23 13:40:35.536  1018  1222 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-23 13:40:35.536  1018  1222 D ActivityManager: retrieveServiceLocked(): component = com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService; callingUser = 0; userId(target) = 0

```
